---
title:  method
linktitle: SetBarCodeReadType
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Sets SingleDecodeType type array for recognition. Must be called before ReadBarCodes() method in C++.'
type: docs
weight: 1400
url: /cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader::SetBarCodeReadType(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) method


Sets [SingleDecodeType](../../singledecodetype/) type array for recognition. Must be called before [ReadBarCodes()](../readbarcodes/) method.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(const System::ArrayPtr<System::SharedPtr<SingleDecodeType>> &barcodeTypes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| barcodeTypes | const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\& | The [SingleDecodeType](../../singledecodetype/) type array to read. |
## Remarks



This sample shows how to detect Code39 and Code128 barcodes. 
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

## See Also

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeReadType(System::SharedPtr\<BaseDecodeType\>) method


Sets decode type for recognition. Must be called before [ReadBarCodes()](../readbarcodes/) method.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(System::SharedPtr<BaseDecodeType> type)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | System::SharedPtr\<BaseDecodeType\> | The type of barcode to read. |
## Remarks



This sample shows how to detect Code39 and Code128 barcodes. 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(new MultiDecodeType(DecodeType.Code39, DecodeType.Code128));
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## See Also

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
