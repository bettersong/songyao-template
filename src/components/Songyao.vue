<template>
    <div>
        <h1>{{ username }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="http://47.100.126.169/zmengBlog" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    </div>
</template>

<script>
export default {
    name: 'songyao',
    data() {
        return {
            username: 'songyao-cli'
        }
    },
    created() {
        window.console.log(`%c ${this.username}.`, 'color: #fff; background-image: repeating-radial-gradient(circle at 30% 60%,#99CCCC 20px, #7171B7 20px, #7171B7 20px, #CCCC99 40px, #CCCC99 60px, #4F9C9C 30px, #4F9C9C 40px, #99CCCC 80px, #99CCCC 50px); font-size: 16px;border-radius:15px 0;padding:5px;');
        window.console.log('脚手架使用教程请看个人博客：47.100.126.169/zmengBlog')
    }
}
</script>

<style>

</style>