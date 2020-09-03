<template>
  <div class="header">
    <div class="header--content">
      <div class="logo">
        <img
          src="https://www.edigitalagency.com.au/wp-content/uploads/instagram-logo-text-black-png.png"
          alt="Instagram"
          class="ig-logo"
        />
      </div>

      <div class="searchbox">
          <input type="text" 
          class="searchtext" 
          v-bind:placeholder="$t('home.placeholder')">
      </div>
      <div class="actions"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
.header {
  position: fixed;
  top: 0;
  width: 100%;
  height: 54px;
  align-items: center;
  display: flex;
  justify-content: center;
  background-color: white;
  margin-bottom: 10px;

  &--content {
    max-width: 975px;
    width: 100%;
    padding: 0 20px;
    flex-direction: row;
    display: flex;

    .logo {
      flex: 1 9999 0%;
      min-width: 40px;

      .ig-logo {
        width: 103px;
        height: 29px;
      }
    }

    .searchbox {
      flex: 0 1 auto;
      min-width: 125px;
      width: 215px;

      .searchtext {
          background-color: #f1f2f5;
          border: solid 1px #dbdbdb;
          border-radius: 5px;
          justify-content: center;
          font-size: 16px;
      }
    }

    .actions {
        align-content: center;
        display: flex;
        flex: 1 0 0%;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: flex-end;
    }
  }
}
</style>