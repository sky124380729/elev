<template>
    <div>{{msg}}</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
    setup() {
        const msg = 'This is a component from elev-standard'
        return {
            msg
        }
    }
})
</script>