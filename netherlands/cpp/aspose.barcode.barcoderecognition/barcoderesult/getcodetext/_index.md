---
title: "methode"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Haalt de code-tekst op met codering in C++."
type: docs
weight: 1000
url: /nl/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Haalt de code-tekst op met codering.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codering | System::SharedPtr\<System::Text::Encoding\> | De codering voor de code-tekst. |

### ReturnValue

Een string die de herkende code-tekst bevat.
## Opmerkingen



Dit voorbeeld toont hoe **GetCodeText** te gebruiken:


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

## Zie ook

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
