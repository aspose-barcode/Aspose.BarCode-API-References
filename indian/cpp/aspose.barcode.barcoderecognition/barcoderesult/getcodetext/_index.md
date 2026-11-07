---
title: "विधि"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " method. C++ में एन्कोडिंग के साथ कोड टेक्स्ट प्राप्त करता है।"
type: docs
weight: 1000
url: /hi/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


एन्कोडिंग के साथ कोड टेक्स्ट प्राप्त करता है।

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| एन्कोडिंग | System::SharedPtr\<System::Text::Encoding\> | कोडटेक्स्ट के लिए एन्कोडिंग। |

### ReturnValue

पहचाने गए कोड टेक्स्ट को सम्मिलित करने वाली स्ट्रिंग।
## टिप्पणियाँ



यह उदाहरण दर्शाता है कि **GetCodeText** का उपयोग कैसे करें:


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

## और देखें

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
