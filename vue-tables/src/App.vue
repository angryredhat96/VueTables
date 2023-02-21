<template>
<div class="app">
<NavBar />
<!-- <RouterLink to="/"><TimePage /></RouterLink>
<RouterLink to="/second"><DatePage /></RouterLink>
<RouterLink to="/table"><BaseTable /></RouterLink> -->
<BaseTable />
</div>
</template>

<script>
import NavBar from './components/ui/NavBar'
import DatePage from './components/pages/DatePage'
import TimePage from './components/pages/TimePage'
import BaseTable from './components/pages/BaseTable'
// import { RouterLink } from 'vue-router'


export default {
    components: {
        NavBar, DatePage, TimePage, BaseTable
    }
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }
    
    body {
    font-family: cursive;
    }
    
    a {
    text-decoration: none;
    }
    
    li {
    list-style: none;
    }
</style>