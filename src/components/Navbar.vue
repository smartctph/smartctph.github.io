<template>
    <nav class="shadow-md">
      <div class="flex flex-row justify-center md:justify-between items-center
      container mx-auto px-20">
        <img :src="require('@/assets/img/smartct-logo-primary-tight.png')"
        width="189px" class="py-2" />
        <ul class="w-full max-w-screen-md hidden md:flex justify-between font-medium">
          <li>
            <a class="text-primary" href="#">Home</a>
          </li>
          <li>
            <a class="text-gray-900" href="#">About</a>
          </li>
          <li>
            <a class="text-gray-900" href="#">Data Portal</a>
          </li>
          <li>
            <a class="text-gray-900" href="#">Services</a>
          </li>
          <li>
            <a class="text-gray-900" href="#">Blog</a>
          </li>
        </ul>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>
