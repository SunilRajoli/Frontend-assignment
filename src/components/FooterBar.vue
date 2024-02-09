<template>
    <div class="footer">
        <div class="container">
            <!-- First Row -->
            <div class="row product">
                <h3>Product</h3>
                <ul>
                    <li>Employee database</li>
                    <li>Payroll</li>
                    <li>Absences</li>
                    <li>Time tracking</li>
                    <li>Shift planner</li>
                    <li>Recruiting</li>
                </ul>
            </div>
    
            <!-- Second Row -->
            <div class="row information">
                <h3>Information</h3>
                <ul>
                    <li>FAQ</li>
                    <li>Blog</li>
                    <li>Support</li>
                </ul>
            </div>
    
            <!-- Third Row -->
            <div class="row company">
                <h3>Company</h3>
                <ul>
                    <li>About us</li>
                    <li>Careers</li>
                    <li>Contact us</li>
                    <li>Lift Media</li>
                </ul>
            </div>
    
            <!-- Last Row -->
            <div class="last-row">
                <div class="component">
                    <h3>Subscribe</h3>
                    <div class="wrapper">
                        <input type="email" placeholder="Email Address">
                    <button>&rarr;</button>
                    </div>
                    
                    <p>Hello, we are Lift Media. Our goal is to translate the positive effects from revolutionizing how companies engage with their clients & their team.</p>
                </div>
            </div>
        </div>
    
        <!-- Line -->
        <div class="line"></div>
    
        <!-- Logo -->
        
    
        <!-- Bar -->
        <div class="bar">
            <div class="logo">
                <img src="../assets/logo.png" alt="">
            </div>
            <div class="text">Terms | Privacy | Cookies</div>
            <div class="icons">
                <div class="linkedin">
                    <img src="../assets/Linkedin.png" alt="">
                </div>
                <div class="facebook">
                    <img src="../assets/Facebook.png" alt="">
                </div>
                <div class="twitter">
                    <img src="../assets/Twitter.png" alt="">
                </div>
            </div>
        </div>
    </div>
    
    </template>
    
    <style scoped>
    /* Footer */
    .footer {
        width: 1440px;
        height: 500px;
    }
    
    /* Container */
    .container {
        width: 1174px;
        height: 300.69px;
        margin-left: 150px;
        padding-top: 70px;
        line-height: 25px;
        font-family: Epilogue;
        display: flex;
        justify-content: space-between;
    }
    
    /* Rows */
    .row {
        position: relative;
    }
    
    
    .row h3 {
        font-size: 20px;
        font-weight: bold;
    }
    
    .row ul {
        list-style-type: none;
        padding: 0;
        margin: 20px 0 0 0;
    }
    
    .row ul li {
        margin-bottom: 10px;
    }
    
    /* Last Row */
    .last-row {
        width: 369.47px;
        height: 251.15px;
        top: 102px;
        left: 937.53px;
        border-radius: 30px;
        background: #203C860D;
        
    }
    
    .wrapper {
        max-width: 100%;
        position: relative;
    }
    
    .last-row .component {
        width: 277.65px;
        height: 197.38px;
        left: 983.44px;
        border-radius: 30px;
        padding: 10px;
        margin-left: 20px;
    }
    
    .last-row .component h3 {
        font-size: 20px;
        font-weight: bold;
    }
    
    .last-row .component input[type="email"] {
        width: 250px;
        height: 45px;
        border-radius: 25px;
        border: 1px solid #ccc;
        margin-bottom: 10px;
        padding: 0 20px;
    }
    
    .last-row .component .wrapper button {
        width: 45px;
        height: 45px;
        border-radius: 45px;
        background-color: #3171DE;
        color: #fff;
        border: none;
        cursor: pointer;
        font-size: 18px;
        position: absolute;
        right: 0;
        transform: translate(28.5%, -124.8%);
    }
    
    .last-row .component p {
        font-size: 14px;
        line-height: 20px;
        margin-top: 10px;
    }
    
    /* Line */
    .line {
        width: 1174px;
        height: 1.01px;
        margin-left: 150px;
        border: 1px solid #0A142F;
        margin-top: 10px;
        opacity: 0.08;
        background: #0A142F;
    }
    
    /* Logo */
    .logo {
        width: 45.58px;
        height: 47px;
        margin-left: 150px;
    }
    
    /* Bar */
    .bar {
        width: auto;
        height: 18.22px;
        margin-top: 60px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-family: Epilogue;
    }
    
    .bar .text {
        flex-grow: 1;
        text-align: center;
    }
    
    .bar .icons {
        display: flex;
        align-items: center;
        margin-right: 160px;
    }
    
    .bar .icons div {
        width: 38.26px;
        height: 35.43px;
        margin-right: 10px;
        /* Add background image for each icon */
    }
    
    </style>