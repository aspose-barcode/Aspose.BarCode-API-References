---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die is ingebed in de 4-state Royal Mailmark-code."
type: docs
weight: 24
url: /nl/java/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

Klasse voor het coderen en decoderen van de tekst die is ingebed in de 4-state Royal Mailmark-code.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Initialiseert een nieuw exemplaar van de  MailmarkCodetext  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Haalt het barcode‑type op. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Null of Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (voor mogelijk toekomstig gebruik) "5" - Deferred (Retail) "6" - Air (Retail) (voor mogelijk toekomstig gebruik) "7" - Surface (Retail) (voor mogelijk toekomstig gebruik) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construeer codetekst vanuit Mailmark-gegevens. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | De PC en DP moeten voldoen aan een PAF-formaat. |
| [getFormat()](#getFormat--) | "0" \\u2013 Null of Test "1" \\u2013 Brief "2" \\u2013 Grote Brief |
| [getItemID()](#getItemID--) | Maximumwaarde is 99999999. |
| [getSupplychainID()](#getSupplychainID--) | Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L. |
| [getVersionID()](#getVersionID--) | Momenteel \"1\" \\u2013 voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Null of Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (voor mogelijk toekomstig gebruik) "5" - Deferred (Retail) "6" - Air (Retail) (voor mogelijk toekomstig gebruik) "7" - Surface (Retail) (voor mogelijk toekomstig gebruik) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | De PC en DP moeten voldoen aan een PAF-formaat. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Null of Test "1" \\u2013 Brief "2" \\u2013 Grote Brief |
| [setItemID(int value)](#setItemID-int-) | Maximumwaarde is 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L. |
| [setVersionID(int value)](#setVersionID-int-) | Momenteel \"1\" \\u2013 voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Initialiseert een nieuw exemplaar van de  MailmarkCodetext  klasse.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Haalt het barcode‑type op.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Null of Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (voor mogelijk toekomstig gebruik) "5" - Deferred (Retail) "6" - Air (Retail) (voor mogelijk toekomstig gebruik) "7" - Surface (Retail) (voor mogelijk toekomstig gebruik) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construeer codetekst vanuit Mailmark-gegevens.

**Returns:**
java.lang.String - Gemaakt codetext
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


De PC en DP moeten voldoen aan een PAF-formaat. Negen tekens tellende string die de internationale \"XY11 \" aangeeft (let op de 5 achterliggende spaties) of een patroon van tekens dat een binnenlandse sorteercode aangeeft. Een binnenlandse sorteercode bestaat uit een outward postcode, een inward postcode en een Delivery Point Suffix.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Null of Test "1" \\u2013 Brief "2" \\u2013 Grote Brief

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


Maximumwaarde is 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


Momenteel \"1\" \\u2013 voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik)

**Returns:**
int
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


Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Gemaakt codetext. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Null of Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (voor mogelijk toekomstig gebruik) "5" - Deferred (Retail) "6" - Air (Retail) (voor mogelijk toekomstig gebruik) "7" - Surface (Retail) (voor mogelijk toekomstig gebruik) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


De PC en DP moeten voldoen aan een PAF-formaat. Negen tekens tellende string die de internationale \"XY11 \" aangeeft (let op de 5 achterliggende spaties) of een patroon van tekens dat een binnenlandse sorteercode aangeeft. Een binnenlandse sorteercode bestaat uit een outward postcode, een inward postcode en een Delivery Point Suffix.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Null of Test "1" \\u2013 Brief "2" \\u2013 Grote Brief

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Maximumwaarde is 99999999.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


Momenteel \"1\" \\u2013 voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

