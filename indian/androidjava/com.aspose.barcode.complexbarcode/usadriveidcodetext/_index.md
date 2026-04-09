---
title: USADriveIdCodetext
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: USA ड्राइविंग लाइसेंस PDF417 कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।
type: docs
weight: 38
url: /hi/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

USA ड्राइविंग लाइसेंस PDF417 कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | डिफ़ॉल्ट कन्स्ट्रक्टर |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | AAMVA संस्करण संख्या 00-99 |
| [getBarcodeType()](#getBarcodeType--) | USA DL (Pdf417) का बारकोड प्रकार लौटाता है। |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | USA DL डेटा से कोडटेक्स्ट बनाएं। |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | यह संख्या जारी करने वाले अधिकार को विशिष्ट रूप से पहचानती है और इसे ISO जारीकर्ता प्राधिकरण (AAMVA) से संपर्क करके प्राप्त किया जा सकता है। |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | अधिकार-विशिष्ट फ़ील्ड्स |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | अधिकार संस्करण संख्या 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | कार्ड के अनिवार्य तत्व (फ़ील्ड)। |
| [getNumberOfEntries()](#getNumberOfEntries--) | सबफ़ाइलों की संख्या 00-99 |
| [getOptionalElements()](#getOptionalElements--) | कार्ड के वैकल्पिक तत्व (फ़ील्ड) |
| [getSubfileDesignator()](#getSubfileDesignator--) | निम्नलिखित सबफ़ाइलों, प्रकारों, ऑफ़सेट और लंबाइयों के बारे में जानकारी शामिल है। |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | कोडटेक्स्ट से USA DL ऑब्जेक्ट को प्रारंभ करें। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | XML में सहेजता है। |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | AAMVA संस्करण संख्या 00-99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | यह संख्या जारी करने वाले अधिकार को विशिष्ट रूप से पहचानती है और इसे ISO जारीकर्ता प्राधिकरण (AAMVA) से संपर्क करके प्राप्त किया जा सकता है। |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | अधिकार-विशिष्ट फ़ील्ड्स |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | अधिकार संस्करण संख्या 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | कार्ड के अनिवार्य तत्व (फ़ील्ड)। |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | सबफ़ाइलों की संख्या 00-99 |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | कार्ड के वैकल्पिक तत्व (फ़ील्ड) |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | निम्नलिखित सबफ़ाइलों, प्रकारों, ऑफ़सेट और लंबाइयों के बारे में जानकारी शामिल है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


डिफ़ॉल्ट कन्स्ट्रक्टर

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
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


AAMVA संस्करण संख्या 00-99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


USA DL (Pdf417) का बारकोड प्रकार लौटाता है।

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


USA DL डेटा से कोडटेक्स्ट बनाएं।

**Returns:**
java.lang.String - निर्मित कोडटेक्स्ट
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


यह संख्या जारी करने वाले अधिकार को विशिष्ट रूप से पहचानती है और इसे ISO जारीकर्ता प्राधिकरण (AAMVA) से संपर्क करके प्राप्त किया जा सकता है। पूर्ण 6-अंकीय IIN को एन्कोड किया जाना चाहिए।

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


अधिकार-विशिष्ट फ़ील्ड्स

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


अधिकार संस्करण संख्या 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


कार्ड के अनिवार्य तत्व (फ़ील्ड)।

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


सबफ़ाइलों की संख्या 00-99

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


कार्ड के वैकल्पिक तत्व (फ़ील्ड)

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


निम्नलिखित सबफ़ाइलों, प्रकारों, ऑफ़सेट और लंबाइयों के बारे में जानकारी शामिल है। महत्वपूर्ण: केवल प्रकार सेट करें, ऑफ़सेट और लंबाई स्वचालित रूप से सेट हो जाएगी।

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


कोडटेक्स्ट से USA DL ऑब्जेक्ट को प्रारंभ करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| constructedCodetext | java.lang.String | निर्मित कोडटेक्स्ट |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


XML में सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | सहेजने के लिए स्ट्रीम |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


AAMVA संस्करण संख्या 00-99

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


यह संख्या जारी करने वाले अधिकार को विशिष्ट रूप से पहचानती है और इसे ISO जारीकर्ता प्राधिकरण (AAMVA) से संपर्क करके प्राप्त किया जा सकता है। पूर्ण 6-अंकीय IIN को एन्कोड किया जाना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


अधिकार-विशिष्ट फ़ील्ड्स

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


अधिकार संस्करण संख्या 00-99

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


कार्ड के अनिवार्य तत्व (फ़ील्ड)।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


सबफ़ाइलों की संख्या 00-99

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


कार्ड के वैकल्पिक तत्व (फ़ील्ड)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


निम्नलिखित सबफ़ाइलों, प्रकारों, ऑफ़सेट और लंबाइयों के बारे में जानकारी शामिल है। महत्वपूर्ण: केवल प्रकार सेट करें, ऑफ़सेट और लंबाई स्वचालित रूप से सेट हो जाएगी।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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

