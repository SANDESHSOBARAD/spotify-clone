<script setup>
import {ref, toRefs, watchEffect} from 'vue';
import {useRoute} from 'vue-router';
const route = useRoute()

const props = defineProps({
    iconString: String,
    iconSize: Number,
    pageUrl: String,
    name: String,
})

const {iconString, pageUrl, name, iconSize} = toRefs(props)

let icon = ref(null)
let textIsHover = ref(false)


</script>


<template>
    <div>

    </div>
</template>



<style lang="scss" scoped>

</style>