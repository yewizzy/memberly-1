<template>
  <!-- Navbar -->
  <div class="container-fluid mx-0 px-0">
    <div class="nav">
      <div class="container">
        <div class="bar">
          <div class="bar-logo"><img src="../../assets/social/memberly-logo.svg" /></div>
          <h5>Nigeria Bar Association</h5>
          <h6>Promoting the rule of law</h6>
        </div>
        <div class="register">
          <button class="button1">Sign In</button>
          <button class="button2">Sign Up</button>
        </div>
      </div>
    </div>
    <div class="member">
      <div class="container">
        <div class="work">
          <h2>MEMBERSHIP MANAGEMENT PORTAL</h2>
          <p>
            Nigeria Bar Association engage in the promotion and protection of
            Human Rights, the Rule of Law, and good governance in Nigeria
          </p>
        </div>
        <div class="member-1">
          <img src="../../assets/lawyer.png" />
        </div>
      </div>
    </div>

    <!-- CARD -->
    <div class="card">
      <h2>Key Features</h2>
      <p>
        Automate your membership management processes from membership data<br />
        management ,fees payment,event registration and more.
      </p>
    </div>

    <div class="card-holder">
      <div class="container">
        <div class="card-1">
          <i class="fas fa-solid fas fa-user-plus fa-2xl"></i>
          <h2>Member Community & Engagement</h2>
          <p>
            Engage with members, improve connections, share contents and measure
            performance at <br />any time.
          </p>
        </div>
        <div class="card-2">
          <i class="fas fa-solid fas fa-wallet fa-2xl"></i>
          <h2>Dues & Fees Management</h2>
          <p>
            Manage annual dues, fees and contributions seamlessly with
            comprehensive report on <br />defaulters.
          </p>
        </div>
        <div class="card-3">
          <i class="fas fa-solid fas fa-calendar-day fa-2xl"></i>
          <h2>Event Registration & Check-in</h2>
          <p>
            Manage free or paid events,<br />
            track registration, attendance and provide convenient ways to<br />
            Check-in
          </p>
        </div>
        <div class="card-4">
          <i class="fas fa-solid fas fa-bell fa-2xl"></i>
          <h2>Notification & Reminders</h2>
          <p>
            Members get notification and reminders on important announcements or
            task via their <br />portal
          </p>
        </div>
      </div>
    </div>
    <!-- footer -->
    <footer class="label">
      <div class="container">
        <p>
          <!-- <font-awesome-icon icon="fa-solid fa-copyright" />  -->
          All rights
          reserved. Nigeria Bar Association
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  setup() {
    
  },
}
</script>

<style>

.nav {
  display: flex;
  font-size: 14px;
  position: fixed;
  align-content: flex-start;
  padding: 10px;
  width: 100%;
  z-index: 1000;
  /* margin: 10px auto; */
  border-bottom: 3px solid green;
  background-color: #e6fff8;
}
.nav img {
  width: 421px;
  height: 61px;
  border: none;
  padding-left: 50px;
  /* padding: 88px; */
}

.register {
  display: flex;
  /* padding: 88px; */
  align-items: center;
  width: 60%;
  justify-content: flex-end;
}
.button1 {
  background-color: #e6fff8;
  color: #15671d;
  border: 1px solid green;
  height: 50px;
  width: 17%;
  border-radius: 24px 0px 0px 24px;
  cursor: pointer;
  font-size: 15px;
  margin-right: 10px;
}
.button2 {
  background-color: #e6fff8;
  color: #15671d;
  border: 1px solid green;
  height: 50px;
  width: 17%;
  align-items: center;
  border-radius: 0px 24px 24px 0px;
  cursor: pointer;
  font-size: 15px;
}
.button2:hover {
  background: #15671d;
  color: #fff;
  transition: all 0.5s ease-in-out;
}
.button1:hover {
  background: #15671d;
  color: #fff;
  transition: all 0.5s ease-in-out;
}
.member {
  display: flex;
  align-items: center;
  width: 100%;
  /* position: relative; */
  background-color: #b5cfb7;
  margin-left: auto;
  margin-right: auto;

  /* opacity: 0.32; */
}
.work {
  display: block;
  align-self: center;
  margin-top: 92px;
}
.work h2 {
  margin-bottom: 0 !important;
  font-size: 50px;
  font-weight: 700;
  line-height: 55px;
  color: #15671d;
  box-sizing: border-box;
  width: 50%;
  /* margin-top: 2px; */
}
.work p {
  color: #343531;
  line-height: 27px;
  font-size: 16px;
  margin: 30px 120px 40px 0px;
}
.member-1 img {
  height: auto;
  width: 100%;
  box-shadow: none;
  object-fit: cover;
  margin-top: 38%;
}

