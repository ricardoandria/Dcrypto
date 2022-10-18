<template>
  <div class="footer_container">
    <ul class="footer_item">
      <h2>FAQ</h2>
      <li>Fee Schedule</li>
      <li>Account</li>
      <li>Margin Trading</li>
      <li>How to File an Inquiry</li>
      <li>Customer Relationship Summary</li>
    </ul>
    <ul class="footer_item">
      <h2>About Ethereal</h2>
      <li>Our story</li>
      <li>Careers</li>
      <li>Blog</li>
      <li>BrokerCheck</li>
      <li>Our Execution Quality</li>
      <li>Script Editor</li>
    </ul>
    <ul class="footer_item">
      <h2>Term & Conditions</h2>
      <li>Privacy Policy</li>
      <li>Business Continuity Plan</li>
      <li>Disclosures</li>
      <li>Data Disclaimer</li>
    </ul>
    <ul class="footer_item contact">
      <h2>Contact us</h2>
      <li>exampleservices@d-cryptage.io</li>
      <li>+1 (888) 828-0816</li>
      <div class="social_container">
        <img src="../assets/img/social/fb.png" alt="" />
        <img src="../assets/img/social/google.png" alt="" />
        <img src="../assets/img/social/linkin.png" alt="" />
        <img src="../assets/img/social/tweeter.png" alt="" />
      </div>
    </ul>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.footer_container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  width: 80%;
  margin: 0 auto;
  padding: 100px 0;
  @media (max-width: 900px) {
    justify-content: space-around;
    width: 100%;
    .contact {
      text-align: end;
      .social_container {
        justify-content: flex-end;
      }
    }
  }
  @media (max-width: 550px) {
    flex-direction: column;
    justify-content: center;
    .footer_item {
      text-align: center;
    }
    .contact {
      text-align: center;

      .social_container {
        justify-content: center;
      }
    }
  }
  .footer_item {
    margin-bottom: 20px;
    h2 {
      margin-bottom: 20px;
    }
    li {
      font-weight: 600;
      margin-bottom: 10px;
    }
    .social_container {
      display: flex;
      gap: 20px;
      img {
        width: 30px;
      }
    }
  }
}
</style>
