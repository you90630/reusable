# Headline > An awesome project.


<!-- Sequenced content (i.e. loop)-->
<div id="example">
    <ul>
        <li v-for="i in 3">Item {{ i }}</li>
    </ul>
</div>

<script>
    Vue.createApp({
        // Options...
    }).mount('#example');
</script>