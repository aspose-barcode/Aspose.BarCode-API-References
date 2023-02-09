---
title: DataMatrixEncodeMode
second_title: Справочник по API Aspose.BarCode для .NET
description: Режим кодирования кодировщика DataMatrix по умолчанию Auto
type: docs
weight: 670
url: /ru/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

Режим кодирования кодировщика DataMatrix, по умолчанию Auto

```csharp
public enum DataMatrixEncodeMode
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Auto | `0` | Автоматически выбирать лучший режим кодирования для Datamatrix encoding |
| ASCII | `1` | Кодирует один буквенно-цифровой или два цифровых символа на байт |
| Full | `6` | Кодировать 8-битные значения |
| Custom | `7` | Кодировать с помощью кодировки, указанной в BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| C40 | `8` | Использует кодировку C40. Кодирует прописные буквенно-цифровые, строчные и специальные символы |
| Text | `9` | Использует кодировку текста. Кодирует строчные буквенно-цифровые, прописные и специальные символы |
| EDIFACT | `10` | Использует кодировку EDIFACT. Использует шесть битов на символ, кодирует цифры, буквы верхнего регистра и множество знаков препинания, но не поддерживает буквы нижнего регистра. |
| ANSIX12 | `11` | Использует кодировку ANSI X12. |
| ExtendedCodetext | `12` | Режим ExtendedCodetext позволяет вручную переключать схемы кодирования в кодовом тексте. |

### Смотрите также

* пространство имен [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->