---
title: SwissQRBill
second_title: Aspose.BarCode für Android via Java API-Referenz
description: SwissQR‑Rechnungsdaten
type: docs
weight: 36
url: /de/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

SwissQR‑Rechnungsdaten
## Methods

| Method | Beschreibung |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Erstellt und setzt eine ISO11649-Gläubigerreferenz aus einem Rohstring, indem der String mit "RF" und der Modulo‑97-Prüfsumme versehen wird. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist. |
| [getAccount()](#getAccount--) | Liest die Kontonummer des Gläubigers. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Liest oder setzt die alternativen Zahlungsschemata. |
| [getAmount()](#getAmount--) | Liest den Zahlungsbetrag. |
| [getBillInformation()](#getBillInformation--) | Liest die zusätzlichen strukturierten Rechnungsinformationen. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Liest die Gläubigeradresse. |
| [getCurrency()](#getCurrency--) | Liest die Zahlungswährung. |
| [getDebtor()](#getDebtor--) | Liest die Schuldneradresse. |
| [getReference()](#getReference--) | Liest die Zahlungsreferenz des Gläubigers. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Liest die zusätzliche unstrukturierte Nachricht. |
| [getVersion()](#getVersion--) | Liest die Version des SwissQR-Rechnungsstandards. |
| [hashCode()](#hashCode--) | Ermittelt den Hashcode für diese Instanz. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Setzt die Kontonummer des Gläubigers. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Liest oder setzt die alternativen Zahlungsschemata. |
| [setAmount(double value)](#setAmount-double-) | Setzt den Zahlungsbetrag. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Setzt die zusätzlichen strukturierten Rechnungsinformationen. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Setzt die Gläubigeradresse. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Setzt die Zahlungswährung. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Setzt die Schuldneradresse. |
| [setReference(String value)](#setReference-java.lang.String-) | Setzt die Zahlungsreferenz des Gläubigers. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Setzt die zusätzliche unstrukturierte Nachricht. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Setzt die Version des SwissQR-Rechnungsstandards. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Erstellt und setzt eine ISO11649-Gläubigerreferenz aus einem Rohstring, indem der String mit "RF" und der Modulo‑97-Prüfsumme versehen wird.

Leerzeichen werden aus der Referenz entfernt.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| rawReference | java.lang.String | Die rohe Referenz. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt, das mit dem aktuellen Objekt verglichen werden soll. |

**Returns:**
boolean -  true  wenn das angegebene Objekt gleich dem aktuellen Objekt ist; andernfalls,  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


Liest die Kontonummer des Gläubigers.

Kontonummern müssen gültige IBANs einer Bank der Schweiz oder Liechtensteins sein. Leerzeichen sind in der Kontonummer erlaubt.

Wert: Die Kontonummer des Gläubigers.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Liest oder setzt die alternativen Zahlungsschemata.

Es sind maximal zwei Schemata mit Parametern zulässig.

Wert: Die alternativen Zahlungsschemata.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Liest den Zahlungsbetrag.

Gültige Werte liegen zwischen 0,01 und 999.999.999,99.

Wert: Der Zahlungsbetrag.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Liest die zusätzlichen strukturierten Rechnungsinformationen.

Wert: Die strukturierten Rechnungsinformationen.

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


Liest die Gläubigeradresse.

Wert: Die Gläubigeradresse.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Liest die Zahlungswährung.

Gültige Werte sind "CHF" und "EUR".

Wert: Die Zahlungswährung.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Liest die Schuldneradresse.

Der Schuldner ist optional. Wenn er weggelassen wird, ist sowohl das Setzen dieses Feldes auf  null  als auch das Setzen einer Adresse mit allen  null  oder leeren Werten in Ordnung.

Wert: Die Schuldneradresse.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Liest die Zahlungsreferenz des Gläubigers.

Die Referenz ist für SwissQR-IBANs obligatorisch, d.h. IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx.

Falls angegeben, muss die Referenz entweder eine gültige SwissQR-Referenz (entsprechend dem ISR-Referenzformat) oder eine gültige Gläubigerreferenz gemäß ISO 11649 ("RFxxxx") sein. Beide können zur Formatierung Leerzeichen enthalten.

Wert: Die Gläubigerzahlungsreferenz.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Liest die zusätzliche unstrukturierte Nachricht.

Wert: Die unstrukturierte Nachricht.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Liest die Version des SwissQR-Rechnungsstandards.

Wert: Die SwissQR-Rechnungsstandardversion.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ermittelt den Hashcode für diese Instanz.

**Returns:**
int - Ein Hashcode für das aktuelle Objekt.
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


Setzt die Kontonummer des Gläubigers.

Kontonummern müssen gültige IBANs einer Bank der Schweiz oder Liechtensteins sein. Leerzeichen sind in der Kontonummer erlaubt.

Wert: Die Kontonummer des Gläubigers.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Liest oder setzt die alternativen Zahlungsschemata.

Es sind maximal zwei Schemata mit Parametern zulässig.

Wert: Die alternativen Zahlungsschemata.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Setzt den Zahlungsbetrag.

Gültige Werte liegen zwischen 0,01 und 999.999.999,99.

Wert: Der Zahlungsbetrag.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Setzt die zusätzlichen strukturierten Rechnungsinformationen.

Wert: Die strukturierten Rechnungsinformationen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Setzt die Gläubigeradresse.

Wert: Die Gläubigeradresse.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Setzt die Zahlungswährung.

Gültige Werte sind "CHF" und "EUR".

Wert: Die Zahlungswährung.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Setzt die Schuldneradresse.

Der Schuldner ist optional. Wenn er weggelassen wird, ist sowohl das Setzen dieses Feldes auf  null  als auch das Setzen einer Adresse mit allen  null  oder leeren Werten in Ordnung.

Wert: Die Schuldneradresse.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Setzt die Zahlungsreferenz des Gläubigers.

Die Referenz ist für SwissQR-IBANs obligatorisch, d.h. IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx.

Falls angegeben, muss die Referenz entweder eine gültige SwissQR-Referenz (entsprechend dem ISR-Referenzformat) oder eine gültige Gläubigerreferenz gemäß ISO 11649 ("RFxxxx") sein. Beide können zur Formatierung Leerzeichen enthalten.

Wert: Die Gläubigerzahlungsreferenz.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Setzt die zusätzliche unstrukturierte Nachricht.

Wert: Die unstrukturierte Nachricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Setzt die Version des SwissQR-Rechnungsstandards.

Wert: Die SwissQR-Rechnungsstandardversion.

**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

