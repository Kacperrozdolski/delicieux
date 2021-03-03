<template>
  <div class="hero-page">
    <div class="hero-page-container">
      <div class="hero-text">
        <div class="text">
          <h1>Food</h1>
          <h3>Discover Restaurant <br />& Delicus Food</h3>
          <input placeholder="Search restaurant, Food" type="text" />
        </div>
      </div>
      <div class="hero-image-container">
        <div class="hero-image">
          <img src="@/assets/food1.png" alt="" />
          <img src="@/assets/salad.png" class="salad" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style lang="scss" scoped>
.hero-page {
  width: 100%;
  height: 100vh;
  background: -webkit-linear-gradient(
    left,
    #fff5ec,
    #fff5ec 72.5%,
    #35cd8c 27.5%,
    #35cd8c
  );
  display: flex;
  justify-content: center;
  .hero-page-container {
    margin-top: 100px;
    max-height: 100%;
    width: 90%;
    position: relative;
    display: flex;
    .hero-text {
      width: 50%;
      height: 100%;
      display: flex;
      justify-content: center;
      .text {
        width: 70%;
        margin-top: 50px;
        h1 {
          font-size: 8rem;
          margin: 0;
          font-weight: 900;
          color: #30248e15;
        }
        h3 {
          color: #2e266f;
          font-size: 2.5rem;
          margin: 0;
        }
        input {
          width: 100%;
          height: 60px;
          padding: 0;
          margin: 0;
          border: 0;
        }
        input::placeholder {
          color: #2e266f;
          font-family: Poppins;
          padding-left: 25px;
        }
      }
    }
    .hero-image-container {
      width: 50%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      .hero-image {
        display: flex;
        justify-content: center;
        align-items: center;
        position: relative;
        img {
          z-index: 2;
          width: 70%;
        }
        .salad {
          z-index: 1;
          position: absolute;
          width: 60%;
          top: -100px;
        }
      }
    }
  }
}
</style>