---
title: Mailmark2DCodetext
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Klasse zum Codieren und Dekodieren des im Royal Mail 2D Mailmark‑Code eingebetteten Textes.
type: docs
weight: 23
url: /de/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Klasse zum Codieren und Dekodieren des im Royal Mail 2D Mailmark‑Code eingebetteten Textes.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Liefert den Barcode-Typ. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | Flagge, die angibt, welche Ebene des Rücksendeservices angefordert wird. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Enthält die Rücksende-Postleitzahl, jedoch keinen DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. |
| [getUPUCountryID()](#getUPUCountryID--) | Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen. |
| [getVersionID()](#getVersionID--) | Identifiziert die Barcode-Version, die für jede Informations‑Typ‑ID relevant ist. |
| [getclass()](#getclass--) | Identifiziert die Klasse des Elements. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Mailmark data from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optional space for use by customer. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [setItemID(int value)](#setItemID-int-) | Identifies the unique item within the Supply Chain ID. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Flagge, die angibt, welche Ebene des Rücksendeservices angefordert wird. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Enthält die Rücksende-Postleitzahl, jedoch keinen DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Identifiziert die Barcode-Version, die für jede Informations‑Typ‑ID relevant ist. |
| [setclass(String value)](#setclass-java.lang.String-) | Identifiziert die Klasse des Elements. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Create default instance of Mailmark2DCodetext class.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Liefert den Barcode-Typ.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construct codetext from Mailmark data.

**Returns:**
java.lang.String – konstruierter Codetext
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Optionaler Raum für die Nutzung durch den Kunden. Maximale Länge je Typ: Typ 7: 6 Zeichen Typ 9: 45 Zeichen Typ 29: 25 Zeichen

**Returns:**
java.lang.String - Kundeninhalt
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Kodierungsmodus des Datamatrix-Barcodes. Standardwert: DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark Type defines size of Data Matrix barcode.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Enthält die Postleitzahl der Lieferadresse mit DPS. Wenn im Inland, enthält die Postleitzahl/DP die folgende Anzahl von Zeichen: Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen) Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen). Die Postleitzahl und DPS müssen einem gültigen PAF®‑Format entsprechen.

**Returns:**
java.lang.String - die Postleitzahl der Lieferadresse mit DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Identifiziert die Royal Mail Mailmark-Barcode-Nutzlast für jeden Produkttyp. Gültige Werte: '0' – Inländisch sortiert & unsortiert 'A' – Online-Postage 'B' – Frankierung 'C' – Konsolidierung

**Returns:**
java.lang.String - Informations‑Typ‑ID
### getItemID() {#getItemID--}
```
public int getItemID()
```


Identifiziert das eindeutige Element innerhalb der Supply‑Chain‑ID. Jeder Mailmark-Barcode muss eine ID tragen, damit er mindestens 90 Tage eindeutig identifiziert werden kann. Maximalwert: 99999999.

**Returns:**
int - Element innerhalb der Supply‑Chain‑ID
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Flagge, die angibt, welche Ebene des Rücksendeservices angefordert wird.

**Returns:**
java.lang.String - RTS‑Flagge
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Enthält die Rücksende-Postleitzahl, jedoch keinen DPS. Die PLZ (ohne DPS) muss einem PAF®‑Format entsprechen.

**Returns:**
java.lang.String - Rücksende-Postleitzahl, jedoch kein DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999.

**Returns:**
int - Supply‑Chain‑ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen.

**Returns:**
java.lang.String - Länder‑ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Identifiziert die Barcode-Version, die für jede Informations‑Typ‑ID relevant ist. Gültige Werte: Derzeit '1'. '0' & '2' bis '9' und 'A' bis 'Z' sind reserviert für mögliche zukünftige Nutzung.

**Returns:**
java.lang.String - Versions‑ID
### getclass() {#getclass--}
```
public String getclass()
```


Identifiziert die Klasse des Elements. Gültige Werte: '1' – 1C (Einzelhandel) '2' – 2C (Einzelhandel) '3' – Economy (Einzelhandel) '5' – Deferred (Einzelhandel) '8' – Premium (Netzwerkzugriff) '9' – Standard (Netzwerkzugriff)

**Returns:**
java.lang.String - Klasse des Elements
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initializes Mailmark data from constructed codetext.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruiertes Codetext. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


Optionaler Raum für die Nutzung durch den Kunden. Maximale Länge je Typ: Typ 7: 6 Zeichen Typ 9: 45 Zeichen Typ 29: 25 Zeichen

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Kundeninhalt |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Kodierungsmodus des Datamatrix-Barcodes. Standardwert: EncodeMode.C40.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Größe des Data Matrix-Barcodes |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Enthält die Postleitzahl der Lieferadresse mit DPS. Wenn im Inland, enthält die Postleitzahl/DP die folgende Anzahl von Zeichen: Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen) Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen). Die Postleitzahl und DPS müssen einem gültigen PAF®‑Format entsprechen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | die Postleitzahl der Lieferadresse mit DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Identifiziert die Royal Mail Mailmark-Barcode-Nutzlast für jeden Produkttyp. Gültige Werte: '0' – Inländisch sortiert & unsortiert 'A' – Online-Postage 'B' – Frankierung 'C' – Konsolidierung

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Informationsart-ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Identifiziert das eindeutige Element innerhalb der Supply‑Chain‑ID. Jeder Mailmark-Barcode muss eine ID tragen, damit er mindestens 90 Tage eindeutig identifiziert werden kann. Maximalwert: 99999999.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | Artikel innerhalb der Lieferketten-ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Flagge, die angibt, welche Ebene des Rücksendeservices angefordert wird.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Enthält die Rücksende-Postleitzahl, jedoch keinen DPS. Die PLZ (ohne DPS) muss einem PAF®‑Format entsprechen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Rücksendepostleitzahl, aber kein DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | Lieferketten-ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Länder-ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Identifiziert die Barcode-Version, die für jede Informations‑Typ‑ID relevant ist. Gültige Werte: Derzeit '1'. '0' & '2' bis '9' und 'A' bis 'Z' sind reserviert für mögliche zukünftige Nutzung.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Versions-ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Identifiziert die Klasse des Elements. Gültige Werte: '1' – 1C (Einzelhandel) '2' – 2C (Einzelhandel) '3' – Economy (Einzelhandel) '5' – Deferred (Einzelhandel) '8' – Premium (Netzwerkzugriff) '9' – Standard (Netzwerkzugriff)

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Klasse des Artikels |

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

