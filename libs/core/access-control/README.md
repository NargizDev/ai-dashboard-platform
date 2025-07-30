# Core ACCESS-CONTROL Library

Изолированная библиотека для ACCESS-CONTROL функциональности в рамках core модуля.

## Назначение

Эта библиотека содержит компоненты и сервисы для работы с ACCESS-CONTROL запросами. Она является отдельной единицей ответственности в рамках core модуля.

## Структура

```
libs/core/access-control/
├── src/
│   ├── lib/
│   │   ├── access-control.ts          # ACCESS-CONTROL компонент
│   │   ├── access-control.html        # HTML шаблон
│   │   ├── access-control.css         # Стили
│   │   └── access-control.spec.ts     # Тесты
│   ├── index.ts             # Публичный API
│   └── test-setup.ts        # Настройка тестов
├── project.json             # Конфигурация проекта
├── tsconfig.json           # TypeScript конфигурация
└── jest.config.ts          # Jest конфигурация
```

## Использование

```typescript
import { AccessControl } from '@ai-dashboard-platform/core/access-control';
```

## Тестирование

```bash
npx nx test core-access-control
```

## Линтинг

```bash
npx nx lint core-access-control
``` 