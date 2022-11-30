<template>
    <div class="nav">
        <ul>
            <li class="navItem" v-for="item in navList" :key="item">
                <a :href="'#' + item.toLocaleLowerCase()">{{ item }}</a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    data() {
        return {
            navList: ["Projects", "About", "Contact"],
        };
    },
};
</script>

<style scoped>
.nav ul {
    display: flex;
    justify-content: space-between;
}

.nav {
    margin: auto;
    padding: 1rem;
    max-width: 600px;
}

.nav li {
    list-style: none;
    padding: 0.5rem;
    text-transform: uppercase;
}
.nav a {
    padding: 0.5rem;
}
/* unvisited link */
a:link {
    color: inherit;
    text-decoration: none;
}

a:visited,
a:link,
a:hover {
    text-decoration: none;
    color: inherit;
}
/* visited link */
a:visited {
    color: inherit;
}

/* mouse over link */
.navItem:hover {
    color: darkblue;
    transition: 200ms;
}

/* selected link */
a:active {
    color: blue;
}
</style>
