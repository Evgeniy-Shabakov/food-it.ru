<template>

   <section>

      <TitleH2 class="mb-10">
         Функциональность
      </TitleH2>

      <div class="grid grid-cols-1 xl:grid-cols-3 gap-8">

         <CardIconAndList :qtyItemsInList=10>

            <template v-slot:icon>
               <IconMobile class="text-green-500" />
            </template>

            <template v-slot:h3>
               Мобильное приложение и сайт
            </template>

            <template #li_1>Личный кабинет клиента</template>
            <template #li_2>Отображение статуса заказа</template>
            <template #li_3>Хранение истории заказов</template>
            <template #li_4>
               Хранение конфигураций пользователя для товаров с возможностью изменять ингредиенты
            </template>
            <template #li_5>Кнопка повторить последний заказ</template>
            <template #li_6>Кнопка повторить заказ для каждого заказа в истории закзов</template>
            <template #li_7>Управление адресами доставки в личном кабинете</template>
            <template #li_8>Изменение типа заказа: самовывоз, доставка, в ресторане</template>
            <template #li_9>Поддержка заказа к столику с вводом номера столика</template>
            <template #li_10>Поддержка заказа в ресторане с функцией "заберу на выдаче"</template>

         </CardIconAndList>

         <CardIconAndList :qtyItemsInList=8>

            <template v-slot:icon>
               <IconAdministrator class="text-blue-500" />
            </template>

            <template v-slot:h3>
               Панель администратора
            </template>

            <template #li_1>Добавление/удаление сотрудников с различными правами доступа</template>
            <template #li_2>Изменение внешнего вида, контактов, графика работы</template>
            <template #li_3>Добавление неограниченного количества городов и точек</template>
            <template #li_4>Зоны доставки с различными условиями доставки</template>
            <template #li_5>
               Настройка типов работы (самовывоз, доставка, в ресторане) для каждого ресторна отдельно
            </template>
            <template #li_6>Стоп-лист для товаров и ингредиентов</template>
            <template #li_7>Добавление/редактирование/удаление категорий и товаров</template>
            <template #li_8>
               Добавление кастомизируемых товаров с возможностью изменять/добавлять/удалять ингредиенты
            </template>

         </CardIconAndList>

         <CardIconAndList :qtyItemsInList=4>

            <template v-slot:icon>
               <IconOrder class="text-purple-500" />
            </template>

            <template v-slot:h3>
               Панель менеджера заказов
            </template>

            <template v-slot:li_1>Онлайн отображение всех заказов для каждого ресторана отдельно</template>
            <template v-slot:li_2>Измение статуса заказов</template>
            <template v-slot:li_3>Карточка заказа с подробными данными о заказе</template>
            <template v-slot:li_4>Функция отмены заказа</template>

         </CardIconAndList>

      </div>

   </section>

</template>