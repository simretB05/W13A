<template>
    <div class="team-main">
        <h2 class="meet_team_title">Meet Our Team</h2>
        <div class="team_members">
            <div class="team">

                <img src="../assets/image-emily.jpg" alt="team member picture">
                <p class="teamember_name">Emily</p>

            
            </div>
            <div class="team">
                <img src="../assets/image-jennie.jpg" alt="team member picture">

                <p class="teamember_name">Jennie</p>
            
            </div>
            <div class="team">
                <img src="../assets/image-thomas.jpg" alt="team member picture">

                <p class="teamember_name">Thomas</p>

            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.team-main{
    width: 40%;
    display: grid;
    place-items: center;
    align-self: start;
    min-height: 20vh;
}
.team_members{
    display: grid;
    place-items: center;
    align-self: start;
    grid-template-columns: 1fr 1fr 1fr;
    margin: 10px 0;
     gap:20px
}

</style>