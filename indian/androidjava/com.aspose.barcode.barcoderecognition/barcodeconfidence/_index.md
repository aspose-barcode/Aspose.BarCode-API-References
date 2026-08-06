---
title: BarCodeConfidence
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: पहचान विश्वास स्तर शामिल करता है
type: docs
weight: 13
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeConfidence
```

पहचान विश्वास स्तर शामिल करता है

--------------------

> ```
> This sample shows how BarCodeConfidence changed, depending on barcode type
>  
>  //Moderate confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
>  //Strong confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.QR);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
> ```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [MODERATE](#MODERATE) | बारकोड (मुख्यतः 1D बारकोड) की पहचान विश्वसनीयता कमजोर चेकसम के साथ या बिना भी। |
| [NONE](#NONE) | बारकोड की पहचान विश्वसनीयता जहाँ कोडटेक्स्ट सही ढंग से पहचाना नहीं गया या बारकोड को संभावित fakeBarCodeExtendedParameters के रूप में पता लगाया गया। |
| [STRONG](#STRONG) | Reed\u2013Solomon जैसे BCH कोडों के साथ पुष्टि की गई पहचान विश्वसनीयता। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MODERATE {#MODERATE}
```
public static final int MODERATE
```


बारकोड (मुख्यतः 1D बारकोड) की पहचान विश्वसनीयता कमजोर चेकसम के साथ या बिना भी। यदि यह कम हो तो कोडटेक्स्ट में कुछ गलत पहचान या नकली पहचान हो सकती है।

### NONE {#NONE}
```
public static final int NONE
```


बारकोड की पहचान विश्वसनीयता जहाँ कोडटेक्स्ट सही ढंग से पहचाना नहीं गया या बारकोड को संभावित fakeBarCodeExtendedParameters के रूप में पता लगाया गया।

### STRONG {#STRONG}
```
public static final int STRONG
```


Reed\u2013Solomon जैसे BCH कोडों के साथ पुष्टि की गई पहचान विश्वसनीयता। पढ़े गए कोडटेक्स्ट में त्रुटियाँ या नकली पहचान नहीं होनी चाहिए।

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

