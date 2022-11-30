<template>
    <TheNavbar> </TheNavbar>
    <TheHero></TheHero>
    <ProjectsList></ProjectsList>
</template>

<script>
import TheNavbar from "./components/TheNavbar.vue";
import TheHero from "./components/TheHero.vue";
import ProjectsList from "./components/ProjectsList.vue";

export default {
    name: "App",
    components: {
        TheNavbar,
        TheHero,
        ProjectsList,
    },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100&display=swap");
* {
    margin: 0;
    padding: 0;
}
body {
    padding: 0 1rem;
    font-family: "Poppins", sans-serif;
    color: #121212;
    max-width: 1280px;
    min-height: 100vh;
    margin: auto;
}
</style>
