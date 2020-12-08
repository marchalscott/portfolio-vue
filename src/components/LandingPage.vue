<template>
  <div class="menu">
    <div class="menu-item">
        Resume
    </div>
    <div class="menu-item ">
        Work
    </div>
    <div class="menu-item">
        About
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
}

.menu-item {
    flex: 1;
    border: 1px solid red;
    text-align: center;
}
</style>