.card {
  width: 80%;
  margin: 20px auto;
}

.card h2 {
  text-align: center;
  font-size: 35px;
  color: #27732f;
}
.card p {
  color: #343531;
  text-align: center;
  font-size: 16px;
  line-height: 24px;
  margin-bottom: 2rem;
}
.card-holder .contaiiner {
  margin: 0 auto;
  width: 75%;
  height: 35vh;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
}
.card-1,
.card-3 {
  border: 1px solid grey;
  text-align: center;
  width: 100%;
  font-size: 16px;
  justify-content: center;
  line-height: 24px;
  padding: 22px;
  margin-bottom: 20px;
}
.card-2,
.card-4 {
  border: 1px solid grey;
  text-align: center;
  width: 100%;
  font-size: 16px;
  justify-content: center;
  line-height: 24px;
  padding: 22px;
  margin-bottom: 50px;
}
.card-1,
.card-2,
.card-3,
.card-4,
i {
  color: #15671d;
}
.card-1 p {
  margin: auto 20px;
}

.label {
  display: flex;
  align-items: center;
  width: 100%;
  height: 10vh;
  background-color: #15671d;
  margin-top: 70px;
  color: #ffffff;
}
/* .container{
    display: flex;
} */

@media (min-width: 992px) {
  .container {
    width: 80vw;
    grid-gap: 30px;
    margin: auto;
    display: flex;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .container {
    /* width: 85vw; */
    width: 80vw;
    /* grid-gap:30px; */
    margin: auto;
    display: grid;
  }

  .member-1 img {
    height: auto;
    width: 100%;
    box-shadow: none;
    object-fit: cover;
    margin-top: 0%;
  }

  .work {
    text-align: center;
    margin-top: 92px;
  }
  .work h2 {
    line-height: 36px;
    font-size: 30px;
    width: 100%;
    margin-top: 80px;
  }
  .work p {
    color: #343531;
    margin: 30px 120px 40px 28px;
  }
}

@media (max-width: 767px) {
  .container {
    width: 85vw;
    margin: auto;
  }
  .member-1 img {
    box-shadow: none;
    object-fit: cover;
    margin-top: 0%;
  }

  .work h2 {
    line-height: 36px;
    font-size: 30px;
    width: 100%;
    text-align: center;
  }
  .work p {
    width: 100%;
    color: #343531;
    line-height: 27px;
    font-size: 16px;
    margin: 30px 120px 40px 0px;
    text-align: center;
  }
  .work {
    margin-top: 175px;
  }
  .button1 {
    background-color: #15671d;
    color: #ffffff;
    border: 1px solid green;
    height: 50px;
    width: 41%;
    border-radius: 24px 0px 0px 24px;
    cursor: pointer;
    font-size: 16px;
    margin-right: 10px;
  }
  .button2 {
    background-color: #15671d;
    color: #ffffff;
    border: 1px solid green;
    height: 50px;
    width: 43%;
    align-items: center;
    border-radius: 0px 24px 24px 0px;
    cursor: pointer;
    font-size: 16px;
  }
  .bar {
    width: 106%;
    display: flex;
    justify-content: flex-end;
    height: 10vh;
    align-items: center;
    align-self: center;
  }
  .card-1,
  .card-2,
  .card-3,
  .card-4 {
    padding: 11px;
    margin-bottom: 50px;
  }
}
</style>