---
title: USADriveIdCodetext
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Klasse zum Codieren und Dekodieren des im USA-Führerschein‑PDF417‑Code eingebetteten Textes.
type: docs
weight: 38
url: /de/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

Klasse zum Codieren und Dekodieren des im USA-Führerschein‑PDF417‑Code eingebetteten Textes.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | Standardkonstruktor |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | AAMVA Versionsnummer 00‑99 |
| [getBarcodeType()](#getBarcodeType--) | Gibt den Barcode‑Typ des USA‑DL (Pdf417) zurück |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Erstelle Codetext aus USA‑DL‑Daten |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | Diese Nummer identifiziert die ausstellende Jurisdiktion eindeutig und kann durch Kontaktaufnahme mit der ISO‑Ausstellungsbehörde (AAMVA) erhalten werden. |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | Jurisdiktionsspezifische Felder |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | Jurisdiktionsversionsnummer 00‑99 |
| [getMandatoryElements()](#getMandatoryElements--) | Obligatorische Elemente (Felder) der Karte |
| [getNumberOfEntries()](#getNumberOfEntries--) | Anzahl 00‑99 der Unterdateien |
| [getOptionalElements()](#getOptionalElements--) | Optionale Elemente (Felder) der Karte |
| [getSubfileDesignator()](#getSubfileDesignator--) | Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialisiere USA‑DL‑Objekt aus Codetext |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | Speichert in XML |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | AAMVA Versionsnummer 00‑99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | Diese Nummer identifiziert die ausstellende Jurisdiktion eindeutig und kann durch Kontaktaufnahme mit der ISO‑Ausstellungsbehörde (AAMVA) erhalten werden. |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | Jurisdiktionsspezifische Felder |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | Jurisdiktionsversionsnummer 00‑99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | Obligatorische Elemente (Felder) der Karte |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | Anzahl 00‑99 der Unterdateien |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | Optionale Elemente (Felder) der Karte |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


Standardkonstruktor

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
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


AAMVA Versionsnummer 00‑99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Gibt den Barcode‑Typ des USA‑DL (Pdf417) zurück

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


Erstelle Codetext aus USA‑DL‑Daten

**Returns:**
java.lang.String – konstruierter Codetext
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


Diese Nummer identifiziert die ausstellende Jurisdiktion eindeutig und kann durch Kontaktaufnahme mit der ISO‑Ausstellungsbehörde (AAMVA) erhalten werden. Das vollständige 6‑stellige IIN sollte kodiert werden.

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


Jurisdiktionsspezifische Felder

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


Jurisdiktionsversionsnummer 00‑99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


Obligatorische Elemente (Felder) der Karte

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


Anzahl 00‑99 der Unterdateien

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


Optionale Elemente (Felder) der Karte

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. Wichtig: Nur den Typ setzen, Offset und Länge werden automatisch gesetzt.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


Initialisiere USA‑DL‑Objekt aus Codetext

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruktierter Codetext |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


Speichert in XML

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | Stream zum Speichern |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


AAMVA Versionsnummer 00‑99

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


Diese Nummer identifiziert die ausstellende Jurisdiktion eindeutig und kann durch Kontaktaufnahme mit der ISO‑Ausstellungsbehörde (AAMVA) erhalten werden. Das vollständige 6‑stellige IIN sollte kodiert werden.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


Jurisdiktionsspezifische Felder

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


Jurisdiktionsversionsnummer 00‑99

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


Obligatorische Elemente (Felder) der Karte

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


Anzahl 00‑99 der Unterdateien

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


Optionale Elemente (Felder) der Karte

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. Wichtig: Nur den Typ setzen, Offset und Länge werden automatisch gesetzt.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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

