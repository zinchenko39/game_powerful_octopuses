# Работа команды Powerful Octopuses

## Установка 
Скопируйте ссылку на наш репозиторий:
```
git clone https://github.com/zinchenko39/game_powerful_octopuses.git
```
Выполните установку:
```
yarn bootstrap
```
Для запуска в режиме разбработки:
```
yarn dev --scope=client
```
## Выполненные задачи
В качестве поддержания единого стиля была использована библиотека MUI.
В ходе работы команды были выполнены следующие задачи:
- Страница регистрации и авторизации:
    - добавлен axios для работы с API;
    - для форм и их валидации использован Formik & Yup;
- Страница с описанием игры, возможностью перейти в другие разделы;
- Страница игры:
    - при нажатии кнопки "играть" происходит отсчет до начала игры;
    - игрок управляет машинкой с помощью стрелок на клавиатуре для передвижения вправо, влево;
    - при столкновении с препятствием игрок проигрывает, появляется экран с окончанием игры на котором есть колчество очков и возможность начать играть заново или перейти в главное меню;
- Страница профиля пользователя;
    - возможность изменение аватара пользователя;
    - возможность изменение пароля;
    - возможность выход из профиля;
- Страница лидерборда;
- Страница форума с темами и отдельными топиками с комментариями;
- Страница 404;
- Страница 500.

Для работы с состоянием был добавлен RTK Query. 
Были внедрены Service Workers для работы приложения без сети.