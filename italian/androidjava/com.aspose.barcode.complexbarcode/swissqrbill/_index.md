---
title: SwissQRBill
second_title: Aspose.BarCode per Android via Java API Reference
description: Dati della fattura SwissQR
type: docs
weight: 36
url: /it/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

Dati della fattura SwissQR
## Methods

| Method | Descrizione |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Crea e imposta un riferimento creditore ISO11649 da una stringa grezza aggiungendo il prefisso "RF" alla stringa e il checksum modulo 97. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'oggetto specificato è uguale all'oggetto corrente. |
| [getAccount()](#getAccount--) | Ottiene il numero di conto del creditore. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Ottiene o imposta gli schemi di pagamento alternativi. |
| [getAmount()](#getAmount--) | Ottiene l'importo del pagamento. |
| [getBillInformation()](#getBillInformation--) | Ottiene le informazioni aggiuntive strutturate della fattura. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Ottiene l'indirizzo del creditore. |
| [getCurrency()](#getCurrency--) | Ottiene la valuta del pagamento. |
| [getDebtor()](#getDebtor--) | Ottiene l'indirizzo del debitore. |
| [getReference()](#getReference--) | Ottiene il riferimento di pagamento del creditore. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Ottiene il messaggio non strutturato aggiuntivo. |
| [getVersion()](#getVersion--) | Ottiene la versione dello standard di fatturazione SwissQR. |
| [hashCode()](#hashCode--) | Ottiene il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Imposta il numero di conto del creditore. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Ottiene o imposta gli schemi di pagamento alternativi. |
| [setAmount(double value)](#setAmount-double-) | Imposta l'importo del pagamento. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Imposta le informazioni aggiuntive strutturate della fattura. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Imposta l'indirizzo del creditore. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Imposta la valuta del pagamento. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Imposta l'indirizzo del debitore. |
| [setReference(String value)](#setReference-java.lang.String-) | Imposta il riferimento di pagamento del creditore. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Imposta il messaggio non strutturato aggiuntivo. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Imposta la versione dello standard di fatturazione SwissQR. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Crea e imposta un riferimento creditore ISO11649 da una stringa grezza aggiungendo il prefisso "RF" alla stringa e il checksum modulo 97.

Gli spazi bianchi vengono rimossi dal riferimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| rawReference | java.lang.String | Il riferimento grezzo. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'oggetto specificato è uguale all'oggetto corrente.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare con l'oggetto corrente. |

**Returns:**
boolean -  true  se l'oggetto specificato è uguale all'oggetto corrente; altrimenti,  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


Ottiene il numero di conto del creditore.

I numeri di conto devono essere IBAN validi di una banca della Svizzera o del Liechtenstein. Gli spazi sono consentiti nel numero di conto.

Valore: Il numero di conto del creditore.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Ottiene o imposta gli schemi di pagamento alternativi.

È consentito un massimo di due schemi con parametri.

Valore: Gli schemi di pagamento alternativi.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Ottiene l'importo del pagamento.

I valori validi sono compresi tra 0.01 e 999,999,999.99.

Valore: L'importo del pagamento.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Ottiene le informazioni aggiuntive strutturate della fattura.

Valore: Le informazioni strutturate della fattura.

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


Ottiene l'indirizzo del creditore.

Valore: L'indirizzo del creditore.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Ottiene la valuta del pagamento.

I valori validi sono "CHF" e "EUR".

Valore: La valuta del pagamento.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Ottiene l'indirizzo del debitore.

Il debitore è facoltativo. Se viene omesso, sia impostare questo campo a  null  sia impostare un indirizzo con tutti i valori  null  o vuoti è accettabile.

Valore: L'indirizzo del debitore.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Ottiene il riferimento di pagamento del creditore.

Il riferimento è obbligatorio per gli IBAN SwissQR, cioè gli IBAN nell'intervallo CHxx30000xxxxxx fino a CHxx31999xxxxx.

Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente al modulo di riferimento ISR) o un riferimento del creditore valido secondo ISO 11649 ("RFxxxx"). Entrambi possono contenere spazi per la formattazione.

Valore: Il riferimento di pagamento del creditore.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Ottiene il messaggio non strutturato aggiuntivo.

Valore: Il messaggio non strutturato.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Ottiene la versione dello standard di fatturazione SwissQR.

Valore: La versione standard della fattura SwissQR.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
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




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


Imposta il numero di conto del creditore.

I numeri di conto devono essere IBAN validi di una banca della Svizzera o del Liechtenstein. Gli spazi sono consentiti nel numero di conto.

Valore: Il numero di conto del creditore.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Ottiene o imposta gli schemi di pagamento alternativi.

È consentito un massimo di due schemi con parametri.

Valore: Gli schemi di pagamento alternativi.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Imposta l'importo del pagamento.

I valori validi sono compresi tra 0.01 e 999,999,999.99.

Valore: L'importo del pagamento.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Imposta le informazioni aggiuntive strutturate della fattura.

Valore: Le informazioni strutturate della fattura.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Imposta l'indirizzo del creditore.

Valore: L'indirizzo del creditore.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Imposta la valuta del pagamento.

I valori validi sono "CHF" e "EUR".

Valore: La valuta del pagamento.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Imposta l'indirizzo del debitore.

Il debitore è facoltativo. Se viene omesso, sia impostare questo campo a  null  sia impostare un indirizzo con tutti i valori  null  o vuoti è accettabile.

Valore: L'indirizzo del debitore.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Imposta il riferimento di pagamento del creditore.

Il riferimento è obbligatorio per gli IBAN SwissQR, cioè gli IBAN nell'intervallo CHxx30000xxxxxx fino a CHxx31999xxxxx.

Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente al modulo di riferimento ISR) o un riferimento del creditore valido secondo ISO 11649 ("RFxxxx"). Entrambi possono contenere spazi per la formattazione.

Valore: Il riferimento di pagamento del creditore.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Imposta il messaggio non strutturato aggiuntivo.

Valore: Il messaggio non strutturato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Imposta la versione dello standard di fatturazione SwissQR.

Valore: La versione standard della fattura SwissQR.

**Parameters:**
| Parameter | Type | Descrizione |
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

