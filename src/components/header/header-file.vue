<script lang="ts">
import "./header.scss"
    export default {
        data(){
            const modes: Object = {
                    'easy': 5,
                    'medium':10,
                    'hard':20
            }
            const selectedMode: Object | null = null
            return {
                modes,
                selectedMode
            }
        }
    }
</script>
<template>
    <div class="header">
        <ul class="menu">
            <li v-for="(val, key) in modes">
                <button 
                class="menu-button"
                
                >
                {{key}}
                </button>
            </li>
        </ul>
    </div>
</template>