<template>
    <div id="whywe" class="container1">
        <div class="main-content">
            <h1>Почему стоит выбрать PurfectPets?</h1>
            <p>В магазине PurfectPets мы понимаем, что ваши питомцы - это не просто животные, а члены семьи. Мы стремимся предложить вам и вашим любимцам только самое лучшее. Вот почему PurfectPets - это ваш лучший выбор:</p>
            <div class="reason">
                <h2>1. Широкий ассортимент товаров</h2>
                <p>Мы предлагаем разнообразный выбор кормов, игрушек, аксессуаров и средств ухода для ваших питомцев. Независимо от того, у вас кошка, собака, грызун, птица или насекомое, вы найдете все необходимое в одном месте.</p>
            </div>
            <div class="reason">
                <h2>2. Высокое качество продукции</h2>
                <p>Все товары в нашем магазине проходят строгий контроль качества. Мы сотрудничаем только с проверенными и надежными брендами, чтобы вы могли быть уверены в безопасности и качестве продукции для ваших питомцев.</p>
            </div>
            <div class="reason">
                <h2>3. Консультации специалистов</h2>
                <p>Наши опытные консультанты всегда готовы помочь вам с выбором. Мы предоставим профессиональные советы по уходу, питанию и воспитанию ваших питомцев, чтобы они были здоровы и счастливы.</p>
            </div>
            <div class="reason">
                <h2>4. Удобный и быстрый сервис</h2>
                <p>Мы знаем, как важно быстро получать необходимые товары для питомцев. Поэтому мы предлагаем удобные способы заказа и быструю доставку, чтобы вы могли сэкономить время и уделить больше внимания своим любимцам.</p>
            </div>
            <div class="reason">
                <h2>5. Программы лояльности и акции</h2>
                <p>PurfectPets ценит своих клиентов и предлагает выгодные программы лояльности. Постоянные акции и скидки позволят вам экономить, не жертвуя качеством продукции.</p>
            </div>
            <div class="reason">
                <h2>6. Социальная ответственность</h2>
                <p>Мы заботимся не только о ваших питомцах, но и о животных, нуждающихся в помощи. PurfectPets активно поддерживает приюты для животных и благотворительные организации, чтобы сделать мир лучше.</p>
            </div>
            <div class="reason">
                <h2>7. Положительные отзывы клиентов</h2>
                <p>Наша лучшая реклама - это довольные клиенты. Прочитайте отзывы на нашем сайте и убедитесь, что мы заслуживаем ваше доверие.</p>
            </div>
            <router-link to="/" class="cta">Выбирайте PurfectPets - ваш питомец заслуживает лучшего!</router-link>
        </div>
    </div>
</template>

<script>
export default {
    methods: {
        returnToHomePage() {
            // Перенаправление на главную страницу
            this.$router.push('/');
        }
    }
}
</script>

<style scoped>
/* Фоновая текстура */
body {
  background-color: #f7f7f7; /* Светло-серый фон */
}

#whywe {
  background-color: #ffffff; /* Белый фон */
  padding: 60px; /* Большие внутренние отступы */
  border-radius: 30px; /* Большие скругленные углы */
  box-shadow: 0px 0px 40px rgba(0, 0, 0, 0.1); /* Более глубокая тень */
}

.container1 {
  max-width: 1200px; /* Очень большая максимальная ширина контейнера */
  margin: 0 auto; /* Центрирование контейнера */
}

.main-content {
  text-align: center; /* Центрирование содержимого */
}

h1, h2 {
  font-family: 'Helvetica Neue', sans-serif; /* Шрифт Helvetica Neue для заголовков */
  color: #333; /* Черный цвет для заголовков */
  font-weight: bold; /* Жирный шрифт для заголовков */
  letter-spacing: 1px; /* Увеличение расстояния между буквами */
}

h1 {
  font-size: 36px; /* Увеличенный размер шрифта для h1 */
}

h2 {
  font-size: 30px; /* Увеличенный размер шрифта для h2 */
  margin-top: 10px; /* Уменьшение верхнего отступа для h2 */
  margin-bottom: 5px; /* Уменьшение нижнего отступа для h2 */
}

.reason {
  background-color: #ffffff; /* Белый фон для блоков с причинами */
  border-radius: 30px; /* Большие скругленные углы */
  padding: 60px; /* Большие внутренние отступы */
  margin-bottom: 60px; /* Большие отступы снизу */
  border: 4px solid #f0f0f0; /* Толстая светло-серая граница */
  box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.1); /* Тень блока */
  transition: transform 0.4s ease-in-out, background-color 0.3s ease; /* Анимация при наведении */
  font-size: larger;
}

.reason:hover {
  transform: translateY(-20px); /* Более глубокий эффект поднятия при наведении */
  background-color: rgba(0, 128, 255, 0.1); /* Еле заметный синий цвет при наведении */
}

p {
  font-family: 'Helvetica Neue', sans-serif; /* Шрифт Helvetica Neue для текста */
  color: #666; /* Темно-серый цвет для текста */
  font-size: 20px; /* Увеличение размера шрифта */
  line-height: 1.8; /* Увеличение межстрочного интервала */
}

.cta {
  font-family: 'Helvetica Neue', sans-serif; /* Шрифт Helvetica Neue для призыва к действию */
  color: #ffffff; /* Белый цвет для призыва к действию */
  background-color: #ff3b30; /* Ярко-красный фон для призыва к действию */
  padding: 25px 50px; /* Большие внутренние отступы */
  border-radius: 50px; /* Круглые углы */
  margin-top: 80px; /* Больший отступ сверху */
  text-transform: uppercase; /* Преобразование текста в верхний регистр */
  letter-spacing: 2px; /* Расстояние между буквами */
  box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.15); /* Более выразительная тень кнопки */
  transition: background-color 0.3s ease; /* Плавное изменение цвета фона при наведении */
  text-decoration: none;
}

.cta:hover {
  background-color: #cc2e23; /* Более темный красный цвет при наведении */
}
</style>
