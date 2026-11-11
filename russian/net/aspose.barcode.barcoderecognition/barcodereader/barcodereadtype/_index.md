---
title: "BarCodeReader.BarCodeReadType"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Свойство BarCodeReader. Получает или задает тип декодирования штрихкода, используемый для распознавания. Должен быть установлен до вызова ReadBarCodes."
type: docs
weight: 30
url: /ru/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

Получает или задает тип декодирования штрихкода, используемый для распознавания. Должен быть установлен до вызова [`ReadBarCodes`](../readbarcodes/).

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## Примеры

Этот пример показывает, как обнаруживать штрихкоды Code39 и Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

### См. также

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


