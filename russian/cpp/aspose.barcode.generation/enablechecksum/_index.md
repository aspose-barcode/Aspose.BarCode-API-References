---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать enum в C++."
type: docs
weight: 6700
url: /ru/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| По умолчанию | 0 | Если контрольная сумма требуется спецификацией — она будет добавлена. |
| Да | 1 | Всегда используйте контрольную сумму, если это возможно. |
| Нет | 2 | Не используйте контрольную сумму. |

## Примечания


Включить контрольную сумму при генерации 1D штрихкодов.

По умолчанию считается «Да» для символогий, где контрольная сумма обязательна, и «Нет», где она лишь возможна.

Контрольная сумма никогда не используется: Codabar

Контрольная сумма возможна: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Контрольная сумма всегда используется: остальные символогии
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
