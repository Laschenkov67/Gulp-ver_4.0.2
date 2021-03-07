# Сборка на gulp ver 4.0.2 

Устанавливать с правами администратора!
В терминале прописать следующее:
1) npm i
2) gulp

# Плагины используемые в сборке:

1) Browsersync 
    Позволяет проводить синхронизированное тестирование браузера, позволяющее сэкономить время.
     - официальная документация: https://browsersync.io/docs
     - установка: npm i browser-sync -D
2) gulp-file-include
    Плагин для включения файлов в проект. По сути это шаблонизатор позволяющий собирать проект состоящий из отдельных компонентов.
     - официальная документация: https://www.npmjs.com/package/gulp-file-include
     - установка: npm i gulp-file-include -D
3) Del 
    Плагин для автоматического удаления файлов из проекта.
     - официальная документация: https://www.npmjs.com/package/del
     - установка: npm i del -D
4) gulp-sass 
    Плагин для работы с scss файлами в проекте. Sass позволяет вкладывать правила CSS друг в друга.
     - официальная документация: https://www.npmjs.com/package/gulp-sass
     - установка: npm i gulp-sass -D
5) gulp-autoprefixer 
    Плагин для автоматического добавления вендорных префиксов к файлам css свойствам.
     - официальная документация: https://www.npmjs.com/package/gulp-autoprefixer
     - установка: npm i gulp-autoprefixer -D
6) gulp-group-css-media-queries 
    Плагин для сборки разбросанных по css файлам @media запросы и добавляет их в конец файла.
     - официальная документация: https://www.npmjs.com/package/gulp-group-css-media-queries
     - установка: npm i gulp-group-css-media-queries -D
7) gulp-clean-css
    Плагин чистит и сжимает css файлы.
     - официальная документация: https://www.npmjs.com/package/gulp-clean-css
     - установка: npm i gulp-clean-css -D
8) gulp-rename
    Плагин для работы с scss файлами в проекте. Sass позволяет вкладывать правила CSS друг в друга.
     - официальная документация: https://www.npmjs.com/package/gulp-rename
     - установка: npm i gulp-rename -D
9) gulp-uglify-es 
    Плагин для сжатия js файлов.
     - официальная документация: https://www.npmjs.com/package/gulp-uglify-es
     - установка: npm i gulp-uglify-es -D
10) gulp-imagemin 
    Плагин для сжатия картинок без потери качества. Он умеет сжимать картинки форматов PNG, JPEG, GIF и SVG. Все остальные (не поддерживаемые) форматы графических файлов просто игнорируются плагином.
     - официальная документация: https://www.npmjs.com/package/gulp-imagemin
     - установка: npm i gulp-imagemin -D
11) gulp-webp-html 
    Плагин для автоматического подключения изображения в html-разметку. Подробнее см. в офицальной документации.
     - официальная документация: https://www.npmjs.com/package/gulp-webp-html
     - установка: npm i gulp-webp-html -D
12) imagemin-webp 
    Плагин и загрузчик для оптимизации (сжатия) всех изображений с помощью imagemin. Не беспокойтесь о размере изображений, теперь они всегда оптимизированы и сжимаются.
     - официальная документация: https://www.npmjs.com/package/imagemin-webp
     - установка: npm i imagemin-webp -D
13) gulp-webpcss 
    Плагин для современного формата изображений в css файлах.
     - официальная документация: hhttps://www.npmjs.com/package/gulp-webpcss
     - установка: npm i gulp-webpcss -D
14) gulp-svg-sprite 
    Плагин который берет массив SVG-файлов , оптимизирует их и сохраняет в SVG-спрайты нескольких типов.
    Подробнее см. в официальной документации.
     - официальная документация: https://www.npmjs.com/package/gulp-svg-sprite
     - установка: npm i gulp-svg-sprite -D
15) gulp-ttf2woff 
    Плагин для создания шрифта WOFF из шрифта TTF
     - официальная документация: https://www.npmjs.com/package/gulp-ttf2woff
     - установка: npm i gulp-ttf2woff -D
16) gulp-ttf2woff2 
     Плагин для создания шрифта WOFF2 из шрифта TTF2.
     - официальная документация: https://www.npmjs.com/package/gulp-ttf2woff2
     - установка: npm i gulp-ttf2woff2 -D
17) gulp-fonter 
    Плагин представляет собой оболочку gulp для fonteditor-core с возможностью одновременного сохранения в нескольких форматах.
     - официальная документация: https://www.npmjs.com/package/gulp-fonter
     - установка: npm i gulp-fonter -D
18) gulp-newer 
    Плагин для сохранения только тех исходных файлов, которые новее, чем соответствующие файлы назначения.
     - официальная документация: https://www.npmjs.com/packagegulp-newer
     - установка: npm i gulp-newer -D

Если возникла проблема с node-sass
npm rebuild node-sass

Проблема с pyton
npm install --global windows-build-tools

Варианты решения проблем c imagemin:
- папки и файлы должны быть названы латиницей без пробелов
- тег img и его содержимое должны быть записаны в одну строку без переносов
- в атрибуте src должен быть указан путь к существующей картинке