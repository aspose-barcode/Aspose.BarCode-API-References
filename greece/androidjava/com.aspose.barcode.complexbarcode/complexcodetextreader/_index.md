---
title: ComplexCodetextReader
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: ComplexCodetextReader αποκωδικοποιεί το κείμενο κώδικα σε καθορισμένο τύπο σύνθετου barcode.
type: docs
weight: 13
url: /el/androidjava/com.aspose.barcode.complexbarcode/complexcodetextreader/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexCodetextReader
```

ComplexCodetextReader αποκωδικοποιεί το κείμενο κώδικα σε καθορισμένο τύπο σύνθετου barcode.

--------------------

> ```
> This sample shows how to recognize and decode SwissQR image.
>   
>   BarCodeReader cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR);
>   cr.read();
>   SwissQRCodetext result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText());
> ```
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryDecodeHIBCLIC(String encodedCodetext)](#tryDecodeHIBCLIC-java.lang.String-) | Αποκωδικοποιεί το κείμενο κώδικα HIBC LIC. |
| [tryDecodeHIBCPAS(String encodedCodetext)](#tryDecodeHIBCPAS-java.lang.String-) | Αποκωδικοποιεί το κείμενο κώδικα HIBC PAS. |
| [tryDecodeMailmark(String encodedCodetext)](#tryDecodeMailmark-java.lang.String-) | Αποκωδικοποιεί το κείμενο κώδικα Mailmark Barcode C και L. |
| [tryDecodeMailmark2D(String encodedCodetext)](#tryDecodeMailmark2D-java.lang.String-) | Αποκωδικοποιεί το κείμενο κώδικα Royal Mail Mailmark 2D. |
| [tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext)](#tryDecodeMaxiCode-int-java.lang.String-) | Αποκωδικοποιεί το κείμενο κώδικα MaxiCode. |
| [tryDecodeSwissQR(String encodedCodetext)](#tryDecodeSwissQR-java.lang.String-) | Αποκωδικοποιεί το κείμενο κώδικα SwissQR. |
| [tryDecodeUSADriveId(String encodedCodetext)](#tryDecodeUSADriveId-java.lang.String-) | Αποκωδικοποιεί το κείμενο κώδικα USADriveId. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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


Αποκωδικοποιεί το κείμενο κώδικα HIBC LIC.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| encodedCodetext | java.lang.String | κωδικοποιημένο κείμενο κώδικα |

**Returns:**
[HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext) - decoded HIBC LIC Complex Codetext or null.
### tryDecodeHIBCPAS(String encodedCodetext) {#tryDecodeHIBCPAS-java.lang.String-}
```
public static HIBCPASCodetext tryDecodeHIBCPAS(String encodedCodetext)
```


Αποκωδικοποιεί το κείμενο κώδικα HIBC PAS.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| encodedCodetext | java.lang.String | κωδικοποιημένο κείμενο κώδικα |

**Returns:**
[HIBCPASCodetext](../../com.aspose.barcode.complexbarcode/hibcpascodetext) - decoded HIBC PAS Complex Codetext or null.
### tryDecodeMailmark(String encodedCodetext) {#tryDecodeMailmark-java.lang.String-}
```
public static MailmarkCodetext tryDecodeMailmark(String encodedCodetext)
```


Αποκωδικοποιεί το κείμενο κώδικα Mailmark Barcode C και L.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| encodedCodetext | java.lang.String | κωδικοποιημένο κείμενο κώδικα |

**Returns:**
[MailmarkCodetext](../../com.aspose.barcode.complexbarcode/mailmarkcodetext) - Decoded Mailmark Barcode C and L or null.
### tryDecodeMailmark2D(String encodedCodetext) {#tryDecodeMailmark2D-java.lang.String-}
```
public static Mailmark2DCodetext tryDecodeMailmark2D(String encodedCodetext)
```


Αποκωδικοποιεί το κείμενο κώδικα Royal Mail Mailmark 2D.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| encodedCodetext | java.lang.String | κωδικοποιημένο κείμενο κώδικα |

**Returns:**
[Mailmark2DCodetext](../../com.aspose.barcode.complexbarcode/mailmark2dcodetext) - decoded Royal Mail Mailmark 2D or null.
### tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext) {#tryDecodeMaxiCode-int-java.lang.String-}
```
public static MaxiCodeCodetext tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext)
```


Αποκωδικοποιεί το κείμενο κώδικα MaxiCode.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| maxiCodeMode | int | Λειτουργία MaxiCode |
| encodedCodetext | java.lang.String | κωδικοποιημένο κείμενο κώδικα |

**Returns:**
[MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext) - Decoded MaxiCode codetext.
### tryDecodeSwissQR(String encodedCodetext) {#tryDecodeSwissQR-java.lang.String-}
```
public static SwissQRCodetext tryDecodeSwissQR(String encodedCodetext)
```


Αποκωδικοποιεί το κείμενο κώδικα SwissQR.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| encodedCodetext | java.lang.String | κωδικοποιημένο κείμενο κώδικα |

**Returns:**
[SwissQRCodetext](../../com.aspose.barcode.complexbarcode/swissqrcodetext) - decoded SwissQRCodetext or null.
### tryDecodeUSADriveId(String encodedCodetext) {#tryDecodeUSADriveId-java.lang.String-}
```
public static USADriveIdCodetext tryDecodeUSADriveId(String encodedCodetext)
```


Αποκωδικοποιεί το κείμενο κώδικα USADriveId.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| encodedCodetext | java.lang.String | Encoded codetext |

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext - Decoded USADriveId or null.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

