---
title: SwissQRCodetext
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα SwissQR.
type: docs
weight: 37
url: /el/androidjava/com.aspose.barcode.complexbarcode/swissqrcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class SwissQRCodetext implements IComplexCodetext
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα SwissQR.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [SwissQRCodetext(SwissQRBill bill)](#SwissQRCodetext-com.aspose.barcode.complexbarcode.SwissQRBill-) | Δημιουργεί μια παρουσία του SwissQRCodetext. |
| [SwissQRCodetext()](#SwissQRCodetext--) | Δημιουργεί μια παρουσία του SwissQRCodetext. |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Λαμβάνει τον τύπο barcode. |
| [getBill()](#getBill--) | Δεδομένα τιμολογίου SwissQR. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Δημιουργεί codetext από τα δεδομένα του λογαριασμού SwissQR |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Bill with constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SwissQRCodetext(SwissQRBill bill) {#SwissQRCodetext-com.aspose.barcode.complexbarcode.SwissQRBill-}
```
public SwissQRCodetext(SwissQRBill bill)
```


Δημιουργεί μια παρουσία του SwissQRCodetext.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| bill | [SwissQRBill](../../com.aspose.barcode.complexbarcode/swissqrbill) | Δεδομένα τιμολογίου SwissQR. |

### SwissQRCodetext() {#SwissQRCodetext--}
```
public SwissQRCodetext()
```


Δημιουργεί μια παρουσία του SwissQRCodetext.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Λαμβάνει τον τύπο barcode.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getBill() {#getBill--}
```
public SwissQRBill getBill()
```


Δεδομένα τιμολογίου SwissQR.

**Returns:**
[SwissQRBill](../../com.aspose.barcode.complexbarcode/swissqrbill)
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


Δημιουργεί codetext από τα δεδομένα του λογαριασμού SwissQR

**Returns:**
java.lang.String - Constructed codetext
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


Initializes Bill with constructed codetext.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Constructed codetext. |

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

