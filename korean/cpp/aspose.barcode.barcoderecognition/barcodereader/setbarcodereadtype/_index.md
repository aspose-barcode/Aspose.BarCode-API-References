---
title: "메서드"
linktitle: "SetBarCodeReadType"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. 인식을 위해 SingleDecodeType 배열을 설정합니다. C++에서 ReadBarCodes() 메서드 호출 전에 반드시 호출해야 합니다."
type: docs
weight: 1600
url: /ko/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader::SetBarCodeReadType method


인식을 위해 [SingleDecodeType](../../singledecodetype/) 배열을 설정합니다. [ReadBarCodes()](../readbarcodes/) 메서드 호출 전에 반드시 호출해야 합니다.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(const System::ArrayPtr<System::SharedPtr<SingleDecodeType>> &barcodeTypes)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| barcodeTypes | const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\& | 읽을 [SingleDecodeType](../../singledecodetype/) 배열입니다. |
## 비고



이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.
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

## 또 보기

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
