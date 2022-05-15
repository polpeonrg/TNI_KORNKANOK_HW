<template>
  <div>
    <h1>My Profile</h1>
    <img src="../assets/background.PNG" alt="background" width="100%" />
    <img
      class="profile"
      src="../assets/profile.PNG"
      alt="profile"
      width="20%"
    />
    <h2>
      Kornkanok Samrit
      <br /><i>THAI-NICHI INSTITUTE OF TECHNOLOGY </i>
    </h2>
    <div class="decoration">
      <img class="decorate" src="../assets/circle.png" alt="dot" />
      <img class="decorate" src="../assets/circle.png" alt="dot" />
      <img class="decorate" src="../assets/circle.png" alt="dot" />
    </div>
    <section>
      <div>
        <p><b> Age :</b> 21 years old</p>
        <p><b> Skill :</b> C, C++, JavaScrip, HTML, CSS, SQL</p>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style >
.profile {
  border-radius: 50%;
  border: 4px solid #8da0a4;
  position: relative;
  bottom: 30px;
}

h2,
.profile {
  display: inline-block;
  vertical-align: top;
  text-align: left;
}

h2 {
  color: #202723;
  margin-top: 8px;
  margin-left: 20px;
  font-size: 20px;
  word-spacing: 5px;
  letter-spacing: 1.2px;
}

h2 i {
  font-size: 12px;
}
</style>