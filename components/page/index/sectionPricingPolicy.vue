<template>

    <section>

        <TitleH2 class="mb-10">
            Ценовая политика
        </TitleH2>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 2xl:px-60">

            <CardIconAndList :qtyItemsInList=4>

                <template v-slot:icon>
                    <IconPlus class="text-green-500" />
                </template>

                <template v-slot:h3>
                    Вы не платите за
                </template>

                <template v-slot:li_1>разработку</template>
                <template v-slot:li_2>поддержку и обслуживание</template>
                <template v-slot:li_3>аренду сервера и доменного имени</template>
                <template v-slot:li_4>СМС оповещения при оформлении заказов и регистрации пользователей</template>

            </CardIconAndList>

            <CardIconAndList :qtyItemsInList=4>

                <template v-slot:icon>
                    <IconPrice class="text-blue-500" />
                </template>

                <template v-slot:h3>
                    Стоимость
                </template>

                <template v-slot:li_1>20р за заказ</template>
                <template v-slot:li_2>Вы платите только за заказы, оформленные через сайт или мобильное приложение</template>
                <template v-slot:li_3>нет фиксированный платежей и процента от суммы чека</template>
                <template v-slot:li_4>нет заказов - нет платежей</template>

            </CardIconAndList>

        </div>

    </section>

</template>