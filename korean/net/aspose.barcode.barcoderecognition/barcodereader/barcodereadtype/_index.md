---
title: "BarCodeReader.BarCodeReadType"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 속성. 인식에 사용되는 바코드 디코드 유형을 가져오거나 설정합니다. ReadBarCodes를 호출하기 전에 설정해야 합니다."
type: docs
weight: 30
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

인식에 사용되는 바코드 디코드 유형을 가져오거나 설정합니다. [`ReadBarCodes`](../readbarcodes/)를 호출하기 전에 설정해야 합니다.

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


