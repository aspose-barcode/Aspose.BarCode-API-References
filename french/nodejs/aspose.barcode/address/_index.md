---
title: "Adresse"
linktitle: "Adresse"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Adresse du créancier ou du débiteur."
type: docs
weight: 10
url: /fr/nodejs/aspose.barcode/address/
---

## Address class

Adresse du créancier ou du débiteur. Vous pouvez soit définir la rue, le numéro de maison, le code postal et la ville (type adresse structurée) ou la ligne d’adresse 1 et 2 (type éléments d’adresse combinés). Le type est automatiquement défini dès qu’un de ces champs est renseigné. Avant de renseigner les champs, le type d’adresse est indéterminé. Si des champs des deux types sont renseignés, le type d’adresse devient conflictuelle. Le nom et le code pays doivent toujours être renseignés sauf si tous les champs sont vides.

```js
new Address()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [clear()](#clear) | Efface tous les champs et définit le type sur AddressType.UNDETERMINED. |
| [equals(obj)](#equals) | Détermine si l'objet spécifié est égal à l'objet actuel. |
| [getAddressLine1()](#getaddressline1) | Obtient la ligne d’adresse 1. La ligne d’adresse 1 contient le nom de la rue, le numéro de maison ou la boîte postale. La définition de ce champ définit l’adresse |
| [getAddressLine2()](#getaddressline2) | Obtient la ligne d’adresse 2. La ligne d’adresse 2 contient le code postal et la ville. La définition de ce champ définit le type d’adresse à Addre |
| [getCountryCode()](#getcountrycode) | Obtient le code pays ISO à deux lettres. Le code pays est obligatoire sauf si l’ensemble de l’adresse contient null ou emtpy val |
| [getHouseNo()](#gethouseno) | Obtient le numéro de maison. La définition de ce champ définit le type d’adresse sur AddressType.STRUCTURED sauf s’il est déjà AddressTyp |
| [getName()](#getname) | Obtient le nom, soit le prénom et le nom de famille d’une personne physique, soit le nom de l’entreprise d’une personne morale. |
| [getPostalCode()](#getpostalcode) | Obtient le code postal. La définition de ce champ définit le type d’adresse sur AddressType.STRUCTURED sauf s’il est déjà AddressType |
| [getStreet()](#getstreet) | Obtient la rue. La rue doit être spécifiée sans le numéro de maison. La définition de ce champ définit le type d’adresse sur AddressT |
| [getTown()](#gettown) | Obtient la ville ou la commune. La définition de ce champ définit le type d’adresse sur AddressType.STRUCTURED sauf s’il est déjà AddressTyp |
| [getType()](#gettype) | Obtient le type d’adresse. Le type d’adresse est automatiquement défini en renseignant soit la rue / le numéro de maison, soit la ligne d’adresse 1 a |
| [hashCode()](#hashcode) | Obtient le code de hachage pour cette instance. |
| [setAddressLine1(value:)](#setaddressline1) | Définit la ligne d’adresse 1. La ligne d’adresse 1 contient le nom de la rue, le numéro de maison ou la boîte postale. La définition de ce champ définit l’adresse |
| [setAddressLine2(value:)](#setaddressline2) | Définit la ligne d'adresse 2. La ligne d'adresse 2 contient le code postal et la ville. La définition de ce champ définit le type d'adresse à Addre |
| [setCountryCode(value)](#setcountrycode) | Définit le code pays ISO à deux lettres. Le code pays est obligatoire sauf si l'ensemble de l'adresse contient des valeurs nulles ou vides val |
| [setHouseNo(value:)](#sethouseno) | Définit le numéro de maison. La définition de ce champ définit le type d'adresse à AddressType.STRUCTURED sauf s'il est déjà AddressTyp |
| [setName(value:)](#setname) | Définit le nom, soit le prénom et le nom de famille d'une personne physique, soit le nom de l'entreprise d'une personne morale. |
| [setPostalCode(value)](#setpostalcode) | Définit le code postal. La définition de ce champ définit le type d'adresse à AddressType.STRUCTURED sauf s'il est déjà AddressType |
| [setStreet(value:)](#setstreet) | Définit la rue. La rue doit être spécifiée sans le numéro de maison. La définition de ce champ définit le type d'adresse à AddressT |
| [setTown(value)](#settown) | Définit la ville ou la commune. La définition de ce champ définit le type d'adresse à AddressType.STRUCTURED sauf s'il est déjà AddressTyp |

### clear() {#clear}

Efface tous les champs et définit le type sur AddressType.UNDETERMINED.

### equals(obj) {#equals}

Détermine si l'objet spécifié est égal à l'objet actuel.

| Paramètre | Description |
| --- | --- |
| obj | L'objet à comparer avec l'objet actuel. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

Obtient la ligne d'adresse 1. La ligne d'adresse 1 contient le nom de la rue, le numéro de maison ou la boîte postale. La définition de ce champ définit le type d'adresse à AddressType.COMBINED_ELEMENTS sauf s'il est déjà AddressType.STRUCTURED, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses à éléments combinés et est optionnel.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

Obtient la ligne d'adresse 2. La ligne d'adresse 2 contient le code postal et la ville. La définition de ce champ définit le type d'adresse à AddressType.COMBINED_ELEMENTS sauf s'il est déjà AddressType.STRUCTURED, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses à éléments combinés. Pour ce type, il est obligatoire.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

Obtient le code pays ISO à deux lettres. Le code pays est obligatoire sauf si l'ensemble de l'adresse contient des valeurs nulles ou vides.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

Obtient le numéro de maison. La définition de ce champ définit le type d'adresse à AddressType.STRUCTURED sauf s'il est déjà AddressType.COMBINED_ELEMENTS, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses structurées et est optionnel.

**Returns:** The house number.

### getName() {#getname}

Obtient le nom, soit le prénom et le nom de famille d’une personne physique, soit le nom de l’entreprise d’une personne morale.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

Obtient le code postal. La définition de ce champ définit le type d'adresse à AddressType.STRUCTURED sauf s'il est déjà AddressType.COMBINED_ELEMENTS, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.

**Returns:** The postal code.

### getStreet() {#getstreet}

Obtient la rue. La rue doit être spécifiée sans le numéro de maison. La définition de ce champ définit le type d'adresse à AddressType.STRUCTURED sauf s'il est déjà AddressType.COMBINED_ELEMENTS, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses structurées et est optionnel.

**Returns:** The street.

### getTown() {#gettown}

Obtient la ville ou la commune. La définition de ce champ définit le type d'adresse à AddressType.STRUCTURED sauf s'il est déjà AddressType.COMBINED_ELEMENTS, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.

**Returns:** The town or city.

### getType() {#gettype}

Obtient le type d'adresse. Le type d'adresse est automatiquement défini en réglant soit la rue / le numéro de maison, soit les lignes d'adresse 1 et 2. Avant de définir les champs, le type d'adresse est Undetermined. Si les champs des deux types sont définis, le type d'adresse devient Conflicting.

**Returns:** The address type.

### hashCode() {#hashcode}

Obtient le code de hachage pour cette instance.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

Définit la ligne d'adresse 1. La ligne d'adresse 1 contient le nom de la rue, le numéro de maison ou la boîte postale. La définition de ce champ définit le type d'adresse à AddressType.COMBINED_ELEMENTS sauf s'il est déjà AddressType.STRUCTURED, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses à éléments combinés et est optionnel.

| Paramètre | Description |
| --- | --- |
| valeur: | La ligne d'adresse 1. |

### setAddressLine2(value:) {#setaddressline2}

Définit la ligne d'adresse 2. La ligne d'adresse 2 contient le code postal et la ville. La définition de ce champ définit le type d'adresse à AddressType.COMBINED_ELEMENTS sauf s'il est déjà AddressType.STRUCTURED, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses à éléments combinés. Pour ce type, il est obligatoire.

| Paramètre | Description |
| --- | --- |
| valeur: | La ligne d'adresse 2. |

### setCountryCode(value) {#setcountrycode}

Définit le code pays ISO à deux lettres. Le code pays est obligatoire sauf si l'ensemble de l'adresse contient des valeurs nulles ou vides.

| Paramètre | Description |
| --- | --- |
| valeur | Le code pays ISO. |

### setHouseNo(value:) {#sethouseno}

Définit le numéro de maison. La définition de ce champ définit le type d'adresse sur AddressType.STRUCTURED sauf s'il est déjà AddressType.COMBINED_ELEMENTS, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses structurées et est facultatif.

| Paramètre | Description |
| --- | --- |
| valeur: | Le numéro de maison. |

### setName(value:) {#setname}

Définit le nom, soit le prénom et le nom de famille d'une personne physique, soit le nom de l'entreprise d'une personne morale.

| Paramètre | Description |
| --- | --- |
| valeur: | Le nom. |

### setPostalCode(value) {#setpostalcode}

Définit le code postal. La définition de ce champ définit le type d'adresse sur AddressType.STRUCTURED sauf s'il est déjà AddressType.COMBINED_ELEMENTS, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.

| Paramètre | Description |
| --- | --- |
| valeur | Le code postal. |

### setStreet(value:) {#setstreet}

Définit la rue. La rue doit être spécifiée sans numéro de maison. La définition de ce champ définit le type d'adresse sur AddressType.STRUCTURED sauf s'il est déjà AddressType.COMBINED_ELEMENTS, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses structurées et est facultatif.

| Paramètre | Description |
| --- | --- |
| valeur: | La rue. |

### setTown(value) {#settown}

Définit la ville ou la commune. La définition de ce champ définit le type d'adresse sur AddressType.STRUCTURED sauf s'il est déjà AddressType.COMBINED_ELEMENTS, auquel cas il devient AddressType.CONFLICTING. Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.

| Paramètre | Description |
| --- | --- |
| valeur | La ville ou la commune. |
