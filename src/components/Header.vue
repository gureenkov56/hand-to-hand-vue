<template lang="">
  <div id='header'>
    <div id="header__wrapper">
      <div class="header__siteName">Hand-To-Hand</div>
      <div class="header__searchAndFilters">
        <div class="searchAndFilters__category">категория</div>
        <div class="searchAndFilters__city">Город</div>
        <div class="searchAndFilters__search">Search</div>
        <div class="searchAndFilters__searchButton">Find</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped>
  #header{
    width: 100%;
    box-shadow: 0px 2px 10px grey;
  }
  #header__wrapper{
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }
  .header__siteName{
    font-weight: 1000;
    margin-bottom: 10px;
  }
  .header__searchAndFilters{
    background-color: #7e47fd;
    border-radius: 4px;
    display: flex;
  }
  .searchAndFilters__category,
  .searchAndFilters__city,
  .searchAndFilters__search{
    background-color: #fff;
    border-radius: 4px;
    margin: 4px;
    padding: 5px 10px;
  }
  .searchAndFilters__search{
    flex: 1;
  }
  .searchAndFilters__searchButton{
    margin: 4px;
    padding: 5px 10px;
    color: white;
  }
</style>