<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


# Миграции в Laravel

**Миграции** — это система контроля версий для базы данных. Они решают следующие проблемы:

- **Версионность**: Отслеживание изменений структуры БД во времени
- **Синхронизация**: Единообразие схемы БД между разными окружениями (разработка, продакшен)
- **Коллаборация**: Возможность команды разработчиков работать с общей структурой БД
- **Откат изменений**: Легкое возвращение к предыдущим версиям схемы базы данных
- **Автоматизация**: Создание и изменение таблиц через код вместо ручных SQL-запросов

# Eloquent ORM в Laravel

**Eloquent ORM** (Object-Relational Mapping) — это система работы с базой данных через объекты PHP. Его основные преимущества:

- **Объектный подход**: Работа с данными как с объектами вместо SQL-запросов
- **Безопасность**: Автоматическая защита от SQL-инъекций
- **Отношения**: Простое определение связей между моделями (один-ко-многим, многие-ко-многим)
- **Мутаторы/аксессоры**: Преобразование данных при записи и чтении
- **Soft Deletes**: Мягкое удаление записей без фактического удаления из БД
- **Timestamp**: Автоматическое управление временными метками created_at и updated_at