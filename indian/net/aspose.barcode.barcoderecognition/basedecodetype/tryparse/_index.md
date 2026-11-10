---
title: "BaseDecodeType.TryParse"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BaseDecodeType विधि। SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि परिवर्तन सफल हुआ या विफल"
type: docs
weight: 40
url: /hi/net/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_2}

SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल।

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | स्ट्रिंग | एक स्ट्रिंग जिसमें "EAN8" या "EAN13" या "CodaBar"... के रूप में SingleDecodeType हो, जिसे परिवर्तित किया जाना है। |
| परिणाम | SingleDecodeType& | जब परिवर्तन सफलतापूर्वक पूरा हो जाता है तो एक वास्तविक SingleDecodeType लौटाया जाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: DecodeType.None. |

### वापसी मान

**true** if parsingType was converted successfully; otherwise, **false**.

### और देखें

* class [SingleDecodeType](../../singledecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse_1}

MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल।

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | स्ट्रिंग | एक स्ट्रिंग जिसमें MultiDecodeType प्रतिनिधित्व हो, जिसे परिवर्तित किया जाना है। |
| परिणाम | MultiDecodeType& | जब परिवर्तन सफलतापूर्वक पूरा हो जाता है तो एक वास्तविक MultiDecodeType लौटाया जाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: new MultiDecodeType(DecodeType.None) |

### वापसी मान

**true** if parsingType was converted successfully; otherwise, **false**.

### और देखें

* class [MultiDecodeType](../../multidecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out BaseDecodeType) {#tryparse}

BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल।

```csharp
public static bool TryParse(string parsingType, out BaseDecodeType result)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | स्ट्रिंग | एक स्ट्रिंग जिसमें MultiDecodeType प्रतिनिधित्व हो, जिसे परिवर्तित किया जाना है। |
| परिणाम | BaseDecodeType& | जब परिवर्तन सफलतापूर्वक पूरा हो जाता है तो एक वास्तविक MultiDecodeType लौटाया जाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: DecodeType.None. |

### वापसी मान

**true** if parsingType was converted successfully; otherwise, **false**.

### और देखें

* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


