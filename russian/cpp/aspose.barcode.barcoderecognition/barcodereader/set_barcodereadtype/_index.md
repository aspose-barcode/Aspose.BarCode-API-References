---
title: "method"
linktitle: "set_BarCodeReadType"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Устанавливает тип декодирования штрих‑кода, используемый для распознавания. Должен быть установлен перед вызовом ReadBarCodes в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodereader/set_barcodereadtype/
---
## BarCodeReader::set_BarCodeReadType method


Устанавливает тип декодирования штрих‑кода, используемый для распознавания. Должен быть установлен перед вызовом [ReadBarCodes](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_BarCodeReadType(System::SharedPtr<BaseDecodeType> value)
```

## Примечания


Этот пример показывает, как обнаружить штрихкоды Code39 и Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

## См. также

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
