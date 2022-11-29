<template>
    <div class="tech_main">
        <div class="body_nav">
            <div class="nav_text">
                <a href="">Home</a> <img src="../assets/star.png" alt=""> <a href="">Factions</a><img
                    src="../assets/star.png" alt=""> <a href="">Roadmap</a>
            </div>
            <div class="main_text">
                <h1>My Technology</h1>
            </div>
        </div>
        <div class="tech_text"></div>
        <div class="tech_about"></div>
    </div>


</template>

<script>
export default {
    name: 'MyTech',
    props: {
    }
}

</script>


<style scoped>

.body_nav{
    padding-top: 200px;
    max-width: 60%;
}

.tech_main {
    background-image: url(../assets/bg_2.jpg);
    background-size: 100%;

    min-height: 100vh;
}
</style>