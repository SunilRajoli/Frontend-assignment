<template>
    <nav class="navbar navbar flex flex-wrap justify-between items-center py-4 px-6 lg:px-12">
      <!-- Logo -->
      <div class="logo">
        <!-- Insert your logo image here -->
        <img src="../assets/logo.png" alt="Logo" width="45px" height="47px" />
      </div>
      
      <!-- Menu -->
      <div class="menu menu flex justify-center items-center space-x-6 mt-4 lg:mt-0 lg:flex-grow lg:justify-end">
        <button class="menu-item home">Home</button>
        <button class="menu-item about-us">About us</button>
        <button class="menu-item services">Services</button>
        <button class="menu-item contact-us">Contact Us</button>
      </div>
      
      <!-- Language Dropdown -->
      <div class="dropdown relative flex items-center mt-4 lg:mt-0">
      <select class="dropdown-select">
        <option value="en">EN</option>
        <option value="in">IN</option>
        <option value="us">US</option>
      </select>
      <div class="dropdown-icon ml-2">
        <phosphor-icon name="caret-down" size="16" />
      </div>

      <!-- Schedule a Call Button -->
      <button class="schedule-call mt-4 lg:mt-0">Schedule a Call</button>
    </div>
     
    </nav>
  </template>
  
  
  <style scoped>
  .navbar {
    width: 1440px;
    height: 98px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
  }
  
  .logo img {
    width: 45px;
    height: 47px;
  }
  
  .menu {
    width: 663px;
    height: 49px;
    border-radius: 50px;
    background-color: #f0f0f0;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .menu button {
    border: none;
    background: none;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 30px 10px 40px;
  }
  
  .menu button.home {
    color: #3056D3;
    font-size: 16px;
    font-weight: 600;
    line-height: 16.4px;
  }
  
  .menu button.about-us,
  .menu button.services,
  .menu button.contact-us {
    color: #3D3D3D;
    font-size: 16px;
    font-weight: 500;
    line-height: 16.4px;
  }
  
  .dropdown {
    position: relative;
  width: 257px; /* Hug(71px) */
  height: 48px; /* Fixed(48px) */
  padding: 6px 16px 6px 16px; /* Padding: 6px 16px 6px 16px */
  border-radius: 12px; /* Border radius: 12px */
  gap: 14px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.dropdown span {
  color: gray; /* Text color: gray */
  
}

.dropdown-select {
  border: none;
}
  
  .schedule-call {
    width: 172px;
    height: 48px;
    padding: 15px 25px;
    border-radius: 50px;
    font-size: 14px;
    border: none;
    background: linear-gradient(0deg, #3171DE, #3171DE);
    color: white;
    cursor: pointer;
    gap: 10px;
  }

  
  </style>
  