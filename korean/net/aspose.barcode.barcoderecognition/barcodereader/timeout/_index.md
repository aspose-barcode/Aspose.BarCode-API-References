---
title: "BarCodeReader.Timeout"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 속성. 인식 프로세스의 타임아웃을 밀리초 단위로 가져오거나 설정합니다"
type: docs
weight: 80
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

인식 프로세스의 타임아웃을 밀리초 단위로 가져오거나 설정합니다.

```csharp
public int Timeout { get; set; }
```

### Property Value

시간 제한.

## 예제

이 샘플은 큰 이미지에서 시간 초과로 인한 인식 중단을 방지하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


