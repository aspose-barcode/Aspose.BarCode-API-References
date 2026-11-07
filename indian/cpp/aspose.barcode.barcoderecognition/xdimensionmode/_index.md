---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में enum का उपयोग कैसे करें।"
type: docs
weight: 4000
url: /hi/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ऑटो | 0 | XDimension का मान AI (SVM) द्वारा पता लगाया जाता है। वर्तमान में यह Normal के समान है |
| छोटा | 1 | BarcodeQuality की गुणवत्ता के साथ 1 पिक्सेल या अधिक छोटे XDimension वाले बारकोड का पता लगाता है |
| सामान्य | 2 | BarcodeQuality या उच्च गुणवत्ता वाले बारकोड की गुणवत्ता के साथ 2 पिक्सेल या अधिक क्लासिक XDimension वाले बारकोड का पता लगाता है। |
| बड़ा | 3 | उच्च-रिज़ॉल्यूशन कैमरों से कैप्चर किए गए BarcodeQuality की गुणवत्ता के साथ बड़े XDimension वाले बारकोड का पता लगाता है। |
| UseMinimalXDimension | 4 | MinimalXDimension में सेट आकार से बारकोड का पता लगाता है और BarcodeQuality से गुणवत्ता लेता है |

## टिप्पणियाँ


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

यह नमूना दिखाता है कि XDimension मोड का उपयोग कैसे करें
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
