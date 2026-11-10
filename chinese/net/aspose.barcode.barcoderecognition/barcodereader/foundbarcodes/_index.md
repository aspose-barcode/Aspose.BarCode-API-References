---
title: "BarCodeReader.FoundBarCodes"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarCodeReader 属性。获取已识别的 BarCodeResults 数组"
type: docs
weight: 50
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/
---
## BarCodeReader.FoundBarCodes property

获取已识别的 [`BarCodeResult`](../../barcoderesult/) 数组

```csharp
public BarCodeResult[] FoundBarCodes { get; }
```

### Property Value

已识别的 [`BarCodeResult`](../../barcoderesult/) 数组

## 示例

此示例展示了如何使用 BarCodeReader 读取条码

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

### 另见

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


