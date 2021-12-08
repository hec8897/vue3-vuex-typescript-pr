<template>
    <div>
        <phoneList/>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import phoneList from './list.vue'

export default defineComponent({
    components:{phoneList}
})
</script>
