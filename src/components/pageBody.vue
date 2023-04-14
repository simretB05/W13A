<template>
    <div class="main">
        <h1>welcome to our company</h1>
        <side-panel/>
        <meet-the-developer/>
        <meet-the-team/>
        
    </div>
</template>
<script>
import SidePanel from './SidePanel.vue';
import MeetTheDeveloper from './MeetTheDeveloper.vue'
import MeetTheTeam from './MeetTheTeam.vue'

export default {
    components: {
        SidePanel,
        MeetTheDeveloper,
        MeetTheTeam
        
    

  }

    }
</script>

<style scoped>
.main{
    display: grid;
    place-items: center;
    min-height: 80vh;
}
h1{
    margin: 10px 0;


}
</style>