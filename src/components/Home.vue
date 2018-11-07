<template>
<div id="app">
    <button v-on:click="count++">Vous m'avez cliqué {{ count }} fois.</button>
</div>
</template>

<script>
export default {
  name: "Home",
    data: function() {
        return  {
            count : 0
        }
    }
}
</script>