## HT1
1. Починить закрытие статьи;
2. Подключить react-date-picker
2.1 Реализовать выбор диапазона дат и вывод их в виде текста;
3. multi-select с помощью react-select;
4. Сделать список комментариев, которые тоже будут открываться и закрываться кнопкой (новую кнопку сделать).

## HT2
1. Анимация открытия/закрытия комментариев;
2. Тест на список комментариев;
3. Покрыть тестом открытие/закрытие всех статей;
4. Написать PropTypes для всего приложения.

## HT3
1. Вынести состояние фильтра в Store;
2. Реализовать фильтрацию статей.

## HT4
1. UI для добавления нового комментария.
2. Написать Middleware для генерации Id комментария.
3. Переписать articles на ключ-значение.
4. Реализовать добавление комментариев к статье.

## HT5
1. При открытии статьи подргружать текст стати (callAPI: '/api/article/:id')
2. Загружать комментарии при открытии комментариев (callAPI:  '/api/comment?article=<article_id>')

## HT6
1. Сделать страницу для отображения всех комментариев (/comments/2)
2. Загружать для каждой страницы по 5 комментариев, загружать каждую страницу только 1 раз (http://localhost:3001/api/comment?limit=5&offset=0)

## HT7
1. Реализовать локализацию (хранить словарь в контексте).
2. Починить баг с открытием статьи по ссылке.
