<template>
  <div class="booking-section">
    <img src="@/assets/lettuce1.png" class="lettuce" />
    <img src="@/assets/lettuce1.png" class="lettuce1" />
    <div class="booking-container">
      <div class="content-wrapper">
        <h1>advance booking</h1>
        <input type="text" placeholder="search restaurant" />
        <table class="date-table">
          <tr>
            <th>Date</th>
            <th>Time</th>
            <th>Guests</th>
          </tr>
          <tr>
            <td>23-09-2020</td>
            <td>5:00 PM</td>
            <td>3 People</td>
          </tr>
        </table>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.booking-section {
  width: 100%;
  height: 100vh;
  background: #ffedde;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  overflow: hidden;
}
.lettuce {
  position: absolute;
  left: -25%;
  width: 57%;
  transform: rotate(10deg);
  z-index: 1;
}
.lettuce1 {
  position: absolute;
  right: -25%;
  width: 54%;
  transform: rotate(-20deg);
  z-index: 1;
}
.booking-container {
  width: 60%;
  height: 60%;
  background: white;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
}
.content-wrapper {
  width: 60%;
  height: 60%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: column;
}

h1 {
  position: relative;
  font-weight: 700;
  color: #2e266f;
  margin: 0;
}
h1::after {
  content: "";
  width: 70%;
  height: 15px;
  background: #35cd8c;
  top: -15px;
  left: 15%;
  position: absolute;
}
input {
  width: 60%;
  height: 45px;
  outline: 1px solid #fff5ec;
  border: 1px solid #35cd8c;
}

input::placeholder {
  color: #2e266f;
}

.date-table {
  width: 60%;
  text-align: left;
  color: #2e266f;
  font-weight: 300;
}
.date-table th {
  font-weight: 500;
  text-align: left;
}
</style>
