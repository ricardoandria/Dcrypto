<template>
  <div class="analyse_container">
    <div class="leftside">
      <h1>Full Extended Hours Trading</h1>

      <p>
        Ethereal supports full extended hours trading, which includes full
        pre-market (4:00 AM - 9:30 AM ET) and after hours (4:00 PM - 8:00 PM ET)
        sessions.
      </p>
      <span>learn more</span>
    </div>
    <div class="rightside">
      <img src="../assets/img/phone.png" alt="" />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.analyse_container {
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
      margin-bottom: 20px;
    }
    span {
      font-weight: 600;
      color: #2919e2;
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
