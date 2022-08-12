<script lang="ts">
import { defineComponent } from 'vue';

    export default defineComponent({
        
        data(){
            const board: Array<Array<number>> = []  
            return {
                board
            }
        },
        created(){
            this.board 
        }
    })
</script>

<template>

</template>