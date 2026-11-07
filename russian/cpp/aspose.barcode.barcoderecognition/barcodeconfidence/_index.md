---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Содержит уровень уверенности распознавания в C++."
type: docs
weight: 3500
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


Содержит уровень уверенности распознавания

```cpp
enum class BarCodeConfidence : int32_t
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Уверенность [Recognition](../../aspose.barcode.barcoderecognition.recognition/) штрихкода, когда текст кода не распознан корректно или штрихкод обнаружен как возможный подделка |
|  | Moderate | 80 | Уверенность [Recognition](../../aspose.barcode.barcoderecognition.recognition/) штрихкода (в основном 1D штрихкодов) с слабой контрольной суммой или без неё. Может содержать некоторые ошибки распознавания текста кода или даже поддельные распознавания, если |

низкая |
| Strong | 100 | Уверенность [Recognition](../../aspose.barcode.barcoderecognition.recognition/) подтверждена кодами BCH, такими как Рид–Соломон. Не должно быть ошибок в прочитанном тексте кода или поддельных распознаваний |

## Примечания


Этот пример показывает, как меняется BarCodeConfidence в зависимости от типа штрихкода
```cpp
[C#]
//Умеренная уверенность
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}

//Сильная уверенность
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
