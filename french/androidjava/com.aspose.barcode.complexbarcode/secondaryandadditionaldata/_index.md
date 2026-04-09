---
title: SecondaryAndAdditionalData
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Classe pour stocker les données secondaires et supplémentaires HIBC LIC.
type: docs
weight: 35
url: /fr/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

Classe pour stocker les données secondaires et supplémentaires HIBC LIC.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée SecondaryAndAdditionalData. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Identifie la date de fabrication. |
| [getExpiryDate()](#getExpiryDate--) | Identifie la date d'expiration. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifie le format de la date d'expiration. |
| [getLotNumber()](#getLotNumber--) | Identifie le numéro de lot ou de lot. |
| [getQuantity()](#getQuantity--) | Identifie la quantité, doit être une valeur entière de 0 à 500. |
| [getSerialNumber()](#getSerialNumber--) | Identifie le numéro de série. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | Instancie les données supplémentaires secondaires et additionnelles à partir du format de chaîne selon la spécification HIBC LIC. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Identifie la date de fabrication. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Identifie la date d'expiration. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Identifie le format de la date d'expiration. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifie le numéro de lot ou de lot. |
| [setQuantity(int value)](#setQuantity-int-) | Identifie la quantité, doit être une valeur entière de 0 à 500. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifie le numéro de série. |
| [toString()](#toString--) | Convertit les données au format de chaîne selon la spécification HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée SecondaryAndAdditionalData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur SecondaryAndAdditionalData à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


Identifie la date de fabrication. La date de fabrication peut être définie à DateTime.MinValue afin de ne pas utiliser ce champ. Valeur par défaut : DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Identifie la date d'expiration. Sera utilisée si ExpiryDateFormat n'est pas défini sur None.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Identifie le format de la date d'expiration.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Identifie le numéro de lot ou de lot. Le numéro de lot/do lot doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Identifie la quantité, doit être une valeur entière de 0 à 500. La quantité peut être définie à -1 afin de ne pas utiliser ce champ. Valeur par défaut : -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Identifie le numéro de série. Le numéro de série doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


Instancie les données supplémentaires secondaires et additionnelles à partir du format de chaîne selon la spécification HIBC LIC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | Chaîne formatée. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Identifie la date de fabrication. La date de fabrication peut être définie à DateTime.MinValue afin de ne pas utiliser ce champ. Valeur par défaut : DateTime.MinValue

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Identifie la date d'expiration. Sera utilisée si ExpiryDateFormat n'est pas défini sur None.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Identifie le format de la date d'expiration.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Identifie le numéro de lot ou de lot. Le numéro de lot/do lot doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Identifie la quantité, doit être une valeur entière de 0 à 500. La quantité peut être définie à -1 afin de ne pas utiliser ce champ. Valeur par défaut : -1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Identifie le numéro de série. Le numéro de série doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Convertit les données au format de chaîne selon la spécification HIBC LIC.

**Returns:**
java.lang.String - Chaîne formatée.
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

