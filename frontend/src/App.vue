<script>
export default{
  data(){
    return{
      likes: 0,
    }
  },
  methods: {
    addLike(){
      this.likes += 1;
      return this.likes;
    },
    removeLike(){
      this.likes -= 1;
      return this.likes;
    }
  }
}
</script>

<template>
  <div>
Заглушка
  </div>
</template>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
