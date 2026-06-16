---
title: Adres
second_title: Aspose.BarCode for Android via Java API-referentie
description: Adres van schuldeiser of schuldenaar.
type: docs
weight: 10
url: /nl/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Adres van schuldeiser of schuldenaar.

U kunt ofwel straat, huisnummer, postcode en plaats (type  *gestructureerd adres* ) of adresregel 1 en 2 (type  *gecombineerde adresselementen* ) instellen. Het type wordt automatisch ingesteld zodra een van deze velden is ingevuld. Voordat de velden worden ingesteld, is het adrestype  *onbepaald* . Als velden van beide types worden ingevuld, wordt het adrestype  *conflicterend* . Naam en landcode moeten altijd worden ingesteld, tenzij alle velden leeg zijn.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Address()](#Address--) | Maakt een instantie van Adres |
## Methods

| Method | Beschrijving |
| --- | --- |
| [clear()](#clear--) | Wis alle velden en stelt het type in op  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven object gelijk is aan het huidige object. |
| [getAddressLine1()](#getAddressLine1--) | Haalt de adresregel 1 op. |
| [getAddressLine2()](#getAddressLine2--) | Haalt de adresregel 2 op. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Haalt de tweeletterige ISO-landcode op. |
| [getHouseNo()](#getHouseNo--) | Haalt het huisnummer op. |
| [getName()](#getName--) | Haalt de naam op, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon. |
| [getPostalCode()](#getPostalCode--) | Haalt de postcode op. |
| [getStreet()](#getStreet--) | Haalt de straat op. |
| [getTown()](#getTown--) | Haalt de plaats of stad op. |
| [getType()](#getType--) | Haalt het adrestype op. |
| [hashCode()](#hashCode--) | Haalt de hashcode op voor dit exemplaar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Stelt de adresregel 1 in. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Stelt de adresregel 2 in. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Stelt de tweeletterige ISO-landcode in. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Stelt het huisnummer in. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Stelt de postcode in. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Stelt de straat in. |
| [setTown(String value)](#setTown-java.lang.String-) | Stelt de plaats of stad in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Maakt een instantie van Adres

### clear() {#clear--}
```
public void clear()
```


Wis alle velden en stelt het type in op  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven object gelijk is aan het huidige object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken met het huidige object. |

**Returns:**
boolean -  true  als het opgegeven object gelijk is aan het huidige object; anders,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Haalt de adresregel 1 op.

Adresregel 1 bevat de straatnaam, het huisnummer of een postbus.

Het instellen van dit veld stelt het adrestype in op  AddressType.CombinedElements  tenzij het al  AddressType.Structured , in dat geval wordt het  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gecombineerde elementenadressen en is optioneel.

Waarde: De adresregel 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Haalt de adresregel 2 op.

Adresregel 2 bevat postcode en plaats.

Het instellen van dit veld stelt het adrestype in op  AddressType.CombinedElements  tenzij het al  AddressType.Structured , in dat geval wordt het  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gecombineerde elementenadressen. Voor dit type is het verplicht.

Waarde: De adresregel 2.

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


Haalt de tweeletterige ISO-landcode op.

De landcode is verplicht tenzij het volledige adres null of lege waarden bevat.

Waarde: De ISO-landcode.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Haalt het huisnummer op.

Het instellen van dit veld zet het adrestype op  AddressType.Structured  tenzij het al  AddressType.CombinedElements , in welk geval het wordt  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.

Waarde: Het huisnummer.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon.

Waarde: De naam.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Haalt de postcode op.

Het instellen van dit veld zet het adrestype op  AddressType.Structured  tenzij het al  AddressType.CombinedElements , in welk geval het wordt  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.

Waarde: De postcode.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Haalt de straat op.

De straat moet worden gespecificeerd zonder huisnummer.

Het instellen van dit veld zet het adrestype op  AddressType.Structured  tenzij het al  AddressType.CombinedElements , in welk geval het wordt  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.

Waarde: De straat.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Haalt de plaats of stad op.

Het instellen van dit veld zet het adrestype op  AddressType.Structured  tenzij het al  AddressType.CombinedElements , in welk geval het wordt  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.

Waarde: De plaats of stad.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Haalt het adrestype op.

Het adrestype wordt automatisch ingesteld door ofwel de straat / huisnummer of adresregel 1 en 2 in te stellen. Voordat de velden worden ingesteld, is het adrestype  *Undetermined* . Als velden van beide types zijn ingesteld, wordt het adrestype  *Conflicting* .

Waarde: Het adrestype.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Haalt de hashcode op voor dit exemplaar.

**Returns:**
int - Een hashcode voor het huidige object.
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


Stelt de adresregel 1 in.

Adresregel 1 bevat de straatnaam, het huisnummer of een postbus.

Het instellen van dit veld stelt het adrestype in op  AddressType.CombinedElements  tenzij het al  AddressType.Structured , in dat geval wordt het  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gecombineerde elementenadressen en is optioneel.

Waarde: De adresregel 1.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Stelt de adresregel 2 in.

Adresregel 2 bevat postcode en plaats.

Het instellen van dit veld stelt het adrestype in op  AddressType.CombinedElements  tenzij het al  AddressType.Structured , in dat geval wordt het  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gecombineerde elementenadressen. Voor dit type is het verplicht.

Waarde: De adresregel 2.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Stelt de tweeletterige ISO-landcode in.

De landcode is verplicht tenzij het volledige adres null of lege waarden bevat.

Waarde: De ISO-landcode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Stelt het huisnummer in.

Het instellen van dit veld zet het adrestype op  AddressType.Structured  tenzij het al  AddressType.CombinedElements , in welk geval het wordt  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.

Waarde: Het huisnummer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon.

Waarde: De naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Stelt de postcode in.

Het instellen van dit veld zet het adrestype op  AddressType.Structured  tenzij het al  AddressType.CombinedElements , in welk geval het wordt  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.

Waarde: De postcode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Stelt de straat in.

De straat moet worden gespecificeerd zonder huisnummer.

Het instellen van dit veld zet het adrestype op  AddressType.Structured  tenzij het al  AddressType.CombinedElements , in welk geval het wordt  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.

Waarde: De straat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Stelt de plaats of stad in.

Het instellen van dit veld zet het adrestype op  AddressType.Structured  tenzij het al  AddressType.CombinedElements , in welk geval het wordt  AddressType.Conflicting .

Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.

Waarde: De plaats of stad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

