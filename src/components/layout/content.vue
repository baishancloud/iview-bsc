<template>
    <div :class="wrapClasses"><slot></slot></div>
</template>
<script>
    const prefixCls = 'bsc-layout';
    export default {
        name: 'Content',
        computed: {
            wrapClasses () {
                return `${prefixCls}-content`;
            }
        }
    };
</script>