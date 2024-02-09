

<template>
  <div class="section-1">
      <div class="background-container">
          <div class="background-image">

          </div>
      </div>
      <div class="text-container">
          <h2 class="font-roboto-flex text-lg font-semibold">TECH SERVICES</h2>
          <h1 class="font-epilogue text-5xl font-medium text-gray-900 leading-10">TechSynergy:<br>Innovate,<br>Create, Elevate</h1>
          <p class="font-epilogue text-base font-medium text-gray-700">Unlocking Possibilities, One Code at a Time</p>
          <button class="btn-see-projects">See Projects</button>
      </div>
  </div>
</template>

<style scoped>
.section-1 {
/* Container for the section */
width: 1440px;
height: 752px;
padding: 55px 10px;
gap: 48px;
}

.background-container {
/* Container for the background image */
width: 100%;
height: 100%;
transform: scaleX(-1); /* Flip the background horizontally */
}

.background-image {
/* Background image */
top: 125px;
left: 1391px;
width: 1102px;
height: 679px;
background-image: url('https://s3-alpha-sig.figma.com/img/ab87/47b2/fb703f485496ca1a73db84779ccb6a3b?Expires=1707696000&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=ZXSKBlSphpDL5LsubNN~CKuliTn31q9Cx-SP7MgVpPaBhMHUDHrvZVSxgh-5evm9FrnBf6SjHfG3wU57ZlDhUCzBCLRREkO8nm8nZ3DecLYnCBlmcA51ukNPF1iKASis6qvD7-KKIYe29DhRM-sOxCBB3fDbLE92OAM5AFJXT2dUIaSqcP3I83O0P1tGjPVKELI~BxTh4hbC4kP0RpsWvu9mVMQz0~vEFPZZY8N1tYJscBLQO8uv40QVKEJQSfxqv-BId8oyIMQ~Ic7QusoPJvs1ZQORlPiQ6n-gQ~P~Bw1bLLx5w5WwE0sm2694Xs3~W5qlNtU1vnxKF11dC~OQ1w__'); /* Replace '/path/to/image-1.jpeg' with the actual path to your background image */
background-size: cover; /* Adjust the background size as needed */
border-radius: 33.53px;
}



.text-container {
/* Styles for text content */
position: absolute;
top: 85%;
left: 60px; /* Adjust the left offset as needed */
transform: translateY(-50%);
color: #3D3D3D; /* Text color */
z-index: 1; /* Ensure text is above the background image */
}

.font-roboto-flex {
  font-family: Epilogue;
  font-size: 20px;
  font-weight: 600;
  line-height: 23px;
  letter-spacing: 0.1em;
  text-align: left;
  color: #F3BC4C;
  
}

.font-epilogue {
  font-family: Epilogue;
}

.text-lg {
  font-size: 20px;
}

.text-5xl {
  font-size: 64px;
}

.text-base {
  font-size: 20px;
}

.btn-see-projects {
  width: 172px;
  height: 48px;
  border-radius: 50px;
  font-size: 16px;
  gap: 10px;
  background-color: #66B066;
  border: 2px solid #66B066;
  color: #ffffff;
}

.text-sm {
  font-size: 16px;
}

.leading-10 {
  line-height: 80px;
}




</style>

