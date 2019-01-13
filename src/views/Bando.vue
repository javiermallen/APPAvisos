<template>
    <div class="contenedor">
        <nav-atras />
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h2 class="tex-center">Últimos bandos</h2>

<!--                     <bandos-alerta />
 -->                </div>
            </div>
        </div>
    </div>
</template>

<script>
/* import Bandosalerta from '@/components/Bandosalerta.vue' */
import Navatras from '@/components/Navatras.vue'
export default {
    name: 'Bando',
    components: {
        /* 'bandos-alerta': Bandosalerta, */
        'nav-atras': Navatras
    }
}
</script>

<style>
    .contenedor {
        padding-top: 4rem;
    }
    
</style>