<template>
    <div class="h-screen w-screen gradient">
        <div class="flex px-5 py-5">
            <h1 class="rubik text-2xl flex-auto"><span class="text-orange-400">My</span>Scheduler</h1>
            
            <button class="font-sans font-bold px-2"><a href="#">Log in</a></button>
            <button class="bg-black text-white rounded-full font-sans font-bold px-4 py-2"><a href="#">Sign up</a></button>      
        </div>
        <div class="flex px-8 py-8">
            <img class="w-[30rem] h-[30rem]" src="/public/schedulerpic.svg" alt="image of schedule">
            <h1>things</h1>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
    .gradient{
        
        background-color: rgb(209, 213, 219);
        background-image: radial-gradient(at 89% 5%, rgb(254, 215, 170) 0, transparent 54%);
    }
    .rubik{
        font-family: 'Rubik Glitch';
    }
</style>