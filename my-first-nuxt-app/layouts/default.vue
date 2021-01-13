<template>
  <div>
    <span> single layout </span>
    <Header /> 
    <!-- //Header出力位置 -->
    <main>
      <hr>
        <nuxt />
        <nuxt-link to="/">トップへ戻る</nuxt-link>
      <hr>
    </main>
    <Footer />
    <!-- //fotter出力位置 -->
  </div>
</template>

<script>
import Header from '~/components/header.vue' //インポート
import Footer from '~/components/fotter.vue' //インポート

export default {
  components:{
    Header, //宣言
    Footer //宣言
  }
};
</script>