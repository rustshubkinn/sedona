[![Netlify Status](https://api.netlify.com/api/v1/badges/dab0e1fc-735f-4838-bec0-f8566bd9bef1/deploy-status)](https://app.netlify.com/sites/dreamy-poincare-1797cd/deploys)

## Sedona

Sedona представляет собой простой веб-сайт состоящий из двух страниц. Страницы написаны с адаптивной резиновой и мобильной версткой. Для сборки проекта используется сборщик Gulp. Присутствует транспайлер Babel для поддержки современного JavaScript (ES6) в браузерах. Дизайн сайта был найден в интернете.

- В проекте используются шаблонизатор Pug и препроцессор SASS.
- Компоненты сайта оформляются в проекте как миксины и являются переиспользуемыми.
- Страницы сверстана с использованием grid и flexbox.

Проект содержит две страницы:

- Домашнюю страницу
- Каталог
  Для перехода в страницу каталога необходимо добавить к адресу проекта [/catalog](https://dreamy-poincare-1797cd.netlify.app/catalog)

## Особенности

- используются препроцессоры [Pug](https://pugjs.org/) и [SCSS](https://sass-lang.com/)
- используется транспайлер [Babel](https://babeljs.io/) для поддержки современного JavaScript (ES6) в браузерах
- используется [Webpack](https://webpack.js.org/) для сборки JavaScript-модулей
- используется проверка кода на ошибки перед коммитом

## :open_file_folder: Файловая структура

```
gulp-pug-starter
├── dist
├── gulp-tasks
├── src
│   ├── blocks
│   ├── fonts
│   ├── img
│   ├── js
│   ├── styles
│   ├── views
│   └── .htaccess
├── gulpfile.babel.js
├── webpack.config.js
├── package.json
├── .babelrc.js
├── .bemrc.js
├── .eslintrc.json
├── .stylelintrc
├── .stylelintignore
└── .gitignore
```

[Live-Version](https://dreamy-poincare-1797cd.netlify.app/)
