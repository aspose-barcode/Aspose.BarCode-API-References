---
title: Adress
second_title: Aspose.BarCode for Android via Java API-referens
description: Adress för borgenär eller gäldenär.
type: docs
weight: 10
url: /sv/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Adress för borgenär eller gäldenär.

Du kan antingen ange street, house number, postal code and town (type  *structured address* ) eller address line 1 and 2 (type  *combined address elements* ). Typen sätts automatiskt så snart något av dessa fält är angivet. Innan fälten sätts är adress typen  *undetermined* . Om fält av båda typerna anges blir adress typen  *conflicting* . Namn och landskod måste alltid anges om inte alla fält är tomma.
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [Address()](#Address--) | Skapar en instans av Adress |
## Methods

| Method | Beskrivning |
| --- | --- |
| [clear()](#clear--) | Rensar alla fält och sätter typen till  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om det angivna objektet är lika med det aktuella objektet. |
| [getAddressLine1()](#getAddressLine1--) | Hämtar adressrad 1. |
| [getAddressLine2()](#getAddressLine2--) | Hämtar adressrad 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Hämtar den tvåbokstaviga ISO-landkoden. |
| [getHouseNo()](#getHouseNo--) | Hämtar husnumret. |
| [getName()](#getName--) | Hämtar namnet, antingen förnamn och efternamn för en fysisk person eller företagsnamnet för en juridisk person. |
| [getPostalCode()](#getPostalCode--) | Hämtar postnumret. |
| [getStreet()](#getStreet--) | Hämtar gatan. |
| [getTown()](#getTown--) | Hämtar staden eller orten. |
| [getType()](#getType--) | Hämtar adresstypen. |
| [hashCode()](#hashCode--) | Hämtar hash‑koden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Sätter adressrad 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Sätter adressrad 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Sätter den tvåbokstaviga ISO-landkoden. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Sätter husnumret. |
| [setName(String value)](#setName-java.lang.String-) | Sätter namnet, antingen förnamn och efternamn för en fysisk person eller företagsnamnet för en juridisk person. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Sätter postnumret. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Sätter gatan. |
| [setTown(String value)](#setTown-java.lang.String-) | Sätter staden eller orten. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Skapar en instans av Adress

### clear() {#clear--}
```
public void clear()
```


Rensar alla fält och sätter typen till  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om det angivna objektet är lika med det aktuella objektet.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med det aktuella objektet. |

**Returns:**
boolean -  true  om det angivna objektet är lika med det aktuella objektet; annars,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Hämtar adressrad 1.

Adressrad 1 innehåller gatunamn, husnummer eller postbox.

Att sätta detta fält sätter adresstypen till  AddressType.CombinedElements  om den inte redan är  AddressType.Structured , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för kombinerade elementadresser och är valfritt.

Värde: Adressrad 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Hämtar adressrad 2.

Adressrad 2 innehåller postnummer och ort.

Att sätta detta fält sätter adresstypen till  AddressType.CombinedElements  om den inte redan är  AddressType.Structured , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för kombinerade elementadresser. För denna typ är det obligatoriskt.

Värde: Adressrad 2.

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


Hämtar den tvåbokstaviga ISO-landkoden.

Landskoden är obligatorisk om inte hela adressen innehåller null eller tomma värden.

Värde: ISO-landskoden.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Hämtar husnumret.

Att ställa in detta fält sätter adresstypen till  AddressType.Structured  om den inte redan är  AddressType.CombinedElements , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för strukturerade adresser och är valfritt.

Värde: Husnumret.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet, antingen förnamn och efternamn för en fysisk person eller företagsnamnet för en juridisk person.

Värde: Namnet.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Hämtar postnumret.

Att ställa in detta fält sätter adresstypen till  AddressType.Structured  om den inte redan är  AddressType.CombinedElements , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

Värde: Postnumret.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Hämtar gatan.

Gatan måste anges utan husnummer.

Att ställa in detta fält sätter adresstypen till  AddressType.Structured  om den inte redan är  AddressType.CombinedElements , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för strukturerade adresser och är valfritt.

Värde: Gatan.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Hämtar staden eller orten.

Att ställa in detta fält sätter adresstypen till  AddressType.Structured  om den inte redan är  AddressType.CombinedElements , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

Värde: Staden eller orten.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Hämtar adresstypen.

Adresstypen sätts automatiskt genom att antingen ange gata / husnummer eller adressrad 1 och 2. Innan fälten sätts är adresstypen  *Undetermined* . Om fält av båda typerna anges blir adresstypen  *Conflicting* .

Värde: Adresstypen.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hash‑koden för detta objekt.

**Returns:**
int - En hash‑kod för det aktuella objektet.
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


Sätter adressrad 1.

Adressrad 1 innehåller gatunamn, husnummer eller postbox.

Att sätta detta fält sätter adresstypen till  AddressType.CombinedElements  om den inte redan är  AddressType.Structured , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för kombinerade elementadresser och är valfritt.

Värde: Adressrad 1.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Sätter adressrad 2.

Adressrad 2 innehåller postnummer och ort.

Att sätta detta fält sätter adresstypen till  AddressType.CombinedElements  om den inte redan är  AddressType.Structured , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för kombinerade elementadresser. För denna typ är det obligatoriskt.

Värde: Adressrad 2.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Sätter den tvåbokstaviga ISO-landkoden.

Landskoden är obligatorisk om inte hela adressen innehåller null eller tomma värden.

Värde: ISO-landskoden.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Sätter husnumret.

Att ställa in detta fält sätter adresstypen till  AddressType.Structured  om den inte redan är  AddressType.CombinedElements , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för strukturerade adresser och är valfritt.

Värde: Husnumret.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sätter namnet, antingen förnamn och efternamn för en fysisk person eller företagsnamnet för en juridisk person.

Värde: Namnet.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Sätter postnumret.

Att ställa in detta fält sätter adresstypen till  AddressType.Structured  om den inte redan är  AddressType.CombinedElements , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

Värde: Postnumret.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Sätter gatan.

Gatan måste anges utan husnummer.

Att ställa in detta fält sätter adresstypen till  AddressType.Structured  om den inte redan är  AddressType.CombinedElements , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för strukturerade adresser och är valfritt.

Värde: Gatan.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Sätter staden eller orten.

Att ställa in detta fält sätter adresstypen till  AddressType.Structured  om den inte redan är  AddressType.CombinedElements , i så fall blir den  AddressType.Conflicting .

Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

Värde: Staden eller orten.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

