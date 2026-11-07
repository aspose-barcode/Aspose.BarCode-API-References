---
title: "enum"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Указывает различные типы автоматических режимов масштабирования на C++."
type: docs
weight: 5200
url: /ru/cpp/aspose.barcode.generation/autosizemode/
---
## AutoSizeMode enum


Указывает различные типы режимов автоматического масштабирования.

```cpp
enum class AutoSizeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Нет | 0 | Автоматическое изменение размера отключено. |
| Nearest | 1 | Изменяет размер штрихкода до ближайшего наименьшего возможного размера, указанного свойствами ImageWidth и ImageHeight. Сохраняет соотношение сторон по умолчанию. |
| Интерполяция | 2 | Изменяет размер штрихкода до указанного размера. Размер может быть задан с помощью свойств ImageWidth и ImageHeight. Сгенерированный штрихкод может стать недействительным (нечитаемым) после масштабирования. |

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
