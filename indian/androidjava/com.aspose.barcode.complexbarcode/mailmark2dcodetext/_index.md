---
title: Mailmark2DCodetext
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Royal Mail 2D Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।
type: docs
weight: 23
url: /hi/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Royal Mail 2D Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Mailmark2DCodetext क्लास का डिफ़ॉल्ट इंस्टेंस बनाएं। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | बारकोड प्रकार प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| [getCustomerContent()](#getCustomerContent--) | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Datamatrix बारकोड का एन्कोड मोड। |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark प्रकार Data Matrix बारकोड का आकार निर्धारित करता है। |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | डिलीवरी एड्रेस के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। |
| [getInformationTypeID()](#getInformationTypeID--) | प्रत्येक प्रोडक्ट प्रकार के लिए रॉयल मेल Mailmark बारकोड पेलोड की पहचान करता है। |
| [getItemID()](#getItemID--) | सप्लाई चेन ID के भीतर अद्वितीय आइटम की पहचान करता है। |
| [getRTSFlag()](#getRTSFlag--) | फ़्लैग जो यह दर्शाता है कि किस स्तर की रिटर्न टू सेंडर सेवा का अनुरोध किया गया है। |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | रिटर्न टू सेंडर पोस्ट कोड शामिल है लेकिन DPS नहीं। |
| [getSupplyChainID()](#getSupplyChainID--) | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। |
| [getUPUCountryID()](#getUPUCountryID--) | UPU कंट्री आईडी की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| [getVersionID()](#getVersionID--) | प्रत्येक इन्फॉर्मेशन टाइप आईडी के अनुसार बारकोड संस्करण की पहचान करता है। |
| [getclass()](#getclass--) | आइटम की क्लास की पहचान करता है। |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | निर्मित कोडटेक्स्ट से Mailmark डेटा इनिशियलाइज़ करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix बारकोड का एन्कोड मोड। |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark प्रकार Data Matrix बारकोड का आकार निर्धारित करता है। |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | डिलीवरी एड्रेस के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | प्रत्येक प्रोडक्ट प्रकार के लिए रॉयल मेल Mailmark बारकोड पेलोड की पहचान करता है। |
| [setItemID(int value)](#setItemID-int-) | सप्लाई चेन ID के भीतर अद्वितीय आइटम की पहचान करता है। |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | फ़्लैग जो यह दर्शाता है कि किस स्तर की रिटर्न टू सेंडर सेवा का अनुरोध किया गया है। |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | रिटर्न टू सेंडर पोस्ट कोड शामिल है लेकिन DPS नहीं। |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | UPU कंट्री आईडी की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | प्रत्येक इन्फॉर्मेशन टाइप आईडी के अनुसार बारकोड संस्करण की पहचान करता है। |
| [setclass(String value)](#setclass-java.lang.String-) | आइटम की क्लास की पहचान करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Mailmark2DCodetext क्लास का डिफ़ॉल्ट इंस्टेंस बनाएं।

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


बारकोड प्रकार प्राप्त करता है।

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Mailmark डेटा से कोडटेक्स्ट बनाएं।

**Returns:**
java.lang.String - निर्मित कोडटेक्स्ट
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। प्रकार के अनुसार अधिकतम लंबाई: टाइप 7: 6 अक्षर, टाइप 9: 45 अक्षर, टाइप 29: 25 अक्षर।

**Returns:**
java.lang.String - ग्राहक सामग्री
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


डेटामैट्रिक्स बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.C40।

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark प्रकार Data Matrix बारकोड का आकार निर्धारित करता है।

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


डिलीवरी एड्रेस के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं: एरिया (1 या 2 अक्षर) जिला (1 या 2 अक्षर) सेक्टर (1 अक्षर) यूनिट (2 अक्षर) DPS (2 अक्षर)। पोस्टकोड और DPS को वैध PAF® फ़ॉर्मेट के अनुरूप होना चाहिए।

**Returns:**
java.lang.String - डिलीवरी एड्रेस का पोस्टकोड DPS के साथ
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


प्रत्येक प्रोडक्ट टाइप के लिए रॉयल मेल मेलमार्क बारकोड पेलोड की पहचान करता है। वैध मान: '0' - घरेलू सॉर्टेड और अनसॉर्टेड, 'A' - ऑनलाइन पोस्टेज, 'B' - फ्रैंकिन्ग, 'C' - कंसॉलिडेशन।

**Returns:**
java.lang.String - इन्फॉर्मेशन टाइप आईडी
### getItemID() {#getItemID--}
```
public int getItemID()
```


सप्लाई चेन आईडी के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक मेलमार्क बारकोड को एक आईडी ले जाना आवश्यक है ताकि इसे कम से कम 90 दिनों तक अद्वितीय रूप से पहचाना जा सके। अधिकतम मान: 99999999।

**Returns:**
int - सप्लाई चेन आईडी के भीतर आइटम
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


फ़्लैग जो यह दर्शाता है कि किस स्तर की रिटर्न टू सेंडर सेवा का अनुरोध किया गया है।

**Returns:**
java.lang.String - RTS फ़्लैग
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


रिटर्न टू सेंडर पोस्ट कोड शामिल है लेकिन DPS नहीं। PC (बिना DPS) को PAF® फ़ॉर्मेट के अनुरूप होना चाहिए।

**Returns:**
java.lang.String - रिटर्न टू सेंडर पोस्ट कोड लेकिन DPS नहीं
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999।

**Returns:**
int - सप्लाई चेन आईडी
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


UPU कंट्री आईडी की पहचान करता है। अधिकतम लंबाई: 4 अक्षर।

**Returns:**
java.lang.String - कंट्री आईडी
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


प्रत्येक इन्फॉर्मेशन टाइप आईडी के अनुसार बारकोड संस्करण की पहचान करता है। वैध मान: वर्तमान में '1'। '0' और '2' से '9' तथा 'A' से 'Z' संभावित भविष्य उपयोग के लिए आरक्षित हैं।

**Returns:**
java.lang.String - वर्ज़न आईडी
### getclass() {#getclass--}
```
public String getclass()
```


आइटम की क्लास की पहचान करता है। वैध मान: '1' - 1C (रिटेल), '2' - 2C (रिटेल), '3' - इकोनॉमी (रिटेल), '5' - डिफर्ड (रिटेल), '8' - प्रीमियम (नेटवर्क एक्सेस), '9' - स्टैंडर्ड (नेटवर्क एक्सेस)।

**Returns:**
java.lang.String - आइटम की क्लास
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


निर्मित कोडटेक्स्ट से Mailmark डेटा इनिशियलाइज़ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| constructedCodetext | java.lang.String | निर्मित कोडटेक्स्ट। |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। प्रकार के अनुसार अधिकतम लंबाई: टाइप 7: 6 अक्षर, टाइप 9: 45 अक्षर, टाइप 29: 25 अक्षर।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | ग्राहक सामग्री |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.C40.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Datamatrix बारकोड का एन्कोड मोड। |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark प्रकार Data Matrix बारकोड का आकार निर्धारित करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Data Matrix बारकोड का आकार |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


डिलीवरी एड्रेस के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं: एरिया (1 या 2 अक्षर) जिला (1 या 2 अक्षर) सेक्टर (1 अक्षर) यूनिट (2 अक्षर) DPS (2 अक्षर)। पोस्टकोड और DPS को वैध PAF® फ़ॉर्मेट के अनुरूप होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | डिलीवरी पते का पोस्टकोड (DPS के साथ) |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


प्रत्येक प्रोडक्ट टाइप के लिए रॉयल मेल मेलमार्क बारकोड पेलोड की पहचान करता है। वैध मान: '0' - घरेलू सॉर्टेड और अनसॉर्टेड, 'A' - ऑनलाइन पोस्टेज, 'B' - फ्रैंकिन्ग, 'C' - कंसॉलिडेशन।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | सूचना प्रकार आईडी |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


सप्लाई चेन आईडी के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक मेलमार्क बारकोड को एक आईडी ले जाना आवश्यक है ताकि इसे कम से कम 90 दिनों तक अद्वितीय रूप से पहचाना जा सके। अधिकतम मान: 99999999।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | सप्लाई चेन आईडी के भीतर आइटम |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


फ़्लैग जो यह दर्शाता है कि किस स्तर की रिटर्न टू सेंडर सेवा का अनुरोध किया गया है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


रिटर्न टू सेंडर पोस्ट कोड शामिल है लेकिन DPS नहीं। PC (बिना DPS) को PAF® फ़ॉर्मेट के अनुरूप होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | प्रेषक को लौटाने का पोस्ट कोड (परंतु DPS नहीं) |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | सप्लाई चेन आईडी |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


UPU कंट्री आईडी की पहचान करता है। अधिकतम लंबाई: 4 अक्षर।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | देश आईडी |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


प्रत्येक इन्फॉर्मेशन टाइप आईडी के अनुसार बारकोड संस्करण की पहचान करता है। वैध मान: वर्तमान में '1'। '0' और '2' से '9' तथा 'A' से 'Z' संभावित भविष्य उपयोग के लिए आरक्षित हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | संस्करण आईडी |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


आइटम की क्लास की पहचान करता है। वैध मान: '1' - 1C (रिटेल), '2' - 2C (रिटेल), '3' - इकोनॉमी (रिटेल), '5' - डिफर्ड (रिटेल), '8' - प्रीमियम (नेटवर्क एक्सेस), '9' - स्टैंडर्ड (नेटवर्क एक्सेस)।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | आइटम की क्लास |

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

