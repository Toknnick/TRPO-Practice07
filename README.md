# Практическая работа 7 — ТРПО

PHP MVC: каркас интернет-магазина, маршрутизация и контроллеры.

**Студент:** Юшин Максим  
**Группа:** ЭПБО-01-25

## Результат

Учебный интернет-магазин с единой точкой входа, Router (маршруты из `routes.csv`),
контроллерами HomeController, CatalogController, ErrorController,
layout-шаблоном и страницами из `pages.json`.

## Технологии

- PHP 8+
- HTML / CSS
- MVC без фреймворка

## Запуск

1. Установите PHP 8+ (`php -v`).
2. В корне проекта:

```bash
php -S localhost:8000 -t public public/router.php