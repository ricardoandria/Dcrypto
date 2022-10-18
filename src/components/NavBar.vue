<template>
  <div class="navbar_container">
    <div class="navbar_wrapper">
      <div class="logo_wrapper">
        <img src="../assets/img/logo.png" alt="" />
      </div>
      <div :class="[toggleNav ? 'navigation_wrapper' : 'dn ']">
        <ul class="nav_links">
          <li>
            <a href="">Features</a>
          </li>
          <li>
            <a href="">Features</a>
          </li>
          <li>
            <a href="">Features</a>
          </li>
          <li>
            <a href="">Features</a>
          </li>
          <li>
            <a href="">Features</a>
          </li>
          <div class="btn_log">
            <button>Log In</button>
            <button>Sign Up</button>
          </div>
        </ul>
      </div>
      <img
        class="menu_btn"
        src="../assets/img/menu.png"
        alt=""
        @click="handleToggle"
      />
    </div>
  </div>
</template>
<script type="module">
export default {
  data() {
    return {
      toggleNav: false,
    };
  },
  methods: {
    handleToggle() {
      this.toggleNav = !this.toggleNav;
      const menubtn = document.querySelector(".menu_btn");
      const navLinks = document.querySelector(".nav_links");

      menubtn.addEventListener("click", () => {
        navLinks.classList.toggle("mobile-menu");
      });
    },
  },
};
</script>
<style lang="scss" scoped>
.nav_links {
  display: flex;
  align-items: center;
  gap: 20px;
  .btn_log {
    display: flex;
    align-items: center;
    gap: 10px;
  }
}
.navbar_container {
  width: 100%;
  background: #051b3b;

  .navbar_wrapper {
    width: 80%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 0 auto;
    padding: 20px 0;
    @media (max-width: 1050px) {
      width: 100%;
      padding: 20px;
    }
    @media (max-width: 900px) {
      padding: 0;
    }

    .logo_wrapper {
      img {
        width: 100px;
      }
    }
    @media (max-width: 900px) {
      .dn {
        display: none;
        .nav_links {
          display: flex;
          align-items: center;
          gap: 20px;
          .btn_log {
            display: flex;
            align-items: center;
            gap: 10px;
          }
        }
      }
    }
    .navigation_wrapper {
      @media (max-width: 900px) {
        background: rgba(255, 255, 255, 0.2);
        backdrop-filter: blur(8px);
        width: 100%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;

        ul {
          display: flex;
          flex-direction: column;
          align-items: center;

          li {
            margin: 25px 0;
            font-size: 1.2rem;
          }
        }
      }
    }
    .menu_btn {
      width: 30px;
      position: absolute;
      right: 35px;
      top: 35px;
      display: none;

      @media (max-width: 900px) {
        display: block;
      }
    }
  }
}
</style>
