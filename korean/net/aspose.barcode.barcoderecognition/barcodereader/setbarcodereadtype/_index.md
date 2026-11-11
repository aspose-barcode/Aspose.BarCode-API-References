---
title: "BarCodeReader.SetBarCodeReadType"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 메서드. 인식을 위해 SingleDecodeType 유형 배열을 설정합니다. ReadBarCodes 메서드 호출 전에 사용해야 합니다"
type: docs
weight: 130
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader.SetBarCodeReadType method

인식을 위해 [`SingleDecodeType`](../../singledecodetype/) 유형 배열을 설정합니다. ReadBarCodes() 메서드 호출 전에 사용해야 합니다.

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | 읽을 [`SingleDecodeType`](../../singledecodetype/) 유형 배열. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 또 보기

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


