---
title: "BarCodeReader.ReadBarCodes"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 메서드. 이미지에서 BarCodeResults를 읽습니다"
type: docs
weight: 110
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader.ReadBarCodes method

이미지에서 [`BarCodeResult`](../../barcoderesult/)s를 읽습니다.

```csharp
public BarCodeResult[] ReadBarCodes()
```

### 반환 값

이미지에서 인식된 [`BarCodeResult`](../../barcoderesult/)s 배열을 반환합니다. 인식된 것이 없으면 빈 배열이 반환됩니다.

## 예제

이 샘플은 BarCodeReader를 사용하여 바코드를 읽는 방법을 보여준다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
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

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 또 보기

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


