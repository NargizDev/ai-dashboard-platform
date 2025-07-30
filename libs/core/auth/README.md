# Core AUTH Library

Изолированная библиотека для AUTH функциональности в рамках core модуля.

## Назначение

Эта библиотека содержит компоненты и сервисы для работы с AUTH запросами. Она является отдельной единицей ответственности в рамках core модуля.

## Структура

```
libs/core/auth/
├── src/
│   ├── lib/
│   │   ├── auth.ts          # AUTH компонент
│   │   ├── auth.html        # HTML шаблон
│   │   ├── auth.css         # Стили
│   │   └── auth.spec.ts     # Тесты
│   ├── index.ts             # Публичный API
│   └── test-setup.ts        # Настройка тестов
├── project.json             # Конфигурация проекта
├── tsconfig.json           # TypeScript конфигурация
└── jest.config.ts          # Jest конфигурация
```

## Использование

```typescript
import { Auth } from '@ai-dashboard-platform/core/auth';
```

## Тестирование

```bash
npx nx test core-auth
```

## Линтинг

```bash
npx nx lint core-auth
``` 