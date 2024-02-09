<template>
  <div class="section">
    <div class="top-section">
      <img class="top-image" src="../assets/Vector 6.png" alt="Top Image" />
      <div class="top-text">
        <p class="top-text-content">Empowering Your Digital Vision: Our Comprehensive Tech Services.</p>
      </div>
    </div>
    <div class="container">
      
      <!-- Article 1 -->
      <div class="article">
          <i class="iconsax" icon-name="document-code-1" style="color: #66B066;"></i>
        <div class="text">
          <p class="heading">Custom SoftwareDevelopment</p>
          <p class="description">Create custom software tailored for your <br />unique needs, including front-end, and core back-end technology.</p>
        </div>
      </div>

      <!-- Article 2 -->
      <div class="article">
          <i class="iconsax" icon-name="media-sliders-3" style="color: #704AF2;"></i>
        <div class="text">
          <p class="heading"><br />QA and Testing</p>
          <p class="description">Create custom software tailored for your unique needs, including front-end, and core back-end technology.</p>
        </div>
      </div>

      <!-- Article 3 -->
      <div class="article">
          <i class="iconsax" icon-name="flow-chart-1" style="color: #F3BC4C;"></i>
        <div class="text">
          <p class="heading"><br />AI and Data Science</p>
          <p class="description">Use leading AI, machine learning, and data engineering technologies to unlock business value.</p>
        </div>
      </div>

      <div class="article">
          <i class="iconsax" icon-name="brush-4" style="color: #E27244;"></i>
        <div class="text">
          <p class="heading"><br />UX/UI Design</p>
          <p class="description">Create beautiful, pixel-perfect, and easy-to-use designs that delight your end users.</p>
        </div>
      </div>

      <div class="article">
          <i class="iconsax" icon-name="mobile" style="color: #5E5DEF;"></i>
        <div class="text">
          <p class="heading">Mobile App <br />Development</p>
          <p class="description">Build performant, scalable, and secure mobile applications for iOS and Android devices.</p>
        </div>
      </div>

      <div class="article">
          <i class="iconsax" icon-name="size" style="color: #DF5E63;"></i>
        <div class="text">
          <p class="heading">Platform and Infrastructure</p>
          <p class="description">Ensure applications are secure, fault tolerant and highly available with our DevOps and Security engineers.</p>
        </div>
      </div>
    </div>
      
    
  </div>
</template>

<style scoped>
.section {
  width: 1440px;
height: 1000px;
top: 1324px;
gap: 79px;
display: flex;
flex-direction: column;
align-items: center;
}

.top-section {
  width: auto;
  height: auto;
  gap: 18px;
  display: flex;
  align-items: center;
}

.top-image {
  width: 90.84px;
  height: 80.88px;
  margin-top: -40px;
}

.top-text {
  width: 731.25px;
  height: auto;
  font-family: 'Epilogue', sans-serif;
  font-size: 40px;
  font-weight: 500;
  line-height: 60px;
  letter-spacing: 0em;
}

.container {
  width: 1350px;
  height: 690px;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 48px;
}

.article {
  width: 385px;
  height: 320px;
  border-radius: 35.39px;
  box-shadow: 0px 5.661764621734619px 14.154411315917969px 0px #00000021;
}

.iconsax {
  font-size: 50px;
  margin: 30px;
}



.article .text {
  width: 370px;
  gap: 16px;
}

.article .heading {
  font-family: 'Epilogue', sans-serif;
  font-size: 25px;
  font-weight: 500;
  color: #3D3D3D;
  padding-left: 30px;
}

.article .description {
  font-family: 'Epilogue', sans-serif;
  font-size: 16px;
  font-weight: 400;
  padding-left: 30px;
}
</style>
