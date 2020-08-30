<template>
    <div>
        <h1>{{ title }}</h1>
        <ul>
<<<<<<< HEAD
          <li v-for="book in books" :key="book.title">{{ book.title }}:{{ book.author}}</li>
        </ul>
=======
            <li></li>
            <li></li>
            <li></li>
>>>>>>> e911da382a6623cda188aa5033332166b4d31650
    </div>
</template>

<script>
    export default {
        name: 'BookList',
        data() {
<<<<<<< HEAD
            return
            {
                books: [
                  {
                    title: 'Self-Reliance',
                    author: 'Ralph Waldo Emerson',
                  },
                  {
                    title: 'American Gods',
                    author: 'Neil Gaiman',
                  },
                  {
                    title: 'Amusing Ourselves to Death',
                    authlor: 'Neil Postman',
                  },
                ]
=======
            return {
                title: 'All Books'
                
>>>>>>> e911da382a6623cda188aa5033332166b4d31650
            }
        },
    }
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
}
<<<<<<< HEAD
ul{
  list-style-type: none;
  padding: 0;
}
li{
  display: block;
  margin: 0 10px;
}
</style>
=======
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: block;
    margin: 0 10px;
}
</style>
>>>>>>> e911da382a6623cda188aa5033332166b4d31650
