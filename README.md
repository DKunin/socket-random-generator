# Упраженение

Упражнение для практики работы с интерфейсами. Простой набор генерируемых данных для различиных отладок.

## Установка

Просто клонировать репозиторий.

## Дано

При запуске `npm start` запускается сервер на `localhost:1212`.
Запущенный сервер делает три вещи:
- Использет папку public, как папку статики
- По запросу `/data` - отдает размером в 60 строк и столбцов с рандомными номерами
- Каждые 3 секунды делает бродкаст по сокету, с сообщением `data`, в которой так же содержится вышеуказанная матрица

## Задача

Сделать интерфейс, который будет выводить указанную матрицу. 
- Интерфейс должен менятся динамически на основании существущего дома.
- При обновлениях интерфейс должен быть отзывчив
- При изменении ячеек в таблице выводимой матрицы, должна быть цветовая индикация - меньше или больше новое значение, по сравнению со старым
- Можно использовать любые механики/фреймворки/библиотеки.

## License

MIT © DKunin