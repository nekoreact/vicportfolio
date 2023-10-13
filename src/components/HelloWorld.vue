<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="w-full p-10">
    <h1 class="w-full text-center mb-4">
      <span class="text-[#fff] shadow-text">
        Frontend Skills
      </span>
    </h1>
    <section class="flex p-5">
      <div class="custom-cards w-[33.3%] h-[450px] flex flex-col items-center p-6">
        <span class="w-[90px] flex items-center justify-center">
          <img src="../assets/html-skill.png" class="w-full">
        </span>
        <h2>HTML5</h2>
        <p>
          When it comes to building frontend UI, the semantic of the DOM is important for me
          i love perfectly semantic html to be crafted from scratch, years of practice and 
          hard work had been delivering beautiful Landing Pages and Simple Static Websites
        </p>
        <span>Take a look of some of them</span>
        <ul>
          <li>My Perfect Dog</li>
          <li>Weeding Paradise</li>
          <li>League of Legends Recreated</li>
        </ul>
      </div>
      <div class="custom-cards w-[33.3%] h-[450px] mx-5 flex flex-col items-center p-6">
        <span class="w-[90px] h-[127px] flex items-center justify-center">
          <img src="../assets/react-skill.png" class="w-full">
        </span>
        <h2>React</h2>
        <p>
          When it comes to building frontend UI, the semantic of the DOM is important for me
          i love perfectly semantic html to be crafted from scratch, years of practice and 
          hard work had been delivering beautiful Landing Pages and Simple Static Websites
        </p>
        <span>Take a look of some of them</span>
        <ul>
          <li>My Perfect Dog</li>
          <li>Weeding Paradise</li>
          <li>League of Legends Recreated</li>
        </ul>
      </div>
      <div class="custom-cards w-[33.3%] h-[450px] flex flex-col items-center p-6">
        <span class="w-[90px] h-[127px] flex items-center justify-center">
          <img src="../assets/logo.svg" class="w-full">
        </span>
        <h2>Vue</h2>
        <p>
          When it comes to building frontend UI, the semantic of the DOM is important for me
          i love perfectly semantic html to be crafted from scratch, years of practice and 
          hard work had been delivering beautiful Landing Pages and Simple Static Websites
        </p>
        <span>Take a look of some of them</span>
        <ul>
          <li>My Perfect Dog</li>
          <li>Weeding Paradise</li>
          <li>League of Legends Recreated</li>
        </ul>
      </div>
      
    </section>
  </div>
  <div class="w-full h-screen backend bg-[#fff]">
    <h1 class="w-full text-center pt-9">
      <span class="text-[#fff] shadow-text">
        Backend Skills
      </span>
    </h1>
    <section class="flex items-center p-5 h-screen -mt-9">
      <div class="w-[50%] flex flex-col items-center p-6">
        <span class="bg-[#fff] p-5 w-[400px] h-[400px] flex items-center justify-center">
          <img src="../assets/laravel.png" class="w-full">
        </span>
        <!-- <h2>HTML5</h2>
        <p>
          When it comes to building frontend UI, the semantic of the DOM is important for me
          i love perfectly semantic html to be crafted from scratch, years of practice and 
          hard work had been delivering beautiful Landing Pages and Simple Static Websites
        </p>
        <span>Take a look of some of them</span>
        <ul>
          <li>My Perfect Dog</li>
          <li>Weeding Paradise</li>
          <li>League of Legends Recreated</li>
        </ul> -->
      </div>
      <div class="w-[50%]  mx-5 flex flex-col items-center p-6">
        <span class="bg-[#fff] w-[400px] h-[400px] flex items-center justify-center">
          <img src="../assets/expressjs.svg" class="w-full">
        </span>
        <!-- <h2>React</h2>
        <p>
          When it comes to building frontend UI, the semantic of the DOM is important for me
          i love perfectly semantic html to be crafted from scratch, years of practice and 
          hard work had been delivering beautiful Landing Pages and Simple Static Websites
        </p>
        <span>Take a look of some of them</span>
        <ul>
          <li>My Perfect Dog</li>
          <li>Weeding Paradise</li>
          <li>League of Legends Recreated</li>
        </ul> -->
      </div>
    </section>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
