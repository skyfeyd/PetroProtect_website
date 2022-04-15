<script setup>
    
</script>

<template>
    <section class="main-presentation">
        <img class="bg" src="../assets/e53d035ddb22ce3764f5e39a45500999.jpg" alt="">
        <img class="bg-1" v-if="count == 1" src="../assets/07e7a8dd10b8521d06ae69355685cfc5.jpg">
        <img class="bg-2" v-if="count == 2" src="">
        <span class="bg-3" v-if="count == 3"></span>
        <div class="text">
        <h1>Lorem<br> ipsum<br> in dolores</h1>
        <a href="#Contact" class="contactUs"><h2>Contact us</h2> 
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M438.6 278.6l-160 160C272.4 444.9 264.2 448 256 448s-16.38-3.125-22.62-9.375c-12.5-12.5-12.5-32.75 0-45.25L338.8 288H32C14.33 288 .0016 273.7 .0016 256S14.33 224 32 224h306.8l-105.4-105.4c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0l160 160C451.1 245.9 451.1 266.1 438.6 278.6z"/>
        </svg></a>
        </div>
        <span class="left-btn" v-on:click=" count -= 1" @click="increment"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 512"><!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M64 448c-8.188 0-16.38-3.125-22.62-9.375c-12.5-12.5-12.5-32.75 0-45.25L178.8 256L41.38 118.6c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0l160 160c12.5 12.5 12.5 32.75 0 45.25l-160 160C80.38 444.9 72.19 448 64 448z"/></svg></span>
        <span class="right-btn" v-on:click="count++" @click="increment"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 512"><!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M64 448c-8.188 0-16.38-3.125-22.62-9.375c-12.5-12.5-12.5-32.75 0-45.25L178.8 256L41.38 118.6c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0l160 160c12.5 12.5 12.5 32.75 0 45.25l-160 160C80.38 444.9 72.19 448 64 448z"/></svg></span>
    </section>
    
</template>

<style>

.main-presentation{
    width: 100%;
    height: 85vh;
    background-color:lightgrey;
    position: relative;
}
img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}

.text{
    width: 80%;
    display:flex;
    justify-content: start;
    align-items: flex-start;
    flex-direction: column;
    margin: 0 auto;
    position: relative;
    z-index: 100;
}

h1{
    font-size: 96px;
    color: white;
}



.contactUs{
  width: 270px;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  background-color: #8EA8C3;
  transition: 300ms ease-in-out;
  border-radius: 25px;
  cursor: pointer;
  text-decoration: none;
  margin-top: -80px
  
}

.bg{
    position: absolute;
    height: 100%;
    width: 100%;
    object-fit: cover;
}


.bg-1{
    width: 100%;
    height: 100%;
    display: flex;
    position: absolute;
    z-index: 10;
    transition: 300ms ease-in-out;
    object-fit: cover;
}

.bg-2{
    width: 100%;
    height: 100%;
    background-color:black;
    display: flex;
    position: absolute;
    z-index: 10;
    transition: 300ms ease-in-out;
}

.bg-3{
    width: 100%;
    height: 100%;
    background-color:blue;
    display: flex;
    position: absolute;
    z-index: 10;
    transition: 300ms ease-in-out;
}



.left-btn{
    width: 50px;
    height: 50px;
    background: rgba(255, 255, 255, 0.43);
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    position: absolute;
    left: 20px;
    top : 45%;
    z-index: 100;
    cursor: pointer;
}

.left-btn > svg {
    width: 70%;
    height: 70%;
    fill: #CBF7ED;
    transform: rotate(180deg);
}

.left-btn:hover{
    margin-top: 2px;
}

.right-btn{
    width: 50px;
    height: 50px;
    background: rgba(255, 255, 255, 0.43);
    display: flex;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    position: absolute;
    right: 20px;
    top : 45%;
    z-index: 100;
    cursor: pointer;
}

.right-btn > svg {
    width: 70%;
    height: 70%;
    fill: #CBF7ED;
}

.right-btn:hover{
    margin-top: 2px;
}

.contactUs> svg{
  width: 0%;
  height: 80%;
  fill: white;
  transition: 300ms ease-in-out;
}

.contactUs > h2{
  color: white;
  transition: 300ms ease-in-out;
  line-height: 0;
  font-weight: 400;
}


.contactUs:hover > svg{
  width: 15%;
  margin-left: 10px;
}
</style>

<script>
export default{
    data(){
        return{
            count : 0
        }
    },
    methods: {
        increment() {
        console.log(this.count)
        if(this.count > 3){
            this.count = 3
        } else if(this.count < 0){
            this.count = 0
        }
    }
  },
}
</script>
