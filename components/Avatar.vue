<template>
    <div class="profile-image" :style="{ width: size, height: size }">
      <img :src="src" :alt="alt" class="image" />
    </div>
  </template>
  
  <script>
  export default {
    props: {
      src: {
        type: String,
        required: true,
      },
      alt: {
        type: String,
        default: 'Profile Image',
      },
      size: {
        type: String,
        default: '100px', // You can change the default size as needed
      },
    },
  };
  </script>
  
  <style scoped>
  .profile-image {
    overflow: hidden;
    border-radius: 50%; /* Makes the image circular */
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #f0f0f0; /* Optional: background color */
  }
  
  .image {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensures the image covers the div */
  }
  </style>
  