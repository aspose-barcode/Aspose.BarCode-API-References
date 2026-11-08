---
title: "metod"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode for C++ API-referens"
description: " method. Hämtar kodtexten med kodning i C++."
type: docs
weight: 1000
url: /sv/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Hämtar kodtexten med kodning.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kodning | System::SharedPtr\<System::Text::Encoding\> | Kodningen för kodtexten. |

### ReturnValue

En sträng som innehåller identifierad kodtext.
## Anmärkningar



Det här exemplet visar hur man använder **GetCodeText**:


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

## Se även

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
