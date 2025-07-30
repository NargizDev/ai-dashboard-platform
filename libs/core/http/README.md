# Core HTTP Library

Изолированная библиотека для HTTP функциональности в рамках core модуля.

## Назначение

Эта библиотека содержит компоненты и сервисы для работы с HTTP запросами. Она является отдельной единицей ответственности в рамках core модуля.

## Структура

```
libs/core/http/
├── src/
│   ├── lib/
│   │   ├── http.ts          # HTTP компонент
│   │   ├── http.html        # HTML шаблон
│   │   ├── http.css         # Стили
│   │   └── http.spec.ts     # Тесты
│   ├── index.ts             # Публичный API
│   └── test-setup.ts        # Настройка тестов
├── project.json             # Конфигурация проекта
├── tsconfig.json           # TypeScript конфигурация
└── jest.config.ts          # Jest конфигурация
```

## Использование

```typescript
import { Http } from '@ai-dashboard-platform/core/http';
```

## Тестирование

```bash
npx nx test core-http
```

## Линтинг

```bash
npx nx lint core-http
``` 