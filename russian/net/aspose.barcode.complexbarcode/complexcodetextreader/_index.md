---
title: ComplexCodetextReader
second_title: Справочник по API Aspose.BarCode для .NET
description: ComplexCodetextReader декодирует кодовый текст в заданный тип сложного штрих-кода.
type: docs
weight: 340
url: /ru/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader декодирует кодовый текст в заданный тип сложного штрих-кода.

```csharp
public sealed class ComplexCodetextReader
```

## Методы

| Имя | Описание |
| --- | --- |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark)(string) | Декодирует кодовый текст Mailmark Barcode C и L. |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d)(string) | Декодирует кодовый текст Royal Mail Mailmark 2D. |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr)(string) | Декодирует кодовый текст SwissQR. |

### Примеры

В этом примере показано, как распознавать и декодировать изображение SwissQR.

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### Смотрите также

* пространство имен [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
