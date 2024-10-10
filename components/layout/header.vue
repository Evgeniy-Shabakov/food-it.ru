<template>
   <header class="bg-white shadow-md" id="top">

      <div class="container mx-auto px-4 py-4 pb-6 flex flex-col items-center gap-4">

         <NuxtLink to="/">
            <img src="/assets/images/Food-IT  logo - мобильное приложение и сайт для доставки еды.png"
               alt="Food-IT Logo" class="h-16 md:h-20" />
         </NuxtLink>

         <h1 class="text-2xl md:text-3xl lg:text-4xl font-bold text-gray-800 text-center px-10">
            Мобильные приложения и сайты
            <span class="text-yellow-500 whitespace-nowrap">
               под ключ
            </span>
            <br />
            для доставки еды, кафе, ресторана
         </h1>

         <a href="mailto:evgeniy_shabakov@mail.ru"
            class="flex items-center px-4 py-2 text-gray-600 hover:text-yellow-800 active:text-yellow-500">
            <IconMail class="mr-2" />
            <span>evgeniy_shabakov@mail.ru</span>
         </a>

         <a href="tel:+79121312653"
            class="flex items-center px-4 py-2 bg-yellow-400 hover:bg-yellow-500 active:bg-yellow-300 rounded-md">
            <IconPhone class="mr-2" />
            <span>+7 (912) 131-26-53</span>
         </a>

      </div>

   </header>
</template>