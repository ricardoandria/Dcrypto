<template>
  <div class="heros_container">
    <div class="heros_wrapper">
      <div class="heros_left">
        <h1 class="heros_title">
          <span class="banner_title"
            >A Smarter, <br />
            More secure</span
          >
          way to trade <span class="crypto_title">Crypto</span>
        </h1>
        <p class="description">
          The future of digital currencies. <br />
          Reciprocal Interchange, <br />
          Mutual Trading.
        </p>
        <button>Get Started</button>
      </div>
      <div class="heros_right">
        <img src="../assets/img/heroImg.png" alt="" />
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.heros_container {
  width: 100%;
  height: calc(100vh - 138.31px);
  background: #051b3b;

  .heros_wrapper {
    width: 80% !important;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto;
    padding-top: 100px;
    @media (max-width: 1050px) {
      padding-top: 100px !important;

      .heros_title {
        font-size: 3.5rem !important;
      }
      .heros_right {
        text-align: center;
      }
    }
    @media (max-width: 460px) {
      padding: 0px !important;
      width: 100% !important;
      padding-top: 100px !important;
    }

    .heros_left {
      width: 50%;
      .heros_title {
        font-size: 4rem;
        max-width: 550px;
        color: white;
        @media (max-width: 741px) {
          font-size: 2.5rem !important;
        }
        @media (max-width: 460px) {
          font-size: 2rem !important;
          line-height: 2.5rem;
        }

        .banner_title {
          text-decoration: underline;
        }
        .crypto_title {
          color: #9abcfe;
        }
      }
      .description {
        color: #fff;
        font-weight: 600;
        font-size: 1.5rem;
        margin: 10px 0;
        @media (max-width: 673px) {
          font-size: 1rem;
        }
      }
      button {
        margin-top: 50px;
        font-size: 1.5rem;
        font-weight: 600;
      }
    }
    .heros_right {
      width: 50%;
      text-align: end;
      img {
        width: 80%;
      }
      @media (max-width: 460px) {
        display: none;
      }
    }
  }
}
</style>
