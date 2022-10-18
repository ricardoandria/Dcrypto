<template>
  <div class="connect_container">
    <div class="leftside">
      <h1>Stay Connected 24/7</h1>

      <p>
        Our customer service reps are ready 24/7 to help guide you through our
        multiple platforms and answer all your questions!
      </p>
    </div>
    <div class="rightside">
      <img src="../assets/img/connect.png" alt="" />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.connect_container {
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
