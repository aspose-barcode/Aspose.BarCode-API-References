---
title: ComplexBarcodeGenerator
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: बैकएंड जटिल बारकोड के लिए ComplexBarcodeGenerator, उदाहरण के लिए।
type: docs
weight: 12
url: /hi/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

बैकएंड जटिल बारकोड (जैसे SwissQR) छवियों के निर्माण के लिए ComplexBarcodeGenerator।

--------------------

> ```
> This sample shows how to create and save a SwissQR image.
>   
>     SwissQRCodetext swissQRCodetext = new SwissQRCodetext();
>     swissQRCodetext.getBill().setAccount("Account");
>     swissQRCodetext.getBill().setBillInformation("BillInformation");
>     // init rest of the fields
>     ComplexBarcodeGenerator cg = new ComplexBarcodeGenerator(swissQRCodetext);
>     BufferedImage res = cg.generateBarCodeImage();
> ```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | ComplexBarcodeGenerator का एक उदाहरण बनाता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [dispose()](#dispose--) | उपयोग में मौजूद किसी भी संसाधन को साफ़ करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है। |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | उत्पादन पैरामीटर। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है। |
| [save(String filename)](#save-java.lang.String-) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है। |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


ComplexBarcodeGenerator का एक उदाहरण बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | जटिल कोडटेक्स्ट |

### dispose() {#dispose--}
```
public void dispose()
```


उपयोग में मौजूद किसी भी संसाधन को साफ़ करें।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है।

**Returns:**
android.graphics.Bitmap - बारकोड छवि। देखें Bitmap।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


उत्पादन पैरामीटर।

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | आउटपुट System.IO.Stream। |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | आउटपुट छवि के फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | सहेजने का पथ। |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | सहेजने का पथ। |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | आउटपुट छवि के फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

