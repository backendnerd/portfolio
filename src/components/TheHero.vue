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
    background-image: url("../assets/mohammad-rahmani-_Fx34KeqIEw1080.jpg");
    background-position: center;
    padding: 8rem 3rem;
    color: #f5f5f5;
    object-fit: cover;
    background-size: cover;
    background-repeat: no-repeat;
}

.intro,
h1 {
    text-shadow: -1px 0px 24px rgb(0, 0, 0);
}
h1 {
    text-align: center;
    font-family: "Courgette", cursive;
    font-size: 4rem;
    margin: 0 auto 0.5rem;
    color: white;
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
