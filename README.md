# AI Dashboard Platform

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ Платформа для создания AI дашбордов с использованием [Nx workspace](https://nx.dev) ✨.

Этот проект представляет собой современную платформу для создания интерактивных дашбордов с интеграцией искусственного интеллекта. Построен на Angular с использованием Nx монорепозитория для эффективного управления кодом.

## О проекте

AI Dashboard Platform - это комплексное решение для создания, управления и визуализации данных с использованием AI технологий. Проект включает:

- **Dashboard приложение** - основное веб-приложение для отображения дашбордов
- **Core библиотеки** - переиспользуемые компоненты и утилиты
- **HTTP модуль** - для работы с API и внешними сервисами

## Технологический стек

- **Frontend**: Angular 17+
- **Монорепозиторий**: Nx
- **Тестирование**: Jest, Cypress
- **Линтинг**: ESLint
- **Форматирование**: Prettier
- **Пакетный менеджер**: pnpm

## Быстрый старт

### Установка зависимостей

```sh
pnpm install
```

### Запуск приложения

```sh
npx nx serve dashboard
```

### Сборка проекта

```sh
npx nx build dashboard
```

### Запуск тестов

```sh
npx nx test dashboard
```

## Структура проекта

```
ai-dashboard-platform/
├── dashboard/          # Основное приложение
├── dashboard-e2e/      # E2E тесты
├── libs/
│   └── core/          # Общие библиотеки
│       └── http/      # HTTP модуль
└── ...
```

## Доступные команды

Для запуска задач с Nx используйте:

```sh
npx nx <target> <project-name>
```

### Примеры команд

```sh
# Сборка приложения
npx nx build dashboard

# Запуск в режиме разработки
npx nx serve dashboard

# Запуск тестов
npx nx test dashboard

# Запуск E2E тестов
npx nx e2e dashboard-e2e

# Создание новой библиотеки
npx nx g @nx/angular:library my-lib
```

## Добавление новых проектов

Для добавления новых проектов используйте Nx генераторы:

```sh
# Добавление Angular приложения
npx nx g @nx/angular:app my-app

# Добавление библиотеки
npx nx g @nx/angular:library my-lib

# Добавление компонента
npx nx g @nx/angular:component my-component --project=dashboard
```

## Настройка CI/CD

### Шаг 1: Подключение к Nx Cloud

```sh
npx nx connect
```

### Шаг 2: Настройка CI workflow

```sh
npx nx g ci-workflow
```

## Полезные ссылки

- [Документация Nx](https://nx.dev)
- [Документация Angular](https://angular.io/docs)
- [Nx Console](https://nx.dev/getting-started/editor-setup)

## Сообщество

Присоединяйтесь к сообществу:
- [Discord](https://go.nx.dev/community)
- [Twitter](https://twitter.com/nxdevtools)
- [LinkedIn](https://www.linkedin.com/company/nrwl)
- [YouTube](https://www.youtube.com/@nxdevtools)
- [Блог](https://nx.dev/blog)
