---
title: "DecodeType.TryParse"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "DecodeType मेथड। SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में बदलता है। रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल"
type: docs
weight: 980
url: /hi/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल।

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | स्ट्रिंग | एक स्ट्रिंग जिसमें "EAN8" या "EAN13" या "CodaBar"... के रूप में SingleDecodeType हो, जिसे परिवर्तित किया जाना है। |
| परिणाम | SingleDecodeType& | जब रूपांतरण सफलतापूर्वक पूरा हो जाता है, तो एक वास्तविक SingleDecodeType लौटाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: DecodeType.None. |

### वापसी मान

**true** if parsingType was converted successfully; otherwise, **false**.

### और देखें

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse}

MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल।

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | स्ट्रिंग | एक स्ट्रिंग जिसका फॉर्मेट "AllSupportedTypes" या "EAN8,EAN13,CodaBar" हो, जिसे परिवर्तित किया जा सके। |
| परिणाम | MultiDecodeType& | जब परिवर्तन सफलतापूर्वक पूरा हो जाता है तो एक वास्तविक MultiDecodeType लौटाया जाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: new MultiDecodeType(DecodeType.None) |

### वापसी मान

**true** if parsingType was converted successfully; otherwise, **false**.

### और देखें

* class [MultiDecodeType](../../multidecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


