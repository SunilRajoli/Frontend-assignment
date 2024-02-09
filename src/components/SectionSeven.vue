<template>

    <div class="section">
        <div class="component">
            <!-- Left Image -->
            
    
            <!-- Profiles -->
            <div class="profiles">
                <div class="image">
                    <img class="left-image" src="../assets/Vector 8.png" alt="Left Image" />
                </div>
                <div class="profile">
                    <img class="photo1" src="../assets/Frame 3254.png" alt="Profile 1" />
                </div>
                <div class="profile">
                    <img class="photo2" src="../assets/Frame 3254-1.png" alt="Profile 12" />
                </div>
                <div class="profile1">
                    <img class="photo3" src="../assets/Organization.png" alt="Profile3" />
                    <p class="photo-text">UX Designers</p>
                </div>
                <div class="profile">
                    <img class="photo4" src="../assets/Frame 3254-2.png" alt="Profile4" />
                </div>
                <div class="profile">
                    <img class="photo5" src="../assets/Frame 3254-3.png" alt="Profile5" />
                </div>
    
                <div class="image">
                    <img class="right-image" src="../assets/Vector 7.png" alt="Right Image" />
                </div>
                <!-- Repeat for other profiles -->
            </div>
    
            <!-- Right Image -->
            
        </div>
    
        <!-- Text: "Let's Form Your Crew." -->
        <p class="text1">Let's Form Your Crew.</p>
    
        <!-- Button: Schedule a Call -->
        <button class="button">Schedule a Call</button>
    </div>
    
    </template>
    
    <style scoped>
    /* Section */
    .section {
        width: 1440px;
        height: 603px;
        left: 2px;
        gap: 57px;
    }
    
    /* Component */
    .component {
        margin-top: 140px;
        width: 1083.26px;
        height: 300px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding-left: 100px;
    }
    
    /* Left Image */
    .left-image {
        margin-top: 150px;
        margin-right: 0px;
        width: 130.95px;
        height: 116.59px;
        transform: translate(58%, -20%);
    }
    
    /* Profiles */
    .profiles {
        display: flex;
        margin-bottom: 80px;
    }
    
    /* Profile */
    .profile {
        width: 200px;
        height: 350px;
        display: flex;
        align-items: center;
    }
    
    .profile1 {
        width: 200px;
        height: 350px;
        display: flex;
        flex-direction: column;
    }
    
    .photo-text {
        width: 139px;
    font-family: Epilogue;
    font-size: 24px;
    font-weight: 600;
    line-height: 32px;
    text-align: center;
    color: #3D3D3D;
    transform: translate(10%, -40%);
    
    }
    
    image {
        width: 200pz;
        height: 200px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    
    .photo1 {
        transform: translate(3%, 1%);
    }
    
    .photo2 {
        transform: translate(-8%, 1%);
    }
    
    /* Profile Photo */
    
    .photo3 {
        width: 250px;
        border-radius: 25.92px;
        height: 250px;
        margin-top: 20px;
        transform: translate(-15%, 1%);
    }
    
    .photo4 {
        transform: translate(-20%, 1%);
    }
    
    .photo5 {
        transform: translate(-29%, 1%);
    }
    
    /* Right Image */
    .right-image {
        margin-top: 60px;
        width: 130.95px;
        height: 116.59px;
        transform: translate(-70%, 10%);
    }
    
    /* Text: "Let's Form Your Crew." */
    p.text1 {
        width: 802px;
        height: 62px;
        font-family: Epilogue;
        font-size: 40px;
        font-weight: 300;
        line-height: 10px;
        letter-spacing: 2px;
        text-align: center;
        margin-left: 350px;
        margin-top: 60px;
    }
    
    /* Button: Schedule a Call */
    .button {
        width: 180px;
        height: 52px;
        margin-left: 650px;
        padding: 18px 20px;
        border-radius: 50px;
        background: linear-gradient(0deg, #3171DE, #3171DE);
        color: white;
        cursor: pointer;
        align-items: center;
        gap: 10px;
        border: none;
      }
    </style>