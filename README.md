Пример загрузки/загрузки файла Spring Boot Rest API
# Пример загрузки/загрузки файла Spring Boot Rest API

# Укажите каталог для загрузки файлов

Откройте src/main/resources/application.propertiesфайл и измените свойство file.upload-dir на путь, по которому вы хотите хранить загруженные файлы.

file.upload-dir=/Users/callicoder/uploads (директория)


# Вот и все! Доступ к приложению можно получить по адресу http://localhost:8080.

Так же можно посмотреть картинку из папки uploadDir - в браузере с помощью " paint.html" = но перед этим ее нужно добавить в папку uploadDir методом POST, а дальше можно достать
