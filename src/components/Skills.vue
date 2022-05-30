<template>
    <div class="skill">
        <div class="skill_heading">Skills</div>

        <div class="skills1">
            <div class="bg_props" style="background-image: url('Images/vue.png')" ></div>
            <div class="bg_props" style="background-image: url('Images/Quasar_Logo.png')" ></div>
            <div class="bg_props" style="background-image: url('Images/vuex.png')" ></div>
            <div class="bg_props" style="background-image: url('../Images/javascript.png')" ></div>
        </div>
        <div class="skills2">
            <div class="bg_props" style="background-image: url('../Images/css3.png')" ></div>
            <div class="bg_props" style="background-image: url('../Images/html5.png')" ></div>
            <div class="bg_props" style="background-image: url('Images/Bootstrap.png')" ></div>
        </div>

        <div class="skill_heading">Tools</div>
        <div class="skills3">
            <div class="bg_props" style="background-image: url('Images/vscode.png')" ></div>
            <div class="bg_props" style="background-image: url('Images/github.png')" ></div>
            <div class="bg_props" style="background-image: url('Images/figma.png')" ></div>
            <div class="bg_props" style="background-image: url('Images/slack.png')" ></div>
            <div class="bg_props" style="background-image: url('Images/trello.png')" ></div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Skills"
}
</script>

<style scoped>
.skill{
    background: whitesmoke;
}
.skill_heading{
    font-size: 3.5rem;
    text-align: center;
    padding: 4% 0 2%;
    font-weight: bold;
    text-decoration: underline;
}
.skills1{
    margin: 1% 0 0;
    padding: 0 10%;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 22px;
    grid-auto-rows: 200px;
    place-items: center;
}
.skills2{
    margin: 2% 0 0;
    padding: 0 15%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 22px;
    grid-auto-rows: 200px;
    place-items: center;
}
.skills3{
    padding: 4% 10%;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 22px;
    grid-auto-rows: 200px;
    place-items: center;
}
.bg_props{
    height: 100%;
    width: 100%;
    background-position: center;
    background-size: contain;
    background-repeat: no-repeat;
}
</style>