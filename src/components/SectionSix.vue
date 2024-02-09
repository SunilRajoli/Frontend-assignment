<template>
    <div class="section">
        <!-- First Component -->
        <div class="component">
            <p class="title">Choose Us: Your Path to Innovation and <br /><span>Success</span></p>
            <img src="../assets/Vector 8.png" alt="Image" class="image1">
        </div>
    
        <!-- Second Component -->
        <div class="component-articles">
            <!-- Article 1 -->
            <div class="article1">
                <div class="box">
                    <p class="text">Expertise Across the Tech Spectrum</p>
                    <p class="description">Our team consists of seasoned developers, designers, and experts who excel in various areas of technology.</p>
                </div>
            </div>
    
            <!-- Article 2 -->
            <div class="article2">
                <div class="box">
                    <p class="text">Proven Track Record of Success</p>
                    <p class="description">Our portfolio is a testament to our ability to deliver impactful results.</p>
                </div>
            </div>
    
            <!-- Article 3 -->
            <div class="article3">
                <div class="box">
                    <p class="text">Collaborative Approach, Transparent Communication</p>
                    <p class="description">We believe in working hand-in-hand with our clients.</p>
                </div>
            </div>
    
            <!-- Article 4 -->
            <div class="article4">
                <div class="box">
                    <p class="text">Tailored Solutions for Your Unique Needs</p>
                    <p class="description">We understand that no two projects are alike.</p>
                </div>
            </div>
        </div>
    
        <!-- Third Component -->
        <div class="component">
            <img src="../assets/Vector 7.png" alt="Image" class="image2">
            <div class="arrows">
          <button class="left-arrow" ><i class="iconsax" icon-name="chevron-left"></i></button>
          <button class="right-arrow" ><i class="iconsax" icon-name="chevron-right"></i></button>
        </div>
        </div>
    </div>
    
    </template>




    <style scoped>
    .section {
        width: 1440px;
        height: 650px;
        margin-top: 30px;
        border-radius: 35.39px;
        display: flex;
      flex-direction: column;
      align-items: center;
      background-color: #F7F7FD;
      overflow-x: hidden;
      overflow-y: hidden;
    }
    
    .component {
        width: 1200px;
        height: 550px;
        position: relative;
    
    }
    
    .component-articles {
        width: 1344px;
        height: 229px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 30px;
        
    }
    
    .article1, .article3 {
        width: 385px;
        height: 229px;
        padding: 37px 28px;
        border-radius: 35.39px;
        box-shadow: 0px 5.661764621734619px 14.154411315917969px 0px #00000021;
    
    }
    
    .article2 {
        width: 385px;
        height: 229px;
        padding: 37px 28px;
        border-radius: 35.39px;
        box-shadow: 0px 5.661764621734619px 14.154411315917969px 0px #00000021;
        background: linear-gradient(232.88deg, #62AE6E 28.46%, #EDE14F 162.02%);
        color: #ffffff;
    
    }
    
    .article4 {
        width: 385px;
        height: 229px;
        padding: 37px 28px;
        border-radius: 35.39px;
        box-shadow: 0px 5.661764621734619px 14.154411315917969px 0px #00000021;
        background: linear-gradient(225.84deg, #3171DE 25.37%, #4AC0F2 135.72%);
        color: #ffffff;
    
    }
    
    .box {
        width: 329px;
        height: 155px;
        top: 37px;
        left: 28px;
        gap: 19px;
    }
    
    .title {
        width: 802px;
        height: 124px;
        margin-top: 48px;
        font-family: Epilogue;
        font-size: 40px;
        font-weight: 500;
        padding-left: 250px;
    }
    
    span {
        color: #4AC0F2;
        padding-left: 250px;
    }
    
    .image1 {
        width: 90.84px;
        height: 80.88px;
        margin-top: 35px;
        top: 0;
        right: 0;
        position: absolute;
    }
    
    .image2 {
        width: 90.84px;
        height: 80.88px;
        margin-top: 35px;
        top: 0;
        left: 0;
        position: absolute;
        padding: 60px;
    }
    
    .arrows {
        width: auto;
        height: 65px;
        display: flex;
        margin-top: 20px;
        margin-left: 550px;
        gap: 10px;
        
      }
    
      .iconsax {
        font-size: 25px;
        color: #000;
        line-height: 30px;
        padding: 4px;
    }
    
      button.left-arrow,
      button.right-arrow {
        width: 50px;
        height: 50px;
        margin-top: 100px;
        position: relative;
        border-radius: 50%;
        background-color: #ffffff; /* Adjust arrow color as needed */
        cursor: pointer;
        border: none;
      }
    
    /* Additional styling for text and description */
    .text {
        width: 327px;
        height: 64px;
        font-family: Epilogue;
        font-size: 24px;
        font-weight: 600;
        line-height: 32px;
        text-align: left;
    }
    
    .description {
        width: 329px;
        height: 48px;
        font-family: Epilogue;
        font-size: 16px;
        font-weight: 400;
        line-height: 24px;
        padding-top: 20px;
        text-align: left;
    }
    
    </style>
    
    