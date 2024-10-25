<template>
    <div class="min-h-screen min-w-screen gradient">
        <!--This is only for phone screens-->
        <div class="bg-slate-900 h-3 w-full sm:hidden"></div>
        <!--This is only for phone screens-->
        <div>
            <titlelink />     
        </div>
        <div class="flex justify-center py-3 px-3 sm:justify-start sm:justify-start">
            <img src="/public/schedulerpic.svg" alt="schedule img" class="size-80">
        </div>

        <!--This is only for phone screens-->
        <div class="flex-col h-72 justify-center relative sm:hidden">
            <h1 class="modak text-center text-2xl">Simplify your college <br> experience!</h1>
        
            <img src="/public/MyScheduler.svg" alt="myscheduler" class="size-64 absolute top-0 right-10">
            
            <img src="/public/morebubble.svg" alt="bubble" class="size-60 absolute top-28 left-10">
        </div>
        <!--This is only for phone screens-->

        <div class="flex justify-center p-12">
            <h1 class="righteous text-2xl text-center">We're here to help you succeed. <br> <span class="speed">Graduate fast!</span></h1>
        </div>

        <div class="grid grid-rows-2 p-8 justify-items-center gap-y-16">
            <div>
                <img src="/public/1stbtmimg.svg" alt="left img" class="size-60">
                <h1 class="text-center righteous text-xl">No need to worry<br> about how it can be done.</h1>
            </div>
            
            <div>
                <img src="/public/middleimg.svg" alt="left img" class="size-60">
                <h1 class="righteous text-center text-xl">Become a college graduate!</h1>
            </div>

            <div>
                <img src="/public/rightimg.svg" alt="right img" class="size-60">
                <h1 class="righteous text-center text-xl">Plan for success.</h1>
            </div>
        </div>
        <!--This is only for phone screens-->
        <div class="bg-slate-900 h-3 w-full sm:hidden"></div>
        <!--This is only for phone screens-->
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
    .modak{
        font-family: 'Modak'
    }
    .righteous{
        font-family: 'Righteous';
    }
    .speed{
        font-family: 'Faster One'
    }
</style>