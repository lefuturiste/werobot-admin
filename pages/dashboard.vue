<template>
    <div>Ceci n'est un dashboard</div>
</template>

<script>
export default {
    mounted () {
		this.$store.commit('SET_TITLE', 'Dashboard')
    }
}
</script>
