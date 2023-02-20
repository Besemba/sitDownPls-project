# Интернет-магазин SitDownPls
Верстка по макету нескольких страниц интернет магазина SitDownPls. 
Этот репозиторий содержит сборщик gulp и все исходные файлы, которые использовались в верстке сайта <br>
Готовый результат можно найти по ссылке https://besemba.github.io/sitDownPls-build/ <br>
Сайт содержит 4 страницы: <br>
Главная <br>
Каталог (по ссылке в шапке "Каталог") <br>
Страница товара (по любой ссылке "Купить") <br>
Страница сотрудничества (по ссылке "Поставщикам" в футере) <br>

### Цель проекта 
Закрепить навыки веб-вёрстки с использованием gulp и препроцессора scss на практике
	
### Задачи: 
- Верстка сайта по макету;
- Адаптив под любые разрешения, в макете приведены разрешения 1920, 1024, 768, 320;
- Работает функционал в виде слайдеров, табов, аккордеонов, плавный скролл по якорям;
- Все интерактивные элементы (кнопки, ссылки) явно дают понять пользователю, что на них можно кликнуть;
- Pixel perfect вёрстка;
- БЭМ-именование классов;
- Минимум медиазапросов для адаптива;
- Валидный код;

### В репозитории находится:
- файл README.md;
- папка gulp со сборщиком
- папка src со всеми исходными файлами
- папка pages с макетами страниц под разные разрешения;
- файл sdp.ru.fig с макетом
- gulpfile.js со скриптами для работы сборщика
- файлы для .json запуска и работы сборщика

Для реализации валидации формы был использован плагин just-validate.js <br>
Для реализации табов был использован jQuery <br>
Для реализации слайдера были использованы плагины slick slider и swiper.js <br>
Для реализации слайдера в фильтре цены был использован JQuery slider <br>
Для реализации селектов был использован JQuery select <br>
Для реализации адаптива использовано свойство Grid <br>
Реализация остальных интерактивных элементов выполнена в javascript <br>

### Для сборки проекта необходимо:
- скачать репозиторий
- в папке с репозиторием запустить командную строку и выполнить команду 'npm install'
- после установки необходимых модулей запустить команду 'npm run dev' для сборки разработчика с запуском локалього сервера. Или 'npm run build' для конечной сборки, тогда создастся папка dist с готовым сайтом


### Заключение
При выполнении работы реализован сайт по макету. Вёрстка адаптивная, семантическая, pixel perfect. Работает весь интерактивный функционал. БЭМ-именование классов. Код валидный. Все поставленные задачи задачи были выполнены.
