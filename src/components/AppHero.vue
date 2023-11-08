<template lang="">
    
    <div>
        <img :src="image" alt="">
    </div>
    
    </template>
    
    <script>
    export default {
        name: 'AppHero',
        data(){
            return {
                image: "../../public/img/naruto_img.jpg",
        }
    }
    }

    </script>
    
    <style scoped>
    div {
        display: flex;
        justify-content: center;
    }
    </style>