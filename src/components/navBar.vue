<script setup>
import Home from '../App.vue'
import Docenten from '../Docenten.vue'

const routes = [
    { path: '/', component: Home },
    { path: '/docenten', component: Docenten },
];
console.log(routes)

</script>

<template>
    <div>
        <div class="title">
            <p>Zangschool De Nachtegaal</p>
        </div>
        <div class="navbar">
            <li><a href="#/">Home</a></li>
            <li><a href="#/docenten">Docenten</a></li>
            <li><a href="#">Zanglessen</a></li>
            <li><a href="#">Prijzen</a></li>
            <li><a href="#">Contact</a></li>
        </div>
    </div>
</template>
