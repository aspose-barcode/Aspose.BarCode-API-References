---
title: "method"
linktitle: "ReadBarCodes"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Читает BarCodeResults из изображения в C++."
type: docs
weight: 1300
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader::ReadBarCodes method


Читает [BarCodeResult](../../barcoderesult/)s из изображения.

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::ReadBarCodes()
```


### ReturnValue

Возвращает массив распознанных [BarCodeResult](../../barcoderesult/)s на изображении. Если ничего не распознано, возвращается пустой массив.
## Примечания


Этот пример показывает, как считывать штрихкоды с помощью [BarCodeReader](../)
```cpp
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


## См. также

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
