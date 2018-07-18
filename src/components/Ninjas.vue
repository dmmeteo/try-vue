<template>
    <div>
        <h1>List of ninjas</h1>
        <ul>
            <li v-for="ninja in ninjas">{{ninja}}</li>
        </ul>
    </div>
</template>

<script>
export default {
    data(){
        return {
            ninjas: [
                {name: 'Ryu', speciality: 'Vue Components', show: false},
                {name: 'Crystal', speciality: 'HTML Wizardry', show: false},
                {name: 'Hitoshi', speciality: 'Click Events', show: false},
                {name: 'Tango', speciality: 'Conditionals', show: false},
                {name: 'Kami', speciality: 'Webpack', show: false},
                {name: 'Yoshi', speciality: 'Data Diggin', show: false}
            ]
        }
    }
}
</script>

<style scoped>
h1{
  color: purple;
}
ul{
  color: red;
}
</style>
