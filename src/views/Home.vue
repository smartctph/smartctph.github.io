<template>
  <div class="home">
    <section class="flex flex-row py-5 items-center lg:justify-between
    lg:flex-no-wrap flex-wrap justify-center container mx-auto lg:px-20 px-10">
      <div class="flex flex-col justify-center lg:justify-between">
        <h1 class="text-5xl font-medium select-none text-center md:text-left">
          Welcome to
        </h1>
        <img class="object-scale-down"
        :src="require('@/assets/img/smartct-colored.svg')" />
      </div>
      <div class="p-2">
        <img class="object-scale-down" :src="require('@/assets/img/rafiki.png')" />
      </div>
    </section>
    <section class="flex flex-row py-10 items-center lg:justify-between justify-center
    lg:space-y-0 space-y-8 lg:flex-no-wrap justify-center flex-wrap lg:space-x-4
    container mx-auto lg:px-20 px-5">
      <div class="flex flex-col space-y-3 max-w-sm">
        <span class="bg-gray-400 px-4 h-20 w-full">
          &nbsp;
        </span>
        <h2 class="text-center text-primary text-2xl font-medium">
          SmartCT Pilot Program
        </h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit,
          sed do eiusmod tempor incididunt ut labore et dolore magna
          aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat.
          Duis aute irure dolor in reprehenderit in voluptate velit
          esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
          occaecat cupidatat non proident, sunt in culpa qui officia
          deserunt mollit anim id est laborum.
        </p>
        <a class="text-secondary text-right font-medium" href="#">
          Learn More
        </a>
      </div>
      <div class="flex flex-col space-y-3 max-w-sm">
        <span class="bg-gray-400 px-4 h-20 w-full">
          &nbsp;
        </span>
        <h2 class="text-center text-primary text-2xl font-medium">
          SmartCT Data Portal
        </h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit,
          sed do eiusmod tempor incididunt ut labore et dolore magna
          aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat.
          Duis aute irure dolor in reprehenderit in voluptate velit
          esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
          occaecat cupidatat non proident, sunt in culpa qui officia
          deserunt mollit anim id est laborum.
        </p>
        <a class="text-secondary text-right font-medium" href="#">
          Learn More
        </a>
      </div>
      <div class="flex flex-col space-y-3 max-w-sm">
        <span class="bg-gray-400 px-4 h-20 w-full">
          &nbsp;
        </span>
        <h2 class="text-center text-primary text-2xl font-medium">
          Free Online Assessment
        </h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit,
          sed do eiusmod tempor incididunt ut labore et dolore magna
          aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat.
          Duis aute irure dolor in reprehenderit in voluptate velit
          esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
          occaecat cupidatat non proident, sunt in culpa qui officia
          deserunt mollit anim id est laborum.
        </p>
        <a class="text-secondary text-right font-medium" href="#">
          Learn More
        </a>
      </div>
    </section>
    <section class="bg-primary py-20">
      <div class="lg:container lg:mx-auto flex scrolling-auto pb-5 overflow-y-visible
      lg:justify-between lg:px-20 space-x-6 overflow-x-auto mx-5">
        <div class="card bg-white rounded-lg max-w-xs p-4 flex flex-col shadow-md flex-shrink-0">
          <span class="bg-gray-400 px-4 h-20 w-20 mx-auto m-2 rounded-full">
            &nbsp;
          </span>
          <h2 class="text-xl text-center font-medium py-2">
            SmartCT Plans
          </h2>
          <p class="mt-4">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
            do eiusmod tempor incididunt ut labore et dolore magna aliqua
          </p>
        </div>
        <div class="card bg-white rounded-lg max-w-xs p-4 flex flex-col shadow-md flex-shrink-0">
          <span class="bg-gray-400 px-4 h-20 w-20 mx-auto m-2 rounded-full">
            &nbsp;
          </span>
          <h2 class="text-xl text-center font-medium py-2">
            SmartCT Data Portal
          </h2>
          <p class="mt-4">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
            do eiusmod tempor incididunt ut labore et dolore magna aliqua
          </p>
        </div>
        <div class="card bg-white rounded-lg max-w-xs p-4 flex flex-col shadow-md flex-shrink-0">
          <span class="bg-gray-400 px-4 h-20 w-20 mx-auto m-2 rounded-full">
            &nbsp;
          </span>
          <h2 class="text-xl text-center font-medium py-2">
            SmartCT Hall
          </h2>
          <p class="mt-4">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
            do eiusmod tempor incididunt ut labore et dolore magna aliqua
          </p>
        </div>
      </div>
    </section>
    <section class="bg-white flex flex-col py-10 container mx-auto lg:px-20 px-5 pb-16">
      <h2 class="text-2xl font-medium text-center my-4">
        Partner Organizations
      </h2>
      <div class="flex flex-row justify-center lg:justify-between mb-2 flex-wrap">
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/1 1.png')" />
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/1 2.png')" />
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/1 3.png')" />
      </div>
      <div class="flex flex-row justify-center lg:justify-between mb-2 flex-wrap">
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/2 1.png')" />
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/2 2.png')" />
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/2 3.png')" />
      </div>
      <div class="flex flex-row justify-center lg:justify-between mb-2 flex-wrap">
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/3 1.png')" />
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/3 2.png')" />
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/3 3.png')" />
        <img class="p-2 flex-shrink" :src="require('@/assets/img/partners/3 4.png')" />
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  },
};
</script>

<style>
  .card {
    height: 20rem;
  }
</style>
