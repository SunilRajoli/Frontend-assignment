
<template>
    <div class="section-2">
      <!-- Text container -->
      <div class="text-container">
        <p>We have multidisciplinary teams to meet any <Span>challenge.</Span></p>
      </div>
      
      <!-- Container for articles -->
      <div class="container">
        <!-- Article 1 -->
        <div class="article">
            <i class="iconsax" icon-name="monitor" style="color: #3171DE;"></i>
          <div class="text">
            <p class="heading">Front-end</p>
            <p class="description">Our frontend developers understand the delicate balance between aesthetics and functionality.</p>
          </div>
        </div>
  
        <!-- Article 2 -->
        <div class="article">
            <i class="iconsax" icon-name="document-code-1" style="color: #3171DE;"></i>
          <div class="text">
            <p class="heading">Back-end</p>
            <p class="description">Our backend developers are the architects of efficiency and security. They design and build the databases and APIs.</p>
          </div>
        </div>
  
        <!-- Article 3 -->
        <div class="article">
            <i class="iconsax" icon-name="driver-1" style="color: #3171DE;"></i>
          <div class="text">
            <p class="heading">Data Analysts</p>
            <p class="description">Our data analytics team is a blend of mathematicians, statisticians, and technology enthusiasts.</p>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .section-2 {
    width: 1440px;
    height: 520px;
    gap: 45px;
  }
  
  .text-container {
    width: auto;
    height: 60px;
    margin-bottom: 40px;
    font-family: 'Epilogue', sans-serif;
    font-size: 32px;
    font-weight: 500;
    text-align: center;
   
  }
  
  .container {
    width: 1250px;
    height: 270px;
    padding: 32.5px 65.5px;
    margin-left: 50px;
    border-radius: 35.39px;
    background: #FFFFFF;
    box-shadow: 0px 5.661764621734619px 14.154411315917969px 0px #00000021;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  
  .article {
    width: 329px;
    height: 205px;
    gap: 35px;
    display: block;
    align-items:center;
    justify-content: space-between;
    
  }
  
  .article .iconsax {
    font-size: 50px;
    
  }
  
  .article .text {
    width: 329px;
  }
  
  .article .heading {
    font-family: 'Epilogue', sans-serif;
    font-size: 28px;
    font-weight: 500;
    line-height: 40px;
    color: #3D3D3D;
  }
  
  .article .description {
    font-family: 'Epilogue', sans-serif;
    font-size: 16px;
    font-weight: 400;
    line-height: 24px;
    text-align: left;
  }

  p span {
    color: #3171DE

  }
  </style>
  