---
title: "metot"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntemi. C++'da kod metnini kodlamayla alır."
type: docs
weight: 1000
url: /tr/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Kod metnini kodlamayla birlikte alır.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kodlama | System::SharedPtr\<System::Text::Encoding\> | Kod metni için kodlama. |

### ReturnValue

Tanımlanan kod metnini içeren bir dize.
## Açıklamalar



Bu örnek **GetCodeText** kullanımını gösterir:


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

## Ayrıca Bakınız

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
