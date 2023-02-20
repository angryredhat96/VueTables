<template>
<div class="app">
<NavBar />
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

</style>