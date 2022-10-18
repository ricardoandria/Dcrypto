<template>
  <div class="time_container">
    <div class="leftside">
      <h1>Full Extended Hours Trading</h1>

      <p>
        Ethereal supports full extended hours trading, which includes full
        pre-market (4:00 AM - 9:30 AM ET) and after hours (4:00 PM - 8:00 PM ET)
        sessions.
      </p>
    </div>
    <div class="rightside">
      <img src="../assets/img/Time.png" alt="" />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.time_container {
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
      width: 50%;
    }
  }
}
</style>
