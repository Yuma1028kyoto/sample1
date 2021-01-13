<template>
  <section >
    <div>
      <h1> Index page </h1>
      <div class="daibubun">
        <div class="sikaku"><p>四角</p></div>
        <div class="sikaku"><p>四角</p></div>
        <div class="sikaku"><p>四角</p></div>
        <div class="sikaku"><p>四角</p></div>
        <div class="sikaku"><p>四角</p></div>
        <div class="sikaku"><p>四角</p></div>
        <div class="sikaku"><p>四角</p></div>
        
        
      </div>
    </div>
  </section>
</template>

<script>
export default {
  layout: 'home'
}
</script>

<style>
.container {
  min-height: 100vh;
  padding: 16px;
}
h3 {
  margin: 16px 0;
  padding: 8px 0;
  border-bottom: solid 1px #e5e5e5;
}
li + li {
  margin: 16px 0;
}
p {
  margin: 8px 0;
}
.daibubun{
  max-width: 600px;
  display: flex;
  flex-wrap: wrap;
  margin: 100px;
}
.sikaku{
  display: flex;
  justify-content: center;
  align-items: center;
  height: 200px;
  width: 300px;
  border: solid 1px #000000;
}
</style>