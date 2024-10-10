<template>

    <section>

        <TitleH2 class="mb-10">Преимущества</TitleH2>

        <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 gap-8">

            <CardAdvantage>
                <template v-slot:number>
                    1
                </template>
                <template v-slot:h3>
                    Увеличение выручки
                </template>
                <template v-slot:p>
                    Всего несколько кликов будут отделять ваших клиентов от заказа. Хранение истории заказов в личном
                    кабинете клиента, позволет ему повторить любой заказ всего за пару кликов
                </template>
            </CardAdvantage>

            <CardAdvantage>
                <template v-slot:number>
                    2
                </template>
                <template v-slot:h3>
                    Бесплатный старт
                </template>
                <template v-slot:p>
                    Вы не платите за разработку и можете попробовать абсолютно бесплатно. Первые 150 заказов,
                    оформленных
                    через сайт или мобильное приложение
                    не оплачиваютя
                </template>
            </CardAdvantage>

            <CardAdvantage>
                <template v-slot:number>
                    3
                </template>
                <template v-slot:h3>
                    Легкое масштабирование
                </template>
                <template v-slot:p>
                    Подключайте неограниченное количество точек и городов к своему мобильному приложению. Клиенты будут
                    заказывать у Вас, находясь в любом городе
                </template>
            </CardAdvantage>

            <CardAdvantage>
                <template v-slot:number>
                    4
                </template>
                <template v-slot:h3>
                    Гибкая настройка
                </template>
                <template v-slot:p>
                    Возможность опционально включать или отключать доставку, самовывоз, подачу к столику для каждой
                    точки
                    отдельно и многое другое
                </template>
            </CardAdvantage>

            <CardAdvantage>
                <template v-slot:number>
                    5
                </template>
                <template v-slot:h3>
                    Онлайн мониторинг
                </template>
                <template v-slot:p>
                    Вы видите все заказы онлайн, их статусы и сроки исполнения
                </template>
            </CardAdvantage>

            <CardAdvantage>
                <template v-slot:number>
                    6
                </template>
                <template v-slot:h3>
                    Запуск за 1 неделю
                </template>
                <template v-slot:p>
                    Разработанная система Food-IT позволят сделать для Вас готовое к работе мобильное приложение и сайт
                    с
                    Вашим брендом всего за одну неделю
                </template>
            </CardAdvantage>

        </div>

    </section>

</template>