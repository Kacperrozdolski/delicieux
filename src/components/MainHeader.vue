<template>
  <nav>
    <div class="logo"><h1>expice</h1></div>
    <menu>
      <ul>
        <li>Menu One</li>
        <li>Menu Two</li>
        <li>Menu Three</li>
        <li>Menu Four</li>
      </ul>
    </menu>
    <div class="user-panel">
      <div class="user-icon">
        <img src="@/assets/user-circle.svg" alt="" />
        <div class="user-dot"></div>
      </div>
      <div class="user-text">
        <p>User</p>
        <img src="@/assets/user-arrow.svg" alt="" />
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
nav {
  width: 90%;
  height: 100px;
  display: flex;
  align-items: center;
  position: absolute;
  .logo {
    width: 15%;
    h1 {
      font-weight: 700;
      color: #35cd8c;
      font-size: 3.5rem;
      margin: 0;
    }
  }
  menu {
    width: 80%;
    display: flex;
    align-items: center;
    justify-content: left;
    ul {
      width: 70%;
      display: flex;
      list-style-type: none;
      justify-content: space-evenly;
      padding: 0;
      color: #2e266f;
      li {
        font-size: 1rem;
      }
    }
  }
  .user-panel {
    width: 15%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;

    .user-icon {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      background: white;
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      .user-dot {
        position: absolute;
        border-radius: 50%;
        width: 12px;
        height: 12px;
        top: 0;
        right: 0;
        background: #31a24c;
      }
    }
    .user-text {
      display: flex;
      p {
        margin-left: 5px;
        margin-right: 5px;
      }
    }
  }
}
</style>
