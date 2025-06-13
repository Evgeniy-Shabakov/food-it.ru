<template>

   <section>

      <TitleH2 class="mb-10">
         Демонстрационная версия
      </TitleH2>

      <div class="flex flex-col gap-8 md:flex-row md:justify-center md:gap-14">

         <CardDemonstration link="https://demopizza.ru">
            <template v-slot:icon>
               <IconGooglePlay class="text-green-500" />
            </template>
            <template v-slot:h3>
               Мобильное приложение
            </template>
            <template v-slot:p>
               Приложение для Android (ссылка будет позже)
            </template>
         </CardDemonstration>

         <CardDemonstration link="https://demopizza.ru">
            <template v-slot:icon>
               <IconInternet class="text-blue-500" />
            </template>
            <template v-slot:h3>
               Сайт
            </template>
            <template v-slot:p>
               Веб-сайт адаптированный под все типы устройств
            </template>
         </CardDemonstration>

      </div>

   </section>

</template>