---
title: Adresse
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Adresse des Gläubigers oder Schuldners.
type: docs
weight: 10
url: /de/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Adresse des Gläubigers oder Schuldners.

Sie können entweder Straße, Hausnummer, Postleitzahl und Ort festlegen (Typ  *structured address* ) oder Adresszeile 1 und 2 (Typ  *combined address elements* ). Der Typ wird automatisch gesetzt, sobald eines dieser Felder gesetzt ist. Vor dem Setzen der Felder ist der Adresstyp  *undetermined* . Wenn Felder beider Typen gesetzt werden, wird der Adresstyp  *conflicting* . Name und Ländercode müssen immer gesetzt sein, es sei denn, alle Felder sind leer.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [Address()](#Address--) | Erstellt eine Instanz von Adresse |
## Methods

| Method | Beschreibung |
| --- | --- |
| [clear()](#clear--) | Löscht alle Felder und setzt den Typ auf  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist. |
| [getAddressLine1()](#getAddressLine1--) | Ruft die Adresszeile 1 ab. |
| [getAddressLine2()](#getAddressLine2--) | Ruft die Adresszeile 2 ab. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Ruft den zweibuchstabigen ISO-Ländercode ab. |
| [getHouseNo()](#getHouseNo--) | Ruft die Hausnummer ab. |
| [getName()](#getName--) | Ruft den Namen ab, entweder den Vor- und Nachnamen einer natürlichen Person oder den Firmennamen einer juristischen Person. |
| [getPostalCode()](#getPostalCode--) | Ruft die Postleitzahl ab. |
| [getStreet()](#getStreet--) | Ruft die Straße ab. |
| [getTown()](#getTown--) | Ruft die Stadt oder Gemeinde ab. |
| [getType()](#getType--) | Ruft den Adresstyp ab. |
| [hashCode()](#hashCode--) | Ermittelt den Hashcode für diese Instanz. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Setzt die Adresszeile 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Setzt die Adresszeile 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Setzt den zweibuchstabigen ISO-Ländercode. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Setzt die Hausnummer. |
| [setName(String value)](#setName-java.lang.String-) | Setzt den Namen, entweder den Vor- und Nachnamen einer natürlichen Person oder den Firmennamen einer juristischen Person. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Setzt die Postleitzahl. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Setzt die Straße. |
| [setTown(String value)](#setTown-java.lang.String-) | Setzt die Stadt oder Gemeinde. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Erstellt eine Instanz von Adresse

### clear() {#clear--}
```
public void clear()
```


Löscht alle Felder und setzt den Typ auf  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt, das mit dem aktuellen Objekt verglichen werden soll. |

**Returns:**
boolean -  true  wenn das angegebene Objekt gleich dem aktuellen Objekt ist; andernfalls,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Ruft die Adresszeile 1 ab.

Adresszeile 1 enthält Straßenname, Hausnummer oder Postfach.

Das Setzen dieses Feldes setzt den Adresstyp auf  AddressType.CombinedElements  sofern er nicht bereits  AddressType.Structured  ist, in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet und ist optional.

Wert: Die Adresszeile 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Ruft die Adresszeile 2 ab.

Adresszeile 2 enthält Postleitzahl und Stadt.

Das Setzen dieses Feldes setzt den Adresstyp auf  AddressType.CombinedElements  sofern er nicht bereits  AddressType.Structured  ist, in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet. Für diesen Typ ist es obligatorisch.

Wert: Die Adresszeile 2.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


Ruft den zweibuchstabigen ISO-Ländercode ab.

Der Ländercode ist obligatorisch, es sei denn, die gesamte Adresse enthält null oder leere Werte.

Wert: Der ISO-Ländercode.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Ruft die Hausnummer ab.

Das Setzen dieses Feldes legt den Adresstyp auf  AddressType.Structured  fest, es sei denn, er ist bereits  AddressType.CombinedElements , in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.

Wert: Die Hausnummer.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Ruft den Namen ab, entweder den Vor- und Nachnamen einer natürlichen Person oder den Firmennamen einer juristischen Person.

Wert: Der Name.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Ruft die Postleitzahl ab.

Das Setzen dieses Feldes legt den Adresstyp auf  AddressType.Structured  fest, es sei denn, er ist bereits  AddressType.CombinedElements , in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

Wert: Die Postleitzahl.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Ruft die Straße ab.

Die Straße muss ohne Hausnummer angegeben werden.

Das Setzen dieses Feldes legt den Adresstyp auf  AddressType.Structured  fest, es sei denn, er ist bereits  AddressType.CombinedElements , in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.

Wert: Die Straße.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Ruft die Stadt oder Gemeinde ab.

Das Setzen dieses Feldes legt den Adresstyp auf  AddressType.Structured  fest, es sei denn, er ist bereits  AddressType.CombinedElements , in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

Wert: Die Stadt oder Gemeinde.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Ruft den Adresstyp ab.

Der Adresstyp wird automatisch entweder durch das Setzen von Straße / Hausnummer oder von Adresszeile 1 und 2 festgelegt. Vor dem Setzen der Felder ist der Adresstyp  *Undetermined* . Wenn Felder beider Typen gesetzt werden, wird der Adresstyp zu  *Conflicting* .

Wert: Der Adresstyp.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ermittelt den Hashcode für diese Instanz.

**Returns:**
int - Ein Hashcode für das aktuelle Objekt.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


Setzt die Adresszeile 1.

Adresszeile 1 enthält Straßenname, Hausnummer oder Postfach.

Das Setzen dieses Feldes setzt den Adresstyp auf  AddressType.CombinedElements  sofern er nicht bereits  AddressType.Structured  ist, in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet und ist optional.

Wert: Die Adresszeile 1.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Setzt die Adresszeile 2.

Adresszeile 2 enthält Postleitzahl und Stadt.

Das Setzen dieses Feldes setzt den Adresstyp auf  AddressType.CombinedElements  sofern er nicht bereits  AddressType.Structured  ist, in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet. Für diesen Typ ist es obligatorisch.

Wert: Die Adresszeile 2.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Setzt den zweibuchstabigen ISO-Ländercode.

Der Ländercode ist obligatorisch, es sei denn, die gesamte Adresse enthält null oder leere Werte.

Wert: Der ISO-Ländercode.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Setzt die Hausnummer.

Das Setzen dieses Feldes legt den Adresstyp auf  AddressType.Structured  fest, es sei denn, er ist bereits  AddressType.CombinedElements , in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.

Wert: Die Hausnummer.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Setzt den Namen, entweder den Vor- und Nachnamen einer natürlichen Person oder den Firmennamen einer juristischen Person.

Wert: Der Name.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Setzt die Postleitzahl.

Das Setzen dieses Feldes legt den Adresstyp auf  AddressType.Structured  fest, es sei denn, er ist bereits  AddressType.CombinedElements , in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

Wert: Die Postleitzahl.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Setzt die Straße.

Die Straße muss ohne Hausnummer angegeben werden.

Das Setzen dieses Feldes legt den Adresstyp auf  AddressType.Structured  fest, es sei denn, er ist bereits  AddressType.CombinedElements , in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.

Wert: Die Straße.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Setzt die Stadt oder Gemeinde.

Das Setzen dieses Feldes legt den Adresstyp auf  AddressType.Structured  fest, es sei denn, er ist bereits  AddressType.CombinedElements , in diesem Fall wird er zu  AddressType.Conflicting .

Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

Wert: Die Stadt oder Gemeinde.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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

