---
title: PrimaryData
second_title: Aspose.BarCode per Android via Java API Reference
description: Classe per la memorizzazione dei dati primari HIBC LIC.
type: docs
weight: 34
url: /it/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Classe per la memorizzazione dei dati primari HIBC LIC.
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore  PrimaryData  specificato. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifica la data del codice di identificazione dell'etichettatore. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifica il numero di prodotto o di catalogo. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifica l'ID dell'unità di misura. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Istanzia i dati primari dal formato stringa secondo la specifica HIBC LIC. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifica la data del codice di identificazione dell'etichettatore. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifica il numero di prodotto o di catalogo. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifica l'ID dell'unità di misura. |
| [toString()](#toString--) | Converte i dati al formato stringa secondo la specifica HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore  PrimaryData  specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore PrimaryData da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


Identifica la data del codice di identificazione del etichettatore. Il codice di identificazione del etichettatore deve essere una stringa alfanumerica di 4 simboli, con il primo carattere sempre alfabetico.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Identifica il numero di prodotto o di catalogo. Il numero di prodotto o di catalogo deve essere una stringa alfanumerica di lunghezza fino a 18 simboli.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Identifica l'ID dell'unità di misura. L'ID dell'unità di misura deve essere un valore intero da 0 a 9.

**Returns:**
int
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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


Istanzia i dati primari dal formato stringa secondo la specifica HIBC LIC.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Stringa formattata. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Identifica la data del codice di identificazione del etichettatore. Il codice di identificazione del etichettatore deve essere una stringa alfanumerica di 4 simboli, con il primo carattere sempre alfabetico.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Identifica il numero di prodotto o di catalogo. Il numero di prodotto o di catalogo deve essere una stringa alfanumerica di lunghezza fino a 18 simboli.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Identifica l'ID dell'unità di misura. L'ID dell'unità di misura deve essere un valore intero da 0 a 9.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

