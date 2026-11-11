---
title: "BarCodeReader.FoundBarCodes"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 속성. 인식된 BarCodeResults 배열을 가져옵니다"
type: docs
weight: 50
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/
---
## BarCodeReader.FoundBarCodes property

인식된 [`BarCodeResult`](../../barcoderesult/)s 배열을 가져옵니다

```csharp
public BarCodeResult[] FoundBarCodes { get; }
```

### Property Value

인식된 [`BarCodeResult`](../../barcoderesult/)s 배열

## 예제

이 샘플은 BarCodeReader를 사용하여 바코드를 읽는 방법을 보여준다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

### 또 보기

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


