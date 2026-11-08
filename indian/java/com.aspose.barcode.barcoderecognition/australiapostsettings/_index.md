---
title: "AustraliaPostSettings"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "AustraliaPost डिकोडिंग पैरामीटर।"
type: docs
weight: 10
url: /hi/java/com.aspose.barcode.barcoderecognition/australiapostsettings/
---
**Inheritance:**
java.lang.Object
```
public class AustraliaPostSettings
```

AustraliaPost डिकोडिंग पैरामीटर। इसमें ऐसे पैरामीटर शामिल हैं जो AustraliaPost प्रतीक विज्ञान के पहचाने गए डेटा पर प्रभाव डालते हैं।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomerInformationDecoder()](#getCustomerInformationDecoder--) | AustraliaPost प्रतीक विज्ञान में उपयोग किए जाने वाले Customer Information Field डिकोडिंग के लिए सार्वजनिक इंटरफ़ेस। |
| [getCustomerInformationInterpretingType()](#getCustomerInformationInterpretingType--) | AustralianPost बारकोड के ग्राहक जानकारी के लिए व्याख्या प्रकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट है CustomerInformationInterpretingType.OTHER। |
| [getIgnoreEndingFillingPatternsForCTable()](#getIgnoreEndingFillingPatternsForCTable--) | CTable विधि के साथ डिकोडिंग के दौरान ग्राहक जानकारी फ़ील्ड में अंतिम भरने पैटर्न को अनदेखा करने के लिए AustraliaPost डिकोडर को बाध्य करने वाला फ़्लैग। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)](#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-) | AustraliaPost प्रतीक विज्ञान में उपयोग किए जाने वाले Customer Information Field डिकोडिंग के लिए सार्वजनिक इंटरफ़ेस। |
| [setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)](#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-) | AustralianPost बारकोड के ग्राहक जानकारी के लिए व्याख्या प्रकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट है CustomerInformationInterpretingType.OTHER। |
| [setIgnoreEndingFillingPatternsForCTable(boolean value)](#setIgnoreEndingFillingPatternsForCTable-boolean-) | CTable विधि के साथ डिकोडिंग के दौरान ग्राहक जानकारी फ़ील्ड में अंतिम भरने पैटर्न को अनदेखा करने के लिए AustraliaPost डिकोडर को बाध्य करने वाला फ़्लैग। |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomerInformationDecoder() {#getCustomerInformationDecoder--}
```
public AustraliaPostCustomerInformationDecoder getCustomerInformationDecoder()
```


AustraliaPost प्रतीक विज्ञान में उपयोग किए जाने वाले Customer Information Field डिकोडिंग के लिए सार्वजनिक इंटरफ़ेस।

**Returns:**
[AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) - Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.
### getCustomerInformationInterpretingType() {#getCustomerInformationInterpretingType--}
```
public CustomerInformationInterpretingType getCustomerInformationInterpretingType()
```


AustralianPost बारकोड के ग्राहक जानकारी के लिए व्याख्या प्रकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट है CustomerInformationInterpretingType.OTHER।

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) - The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode
### getIgnoreEndingFillingPatternsForCTable() {#getIgnoreEndingFillingPatternsForCTable--}
```
public boolean getIgnoreEndingFillingPatternsForCTable()
```


CTable विधि के साथ डिकोडिंग के दौरान ग्राहक जानकारी फ़ील्ड में अंतिम भरने पैटर्न को अनदेखा करने के लिए AustraliaPost डिकोडर को बाध्य करने वाला फ़्लैग। CTable एन्कोडिंग विधि में एन्कोडिंग तालिका में कोई अंतर नहीं होता और "333" क्रम के भरने पैटर्न को अक्षर "z" के रूप में डिकोड किया जाता है। उदाहरण BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); BufferedImage image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - CTable विधि डिकोडिंग के दौरान अंतिम भरने पैटर्न को अनदेखा करने के लिए AustraliaPost डिकोडर को बाध्य करने वाला फ़्लैग
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




### setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value) {#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-}
```
public void setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)
```


AustraliaPost प्रतीक विज्ञान में उपयोग किए जाने वाले Customer Information Field डिकोडिंग के लिए सार्वजनिक इंटरफ़ेस।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) |  |

### setCustomerInformationInterpretingType(CustomerInformationInterpretingType value) {#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-}
```
public void setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)
```


AustralianPost बारकोड के ग्राहक जानकारी के लिए व्याख्या प्रकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट है CustomerInformationInterpretingType.OTHER।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | AustralianPost बारकोड के ग्राहक जानकारी का व्याख्या प्रकार (CTable, NTable या Other) |

### setIgnoreEndingFillingPatternsForCTable(boolean value) {#setIgnoreEndingFillingPatternsForCTable-boolean-}
```
public void setIgnoreEndingFillingPatternsForCTable(boolean value)
```


CTable विधि के साथ डिकोडिंग के दौरान ग्राहक जानकारी फ़ील्ड में अंतिम भरने पैटर्न को अनदेखा करने के लिए AustraliaPost डिकोडर को बाध्य करने वाला फ़्लैग। CTable एन्कोडिंग विधि में एन्कोडिंग तालिका में कोई अंतर नहीं होता और "333" क्रम के भरने पैटर्न को अक्षर "z" के रूप में डिकोड किया जाता है। उदाहरण BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); BufferedImage image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

