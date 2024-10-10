<template>

    <section>

        <TitleH2 class="mb-10">
            Функциональность
        </TitleH2>

        <div class="grid grid-cols-1 xl:grid-cols-3 gap-8">

        <CardIconAndList :qtyItemsInList=9>

            <template v-slot:icon>
                <IconMobile class="text-green-500" />
            </template>

            <template v-slot:h3>
                Мобильное приложение и сайт
            </template>

            <template v-slot:li_1>Личный кабинет клиента</template>
            <template v-slot:li_2>Отображение статуса заказа</template>
            <template v-slot:li_3>Хранение истории заказов</template>
            <template v-slot:li_4>Кнопка повторить последний заказ</template>
            <template v-slot:li_5>Кнопка повторить заказ для каждого заказа в истории закзов</template>
            <template v-slot:li_6>Управление адресами доставки в личном кабинете</template>
            <template v-slot:li_7>Изменение типа заказа: самовывоз, доставка, в ресторане</template>
            <template v-slot:li_8>Поддержка заказа к столику с вводом номера столика</template>
            <template v-slot:li_9>Поддержка заказа в ресторане с функцией "заберу на выдаче"</template>

        </CardIconAndList>

        <CardIconAndList :qtyItemsInList=6>

            <template v-slot:icon>
                <IconAdministrator class="text-blue-500" />
            </template>

            <template v-slot:h3>
                Панель администратора
            </template>

            <template v-slot:li_1>Добавление/удаление сотрудников с различными правами доступа</template>
            <template v-slot:li_2>Изменение внешнего вида, контактов, графика работы</template>
            <template v-slot:li_3>Добавление неограниченного количества городов и точек</template>
            <template v-slot:li_4>Установка параметров доставки (стоимость, минимальнуя сумма и т.д) для каждого
                города отдельно</template>
            <template v-slot:li_5>Настройка типов работы (самовывоз, доставка, в ресторане) для каждого ресторна
                отдельно</template>
            <template v-slot:li_6>Добавление/редактирование/удаление категорий и товаров</template>

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