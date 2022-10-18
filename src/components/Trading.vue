<template>
  <div class="trading_container">
    <div class="trading_header">
      <h1>Trading Privileges</h1>
      <p>
        Diversifying your portfolio with a comprehensive suite of investment
        product including stocks, fractional shares, options,ETFs,OTC, and ADRs
      </p>
    </div>
    <div class="card_container">
      <div class="card">
        <img src="../assets/img/stock.png" alt="" />
        <h5 class="card_title">Stocks</h5>
        <p class="card_desc">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure,
          dolorem.
        </p>
        <button class="card_btn" href="">Get started</button>
      </div>
      <div class="card">
        <img src="../assets/img/option.png" alt="" />
        <h5 class="card_title">Options</h5>
        <p class="card_desc">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure,
          dolorem.
        </p>
        <button class="card_btn" href="">Get started</button>
      </div>
      <div class="card">
        <img src="../assets/img/etfs.png" alt="" />
        <h5 class="card_title">ETFs</h5>
        <p class="card_desc">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure,
          dolorem.
        </p>
        <button class="card_btn" href="">Get started</button>
      </div>
      <div class="card">
        <img src="../assets/img/otc.png" alt="" />
        <h5 class="card_title">OTC</h5>
        <p class="card_desc">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure,
          dolorem.
        </p>
        <button class="card_btn" href="">Get started</button>
      </div>
      <div class="card">
        <img src="../assets/img/adrs.png" alt="" />
        <h5 class="card_title">ADRs</h5>
        <p class="card_desc">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure,
          dolorem.
        </p>
        <button class="card_btn" href="">Get started</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.trading_container {
  width: 80%;
  margin: 0 auto;
  padding: 150px 0;
  .trading_header {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    h1 {
      color: #361818;
      font-size: 40px;
      margin-bottom: 40px;
      font-weight: 700;
    }
    p {
      color: #361818;
      max-width: 650px;
      font-size: 24px;
      font-weight: 600;
      text-align: center;
    }
  }
  .card_container {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 50px;
    .card {
      width: 200px;
      padding: 10px;
      box-shadow: 0px 4px 30px 4px rgba(0, 0, 0, 0.15);
      border-radius: 30px;
      padding-bottom: 10px;

      img {
        width: 50px;
        padding-bottom: 10px;
      }
      .card_title {
        font-size: 20px;
        padding-bottom: 10px;
        font-weight: 800 !important;
      }
      .card_desc {
        font-size: 15px;
        font-weight: 600;
        padding-bottom: 10px;
      }
      .card_btn {
        float: right;
        background: white;
        color: #2919e2;
      }
    }
  }
}
</style>
