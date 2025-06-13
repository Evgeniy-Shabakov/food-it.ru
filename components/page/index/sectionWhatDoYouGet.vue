<template>

    <section>

        <TitleH2 class="mb-4">
            Что вы получаете при заказе мобильного приложения и сайта под&nbsp;ключ
        </TitleH2>

        <p class="mb-8 text-xl md:text-2xl text-center text-gray-600">
            современные решения для доставки еды, кафе и
            ресторанов
        </p>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

            <CardDescription :h3Visible=true>
                <template v-slot:h3>
                    Мобильное приложение для Android
                </template>
                <template v-slot:div>
                    <p>Мобильное приложение с Вашим собственным брендом для Android</p>

                </template>
            </CardDescription>

            <CardDescription :h3Visible=true>
                <template v-slot:h3>
                    Мобильное приложение для iOS
                </template>
                <template v-slot:div>
                    <p>Мобильное приложение с Вашим собственным брендом для iOS</p>
                </template>
            </CardDescription>

            <CardDescription :h3Visible=true>
                <template v-slot:h3>
                    Веб-сайт
                </template>
                <template v-slot:div>
                    <p>Сайт с Вашим собственным доменным именем адаптированный для мобильных телефонов, планшетов и
                        мониторов</p>
                </template>
            </CardDescription>

            <CardDescription :h3Visible=true>
                <template v-slot:h3>
                    Панель администратора
                </template>
                <template v-slot:div>
                    <p>
                        Веб-сервис (сайт), позволяющий Вам полностью управлять контентом вашего мобильного приложения и
                        сайта (добавлять и удалять товары и категории, настраивать внешний вид и т.д.)
                    </p>
                </template>
            </CardDescription>

            <CardDescription :h3Visible=true>
                <template v-slot:h3>
                    Панель менеджера заказов
                </template>
                <template v-slot:div>
                    <p>Веб-сервис (сайт), позволяющий Вам видеть в онлайн режиме все заказы и менять их статусы</p>
                </template>
            </CardDescription>

            <!-- <CardDescription :h3Visible=true>
                <template v-slot:h3>
                    Мобильное приложение для курьера
                </template>
                <template v-slot:div>
                    <p>Данная опция пока недоступна и планируется в разработку</p>
                </template>
            </CardDescription> -->

        </div>

    </section>
</template>