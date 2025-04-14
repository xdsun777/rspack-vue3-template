<template>
    <div id="app">
        <button @click="count++">{{ count }}</button>
        <img src="@assets/navbar-logo-dark.png" alt="rspack logo" width="200" height="200" />
    </div>
</template>

<script>
export default {
    data() {
        return {
            count: 0
        }
    }
}
</script>

<style></style>