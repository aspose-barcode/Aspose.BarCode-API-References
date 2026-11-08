---
title: "BarcodeSettings"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "मुख्य BarCode डिकोडिंग पैरामीटर।"
type: docs
weight: 19
url: /hi/java/com.aspose.barcode.barcoderecognition/barcodesettings/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeSettings
```

मुख्य BarCode डिकोडिंग पैरामीटर। इसमें ऐसे पैरामीटर शामिल हैं जो पहचाने गए डेटा पर प्रभाव डालते हैं।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustraliaPost()](#getAustraliaPost--) | AustraliaPost डिकोडिंग पैरामीटर प्राप्त करता है |
| [getChecksumValidation()](#getChecksumValidation--) | 1D और पोस्टल बारकोड की पहचान के दौरान चेकसम सत्यापन सक्षम करें। |
| [getClass()](#getClass--) |  |
| [getDetectEncoding()](#getDetectEncoding--) | फ़्लैग जो इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करता है। |
| [getStripFNC()](#getStripFNC--) | कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। |
| [hashCode()](#hashCode--) |  |
| [isOnlyRequestedTypes()](#isOnlyRequestedTypes--) | केवल उन बारकोड प्रकारों को लौटाता है जो पहचान के लिए स्पष्ट रूप से निर्दिष्ट किए गए हैं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChecksumValidation(ChecksumValidation value)](#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-) | 1D और पोस्टल बारकोड की पहचान के दौरान चेकसम सत्यापन सक्षम करें। |
| [setDetectEncoding(boolean value)](#setDetectEncoding-boolean-) | फ़्लैग जो इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करता है। |
| [setOnlyRequestedTypes(boolean value)](#setOnlyRequestedTypes-boolean-) | केवल उन बारकोड प्रकारों को लौटाता है जो पहचान के लिए स्पष्ट रूप से निर्दिष्ट किए गए हैं। |
| [setStripFNC(boolean value)](#setStripFNC-boolean-) | कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustraliaPost() {#getAustraliaPost--}
```
public AustraliaPostSettings getAustraliaPost()
```


AustraliaPost डिकोडिंग पैरामीटर प्राप्त करता है

**Returns:**
[AustraliaPostSettings](../../com.aspose.barcode.barcoderecognition/australiapostsettings) - The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology
### getChecksumValidation() {#getChecksumValidation--}
```
public ChecksumValidation getChecksumValidation()
```


1D और पोस्टल बारकोड की पहचान के दौरान चेकसम वैधता सक्षम करें। डिफ़ॉल्ट रूप से उन सिम्बोलॉजीज़ के लिए हाँ माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ नहीं। चेकसम कभी उपयोग नहीं किया जाता: Codabar, PatchCode, Pharmacode, DataLogic2of5 चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN चेकसम हमेशा उपयोग किया जाता है: Rest symbologies उदाहरण BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Returns:**
[ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) - Enable checksum validation during recognition for 1D and Postal barcodes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDetectEncoding() {#getDetectEncoding--}
```
public boolean getDetectEncoding()
```


फ़्लैग जो इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करता है। डिफ़ॉल्ट मान true है।

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

मान: फ़्लैग जो इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करता है

**Returns:**
boolean
### getStripFNC() {#getStripFNC--}
```
public boolean getStripFNC()
```


कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। डिफ़ॉल्ट मान false है। उदाहरण BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। डिफ़ॉल्ट मान false है।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOnlyRequestedTypes() {#isOnlyRequestedTypes--}
```
public boolean isOnlyRequestedTypes()
```


केवल उन बारकोड प्रकारों को लौटाता है जो पहचान के लिए स्पष्ट रूप से निर्दिष्ट किए गए हैं। जब सक्षम किया जाता है, तो अन्य संगत या समकक्ष प्रकारों के पहचाने गए बारकोड फ़िल्टर हो जाते हैं। डिफ़ॉल्ट मान false है।

उदाहरण:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("c:\\test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Returns:**
boolean - true यदि केवल स्पष्ट रूप से अनुरोधित बारकोड प्रकार लौटाए जाते हैं; अन्यथा false
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChecksumValidation(ChecksumValidation value) {#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-}
```
public void setChecksumValidation(ChecksumValidation value)
```


1D और पोस्टल बारकोड की पहचान के दौरान चेकसम वैधता सक्षम करें। डिफ़ॉल्ट रूप से उन सिम्बोलॉजीज़ के लिए हाँ माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ नहीं। चेकसम कभी उपयोग नहीं किया जाता: Codabar, PatchCode, Pharmacode, DataLogic2of5 चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN चेकसम हमेशा उपयोग किया जाता है: Rest symbologies उदाहरण BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) | 1D और पोस्टल बारकोड की पहचान के दौरान चेकसम सत्यापन सक्षम करें। |

### setDetectEncoding(boolean value) {#setDetectEncoding-boolean-}
```
public void setDetectEncoding(boolean value)
```


फ़्लैग जो इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करता है। डिफ़ॉल्ट मान true है।

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

मान: फ़्लैग जो इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setOnlyRequestedTypes(boolean value) {#setOnlyRequestedTypes-boolean-}
```
public void setOnlyRequestedTypes(boolean value)
```


केवल उन बारकोड प्रकारों को लौटाता है जो पहचान के लिए स्पष्ट रूप से निर्दिष्ट किए गए हैं। जब सक्षम किया जाता है, तो अन्य संगत या समकक्ष प्रकारों के पहचाने गए बारकोड फ़िल्टर हो जाते हैं। डिफ़ॉल्ट मान false है।

उदाहरण:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("c:\\test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes())
 {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setStripFNC(boolean value) {#setStripFNC-boolean-}
```
public void setStripFNC(boolean value)
```


कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। डिफ़ॉल्ट मान false है। उदाहरण BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। डिफ़ॉल्ट मान false है। |

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
public final native void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

