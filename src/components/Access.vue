<template>
  <div class="access_container">
    <div class="leftside">
      <h1>Free Access to Etheral Desktop</h1>

      <p>
        Everyone has access to our advanced and fully customizable desktop
        platform. You can consolidate your watchlists, analyze charts, place
        orders, and check your positions across all of Ethereal's platforms
        (mobile, PC, and web). Stay current with the markets and manage your
        investments wherever you are.
      </p>
    </div>
    <div class="rightside">
      <img src="../assets/img/pc.png" alt="" />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.access_container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 80%;
  padding: 100px 0;
  margin: 0 auto;
  .leftside {
    width: 50%;
    h1 {
      max-width: 400px;
      margin-bottom: 50px;
    }
    p {
      max-width: 500px;
      font-weight: 600;
      font-size: 1.2rem;
    }
  }
  .rightside {
    width: 50%;
    text-align: center;
    img {
      width: 70%;
    }
  }
}
</style>
