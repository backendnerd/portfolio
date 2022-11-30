<template>
    <div class="projectContainer">
        <h2 class="projectsHeading">Projects I Made:</h2>
        <section id="projects" class="projects">
            <ProjectCard v-for="index in 10" :key="index"></ProjectCard>
        </section>
    </div>
</template>

<script>
import ProjectCard from "./ProjectCard.vue";

export default {
    data() {
        return {};
    },
    components: {
        ProjectCard,
    },
};
</script>

<style scoped>
#projects {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 2rem;
    margin: auto;
}
.projectsHeading {
    position: absolute;
    background-color: white;
    color: #222;
    transform: translateY(-100%);
    left: 7.5%;
    padding: 0 0.5rem;
}

.projectContainer {
    position: relative;
    margin: 2rem 0;
    padding: 1rem;
    border: 2px solid darkblue;
    border-radius: 10px;
}
</style>
