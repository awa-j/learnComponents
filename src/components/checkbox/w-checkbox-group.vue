<template>
    <div></div>
</template>

<script>
import Emitter from '@/mixins/emitter.js';
export default {
    props: {
        model: {
            type: String,
            default: '',
        }
    },
    mixins: [Emitter],
    
}
</script>