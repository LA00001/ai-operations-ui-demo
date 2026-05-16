# AI Operations UI Demo

Простой Blazor UI-прототип для операционных инструкций.

## Что показывает
- Blazor Server UI
- ввод тем `101 102`
- справочник тем 101–115
- предпросмотр будущего документа

## Запуск
```bash
dotnet run
```

Откроется: `https://localhost:60001`

## Примечание
Это первый этап portfolio-серии. Полный workflow pipeline находится в проекте `ai-document-workflow-demo`.


## Fix v2
Добавлен `@using Microsoft.AspNetCore.Components.Routing` в `_Imports.razor`.
Без этого Blazor не распознавал `Router`, `Found`, `NotFound`, и сборка падала на `routeData`.


## License

Copyright (c) 2026 Андрей / LA00001. All rights reserved.

This repository is a portfolio demo. Private backend logic, API keys and production configuration are excluded.