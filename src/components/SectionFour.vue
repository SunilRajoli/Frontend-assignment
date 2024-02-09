<template>
  <div class="next-section">
    <!-- First Component -->
    <div class="first-component">
      <p class="first-component-heading">Trusted by Leading Organizations</p>
      <p class="first-component-description">Our 4,000+ team has expertise in almost <br />every programming language.</p>
    </div>

    <!-- Second Component -->
    <div class="second-component">
      <div class="logos">
        <img src="../assets/samsung.png" alt="Samsung" class="logo" />
        <img src="../assets/microsoft.png" alt="Microsoft" class="logo" />
        <img src="../assets/google.png" alt="Google" class="logo" />
        <img src="../assets/slack.png" alt="Slack" class="logo" />
        <img src="../assets/lg.png" alt="LG" class="logo" />
        <img src="../assets/sony.png" alt="Sony" class="logo" />
      </div>
    </div>

    <!-- Button -->
    <button class="full-repertoire-btn">Our Full Repertoire</button>
  </div>
</template>

<style scoped>
.next-section {
  margin: 50px;
  width: 1440px;
  height: 450px;
  border-radius: 35.39px;
  display: flex;
flex-direction: column;
align-items: center;
background: #f0f0f0;
}

.first-component {
  width: 665px;
  height: 120px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.first-component-heading {
  width: 665px;
  height: 30px;
  font-family: 'Epilogue', sans-serif;
  font-size: 40px;
  font-weight: 500;
}

.first-component-description {
  width: 561px;
  height: 20px;
  padding-bottom: 10px;
  font-family: 'Epilogue', sans-serif;
  font-size: 20px;
  font-weight: 300;
  text-align: center;
}

.second-component {
  top: 30px;
  height: 150.89px;
  padding: 30px;
  align-items: center;
}

.logos {
  display: flex;

}

.logo {
  padding: 70px;
  width: 117px;
  height: 45px;
}


.full-repertoire-btn {
  width: 244px;
  padding: 20px;
  font-size: 16px;
  border-radius: 50px;
  background-color: #3171DE;
  color: #ffffff;
  border: none;
}
</style>
