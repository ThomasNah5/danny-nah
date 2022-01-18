<template>
  <div>
    <header>
          <div class="header-wrapper bg-gray-100 flex flex-col  p-4 mb-8 sm:flex-row text-lg ">
              <div class=" text-3xl mt-2 leading-10 font-sans font-normal  sm:w-1/2 mr-8 md:mr-12 lg:mr-28">
               Hey 👋🏿 I'm <span class="text-3xl text-blue-300 font-semibold">Danny Nah.</span>
               I'm an aspiring software engineer, UI/UX designer and professional footballer. 
               I'm also a video-game enthusiast, a hip-hop head, and a master procrastinator.
               I created this website as a place to document my journey as I learn new 
               things and share them with you.
              </div>
              <div class="">
                <img class="object-contain h-96 mt-6 mx-auto content-center sm:w-2/2 md:mt-2 lg:mt-2" src="https://images.unsplash.com/photo-1507238691740-187a5b1d37b8?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=693&q=80" alt="">
             </div>
          </div>
      </header>
      <section>
      <NuxtLink to="/explore" class="mx-4  text-2xl font-medium hover:border border-b-4 border-blue-300 ">Explore</NuxtLink>
      <div class="explore mx-4 my-4 p-4 rounded-xl bg-gray-200 md: max-w-2xl  xl:">
       <h1 class="mt-4 text-xl font-medium">💻 Technologies I intend to learn in 2021</h1>
       <p>As an aspiring software engineer getting acquainted with mutiple technologies is important even in the same domain.
          See what I'm learning this year.
       </p>
      </div>
      <div class="explore mx-4 my-4 p-4 rounded-xl bg-gray-200 md: max-w-2xl  xl:">
       <h1 class="mt-4 text-xl font-medium">💻 Technologies I intend to learn in 2021</h1>
       <p>As an aspiring software engineer getting acquainted with mutiple technologies is important even in the same domain.
          See what I'm learning this year.
       </p>
      </div>
      </section>
      <section class="mx-4 my-6">
        <h1 class="text-2xl font-medium">My Blog Articles<span class="ml-80 text-sm">View All</span></h1>
        <div class="mt-12">
        <div class="flex my-4">
         <h1>Dec 8</h1>
         <p class="ml-56">My First Project</p>
        </div>
        <div class="flex my-4">
         <h1>Dec 8</h1>
         <p class="ml-56">Why Agile Development</p>
        </div>
        <div class="flex my-4">
         <h1>Dec 8</h1>
         <p class="ml-56">How I use Notion to prepare for projects</p>
        </div>
        <div class="flex my-6">
         <h1>Dec 8</h1>
         <p class="ml-56">My Tech Stack</p>
        </div>
        <div class="flex my-4">
         <h1>Dec 8</h1>
         <p class="ml-56">My 2021 so far</p>
        </div>
        </div>
      </section>
  </div>
</template>

<script>
export default {


}
</script>

<style>

</style>
