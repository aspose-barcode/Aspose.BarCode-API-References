---
title: EnableChecksum
second_title: Справочник по API Aspose.BarCode для .NET
description: Включить контрольную сумму при генерации одномерных штрих-кодов.
type: docs
weight: 710
url: /ru/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

Включить контрольную сумму при генерации одномерных штрих-кодов.

Значение по умолчанию трактуется как «Да» для кодировок, которые должны содержать контрольную сумму, и как «Нет», если возможна только контрольная сумма.

Контрольная сумма никогда не использовалась: Codabar

Возможна контрольная сумма: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Контрольная сумма всегда используется: Остальные символы

```csharp
public enum EnableChecksum
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Default | `0` | Если по спецификации требуется контрольная сумма - она будет прикреплена. |
| Yes | `1` | По возможности всегда используйте контрольную сумму. |
| No | `2` | Не использовать контрольную сумму. |

### Смотрите также

* пространство имен [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->