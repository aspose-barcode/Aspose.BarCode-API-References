---
title: AustraliaPostSettings
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: AustraliaPost डिकोडिंग पैरामीटर।
type: docs
weight: 10
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/australiapostsettings/
---
**Inheritance:**
java.lang.Object
```
public class AustraliaPostSettings
```

AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbology.
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomerInformationDecoder()](#getCustomerInformationDecoder--) | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. |
| [getCustomerInformationInterpretingType()](#getCustomerInformationInterpretingType--) | Gets or sets the Interpreting Type for the Customer Information of AustralianPost BarCode.DEFAULT is CustomerInformationInterpretingType.OTHER. |
| [getIgnoreEndingFillingPatternsForCTable()](#getIgnoreEndingFillingPatternsForCTable--) | The flag which force AustraliaPost decoder to ignore last filling patterns in Customer Information Field during decoding as CTable method. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)](#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-) | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. |
| [setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)](#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-) | Gets or sets the Interpreting Type for the Customer Information of AustralianPost BarCode.DEFAULT is CustomerInformationInterpretingType.OTHER. |
| [setIgnoreEndingFillingPatternsForCTable(boolean value)](#setIgnoreEndingFillingPatternsForCTable-boolean-) | The flag which force AustraliaPost decoder to ignore last filling patterns in Customer Information Field during decoding as CTable method. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.

**Returns:**
[AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) - Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.
### getCustomerInformationInterpretingType() {#getCustomerInformationInterpretingType--}
```
public CustomerInformationInterpretingType getCustomerInformationInterpretingType()
```


Gets or sets the Interpreting Type for the Customer Information of AustralianPost BarCode.DEFAULT is CustomerInformationInterpretingType.OTHER.

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) - The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode
### getIgnoreEndingFillingPatternsForCTable() {#getIgnoreEndingFillingPatternsForCTable--}
```
public boolean getIgnoreEndingFillingPatternsForCTable()
```


फ़्लैग जो AustraliaPost डिकोडर को CTable विधि के दौरान डिकोडिंग के समय Customer Information Field में अंतिम भरने पैटर्न को अनदेखा करने के लिए मजबूर करता है। CTable एन्कोडिंग विधि में एन्कोडिंग टेबल में कोई अंतर नहीं है और "333" क्रम के भरने पैटर्न को अक्षर "z" के रूप में डिकोड किया जाता है। Example BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - फ़्लैग जो AustraliaPost डिकोडर को CTable विधि डिकोडिंग के दौरान अंतिम भरने पैटर्न को अनदेखा करने के लिए मजबूर करता है
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


Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) |  |

### setCustomerInformationInterpretingType(CustomerInformationInterpretingType value) {#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-}
```
public void setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)
```


Gets or sets the Interpreting Type for the Customer Information of AustralianPost BarCode.DEFAULT is CustomerInformationInterpretingType.OTHER.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | ग्राहक जानकारी के लिए AustralianPost बारकोड का व्याख्या प्रकार (CTable, NTable या Other) |

### setIgnoreEndingFillingPatternsForCTable(boolean value) {#setIgnoreEndingFillingPatternsForCTable-boolean-}
```
public void setIgnoreEndingFillingPatternsForCTable(boolean value)
```


फ़्लैग जो AustraliaPost डिकोडर को CTable विधि के दौरान डिकोडिंग के समय Customer Information Field में अंतिम भरने पैटर्न को अनदेखा करने के लिए मजबूर करता है। CTable एन्कोडिंग विधि में एन्कोडिंग टेबल में कोई अंतर नहीं है और "333" क्रम के भरने पैटर्न को अक्षर "z" के रूप में डिकोड किया जाता है। Example BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| Parameter | Type | विवरण |
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

