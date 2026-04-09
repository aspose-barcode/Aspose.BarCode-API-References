---
title: ComplexCodetextReader
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: ComplexCodetextReader decodes codetext to specified complex barcode type.
type: docs
weight: 13
url: /hi/androidjava/com.aspose.barcode.complexbarcode/complexcodetextreader/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexCodetextReader
```

ComplexCodetextReader decodes codetext to specified complex barcode type.

--------------------

> ```
> This sample shows how to recognize and decode SwissQR image.
>   
>   BarCodeReader cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR);
>   cr.read();
>   SwissQRCodetext result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText());
> ```
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryDecodeHIBCLIC(String encodedCodetext)](#tryDecodeHIBCLIC-java.lang.String-) | HIBC LIC कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeHIBCPAS(String encodedCodetext)](#tryDecodeHIBCPAS-java.lang.String-) | HIBC PAS कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeMailmark(String encodedCodetext)](#tryDecodeMailmark-java.lang.String-) | Mailmark बारकोड C और L कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeMailmark2D(String encodedCodetext)](#tryDecodeMailmark2D-java.lang.String-) | Royal Mail Mailmark 2D कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext)](#tryDecodeMaxiCode-int-java.lang.String-) | MaxiCode कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeSwissQR(String encodedCodetext)](#tryDecodeSwissQR-java.lang.String-) | SwissQR कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeUSADriveId(String encodedCodetext)](#tryDecodeUSADriveId-java.lang.String-) | USADriveId कोडटेक्स्ट को डिकोड करता है। |
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
### tryDecodeHIBCLIC(String encodedCodetext) {#tryDecodeHIBCLIC-java.lang.String-}
```
public static HIBCLICComplexCodetext tryDecodeHIBCLIC(String encodedCodetext)
```


HIBC LIC कोडटेक्स्ट को डिकोड करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड कोडटेक्स्ट |

**Returns:**
[HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext) - decoded HIBC LIC Complex Codetext or null.
### tryDecodeHIBCPAS(String encodedCodetext) {#tryDecodeHIBCPAS-java.lang.String-}
```
public static HIBCPASCodetext tryDecodeHIBCPAS(String encodedCodetext)
```


HIBC PAS कोडटेक्स्ट को डिकोड करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड कोडटेक्स्ट |

**Returns:**
[HIBCPASCodetext](../../com.aspose.barcode.complexbarcode/hibcpascodetext) - decoded HIBC PAS Complex Codetext or null.
### tryDecodeMailmark(String encodedCodetext) {#tryDecodeMailmark-java.lang.String-}
```
public static MailmarkCodetext tryDecodeMailmark(String encodedCodetext)
```


Mailmark बारकोड C और L कोडटेक्स्ट को डिकोड करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड कोडटेक्स्ट |

**Returns:**
[MailmarkCodetext](../../com.aspose.barcode.complexbarcode/mailmarkcodetext) - Decoded Mailmark Barcode C and L or null.
### tryDecodeMailmark2D(String encodedCodetext) {#tryDecodeMailmark2D-java.lang.String-}
```
public static Mailmark2DCodetext tryDecodeMailmark2D(String encodedCodetext)
```


Royal Mail Mailmark 2D कोडटेक्स्ट को डिकोड करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड कोडटेक्स्ट |

**Returns:**
[Mailmark2DCodetext](../../com.aspose.barcode.complexbarcode/mailmark2dcodetext) - decoded Royal Mail Mailmark 2D or null.
### tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext) {#tryDecodeMaxiCode-int-java.lang.String-}
```
public static MaxiCodeCodetext tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext)
```


MaxiCode कोडटेक्स्ट को डिकोड करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| maxiCodeMode | int | MaxiCode मोड |
| encodedCodetext | java.lang.String | एन्कोडेड कोडटेक्स्ट |

**Returns:**
[MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext) - Decoded MaxiCode codetext.
### tryDecodeSwissQR(String encodedCodetext) {#tryDecodeSwissQR-java.lang.String-}
```
public static SwissQRCodetext tryDecodeSwissQR(String encodedCodetext)
```


SwissQR कोडटेक्स्ट को डिकोड करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड कोडटेक्स्ट |

**Returns:**
[SwissQRCodetext](../../com.aspose.barcode.complexbarcode/swissqrcodetext) - decoded SwissQRCodetext or null.
### tryDecodeUSADriveId(String encodedCodetext) {#tryDecodeUSADriveId-java.lang.String-}
```
public static USADriveIdCodetext tryDecodeUSADriveId(String encodedCodetext)
```


USADriveId कोडटेक्स्ट को डिकोड करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड कोडटेक्स्ट |

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext - डिकोडेड USADriveId या null.
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

