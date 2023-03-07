# mesto-react

## Обзор

* Описание
* Технологиии
* Ссылка на проект

### Описание ###

Приложение для размещения фотографий интересных мест. Проект реализован на **React.js**. Пользователь может редактировать свой профиль, добавлять и удалять карточки с фото. Каждый пользователь видит все карточки и может их лайкать, но удалить может только те что загрузил сам.

### Технологии ###

* **React.js**, **JSX** Приложение построено на функциональных компонентах и **Hooks**. 
* Основные хуки: 
    * **useState**; 
    * **useEffect**;
    * **useContext**;
    * **useNavigate(react-router-dom)**;
    * сугубо в ознакомительных целях использован хук **useRef**.
Приложение использует два внешних API, одно предоставляет/сохраняет данные карточек, другое предназначено для регистрации и авторизации пользователей. Аутентификация по паролю. Для хранения jwt используется local storage. 
* Код портирован с аналогичного моего приложения, построенного на чистом JavaScript без сторонних библиотек.
* Адаптивная верстка **HTML5** для разрешения от 1280px до 320px. 
* Использованы семантические теги.
* **CSS3** flex, grid, animation.
* Работа с макетом в **Figma**
* Cтруктура проекта по **БЭМ**
* Система контроля версий **GIT**

[Link to gh-pages](https://maksnikulnikov.github.io/react-mesto-auth/)
