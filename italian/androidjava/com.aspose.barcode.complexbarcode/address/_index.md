---
title: "Indirizzo"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Indirizzo del creditore o del debitore."
type: docs
weight: 10
url: /it/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Indirizzo del creditore o del debitore.

Puoi impostare o via, numero civico, codice postale e città (tipo  *structured address* ) oppure riga indirizzo 1 e 2 (tipo  *combined address elements* ). Il tipo viene impostato automaticamente non appena uno di questi campi è impostato. Prima di impostare i campi, il tipo di indirizzo è  *undetermined* . Se i campi di entrambi i tipi sono impostati, il tipo di indirizzo diventa  *conflicting* . Il nome e il codice paese devono essere sempre impostati a meno che tutti i campi siano vuoti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Address()](#Address--) | Crea un'istanza di Indirizzo |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clear()](#clear--) | Cancella tutti i campi e imposta il tipo su  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'oggetto specificato è uguale all'oggetto corrente. |
| [getAddressLine1()](#getAddressLine1--) | Restituisce la riga indirizzo 1. |
| [getAddressLine2()](#getAddressLine2--) | Restituisce la riga indirizzo 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Ottiene il codice paese ISO a due lettere. |
| [getHouseNo()](#getHouseNo--) | Ottiene il numero civico. |
| [getName()](#getName--) | Ottiene il nome, sia il nome e cognome di una persona fisica sia il nome dell'azienda di una persona giuridica. |
| [getPostalCode()](#getPostalCode--) | Ottiene il codice postale. |
| [getStreet()](#getStreet--) | Ottiene la via. |
| [getTown()](#getTown--) | Ottiene il comune o la città. |
| [getType()](#getType--) | Ottiene il tipo di indirizzo. |
| [hashCode()](#hashCode--) | Ottiene il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Imposta la riga indirizzo 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Imposta la riga indirizzo 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Imposta il codice paese ISO a due lettere. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Imposta il numero civico. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome, sia il nome e cognome di una persona fisica sia il nome dell'azienda di una persona giuridica. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Imposta il codice postale. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Imposta la via. |
| [setTown(String value)](#setTown-java.lang.String-) | Imposta il comune o la città. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Crea un'istanza di Indirizzo

### clear() {#clear--}
```
public void clear()
```


Cancella tutti i campi e imposta il tipo su  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'oggetto specificato è uguale all'oggetto corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare con l'oggetto corrente. |

**Returns:**
boolean -  true  se l'oggetto specificato è uguale all'oggetto corrente; altrimenti,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Restituisce la riga indirizzo 1.

La riga indirizzo 1 contiene il nome della via, il numero civico o la casella postale.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.CombinedElements  a meno che non sia già  AddressType.Structured , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per gli indirizzi a elementi combinati ed è opzionale.

Valore: La riga indirizzo 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Restituisce la riga indirizzo 2.

La riga indirizzo 2 contiene il codice postale e il comune.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.CombinedElements  a meno che non sia già  AddressType.Structured , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per gli indirizzi a elementi combinati. Per questo tipo, è obbligatorio.

Valore: La riga indirizzo 2.

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


Ottiene il codice paese ISO a due lettere.

Il codice paese è obbligatorio a meno che l'intero indirizzo contenga valori  null  o vuoti.

Valore: Il codice paese ISO.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Ottiene il numero civico.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.Structured  a meno che non sia già  AddressType.CombinedElements , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per indirizzi strutturati ed è opzionale.

Valore: Il numero civico.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome, sia il nome e cognome di una persona fisica sia il nome dell'azienda di una persona giuridica.

Valore: Il nome.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Ottiene il codice postale.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.Structured  a meno che non sia già  AddressType.CombinedElements , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

Valore: Il codice postale.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Ottiene la via.

La via deve essere specificata senza numero civico.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.Structured  a meno che non sia già  AddressType.CombinedElements , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per indirizzi strutturati ed è opzionale.

Valore: La via.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Ottiene il comune o la città.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.Structured  a meno che non sia già  AddressType.CombinedElements , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

Valore: La città o il paese.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Ottiene il tipo di indirizzo.

Il tipo di indirizzo viene impostato automaticamente impostando la via / numero civico oppure le righe di indirizzo 1 e 2. Prima di impostare i campi, il tipo di indirizzo è  *Undetermined* . Se i campi di entrambi i tipi sono impostati, il tipo di indirizzo diventa  *Conflicting* .

Valore: Il tipo di indirizzo.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottiene il codice hash per questa istanza.

**Returns:**
int - Un codice hash per l'oggetto corrente.
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


Imposta la riga indirizzo 1.

La riga indirizzo 1 contiene il nome della via, il numero civico o la casella postale.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.CombinedElements  a meno che non sia già  AddressType.Structured , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per gli indirizzi a elementi combinati ed è opzionale.

Valore: La riga indirizzo 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Imposta la riga indirizzo 2.

La riga indirizzo 2 contiene il codice postale e il comune.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.CombinedElements  a meno che non sia già  AddressType.Structured , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per gli indirizzi a elementi combinati. Per questo tipo, è obbligatorio.

Valore: La riga indirizzo 2.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Imposta il codice paese ISO a due lettere.

Il codice paese è obbligatorio a meno che l'intero indirizzo contenga valori  null  o vuoti.

Valore: Il codice paese ISO.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Imposta il numero civico.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.Structured  a meno che non sia già  AddressType.CombinedElements , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per indirizzi strutturati ed è opzionale.

Valore: Il numero civico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome, sia il nome e cognome di una persona fisica sia il nome dell'azienda di una persona giuridica.

Valore: Il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Imposta il codice postale.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.Structured  a meno che non sia già  AddressType.CombinedElements , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

Valore: Il codice postale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Imposta la via.

La via deve essere specificata senza numero civico.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.Structured  a meno che non sia già  AddressType.CombinedElements , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per indirizzi strutturati ed è opzionale.

Valore: La via.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Imposta il comune o la città.

Impostare questo campo imposta il tipo di indirizzo su  AddressType.Structured  a meno che non sia già  AddressType.CombinedElements , nel qual caso diventa  AddressType.Conflicting .

Questo campo è utilizzato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

Valore: La città o il paese.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

