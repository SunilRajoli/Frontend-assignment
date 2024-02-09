<template>
  <div class="section">
      
    
    <!-- Background Image on Left Side -->
    <div class="background-text-wrapper">
      <img src="../assets/Vector 7.png" alt="">
    <!-- Background Image -->
      <div class="background-image"></div>

    <!-- Text Component -->
      <div class="text-component">
        <p class="text1">We've stopped counting. Over 500 brands count on us.</p>
        <p class="text2">Our 4,000+ team has expertise in almost <br /> every programming language.</p>
      </div>
    </div>

    <!-- Overflow Component with Background Image -->
    <div class="overflow-component" >
      <div class="container articles-container" ref="articlesContainer">
        <div class="article" >
      <div class="stars">⭐⭐️⭐️⭐️⭐️️</div>
      <div class="text">
          <p class="heading">"Exceptional Solutions, Exceeded Expectations!"</p>
          <p class="description">"Working with Nearshore has been an absolute pleasure. Their team took the time to understand our unique needs and delivered a solution that not only met but exceeded our expectations. Their expertise and commitment to excellence are truly commendable."</p>
      </div>
      <div class="line"></div>
      <div class="text-box">
        <img src="../assets/Group.png" alt="">
        <div class="image-text">
          <p class="name">Mary Johnson</p>
          <p class="position">CEO of TechCraft Solutions</p>
      </div>
      </div>
  </div>

  <!-- Article 2 -->
  <div class="article">
      <!-- Same structure as Article 1 -->
      <div class="stars">⭐⭐️⭐️⭐️⭐️️</div>
      <div class="text">
          <p class="heading">"Transformed Our Business with Innovative Tech!"</p>
          <p class="description">"We owe a significant part of our success to [Company Name]. Their custom software solution streamlined our processes, saving us time and resources. Their team's dedication to innovation and problem-solving is unmatched. We're grateful for their partnership."</p>
      </div>
      <div class="line"></div>
      <div class="text-box">
        <img src="../assets/Group2.png" alt="">
        <div class="image-text">
          <p class="name">Mark Williams</p>
          <p class="position">COO of InnovateNow Inc</p>
      </div>
      </div>
  </div>

  <!-- Article 3 -->
  <div class="article">
      <!-- Same structure as Article 1 -->
      <div class="stars">⭐⭐️⭐️⭐️⭐️️</div>
      <div class="text">
          <p class="heading">"Sculpted User Experiences Beyond Imagination!"</p>
          <p class="description">"The UI/UX design crafted by [Company Name] turned our app into a masterpiece. The attention to detail, intuitive design, and user-centric approach have resulted in rave reviews from our customers. Their design expertise has taken our brand to a whole new level."</p>
      </div>
      <div class="line"></div>
      <div class="text-box">
        <img src="../assets/Dovetail.png" alt="">
        <div class="image-text">
          <p class="name">Emily Clark</p>
          <p class="position">CMO of Visionary Apps</p>
      </div>
      </div>
  </div>

  <!-- Article 4 -->
  <div class="article">
      <!-- Same structure as Article 1 -->
      <div class="stars">⭐⭐️⭐️⭐️⭐️️</div>
      <div class="text">
          <p class="heading">"Sculpted User Experiences Beyond Imagination!"</p>
          <p class="description">"The UI/UX design crafted by [Company Name] turned our app into a masterpiece. The attention to detail, intuitive design, and user-centric approach have resulted in rave reviews from our customers. Their design expertise has taken our brand to a whole new level."</p>
      </div>
      
      <div class="line"></div>
      <img src="../assets/Dovetail.png" alt="">
        
        <div class="image-text">
          <p class="name">Emily Clark</p>
          <p class="position">CMO of Visionary Apps</p>
      </div>
      
  </div>
      </div>

  </div>

  <div class="component">
      <div class="arrows">
    <div class="left-arrow" ><i class="iconsax" icon-name="chevron-left"></i></div>
    <div class="right-arrow"><i class="iconsax" icon-name="chevron-right"></i></div>
  </div>
  </div>
  
</div>
</template>






<style scoped>
/* Section Styles */
.section {
width: 1440px;
height: 1150px;
}


/* Background Image and Text Wrapper */
.background-text-wrapper {
display: flex;
margin-top: 100px;
}

.background-text-wrapper img {
width: 136.15px;
height: 121.22px;
opacity: 0.8px;
transform: translate(57%, 80%);
}

/* Background Image */
.background-image {
width: 589.74px;
height: 580.25px;
background-image: url('../assets/Intersect.png');
background-size: cover;
background-position: center;
}

/* Text Component */
.text-component {
width: 561px;
margin-left: 42px; /* Adjust as needed */
}

.text1 {
width: 553px;
height: 162px;
font-family: 'Epilogue', sans-serif;
font-size: 45px;
font-weight: 500;
line-height: 54px;
}

.text2 {
width: 561px;
height: 50px;
font-family: 'Epilogue', sans-serif;
font-size: 25px;
font-weight: 500;
line-height: 25px;
}

/* Overflow Component with Background Image */
.overflow-component {
  width: 1440px; /* Adjust as needed */
  height: 700px; /* Adjust as needed */
  padding: 40px 48px; /* Adjust as needed */
  display: flex;
  flex-direction: column;
  transform: translate(-3%, -25%);
  overflow-x: hidden;
  overflow-y: hidden;
  
}

.container{
  width: 1440px;
gap: 38.98px;
display: flex;
align-items: center;
justify-content: space-between;
background: linear-gradient(0deg, #FFFFFF, #FFFFFF),
linear-gradient(0deg, #F0F0F7, #F0F0F7);

}

.article {
  width: 1350px;
  height: 450px;
  gap: 38.98px;
  box-shadow: 0px 5.661764621734619px 14.154411315917969px 0px #00000021;
  border-radius: 22px;
  padding: 40px;
}

.stars {
  width: 156px;
  height: 28px;
  font-family: 'DM Sans', sans-serif;
  font-size: 22px;
  padding: 10px;
  font-weight: 700;
  line-height: 20px;
  letter-spacing: 2.8873629570007324px;
  text-align: left;
}

.text {
  width: 326.05px;
  height: 294.66px;
}

.heading {
  width: 326.05px;
  height: 73px;
  font-family: 'DM Sans', sans-serif;
  font-size: 24px;
  font-weight: 700;
  line-height: 36px;
  letter-spacing: 0px;
  text-align: left;
}

.description {
  width: 326.05px;
  height: 213px;
  font-family: 'DM Sans', sans-serif;
  font-size: 17px;
  font-weight: 400;
  line-height: 30px;
  letter-spacing: 0px;
  text-align: left;
}

.line {
  width: 326.05px;
  margin-top: 25px;
  border: 1.08px solid #000;
}



img {
width: 30px;
height: 30px;
padding: 30px 15px 5px 10px;

}

.image-text {

  display: flex;
  align-items: center;
  flex-direction: column;
}

.name {
font-family: DM Sans;
font-size: 20px;
font-weight: 700;
transform: translate(-20%, -330%);

}

.position {
font-family: DM Sans;
font-size: 13px;
font-weight: 600;
transform: translate(-5%, -650%);

}

.arrows {
  width: 150px;
  height: 65px;
  display: flex;
  margin-left: 680px;
  gap: 10px;
  line-height: 55px;
  transform: translate(-5%, -430%);
  
}

.iconsax {
  font-size: 25px;
  color: 000;
  padding: 12px;
}

.left-arrow,
.right-arrow {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background-color: lightgray; /* Adjust arrow color as needed */
  cursor: pointer;
}

</style>
