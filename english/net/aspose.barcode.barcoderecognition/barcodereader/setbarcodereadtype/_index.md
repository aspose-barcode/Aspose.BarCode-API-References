---
title: BarCodeReader.SetBarCodeReadType
second_title: Aspose.BarCode for .NET API Reference
description: BarCodeReader method. Sets SingleDecodeType type array for recognition. Must be called before ReadBarCodes method
type: docs
weight: 130
url: /net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## SetBarCodeReadType(params SingleDecodeType[]) {#setbarcodereadtype_1}

Sets [`SingleDecodeType`](../../singledecodetype/) type array for recognition. Must be called before ReadBarCodes() method.

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | The [`SingleDecodeType`](../../singledecodetype/) type array to read. |

## Examples

This sample shows how to detect Code39 and Code128 barcodes.

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

### See Also

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeReadType(BaseDecodeType) {#setbarcodereadtype}

Sets decode type for recognition. Deprecated. Use [`BarCodeReadType`](../barcodereadtype/) property instead.

```csharp
[Obsolete("SetBarCodeReadType is deprecated. Use the BarCodeReadType property instead.")]
public void SetBarCodeReadType(BaseDecodeType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | BaseDecodeType | The type of barcode to read. |

### See Also

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


