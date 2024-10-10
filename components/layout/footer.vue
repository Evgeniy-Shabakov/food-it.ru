<template>

  <footer class="bg-gray-800 text-white py-4">

    <a href="#top" class="block text-center py-2 underline hover:text-yellow-800 active:text-yellow-500">
      Наверх
    </a>

    <div class="container mx-auto px-4 text-center">

      <div class="grid grid-cols-1 place-items-center md:grid-cols-3 md:px-30 lg:px-40">

        <NuxtLink to="/" class="hidden md:block">
          <img src="/assets/images/Food-IT  logo - мобильное приложение и сайт для доставки еды.png" alt="Food-IT Logo"
            class="h-10" />
        </NuxtLink>

        <a href="mailto:evgeniy_shabakov@mail.ru"
          class="flex items-center px-4 py-2 hover:text-yellow-800 active:text-yellow-500">
          <IconMail class="mr-2" />
          <span>evgeniy_shabakov@mail.ru</span>
        </a>

        <a href="tel:+79121312653" class="flex items-center px-4 py-2 hover:text-yellow-800 active:text-yellow-500">
          <IconPhone class="mr-2" />
          <span>+7 (912) 131-26-53</span>
        </a>

      </div>

      <p class="mt-2">
        &copy; 2025 Food-IT. Все права защищены.
      </p>

    </div>

  </footer>

</template>