<template>
    <JqxSplitter :theme="'material'" 
        :width="850" :height="400" :orientation="'horizontal'"
        :panels="[{ size: 100 }, { size: 300 }]">
        <div class="splitter-panel">
            Panel 1
        </div>
        <div class="splitter-panel">
            Panel 2
        </div>
    </JqxSplitter>
</template>

<script>
    import JqxSplitter from 'jqwidgets-scripts/jqwidgets-vue/vue_jqxsplitter.vue';

    export default {
        components: {
            JqxSplitter
        }
    }
</script>

<style>
  
   
</style>