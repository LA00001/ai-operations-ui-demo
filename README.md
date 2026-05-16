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

## ИСТОРИЯ
1 ai-operations-ui-demo.zip — простой Blazor UI
2 topic-knowledge-base-demo.zip — справочник тем 101–115
3 docx-generator-demo.zip — отдельная генерация DOCX
4 workflow-pipeline-demo.zip — конвейер в консольном варианте
5 generated-files-api-demo.zip — API для выдачи файлов
6 ai-document-workflow-demo.zip — главный полный MVP с UI + конвейером


## License

Copyright (c) 2026 Андрей / LA00001

All rights reserved.

This repository is provided for portfolio and demonstration purposes only.
Copying, redistribution, modification, sublicensing, commercial use, or publication
of the source code is not permitted without prior written permission from the author.

---

Авторское право (c) 2026 Андрей / LA00001

Все права защищены.

Данный репозиторий предоставлен только для демонстрации в портфолио.
Копирование, распространение, изменение, сублицензирование, коммерческое использование
или публикация исходного кода не допускаются без предварительного письменного разрешения автора.
