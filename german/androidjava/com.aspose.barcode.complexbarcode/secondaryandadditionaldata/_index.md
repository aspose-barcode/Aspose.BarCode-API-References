---
title: SecondaryAndAdditionalData
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Klasse zum Speichern sekundärer und zusätzlicher HIBC LIC‑Daten.
type: docs
weight: 35
url: /de/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

Klasse zum Speichern sekundärer und zusätzlicher HIBC LIC‑Daten.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen  SecondaryAndAdditionalData  Wert entspricht. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Identifiziert das Herstellungsdatum. |
| [getExpiryDate()](#getExpiryDate--) | Identifiziert das Verfallsdatum. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifiziert das Format des Verfallsdatums. |
| [getLotNumber()](#getLotNumber--) | Identifiziert Los- oder Chargennummer. |
| [getQuantity()](#getQuantity--) | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. |
| [getSerialNumber()](#getSerialNumber--) | Identifiziert die Seriennummer. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | Instanziiert sekundäre und zusätzliche Ergänzungsdaten aus dem Zeichenkettenformat gemäß HIBC LIC Spezifikation. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Identifiziert das Herstellungsdatum. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Identifiziert das Verfallsdatum. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Identifiziert das Format des Verfallsdatums. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifiziert Los- oder Chargennummer. |
| [setQuantity(int value)](#setQuantity-int-) | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifiziert die Seriennummer. |
| [toString()](#toString--) | Konvertiert Daten in das Zeichenkettenformat gemäß HIBC LIC Spezifikation. |
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


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen  SecondaryAndAdditionalData  Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein  SecondaryAndAdditionalData  Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
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


Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Identifiziert das Verfallsdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Identifiziert das Format des Verfallsdatums.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Identifiziert Los- oder Chargennummer. Los-/Chargennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. .

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Die Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Identifiziert die Seriennummer. Die Seriennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
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


Instanziiert sekundäre und zusätzliche Ergänzungsdaten aus dem Zeichenkettenformat gemäß HIBC LIC Spezifikation.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | Formatierte Zeichenkette. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: DateTime.MinValue

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Identifiziert das Verfallsdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Identifiziert das Format des Verfallsdatums.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Identifiziert Los- oder Chargennummer. Los-/Chargennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. .

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Die Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: -1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Identifiziert die Seriennummer. Die Seriennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Konvertiert Daten in das Zeichenkettenformat gemäß HIBC LIC Spezifikation.

**Returns:**
java.lang.String - Formatierte Zeichenkette.
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

