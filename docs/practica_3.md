# Добро пожаловать в документацию Warriors Project
  Warriors Project - это приложение, позволяющее управлять информацией о воинах, их умениях и профессиях. Здесь вы найдете подробную информацию о том, как использовать API и взаимодействовать с различными компонентами системы.
# Управление учетной записью

## Изменение учетных данных

- **URL:** `/auth/user/`
- **Метод:** `PUT`
- **Описание:** Обновляет информацию о пользователе.
- **Параметры:**
  - `username` (string): Новое имя пользователя.
  - `password` (string): Новый пароль.

# Аутентификация

## Вход в систему

- **URL:** `/auth/login/`
- **Метод:** `POST`
- **Описание:** Аутентифицирует пользователя и выдает токен.
- **Параметры:**
  - `username` (string): Имя пользователя.
  - `password` (string): Пароль.

## Создание нового пользователя

- **URL:** `/auth/register/`
- **Метод:** `POST`
- **Описание:** Регистрирует нового пользователя.
- **Параметры:**
  - `username` (string): Имя пользователя.
  - `password` (string): Пароль.
 
# Skills Endpoint

## Получение списка умений

- **URL:** `/war/skills/`
- **Метод:** `GET`
- **Описание:** Возвращает список всех умений.

## Создание умения

- **URL:** `/war/skills/create`
- **Метод:** `POST`
- **Описание:** Создает новое умение.
- **Параметры:**
  - `title` (string): Название умения.
 
# Warriors with Professions

## Получение списка воинов с профессиями

- **URL:** `/war/warriors/professions/`
- **Метод:** `GET`
- **Описание:** Возвращает список всех воинов вместе с их профессиями.

# Warriors with Skills

## Получение списка воинов с умениями

- **URL:** `/war/warriors/skills/`
- **Метод:** `GET`
- **Описание:** Возвращает список всех воинов вместе с их умениями.

[Назад к главной странице](index.md)
    
