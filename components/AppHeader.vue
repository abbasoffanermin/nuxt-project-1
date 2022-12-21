<template>
    <div>
        <ul>
            <li>
             <NuxtLink to="/" class="home">Home</NuxtLink>   
            </li>
            <li>
             <NuxtLink to="/aboutpage">About</NuxtLink>   
            </li>
            <li>
             <NuxtLink to="/samplepost">Sample Post</NuxtLink>   
            </li>
            <li>
             <NuxtLink to="/contact">Contact</NuxtLink>   
            </li>
           
            
        </ul>
    </div>
</template>

<style>
ul{
    display: flex;
    justify-content: end;
    margin-left: 20px;
}
li{
    text-decoration: none;
    margin-left: 20px;
}
</style>