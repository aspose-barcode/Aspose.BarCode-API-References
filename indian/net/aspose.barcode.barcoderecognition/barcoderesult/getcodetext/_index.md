---
title: "BarCodeResult.GetCodeText"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeResult मेथड। एन्कोडिंग के साथ कोड टेक्स्ट प्राप्त करता है"
type: docs
weight: 130
url: /hi/net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

एन्कोडिंग के साथ कोड टेक्स्ट प्राप्त करता है।

```csharp
public string GetCodeText(Encoding encoding)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| एन्कोडिंग | एन्कोडिंग | कोडटेक्स्ट के लिए एन्कोडिंग। |

### वापसी मान

एक स्ट्रिंग जिसमें पहचाना गया कोड टेक्स्ट शामिल है।

## उदाहरण

यह उदाहरण दिखाता है कि `GetCodeText` का उपयोग कैसे करें:

```csharp
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

### और देखें

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


