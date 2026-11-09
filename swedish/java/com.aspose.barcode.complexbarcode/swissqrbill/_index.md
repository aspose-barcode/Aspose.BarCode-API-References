---
title: "SwissQRBill"
second_title: "Aspose.BarCode för Java API-referens"
description: "SwissQR-fakturadata"
type: docs
weight: 35
url: /sv/java/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

SwissQR-fakturadata
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Skapar och sätter en ISO11649-kreditorreferens från en rå sträng genom att prefixa strängen med "RF" och modulo-97-kontrollen. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om det angivna objektet är lika med det aktuella objektet. |
| [getAccount()](#getAccount--) | Hämtar kreditörens kontonummer. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Hämtar eller sätter de alternativa betalningsschemana. |
| [getAmount()](#getAmount--) | Hämtar betalningsbeloppet. |
| [getBillInformation()](#getBillInformation--) | Hämtar den ytterligare strukturerade fakturainformationen. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Hämtar kreditörens adress. |
| [getCurrency()](#getCurrency--) | Hämtar betalningsvalutan. |
| [getDebtor()](#getDebtor--) | Hämtar gäldenärens adress. |
| [getReference()](#getReference--) | Hämtar kreditörens betalningsreferens. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Hämtar det ytterligare ostrukturerade meddelandet. |
| [getVersion()](#getVersion--) | Hämtar versionen av SwissQR-fakturastandarden. |
| [hashCode()](#hashCode--) | Hämtar hash‑koden för den här instansen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Sätter kreditörens kontonummer. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Hämtar eller sätter de alternativa betalningsschemana. |
| [setAmount(double value)](#setAmount-double-) | Sätter betalningsbeloppet. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Sätter den ytterligare strukturerade fakturainformationen. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Sätter kreditörens adress. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Sätter betalningsvalutan. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Sätter gäldenärens adress. |
| [setReference(String value)](#setReference-java.lang.String-) | Sätter kreditörens betalningsreferens. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Sätter det ytterligare ostrukturerade meddelandet. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Sätter versionen av SwissQR-fakturastandarden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Skapar och sätter en ISO11649-kreditorreferens från en rå sträng genom att prefixa strängen med "RF" och modulo-97-kontrollen.

Blanksteg tas bort från referensen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rawReference | java.lang.String | Den råa referensen. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om det angivna objektet är lika med det aktuella objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med det aktuella objektet. |

**Returns:**
boolean -  true  om det angivna objektet är lika med det aktuella objektet; annars,  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


Hämtar kreditörens kontonummer.

Kontonummer måste vara giltiga IBAN för en bank i Schweiz eller Liechtenstein. Mellanslag är tillåtna i kontonumret.

Värde: Kreditorns kontonummer.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Hämtar eller sätter de alternativa betalningsschemana.

Högst två scheman med parametrar är tillåtna.

Värde: De alternativa betalningsschemana.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Hämtar betalningsbeloppet.

Giltiga värden är mellan 0.01 och 999,999,999.99.

Värde: Betalningsbeloppet.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Hämtar den ytterligare strukturerade fakturainformationen.

Värde: Den strukturerade fakturainformationen.

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


Hämtar kreditörens adress.

Värde: Kreditorns adress.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Hämtar betalningsvalutan.

Giltiga värden är "CHF" och "EUR".

Värde: Betalningsvalutan.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Hämtar gäldenärens adress.

Skuldsättaren är valfri. Om den utelämnas är både att sätta detta fält till  null  eller att ange en adress med alla  null  eller tomma värden acceptabelt.

Värde: Skuldsättarens adress.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Hämtar kreditörens betalningsreferens.

Referensen är obligatorisk för SwissQR-IBAN, d.v.s. IBAN i intervallet CHxx30000xxxxxx till CHxx31999xxxxx.

Om angiven måste referensen vara antingen en giltig SwissQR-referens (motsvarande ISR-referensform) eller en giltig kreditorreferens enligt ISO 11649 ("RFxxxx"). Båda kan innehålla mellanslag för formatering.

Värde: Kreditorns betalningsreferens.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Hämtar det ytterligare ostrukturerade meddelandet.

Värde: Det ostrukturerade meddelandet.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Hämtar versionen av SwissQR-fakturastandarden.

Värde: SwissQR-fakturastandardens version.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hash‑koden för den här instansen.

**Returns:**
int - En hash‑kod för det aktuella objektet.
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


Sätter kreditörens kontonummer.

Kontonummer måste vara giltiga IBAN för en bank i Schweiz eller Liechtenstein. Mellanslag är tillåtna i kontonumret.

Värde: Kreditorns kontonummer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Hämtar eller sätter de alternativa betalningsschemana.

Högst två scheman med parametrar är tillåtna.

Värde: De alternativa betalningsschemana.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Sätter betalningsbeloppet.

Giltiga värden är mellan 0.01 och 999,999,999.99.

Värde: Betalningsbeloppet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Sätter den ytterligare strukturerade fakturainformationen.

Värde: Den strukturerade fakturainformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Sätter kreditörens adress.

Värde: Kreditorns adress.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Sätter betalningsvalutan.

Giltiga värden är "CHF" och "EUR".

Värde: Betalningsvalutan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Sätter gäldenärens adress.

Skuldsättaren är valfri. Om den utelämnas är både att sätta detta fält till  null  eller att ange en adress med alla  null  eller tomma värden acceptabelt.

Värde: Skuldsättarens adress.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Sätter kreditörens betalningsreferens.

Referensen är obligatorisk för SwissQR-IBAN, d.v.s. IBAN i intervallet CHxx30000xxxxxx till CHxx31999xxxxx.

Om angiven måste referensen vara antingen en giltig SwissQR-referens (motsvarande ISR-referensform) eller en giltig kreditorreferens enligt ISO 11649 ("RFxxxx"). Båda kan innehålla mellanslag för formatering.

Värde: Kreditorns betalningsreferens.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Sätter det ytterligare ostrukturerade meddelandet.

Värde: Det ostrukturerade meddelandet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Sätter versionen av SwissQR-fakturastandarden.

Värde: SwissQR-fakturastandardens version.

**Parameters:**
| Parameter | Typ | Beskrivning |
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
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

