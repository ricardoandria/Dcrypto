<template>
  <div class="container">
    <div class="account_container">
      <div class="account_header">
        <h1>Account Types</h1>
        <p>
          Different types of brokerage accounts to satisfy your different
          investment objectives
        </p>
      </div>
      <div class="account_content">
        <div class="account_img">
          <img src="../assets/img/account.png" alt="" />
        </div>
        <div class="desc_account">
          <div class="card_account">
            <span class="profile">IRA</span>
            <div class="card_right">
              <h2 class="name">IRA</h2>
              <p class="card_details">
                Save for retirement with Ethereal Traditional, <br />
                Roth or Rollover IRA
              </p>

              <span class="btn">More</span>
            </div>
          </div>
          <div class="card_account">
            <span class="profile">IBA</span>
            <div class="card_right">
              <h2 class="name">Individual Brokerage Account</h2>
              <p class="card_details">
                Individual Brokerage Account Individual brokerage account is the
                general account which allows you to buy and sell securities and
                assets
              </p>

              <span class="btn">More</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.container {
  width: 100%;
  background-color: #ebecf8;
  .account_container {
    width: 80%;
    margin: 0 auto;
    padding: 100px 0;
    .account_header {
      display: flex;
      flex-direction: column;
      align-items: center;
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
  }
  .account_content {
    display: flex;
    margin-top: 100px;
    width: 100%;
    @media (max-width: 991px) {
      .account_img {
        display: none;
      }
      .desc_account {
        width: 100% !important;
      }
    }
    @media (max-width: 600px) {
      .desc_account {
        width: 100% !important;
      }
      .card_details {
        max-width: 300px;
      }
      .name {
        width: fit-content;
      }
    }
    .account_img {
      width: 50%;
      text-align: end;

      img {
        width: 100%;
        padding: 0;
      }
    }
    .desc_account {
      width: 50%;

      .card_account {
        display: flex;

        gap: 10px;
        margin-bottom: 20px;
        cursor: pointer;
        transition: ease-in 0.5s;
        padding: 5px;
        border-radius: 15px;
        &:hover {
          box-shadow: rgba(6, 24, 44, 0.4) 0px 0px 0px 2px,
            rgba(6, 24, 44, 0.65) 0px 4px 6px -1px,
            rgba(255, 255, 255, 0.08) 0px 1px 0px inset;
        }
        .profile {
          width: 50px;
          height: 50px;
          border-radius: 50%;
          background: #2919e2;
          display: flex;
          align-items: center;
          justify-content: center;
          color: white;
          font-weight: 600;
        }
        .card_right {
          width: 445px;

          .name {
            margin-bottom: 20px;
          }
          p {
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 30px;
          }
          .btn {
            color: #2919e2;
            font-weight: 600;
          }
        }
      }
    }
  }
}
</style>
