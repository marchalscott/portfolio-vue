<template>
  <div class="menu">
    <div class="menu-item">
        <a href = "" target = "_blank"> Home </a>
    </div>
    <div class="menu-item">
        <a href = "" target = "_blank"> Work Examples </a>
    </div>
    <div class="menu-item">
        <a href = "" target = "_blank"> Portfolio </a>
    </div>
    <div class="menu-item">
        <a href = "" target = "_blank"> Social </a>
    </div>
    <div class="menu-item">
        <a href = "" target = "_blank"> About </a>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.menu {
    display: flex;
    align-items: center;
    justify-content: space-around;
    text-decoration: none;
}

.menu-item {
    color: black;
    flex: 1;
    font-family: -apple-system, BlinkMacSystemFont, Roboto, Oxygen, Ubuntu, Cantarell, Helvetica, sans-serif;
    text-align: center;
    text-decoration: none;
}
</style>