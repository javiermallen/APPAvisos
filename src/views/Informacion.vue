<template>
    <div class="contenedor">
        <nav-atras />
        <div>
            Información
        </div>
    </div>
</template>

<script>
import Navatras from '@/components/Navatras.vue'

export default {
    name: 'informacion',
    components: {
        'nav-atras': Navatras,

    }
}
</script>

<style>
    .contenedor {
        padding-top: 4rem;
    } 
</style>
