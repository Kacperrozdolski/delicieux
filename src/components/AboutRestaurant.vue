<template>
  <div class="about-restaurant">
    <div class="about-header">
      <h1>Some Tope Restaurant For Dining In Or Take Away!</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sequi eveniet,
        sapiente expedita dolor amet ratione architecto placeat repudiandae,
        sint voluptatibus laborum obcaecati magnam deleniti et? Quam, ex.
        Quibusdam, numquam voluptas!
      </p>
    </div>
    <div class="about-body">
      <div class="about-cell">
        <div class="about-card">
          <img src="@/assets/about1.png" alt="" />
          <div class="about-card-content">
            <h1>The Wonton</h1>
            <p>
              we are all about we are all about to the fullest and all content
              dining out or in!dining out or in!
            </p>
            <h2>Newcastle City</h2>
          </div>
        </div>
      </div>
      <div class="about-cell">
        <div class="about-card">
          <img src="@/assets/about2.jpg" alt="" />
          <div class="about-card-content">
            <h1>Fire Water</h1>
            <p>
              we are all about we are all about to the fullest and all content
              dining out or in!dining out or in!
            </p>
            <h2>Bristol City</h2>
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
.about-restaurant {
  width: 100%;
  height: 100vh;
  background: #fff5ec;
  padding-top: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  .about-header {
    width: 90%;
    height: 20%;
    display: flex;
    h1 {
      color: #2e266f;
      font-size: 2rem;
      width: 45%;
      position: relative;
      margin-left: 30px;
    }
    h1:before {
      content: "";
      position: absolute;
      background: #35cd8c;
      bottom: 0;
      left: -30px;
      height: 100%;
      width: 25px;
    }
    p {
      width: 40%;
      color: #707070;
      font-size: 1rem;
    }
  }
  .about-body {
    height: 80%;
    width: 90%;
    display: flex;
    .about-cell {
      height: 100%;
      margin-right: 20px;
      display: flex;
      align-items: center;
      .about-card {
        height: 70%;
        position: relative;
        img {
          height: 100%;
          border-radius: 1.5rem;
        }
        .about-card-content {
          position: absolute;
          z-index: 1;
          bottom: 0;
          height: 40%;
          width: 100%;
          border-radius: 0 0 1.5rem 1.5rem;
          background: #35cd8bd0;
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
          color: white;
          h1 {
            margin: 0 0 5px 0;
            width: 80%;
            font-size: 1.25rem;
            font-weight: 900;
          }
          p {
            width: 80%;
            margin: 0 0 5px 0;
            font-size: 0.75rem;
            font-weight: 300;
          }
          h2 {
            width: 80%;
            margin: 0;
            font-size: 0.75rem;
            font-weight: 300;
          }
        }
      }
    }
  }
}
</style>
