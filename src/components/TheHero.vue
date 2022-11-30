<template>
    <div class="hero">
        <h1>Youness.</h1>
        <p class="intro">
            I'm a
            <span class="name">web developer</span> from Marrakech, Morocco.
            Currently looking for a job. In my spare time I enjoy playing Chess,
            and building my own projects. My preferred tools are <u>NodeJs</u>,
            <u>TailwindCSS</u> and <u>Vue.js</u>.
        </p>
    </div>
</template>

<script>
export default {
    data() {
        return {};
    },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Courgette&display=swap");
.hero {
    padding: 4rem 3rem;
}

h1 {
    text-align: center;
    font-family: "Courgette", cursive;
    font-size: 4rem;
    margin: 0 auto 0.5rem;
    color: rgb(0, 0, 58);
}
.intro {
    max-width: 700px;
    margin: auto;
    text-align: center;
}

.name {
    font-weight: 500;
}
</style>
