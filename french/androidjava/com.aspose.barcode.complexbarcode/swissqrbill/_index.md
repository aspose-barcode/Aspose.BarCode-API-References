---
title: SwissQRBill
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Données de facture SwissQR
type: docs
weight: 36
url: /fr/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

Données de facture SwissQR
## Méthodes

| Méthode | Description |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet spécifié est égal à l'objet actuel. |
| [getAccount()](#getAccount--) | Gets the creditor's account number. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Obtient ou définit les schémas de paiement alternatifs. |
| [getAmount()](#getAmount--) | Obtient le montant du paiement. |
| [getBillInformation()](#getBillInformation--) | Obtient les informations de facture structurées supplémentaires. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Obtient l'adresse du créancier. |
| [getCurrency()](#getCurrency--) | Obtient la devise du paiement. |
| [getDebtor()](#getDebtor--) | Obtient l'adresse du débiteur. |
| [getReference()](#getReference--) | Obtient la référence de paiement du créancier. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Obtient le message non structuré supplémentaire. |
| [getVersion()](#getVersion--) | Obtient la version de la norme de facture SwissQR. |
| [hashCode()](#hashCode--) | Gets the hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Définit le numéro de compte du créancier. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Obtient ou définit les schémas de paiement alternatifs. |
| [setAmount(double value)](#setAmount-double-) | Définit le montant du paiement. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Définit les informations de facture structurées supplémentaires. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Définit l'adresse du créancier. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Définit la devise du paiement. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Définit l'adresse du débiteur. |
| [setReference(String value)](#setReference-java.lang.String-) | Définit la référence de paiement du créancier. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Définit le message non structuré supplémentaire. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Définit la version de la norme de facture SwissQR. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum.

Les espaces blancs sont supprimés de la référence

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rawReference | java.lang.String | La référence brute. |

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
### getAccount() {#getAccount--}
```
public String getAccount()
```


Gets the creditor's account number.

Les numéros de compte doivent être des IBAN valides d'une banque de Suisse ou du Liechtenstein. Les espaces sont autorisés dans le numéro de compte.

Valeur : le numéro de compte du créancier.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Obtient ou définit les schémas de paiement alternatifs.

Un maximum de deux schémas avec paramètres est autorisé.

Valeur : les schémas de paiement alternatifs.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Obtient le montant du paiement.

Les valeurs valides sont comprises entre 0,01 et 999 999 999,99.

Valeur : le montant du paiement.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Obtient les informations de facture structurées supplémentaires.

Valeur : les informations de facture structurées.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


Obtient l'adresse du créancier.

Valeur : l’adresse du créancier.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Obtient la devise du paiement.

Les valeurs valides sont "CHF" et "EUR".

Valeur : la devise du paiement.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Obtient l'adresse du débiteur.

Le débiteur est facultatif. S’il est omis, il est acceptable de mettre ce champ à  null  ou de définir une adresse avec toutes les valeurs  null  ou vides.

Valeur : l’adresse du débiteur.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Obtient la référence de paiement du créancier.

La référence est obligatoire pour les IBAN SwissQR, c.-à-d. les IBAN dans la plage CHxx30000xxxxxx à CHxx31999xxxxx.

Si spécifiée, la référence doit être soit une référence SwissQR valide (correspondant au formulaire de référence ISR), soit une référence de créancier valide selon la norme ISO 11649 ("RFxxxx"). Les deux peuvent contenir des espaces pour le formatage.

Valeur : la référence de paiement du créancier.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Obtient le message non structuré supplémentaire.

Valeur : le message non structuré.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Obtient la version de la norme de facture SwissQR.

Valeur : la version du standard de facture SwissQR.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
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




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


Définit le numéro de compte du créancier.

Les numéros de compte doivent être des IBAN valides d'une banque de Suisse ou du Liechtenstein. Les espaces sont autorisés dans le numéro de compte.

Valeur : le numéro de compte du créancier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Obtient ou définit les schémas de paiement alternatifs.

Un maximum de deux schémas avec paramètres est autorisé.

Valeur : les schémas de paiement alternatifs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Définit le montant du paiement.

Les valeurs valides sont comprises entre 0,01 et 999 999 999,99.

Valeur : le montant du paiement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Définit les informations de facture structurées supplémentaires.

Valeur : les informations de facture structurées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Définit l'adresse du créancier.

Valeur : l’adresse du créancier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Définit la devise du paiement.

Les valeurs valides sont "CHF" et "EUR".

Valeur : la devise du paiement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Définit l'adresse du débiteur.

Le débiteur est facultatif. S’il est omis, il est acceptable de mettre ce champ à  null  ou de définir une adresse avec toutes les valeurs  null  ou vides.

Valeur : l’adresse du débiteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Définit la référence de paiement du créancier.

La référence est obligatoire pour les IBAN SwissQR, c.-à-d. les IBAN dans la plage CHxx30000xxxxxx à CHxx31999xxxxx.

Si spécifiée, la référence doit être soit une référence SwissQR valide (correspondant au formulaire de référence ISR), soit une référence de créancier valide selon la norme ISO 11649 ("RFxxxx"). Les deux peuvent contenir des espaces pour le formatage.

Valeur : la référence de paiement du créancier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Définit le message non structuré supplémentaire.

Valeur : le message non structuré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Définit la version de la norme de facture SwissQR.

Valeur : la version du standard de facture SwissQR.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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

