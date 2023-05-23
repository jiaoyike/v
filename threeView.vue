<template>
  <div class="home-list">
    <header></header>
    <main>
      <p>1</p>
      <p>2</p>
      <p>3</p>
      <p>4</p>
      <p>5</p>
      <p>1</p>
      <p>2</p>
      <p>3</p>
      <p>4</p>
      <p>5</p>
      <p>1</p>
      <p>2</p>
      <p>3</p>
      <p>4</p>
      <p>5</p>
      <p>2</p>
    </main>
  </div>
</template>

<script>

</script>

<style lang="scss" scoped>
.home-list {
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: column;
  header {
    height: 50px;
    border: 1px solid;
    border-bottom: none;
  }
  main {
    flex: 1;
    overflow: auto;
    border: 1px solid;
  }
  footer {
    height: 50px;
    border: 1px solid;
    border-top: none;
  }
}
</style>