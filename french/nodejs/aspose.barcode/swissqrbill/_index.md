---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Données de facture SwissQR"
type: docs
weight: 920
url: /fr/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

Données de facture SwissQR

```js
new SwissQRBill()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Crée et définit une référence créancier ISO11649 à partir d'une chaîne brute en préfixant la chaîne avec "RF" et le modulo 97 che |
| [equals(obj)](#equals) | Détermine si l'objet spécifié est égal à l'objet actuel. |
| [getAccount()](#getaccount) | Obtient le numéro de compte du créancier. Les numéros de compte doivent être des IBAN valides d'une banque de Suisse ou du Liechtenstein. Espace |
| [getAlternativeSchemes()](#getalternativeschemes) | Obtient ou définit les schémas de paiement alternatifs. Un maximum de deux schémas avec paramètres est autorisé. |
| [getAmount()](#getamount) | Obtient le montant du paiement. Les valeurs valides sont comprises entre 0,01 et 999 999 999,99. |
| [getBillInformation()](#getbillinformation) | Obtient les informations supplémentaires structurées de la facture. |
| [getCreditor()](#getcreditor) | Obtient l'adresse du créancier. |
| [getCurrency()](#getcurrency) | Obtient la devise du paiement. Les valeurs valides sont "CHF" et "EUR". |
| [getDebtor()](#getdebtor) | Obtient l'adresse du débiteur. Le débiteur est optionnel. S'il est omis, le fait de définir ce champ sur null ou de définir une adresse |
| [getReference()](#getreference) | Obtient la référence de paiement du créancier. La référence est obligatoire pour les IBAN SwissQR, c.-à-d. les IBAN dans la plage CHxx30000xxxxx |
| [getUnstructuredMessage()](#getunstructuredmessage) | Obtient le message non structuré supplémentaire. |
| [getVersion()](#getversion) | Obtient la version de la norme de facture SwissQR. |
| [hashCode()](#hashcode) | Obtient le code de hachage pour cette instance. |
| [setAccount(value:)](#setaccount) | Définit le numéro de compte du créancier. Les numéros de compte doivent être des IBAN valides d'une banque de Suisse ou du Liechtenstein. Espace |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Obtient ou définit les schémas de paiement alternatifs. Un maximum de deux schémas avec paramètres est autorisé. |
| [setAmount(value)](#setamount) | Définit le montant du paiement. Les valeurs valides sont comprises entre 0,01 et 999 999 999,99. |
| [setBillInformation(value:)](#setbillinformation) | Définit les informations de facture structurées supplémentaires. |
| [setCreditor(value:)](#setcreditor) | Définit l'adresse du créancier. |
| [setCurrency(value)](#setcurrency) | Définit la devise du paiement. |
| [setDebtor(value:)](#setdebtor) | Définit l'adresse du débiteur. Le débiteur est optionnel. S'il est omis, le fait de définir ce champ sur null ou de définir une adresse |
| [setReference(value)](#setreference) | Définit la référence de paiement du créancier. La référence est obligatoire pour les IBAN SwissQR, c.-à-d. les IBAN dans la plage CHxx30000xxxxx |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Définit le message non structuré supplémentaire. |
| [setVersion(value)](#setversion) | Définit la version de la norme de facture SwissQR. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Crée et définit une référence de créancier ISO11649 à partir d'une chaîne brute en préfixant la chaîne avec "RF" et le checksum modulo 97. Les espaces sont supprimés de la référence

| Paramètre | Description |
| --- | --- |
| rawReference | La référence brute. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Détermine si l'objet spécifié est égal à l'objet actuel.

| Paramètre | Description |
| --- | --- |
| obj | L'objet à comparer avec l'objet actuel. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Obtient le numéro de compte du créancier. Les numéros de compte doivent être des IBAN valides d'une banque de Suisse ou du Liechtenstein. Les espaces sont autorisés dans le numéro de compte.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Obtient ou définit les schémas de paiement alternatifs. Un maximum de deux schémas avec paramètres est autorisé.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Obtient le montant du paiement. Les valeurs valides sont comprises entre 0,01 et 999 999 999,99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Obtient les informations supplémentaires structurées de la facture.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Obtient l'adresse du créancier.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Obtient la devise du paiement. Les valeurs valides sont "CHF" et "EUR".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Obtient l'adresse du débiteur. Le débiteur est optionnel. S'il est omis, le fait de définir ce champ sur null ou de définir une adresse avec toutes les valeurs nulles ou vides est acceptable.

**Returns:** The debtor address.

### getReference() {#getreference}

Obtient la référence de paiement du créancier. La référence est obligatoire pour les IBAN SwissQR, c.-à-d. les IBAN dans la plage CHxx30000xxxxxx à CHxx31999xxxxx. Si spécifiée, la référence doit être soit une référence SwissQR valide (correspondant au formulaire de référence ISR) soit une référence de créancier valide selon ISO 11649 ("RFxxxx"). Les deux peuvent contenir des espaces pour le formatage.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Obtient le message non structuré supplémentaire.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Obtient la version de la norme de facture SwissQR.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Obtient le code de hachage pour cette instance.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Définit le numéro de compte du créancier. Les numéros de compte doivent être des IBAN valides d'une banque de Suisse ou du Liechtenstein. Les espaces sont autorisés dans le numéro de compte.

| Paramètre | Description |
| --- | --- |
| valeur: | Le numéro de compte du créancier. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Obtient ou définit les schémas de paiement alternatifs. Un maximum de deux schémas avec paramètres est autorisé.

| Paramètre | Description |
| --- | --- |
| valeur: | Les schémas de paiement alternatifs. |

### setAmount(value) {#setamount}

Définit le montant du paiement. Les valeurs valides sont comprises entre 0,01 et 999 999 999,99.

| Paramètre | Description |
| --- | --- |
| valeur | Le montant du paiement. |

### setBillInformation(value:) {#setbillinformation}

Définit les informations de facture structurées supplémentaires.

| Paramètre | Description |
| --- | --- |
| valeur: | Les informations de facture structurées. |

### setCreditor(value:) {#setcreditor}

Définit l'adresse du créancier.

| Paramètre | Description |
| --- | --- |
| valeur: | L'adresse du créancier. |

### setCurrency(value) {#setcurrency}

Définit la devise du paiement.

| Paramètre | Description |
| --- | --- |
| valeur | Les valeurs valides sont "CHF" et "EUR". |

### setDebtor(value:) {#setdebtor}

Définit l'adresse du débiteur. Le débiteur est facultatif. S'il est omis, il est acceptable de définir ce champ à null ou de définir une adresse avec toutes les valeurs nulles ou vides.

| Paramètre | Description |
| --- | --- |
| valeur: | L'adresse du débiteur. |

### setReference(value) {#setreference}

Définit la référence de paiement du créancier. La référence est obligatoire pour les IBAN SwissQR, c.-à-d. les IBAN dans la plage CHxx30000xxxxxx à CHxx31999xxxxx. Si elle est spécifiée, la référence doit être soit une référence SwissQR valide (correspondant au formulaire de référence ISR), soit une référence de créancier valide selon la norme ISO 11649 ("RFxxxx"). Les deux peuvent contenir des espaces pour le formatage.

| Paramètre | Description |
| --- | --- |
| valeur | La référence de paiement du créancier. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Définit le message non structuré supplémentaire.

| Paramètre | Description |
| --- | --- |
| valeur: | Le message non structuré. |

### setVersion(value) {#setversion}

Définit la version de la norme de facture SwissQR.

| Paramètre | Description |
| --- | --- |
| valeur | La version standard de la facture SwissQR. |
