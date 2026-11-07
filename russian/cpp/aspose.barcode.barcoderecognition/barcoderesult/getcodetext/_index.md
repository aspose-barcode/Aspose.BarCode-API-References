---
title: "method"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Получает текст кода с кодировкой в C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Получает текст кода с кодировкой.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| кодировка | System::SharedPtr\<System::Text::Encoding\> | Кодировка для текста кода. |

### ReturnValue

Строка, содержащая распознанный текст кода.
## Примечания



Этот пример показывает, как использовать **GetCodeText**:


```cpp
[C#]
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## См. также

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
