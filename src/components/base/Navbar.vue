<template>
  <div class=" navbar columns is-gapless">
    <div class="column panels">
      <i class="fas fa-bars"></i>
    </div>
    <div class="column lists">
      Food Items
    </div>
    <div class="column search">
      <i class="fas fa-search"></i>
        <input type="text" class="form-control" id="inputSearch" placeholder="Search...">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>

<style lang="scss" scoped>
.columns.is-gapless:not(:last-child) {
    margin-bottom: 0;
}
.navbar{
    top: 0px;
    position: sticky;
    align-items: center;
    box-shadow: 4px 1px 5px rgba(0,0,0,0.2);
    display: flex;
}
.panels{
    font-size: 1.5em;
    margin-left: 20px !important;
    text-align: left;
    // border: 1px solid blue;
    margin-left: 10px;
  }

.lists {
  font-size: 1.5em;
  text-align: center;
  color: #000;
  font-weight: 600;
  margin: 10px !important;
}
.search{
    font-size: 1.5em;
    text-align: right;
    margin-right: 20px !important;
}
.filter {
  margin-top: -5px;
}
.form-control {
    margin-left: 45px;
}
.search {
    margin-left: 600px;
    margin-top: -33px;
    width: auto;
}
.search img {
    width: 30px;
    height: 30px;
}
</style>
