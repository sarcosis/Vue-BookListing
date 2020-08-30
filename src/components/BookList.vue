<template>
    <div>
        <h1>{{ title }}</h1>
        <ul>
            <li></li>
            <li></li>
            <li></li>
    </div>
</template>

<script>
    export default {
        name: 'BookList',
        data() {
            return {
                title: 'All Books'
                
            }
        },
    }
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: block;
    margin: 0 10px;
}
</style>