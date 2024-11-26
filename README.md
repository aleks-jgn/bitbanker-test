# Тестовая задача для Bitbanker

## Описание задания:
Необходимо разработать простое веб-приложение для управления постами. Приложение должно:
1. Отображать список постов, полученных из API JSONPlaceholder: https://jsonplaceholder.typicode.com/posts.
2. Позволять добавлять новые посты с помощью API.
3. Поддерживать редактирование информации о существующих постах.
4. Реализовать возможность удаления постов.

## Стек:
- Vue 3 (Composition API)
- TypeScript
- HTTP-клиент: axios
- API: JSONPlaceholder
- Управление состоянием: Pinia
- Маршрутизация: Vue Router
- Vite

## Текущая реализация:
https://aleks-jgn.github.io/bitbanker-test/
- На гавной странице есть кнопка "Load Posts" - она подгружает на страницу посты из https://jsonplaceholder.typicode.com/posts
- Каждый пост кликабелен для просмотра
- Каждый пост можно удалить кнопкой "Delete"
- Каждый пост можно отредактировать кнопкой "Edit"

## Project setup
```
npm install
```

## Compiles and hot-reloads for development
Starts a local web server for development, and will automatically change when code changes
```
npm run dev
```

## Compiles and minifies for production
Builds the project, and outputs to the folder ./dist
```
npm run build
```

## Compiles and minifies for previewing
Start a local web server that serves the built solution from ./dist for previewing
```
npm run preview
```
