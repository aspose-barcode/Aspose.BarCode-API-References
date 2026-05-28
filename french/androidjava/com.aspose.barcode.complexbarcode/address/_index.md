---
title: Adresse
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Adresse du créancier ou du débiteur.
type: docs
weight: 10
url: /fr/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Adresse du créancier ou du débiteur.

Vous pouvez soit définir la rue, le numéro de maison, le code postal et la ville (type  *adresse structurée* ) ou la ligne d'adresse 1 et 2 (type  *éléments d'adresse combinés* ). Le type est automatiquement défini dès qu'un de ces champs est renseigné. Avant de renseigner les champs, le type d'adresse est  *indéterminé* . Si des champs des deux types sont renseignés, le type d'adresse devient  *conflictuel* . Le nom et le code pays doivent toujours être renseignés sauf si tous les champs sont vides.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Address()](#Address--) | Crée une instance de Adresse |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clear()](#clear--) | Efface tous les champs et définit le type sur  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet spécifié est égal à l'objet actuel. |
| [getAddressLine1()](#getAddressLine1--) | Obtient la ligne d'adresse 1. |
| [getAddressLine2()](#getAddressLine2--) | Obtient la ligne d'adresse 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Obtient le code pays ISO à deux lettres. |
| [getHouseNo()](#getHouseNo--) | Obtient le numéro de maison. |
| [getName()](#getName--) | Obtient le nom, soit le prénom et le nom de famille d'une personne physique, soit le nom de l'entreprise d'une personne morale. |
| [getPostalCode()](#getPostalCode--) | Obtient le code postal. |
| [getStreet()](#getStreet--) | Obtient la rue. |
| [getTown()](#getTown--) | Obtient la ville ou la municipalité. |
| [getType()](#getType--) | Obtient le type d'adresse. |
| [hashCode()](#hashCode--) | Gets the hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Définit la ligne d'adresse 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Définit la ligne d'adresse 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Définit le code pays ISO à deux lettres. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Définit le numéro de maison. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom, soit le prénom et le nom de famille d'une personne physique, soit le nom de l'entreprise d'une personne morale. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Définit le code postal. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Définit la rue. |
| [setTown(String value)](#setTown-java.lang.String-) | Définit la ville ou la municipalité. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Crée une instance de Adresse

### clear() {#clear--}
```
public void clear()
```


Efface tous les champs et définit le type sur  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'objet spécifié est égal à l'objet actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current object. |

**Returns:**
boolean -  true  if the specified object is equal to the current object; otherwise,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Obtient la ligne d'adresse 1.

La ligne d'adresse 1 contient le nom de la rue, le numéro de maison ou la boîte postale.

Définir ce champ définit le type d'adresse sur  AddressType.CombinedElements  sauf s'il est déjà  AddressType.Structured , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses à éléments combinés et est facultatif.

Valeur : la ligne d'adresse 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Obtient la ligne d'adresse 2.

La ligne d'adresse 2 contient le code postal et la ville.

Définir ce champ définit le type d'adresse sur  AddressType.CombinedElements  sauf s'il est déjà  AddressType.Structured , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses à éléments combinés. Pour ce type, il est obligatoire.

Valeur : la ligne d'adresse 2.

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


Obtient le code pays ISO à deux lettres.

Le code pays est obligatoire sauf si l'ensemble de l'adresse contient des valeurs null ou vides.

Valeur : le code pays ISO.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Obtient le numéro de maison.

Définir ce champ définit le type d'adresse sur  AddressType.Structured  sauf s'il est déjà  AddressType.CombinedElements , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses structurées et est facultatif.

Valeur : le numéro de maison.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Obtient le nom, soit le prénom et le nom de famille d'une personne physique, soit le nom de l'entreprise d'une personne morale.

Valeur : le nom.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Obtient le code postal.

Définir ce champ définit le type d'adresse sur  AddressType.Structured  sauf s'il est déjà  AddressType.CombinedElements , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.

Valeur : le code postal.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Obtient la rue.

La rue doit être spécifiée sans numéro de maison.

Définir ce champ définit le type d'adresse sur  AddressType.Structured  sauf s'il est déjà  AddressType.CombinedElements , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses structurées et est facultatif.

Valeur : la rue.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Obtient la ville ou la municipalité.

Définir ce champ définit le type d'adresse sur  AddressType.Structured  sauf s'il est déjà  AddressType.CombinedElements , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.

Valeur : la ville ou la commune.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Obtient le type d'adresse.

Le type d'adresse est automatiquement défini en renseignant soit la rue / le numéro de maison, soit les lignes d'adresse 1 et 2. Avant de définir les champs, le type d'adresse est  *Undetermined* . Si les champs des deux types sont renseignés, le type d'adresse devient  *Conflicting* .

Valeur : le type d'adresse.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gets the hash code for this instance.

**Returns:**
int - A hash code for the current object.
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


Définit la ligne d'adresse 1.

La ligne d'adresse 1 contient le nom de la rue, le numéro de maison ou la boîte postale.

Définir ce champ définit le type d'adresse sur  AddressType.CombinedElements  sauf s'il est déjà  AddressType.Structured , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses à éléments combinés et est facultatif.

Valeur : la ligne d'adresse 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Définit la ligne d'adresse 2.

La ligne d'adresse 2 contient le code postal et la ville.

Définir ce champ définit le type d'adresse sur  AddressType.CombinedElements  sauf s'il est déjà  AddressType.Structured , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses à éléments combinés. Pour ce type, il est obligatoire.

Valeur : la ligne d'adresse 2.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Définit le code pays ISO à deux lettres.

Le code pays est obligatoire sauf si l'ensemble de l'adresse contient des valeurs null ou vides.

Valeur : le code pays ISO.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Définit le numéro de maison.

Définir ce champ définit le type d'adresse sur  AddressType.Structured  sauf s'il est déjà  AddressType.CombinedElements , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses structurées et est facultatif.

Valeur : le numéro de maison.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom, soit le prénom et le nom de famille d'une personne physique, soit le nom de l'entreprise d'une personne morale.

Valeur : le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Définit le code postal.

Définir ce champ définit le type d'adresse sur  AddressType.Structured  sauf s'il est déjà  AddressType.CombinedElements , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.

Valeur : le code postal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Définit la rue.

La rue doit être spécifiée sans numéro de maison.

Définir ce champ définit le type d'adresse sur  AddressType.Structured  sauf s'il est déjà  AddressType.CombinedElements , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses structurées et est facultatif.

Valeur : la rue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Définit la ville ou la municipalité.

Définir ce champ définit le type d'adresse sur  AddressType.Structured  sauf s'il est déjà  AddressType.CombinedElements , auquel cas il devient  AddressType.Conflicting .

Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.

Valeur : la ville ou la commune.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

