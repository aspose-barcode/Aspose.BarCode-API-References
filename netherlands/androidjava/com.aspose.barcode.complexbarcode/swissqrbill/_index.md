---
title: "SwissQRBill"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: "SwissQR-factuurgegevens"
type: docs
weight: 35
url: /nl/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

SwissQR-factuurgegevens
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Maakt en stelt een ISO11649 crediteurreferentie in vanuit een ruwe string door de string te prefixen met "RF" en de modulo 97-controlegetal. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven object gelijk is aan het huidige object. |
| [getAccount()](#getAccount--) | Verkrijgt het rekeningnummer van de crediteur. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Verkrijgt of stelt de alternatieve betaalschema's in. |
| [getAmount()](#getAmount--) | Verkrijgt het betalingsbedrag. |
| [getBillInformation()](#getBillInformation--) | Verkrijgt de aanvullende gestructureerde factuurinformatie. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Verkrijgt het adres van de crediteur. |
| [getCurrency()](#getCurrency--) | Verkrijgt de betaalvaluta. |
| [getDebtor()](#getDebtor--) | Haalt het debiteuradres op. |
| [getReference()](#getReference--) | Haalt de crediteurbetalingsreferentie op. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Haalt het aanvullende ongestructureerde bericht op. |
| [getVersion()](#getVersion--) | Haalt de versie van de SwissQR-factuurstandaard op. |
| [hashCode()](#hashCode--) | Haalt de hashcode op voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Stelt het rekeningnummer van de crediteur in. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Verkrijgt of stelt de alternatieve betaalschema's in. |
| [setAmount(double value)](#setAmount-double-) | Stelt het betalingsbedrag in. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Stelt de aanvullende gestructureerde factuurinformatie in. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Stelt het crediteuradres in. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Stelt de betaalvaluta in. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Stelt het debiteuradres in. |
| [setReference(String value)](#setReference-java.lang.String-) | Stelt de crediteurbetalingsreferentie in. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Stelt het aanvullende ongestructureerde bericht in. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Stelt de versie van de SwissQR-factuurstandaard in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Maakt en stelt een ISO11649 crediteurreferentie in vanuit een ruwe string door de string te prefixen met "RF" en de modulo 97-controlegetal.

Witruimte wordt uit de referentie verwijderd

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rawReference | java.lang.String | De ruwe referentie. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven object gelijk is aan het huidige object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken met het huidige object. |

**Returns:**
boolean -  true  als het opgegeven object gelijk is aan het huidige object; anders,  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


Verkrijgt het rekeningnummer van de crediteur.

Rekeningnummers moeten geldige IBAN's zijn van een bank uit Zwitserland of Liechtenstein. Spaties zijn toegestaan in het rekeningnummer.

Waarde: Het rekeningnummer van de crediteur.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Verkrijgt of stelt de alternatieve betaalschema's in.

Er mogen maximaal twee schema's met parameters worden gebruikt.

Waarde: De alternatieve betalingsschema's.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Verkrijgt het betalingsbedrag.

Geldige waarden liggen tussen 0,01 en 999.999.999,99.

Waarde: Het betalingsbedrag.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Verkrijgt de aanvullende gestructureerde factuurinformatie.

Waarde: De gestructureerde factuurinformatie.

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


Verkrijgt het adres van de crediteur.

Waarde: Het crediteuradres.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Verkrijgt de betaalvaluta.

Geldige waarden zijn "CHF" en "EUR".

Waarde: De betaalvaluta.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Haalt het debiteuradres op.

De schuldenaar is optioneel. Als het wordt weggelaten, is zowel het instellen van dit veld op  null  als het instellen van een adres met alle  null  of lege waarden ok.

Waarde: Het adres van de schuldenaar.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Haalt de crediteurbetalingsreferentie op.

De referentie is verplicht voor SwissQR IBAN's, d.w.z. IBAN's in het bereik CHxx30000xxxxxx tot CHxx31999xxxxx.

Indien gespecificeerd, moet de referentie ofwel een geldige SwissQR-referentie (overeenkomend met ISR-referentieformulier) of een geldige crediteurreferentie volgens ISO 11649 ("RFxxxx") zijn. Beide mogen spaties bevatten voor opmaak.

Waarde: De crediteurbetalingsreferentie.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Haalt het aanvullende ongestructureerde bericht op.

Waarde: Het ongestructureerde bericht.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Haalt de versie van de SwissQR-factuurstandaard op.

Waarde: De SwissQR-factuurstandaardversie.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Haalt de hashcode op voor deze instantie.

**Returns:**
int - Een hashcode voor het huidige object.
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


Stelt het rekeningnummer van de crediteur in.

Rekeningnummers moeten geldige IBAN's zijn van een bank uit Zwitserland of Liechtenstein. Spaties zijn toegestaan in het rekeningnummer.

Waarde: Het rekeningnummer van de crediteur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Verkrijgt of stelt de alternatieve betaalschema's in.

Er mogen maximaal twee schema's met parameters worden gebruikt.

Waarde: De alternatieve betalingsschema's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Stelt het betalingsbedrag in.

Geldige waarden liggen tussen 0,01 en 999.999.999,99.

Waarde: Het betalingsbedrag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Stelt de aanvullende gestructureerde factuurinformatie in.

Waarde: De gestructureerde factuurinformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Stelt het crediteuradres in.

Waarde: Het crediteuradres.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Stelt de betaalvaluta in.

Geldige waarden zijn "CHF" en "EUR".

Waarde: De betaalvaluta.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Stelt het debiteuradres in.

De schuldenaar is optioneel. Als het wordt weggelaten, is zowel het instellen van dit veld op  null  als het instellen van een adres met alle  null  of lege waarden ok.

Waarde: Het adres van de schuldenaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Stelt de crediteurbetalingsreferentie in.

De referentie is verplicht voor SwissQR IBAN's, d.w.z. IBAN's in het bereik CHxx30000xxxxxx tot CHxx31999xxxxx.

Indien gespecificeerd, moet de referentie ofwel een geldige SwissQR-referentie (overeenkomend met ISR-referentieformulier) of een geldige crediteurreferentie volgens ISO 11649 ("RFxxxx") zijn. Beide mogen spaties bevatten voor opmaak.

Waarde: De crediteurbetalingsreferentie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Stelt het aanvullende ongestructureerde bericht in.

Waarde: Het ongestructureerde bericht.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Stelt de versie van de SwissQR-factuurstandaard in.

Waarde: De SwissQR-factuurstandaardversie.

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

