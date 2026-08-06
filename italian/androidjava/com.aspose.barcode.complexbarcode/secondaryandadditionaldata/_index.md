---
title: SecondaryAndAdditionalData
second_title: Aspose.BarCode per Android via Java API Reference
description: Classe per la memorizzazione dei dati secondari e aggiuntivi HIBC LIC.
type: docs
weight: 35
url: /it/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

Classe per la memorizzazione dei dati secondari e aggiuntivi HIBC LIC.
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore  SecondaryAndAdditionalData  specificato. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Identifica la data di produzione. |
| [getExpiryDate()](#getExpiryDate--) | Identifica la data di scadenza. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifica il formato della data di scadenza. |
| [getLotNumber()](#getLotNumber--) | Identifica il numero di lotto o batch. |
| [getQuantity()](#getQuantity--) | Identifica la quantità, deve essere un valore intero da 0 a 500. |
| [getSerialNumber()](#getSerialNumber--) | Identifica il numero di serie. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | Istanzia i dati supplementari secondari e aggiuntivi dal formato stringa secondo la specifica HIBC LIC. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Identifica la data di produzione. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Identifica la data di scadenza. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Identifica il formato della data di scadenza. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifica il numero di lotto o batch. |
| [setQuantity(int value)](#setQuantity-int-) | Identifica la quantità, deve essere un valore intero da 0 a 500. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifica il numero di serie. |
| [toString()](#toString--) | Converte i dati al formato stringa secondo la specifica HIBC LIC. |
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


Restituisce un valore che indica se questa istanza è uguale a un valore  SecondaryAndAdditionalData  specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore  SecondaryAndAdditionalData  da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
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


Identifica la data di produzione. La data di produzione può essere impostata a DateTime.MinValue per non utilizzare questo campo. Valore predefinito: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Identifica la data di scadenza. Verrà utilizzata se ExpiryDateFormat non è impostato su None.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Identifica il formato della data di scadenza.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Identifica il numero di lotto o batch. Il numero di lotto/batch deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. .

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Identifica la quantità, deve essere un valore intero da 0 a 500. La quantità può essere impostata a -1 per non utilizzare questo campo. Valore predefinito: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Identifica il numero di serie. Il numero di serie deve essere una stringa alfanumerica fino a 18 simboli di lunghezza.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
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


Istanzia i dati supplementari secondari e aggiuntivi dal formato stringa secondo la specifica HIBC LIC.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | Stringa formattata. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Identifica la data di produzione. La data di produzione può essere impostata a DateTime.MinValue per non utilizzare questo campo. Valore predefinito: DateTime.MinValue

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Identifica la data di scadenza. Verrà utilizzata se ExpiryDateFormat non è impostato su None.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Identifica il formato della data di scadenza.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Identifica il numero di lotto o batch. Il numero di lotto/batch deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. .

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Identifica la quantità, deve essere un valore intero da 0 a 500. La quantità può essere impostata a -1 per non utilizzare questo campo. Valore predefinito: -1

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Identifica il numero di serie. Il numero di serie deve essere una stringa alfanumerica fino a 18 simboli di lunghezza.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Converte i dati al formato stringa secondo la specifica HIBC LIC.

**Returns:**
java.lang.String - Stringa formattata.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

