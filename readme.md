Для запуска тестов в selenium grid:
- установить последний jdk
- отсюда: https://www.selenium.dev/downloads/ загрузить selenium server и драйвера под браузеры (версия драйвера должна подходить под версию браузера!)
- все загруженные файлы поместить в отдельную папку
- из папки запустить терминал, ввести: java -jar selenium-server-{version}.jar standalone
- перейти в браузере по url: http://localhost:4444/ui - убедиться, что браузеры на месте
- запустить тест (команда на запуск из терминала есть в файле с тестом)
