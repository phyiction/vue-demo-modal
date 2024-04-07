<script setup>

const props = defineProps(['id', 'title','buttonText'])
</script>

<template>
    <div :id="id" class="modal-window">
        <div>            
            <a href="#" title="close" class="modal-close">Close</a> 
            <h1>{{ title }}</h1>
            <div class="content">
                <slot />        
            </div>
        </div>
    </div>
</template>