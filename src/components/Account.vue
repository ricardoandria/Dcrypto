<template>
  <div class="container" id="account">
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
    padding: 100px 0 50px 0;
    .account_header {
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
    .account_content {
      display: flex;
      width: 100%;
      margin-top: 50px;
      gap: 30px;

      .account_img {
        width: 40%;
        text-align: end;
        img {
          width: 70%;
        }
      }
      .desc_account {
        width: 60%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        .card_account {
          display: flex;
          justify-content: center;
          gap: 20px;
          padding: 10px;
          margin-bottom: 50px;
          border-radius: 20px;
          cursor: pointer;
          transition: all 0.5s ease;
          position: relative;
          &:hover {
            box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
          }
          @media (max-width: 1000px) {
            box-shadow: rgba(0, 0, 0, 0.02) 0px 1px 3px 0px,
              rgba(27, 31, 35, 0.15) 0px 0px 0px 1px;
          }
          .profile {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            box-shadow: rgba(50, 50, 93, 0.25) 0px 2px 5px -1px,
              rgba(0, 0, 0, 0.3) 0px 1px 3px -1px;
            display: flex;
            align-items: center;
            justify-content: center;
            @media (max-width: 1000px) {
              position: absolute;
              top: -25px;
              right: -10px;
              background-color: #6737c1;
              color: white;
            }
          }
          .card_right {
            .name {
              padding: 0;
              margin-bottom: 5px;
            }
            .card_details {
              font-weight: 700;
              margin-bottom: 30px;
              font-size: 1.2rem;
            }
            .btn {
              color: #263aa5;
              font-weight: 700;
            }
          }
        }
      }
    }
  }
}
</style>
