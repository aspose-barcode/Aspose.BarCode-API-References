---
title: SwissQRCodetext
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Klasse zum Codieren und Dekodieren des im SwissQR‑Code eingebetteten Textes.
type: docs
weight: 37
url: /de/androidjava/com.aspose.barcode.complexbarcode/swissqrcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class SwissQRCodetext implements IComplexCodetext
```

Klasse zum Codieren und Dekodieren des im SwissQR‑Code eingebetteten Textes.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [SwissQRCodetext(SwissQRBill bill)](#SwissQRCodetext-com.aspose.barcode.complexbarcode.SwissQRBill-) | Erstellt eine Instanz von SwissQRCodetext. |
| [SwissQRCodetext()](#SwissQRCodetext--) | Erstellt eine Instanz von SwissQRCodetext. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Liefert den Barcode-Typ. |
| [getBill()](#getBill--) | SwissQR‑Rechnungsdaten |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Erstellt Codetext aus SwissQR-Rechnungsdaten. |
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


Erstellt eine Instanz von SwissQRCodetext.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| bill | [SwissQRBill](../../com.aspose.barcode.complexbarcode/swissqrbill) | SwissQR‑Rechnungsdaten |

### SwissQRCodetext() {#SwissQRCodetext--}
```
public SwissQRCodetext()
```


Erstellt eine Instanz von SwissQRCodetext.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Liefert den Barcode-Typ.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getBill() {#getBill--}
```
public SwissQRBill getBill()
```


SwissQR‑Rechnungsdaten

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


Erstellt Codetext aus SwissQR-Rechnungsdaten.

**Returns:**
java.lang.String – konstruierter Codetext
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruiertes Codetext. |

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

