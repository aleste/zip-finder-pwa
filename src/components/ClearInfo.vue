<template>
    <ion-button 
        color="light" 
        expand="block"
        v-if="info"
        @click="$emit('clear-info')"
        >
        Limpiar
    </ion-button>
</template>

<script>
export default {
    name: "ClearInfo",
    props: ["info"]
}
</script>

