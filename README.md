# Gulp
Gulp bild
Команда для установки всех пакетов:
npm i gulp gulp-sass sass gulp-file-include gulp-clean gulp-server-livereload gulp-sourcemaps gulp-plumber gulp-notify gulp-group-css-media-queries --save-dev
----------------------------------------------------------------------
Описание пакетов:
gulp - собственно Gulp
gulp-sass - Сборка SASS / SCSS
sass - Необходим для сборки SASS / SCSS
gulp-file-include - Подключение файлов друг в друга. HTML include
gulp-clean - Удаление файлов
gulp-server-livereload - Сервер с автообновлением страницы
gulp-sourcemaps - Исходные карты для CSS
gulp-plumber - Фикс ошибок при сборке
gulp-notify - Нотификации
gulp-group-css-media-queries - Группировка CSS медиа запросов

----------------------------------------------------------------------
Картинки:
npm i gulp-imagemin@7 --save-dev

.pipe(imagemin({ verbose: true }))


----------------------------------------------------------------------

Ускорение сборки

npm install --save-dev gulp-changed

- использование в картинках, HTML, JS, CSS


----------------------------------------------------------------------


web-p

npm i gulp-webp gulp-webp-html gulp-webp-css --save-dev
