---
title: "metot"
linktitle: "SetBarCodeReadType"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntem. Tanıma için SingleDecodeType türü dizisini ayarlar. C++'da ReadBarCodes() yönteminden önce çağrılmalıdır."
type: docs
weight: 1600
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader::SetBarCodeReadType method


Tanıma için [SingleDecodeType](../../singledecodetype/) türü dizisini ayarlar. [ReadBarCodes()](../readbarcodes/) yönteminden önce çağrılmalıdır.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(const System::ArrayPtr<System::SharedPtr<SingleDecodeType>> &barcodeTypes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeTypes | const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\& | Okunacak [SingleDecodeType](../../singledecodetype/) türü dizisi. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
```cpp
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

## Ayrıca Bakınız

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
