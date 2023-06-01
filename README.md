Утилита для просмотра занятого пространства на диске
================================

## Приложение создано с использованием следующих технологий:
 - Maven 
 - Java SE
 - Java FX

## Данное приложение оценивает содержимое выбранной папки в файловой системе
## -  выводит круговой график в соответсвии с размером объектов
## -  в динамике рассчитывает размер при переходе между директориями, как в корень так и к наследникам

## Локальный запуск приложения
- Установить IntelliJ IDEA
- Скачать SDK JavaFX по ссылке ***https://gluonhq.com/products/javafx/*** для своей системы
- Добавить библиотеку к проекту папку ***lib*** из SDK JavaFX по пути File->Project Structure->Libraries
- Добавить ***VM options*** Run->Edit configurations запись по ссылке ***https://openjfx.io/openjfx-docs//***
  - Linux/Mac: --module-path /path/to/javafx-sdk-version/lib --add-modules javafx.controls,javafx.fxml
  - Windows: --module-path "\path\to\javafx-sdk-version\lib" --add-modules javafx.controls,javafx.fxml


## Запустить

- Starter -> run

