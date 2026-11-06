---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Klass för kodning och avkodning av text som är inbäddad i 4‑stegs Royal Mailmark‑koden."
type: docs
weight: 24
url: /sv/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

Klass för kodning och avkodning av text som är inbäddad i 4‑stegs Royal Mailmark‑koden.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Initierar en ny instans av klassen MailmarkCodetext. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Hämtar streckkodstyp. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Null eller Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (för potentiellt framtida användning) "5" - Uppskjuten (Retail) "6" - Luft (Retail) (för potentiellt framtida användning) "7" - Yta (Retail) (för potentiellt framtida användning) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Konstruera kodtext från Mailmark-data. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | PC och DP måste följa ett PAF-format. |
| [getFormat()](#getFormat--) | "0" \\u2013 Null eller Test "1" \\u2013 Brev "2" \\u2013 Stort brev |
| [getItemID()](#getItemID--) | Maximalt värde är 99999999. |
| [getSupplychainID()](#getSupplychainID--) | Maximala värden är 99 för Barcode C och 999999 för Barcode L. |
| [getVersionID()](#getVersionID--) | För närvarande "1" \\u2013 För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initierar Mailmark-data från konstruerad kodtext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Null eller Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (för potentiellt framtida användning) "5" - Uppskjuten (Retail) "6" - Luft (Retail) (för potentiellt framtida användning) "7" - Yta (Retail) (för potentiellt framtida användning) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | PC och DP måste följa ett PAF-format. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Null eller Test "1" \\u2013 Brev "2" \\u2013 Stort brev |
| [setItemID(int value)](#setItemID-int-) | Maximalt värde är 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Maximala värden är 99 för Barcode C och 999999 för Barcode L. |
| [setVersionID(int value)](#setVersionID-int-) | För närvarande "1" \\u2013 För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Initierar en ny instans av klassen MailmarkCodetext.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Hämtar streckkodstyp.

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


"0" - Null eller Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (för potentiellt framtida användning) "5" - Uppskjuten (Retail) "6" - Luft (Retail) (för potentiellt framtida användning) "7" - Yta (Retail) (för potentiellt framtida användning) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Konstruera kodtext från Mailmark-data.

**Returns:**
java.lang.String - Konstruerad kodtext
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


PC och DP måste följa ett PAF-format. Nio tecken lång sträng som anger internationell "XY11 " (observera de 5 efterföljande mellanslagen) eller ett mönster av tecken som anger en inhemsk sorteringskod. En inhemsk sorteringskod består av ett utåtriktat postnummer, ett inåtriktat postnummer och ett leveranspunktsuffix.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Null eller Test "1" \\u2013 Brev "2" \\u2013 Stort brev

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


Maximalt värde är 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Maximala värden är 99 för Barcode C och 999999 för Barcode L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


För närvarande "1" \\u2013 För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning)

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


Initierar Mailmark-data från konstruerad kodtext.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruerad kodtext. |

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


"0" - Null eller Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (för potentiellt framtida användning) "5" - Uppskjuten (Retail) "6" - Luft (Retail) (för potentiellt framtida användning) "7" - Yta (Retail) (för potentiellt framtida användning) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


PC och DP måste följa ett PAF-format. Nio tecken lång sträng som anger internationell "XY11 " (observera de 5 efterföljande mellanslagen) eller ett mönster av tecken som anger en inhemsk sorteringskod. En inhemsk sorteringskod består av ett utåtriktat postnummer, ett inåtriktat postnummer och ett leveranspunktsuffix.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Null eller Test "1" \\u2013 Brev "2" \\u2013 Stort brev

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Maximalt värde är 99999999.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Maximala värden är 99 för Barcode C och 999999 för Barcode L.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


För närvarande "1" \\u2013 För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

