<template>
    <div>
        <ul>
            <li>{{book.title}} : {{book.author}}</li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: 'BookItem',
        props: ['book'],
    }
</script>

<style lang="scss" scoped>
li {
  display: block;
  margin: 0 10px;
}
</style>