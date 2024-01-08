<script>
    export default {
        data() {
            return {
                count: 0,
            };
        },
        methods: {
            incrementCount() {
                this.count++;
            }
        },
    };
</script>

<template>
    <div>
        {{ count }}
    </div>
    <button @click='incrementCount'>
        ++
    </button>
    <div>
        main body
    </div>
    <div>
        footer
    </div>
</template>

