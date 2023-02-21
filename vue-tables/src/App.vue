<template>
<div class="app">
<NavBar />
<DatePage />
</div>
</template>

<script>
import NavBar from './components/ui/NavBar'
import DatePage from './components/pages/DatePage'
import TimePage from './components/pages/TimePage'

export default {
    components: {
        NavBar, DatePage, TimePage
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