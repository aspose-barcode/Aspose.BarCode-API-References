---
title: "IComplexCodetext"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "ComplexBarcodeGenerator के साथ उपयोग किए जाने वाले जटिल कोडटेक्स्ट के लिए इंटरफ़ेस।"
type: docs
weight: 39
url: /hi/java/com.aspose.barcode.complexbarcode/icomplexcodetext/
---```
public interface IComplexCodetext
```

Interface for complex codetext used with ComplexBarcodeGenerator.
## Methods

| Method | Description |
| --- | --- |
| [getBarcodeType()](#getBarcodeType--) | Gets barcode type. |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext for complex barcode |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes instance with constructed codetext. |
### getBarcodeType() {#getBarcodeType--}
```
public abstract BaseEncodeType getBarcodeType()
```


Gets barcode type.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getConstructedCodetext() {#getConstructedCodetext--}
```
public abstract String getConstructedCodetext()
```


Construct codetext for complex barcode

**Returns:**
java.lang.String - Constructed codetext
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public abstract void initFromString(String constructedCodetext)
```


Initializes instance with constructed codetext.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Constructed codetext. |

