# Адаптивный лендинг

Проект был создан с помощью сборщика GULP, с использованием препроцессора css - SASS

Настройки сборки находятся в файле gulpfile.js, где
  1) Исходные файлы находятся в папке src
  2) HTML страница разбита на несколько частей (hedear.html; sidebar.html; index.html), которые вставляются в файл default.thml( функция html)
  3) CSS разбит на несколько частей в папке SCSS( папка blocks и папка media ), которые импортируется в главный файл style.scss( функция css)
  4) Код JS находится в файле app.js и подгружается функцией js  
  5) Также подключен browserSync для упрощения разработки
  6) Функции с приставкой 'watches...' созданы для ускоренной загрузки изменений в реальном времени
  7) Функция images оптимизирует загрузку картинок 
  8) Проэкт собирается в папку dist с аналогичной файловой структурой исходников(перед повторной сборкой все файлы в этой директории удаляются функцией clean)
  9) Внизу прописаны команды для сборщика, по умолчанию вызывается команда watch
  10) Для запуска проэкта необходимо ввести в консоль команду gulp
  
