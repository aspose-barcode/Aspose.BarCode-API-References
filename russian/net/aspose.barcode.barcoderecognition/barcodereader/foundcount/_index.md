---
title: FoundCount
second_title: Справочник по API Aspose.BarCode для .NET
description: Получает количество распознанных штрих-кодов
type: docs
weight: 50
url: /ru/net/aspose.barcode.barcoderecognition/barcodereader/foundcount/
---
## BarCodeReader.FoundCount property

Получает количество распознанных штрих-кодов

```csharp
public int FoundCount { get; }
```

### Стоимость имущества

Количество распознанных штрих-кодов

### Примеры

В этом примере показано, как считывать штрих-коды с помощью BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

### Смотрите также

* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->