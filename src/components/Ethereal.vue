<template>
  <div class="Ethereal_container">
    <div class="Ethereal_wrapper">
      <div class="leftside">
        <img src="../assets/img/ethereal.png" alt="" />
      </div>
      <div class="rightside">
        <h3>Open an Ethereal Account Now!</h3>

        <p class="p1">
          Open your Ethereal individual brokerage account and IRAs now!
        </p>

        <p class="p2">
          In order to verify your identity, a government issued ID card with
          your photo, name, and date of birth is required to open an account
          with Ethereal. Please have the documents prepared in advance.
        </p>

        <button>Open an Account</button>

        <p>
          *Ethereal Financial LLC is member of FINRA, SIPC, NASDAQ and NYSE.
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.Ethereal_container {
  width: 100%;
  background: #f3f4f5;
  .Ethereal_wrapper {
    display: flex;
    padding: 100px 0;
    .leftside {
      width: 50%;
      text-align: center;
      img {
        width: 50%;
      }
    }
    .rightside {
      width: 50%;
      display: flex;
      flex-direction: column;
      gap: 30px;
      p {
        font-weight: 600;
      }
      .p1 {
        max-width: 350px;
      }
      .p2 {
        max-width: 420px;
        line-height: 1.5rem;
      }
      button {
        width: fit-content;
      }
    }
  }
}
</style>
