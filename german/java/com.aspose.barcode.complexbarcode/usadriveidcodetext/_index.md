---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren des im US-Führerschein‑PDF417‑Code eingebetteten Textes."
type: docs
weight: 37
url: /de/java/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

Klasse zum Kodieren und Dekodieren des im US-Führerschein‑PDF417‑Code eingebetteten Textes.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | Standardkonstruktor |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | AAMVA Versionsnummer 00‑99 |
| [getBarcodeType()](#getBarcodeType--) | Gibt den Barcode-Typ des USA‑DL (Pdf417) zurück. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Erstelle Codetext aus USA‑DL‑Daten |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | Diese Nummer identifiziert eindeutig die ausstellende Gerichtsbarkeit und kann durch Kontaktaufnahme mit der ISO Issuing Authority(AAMVA) erhalten werden. |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | Jurisdiktionsspezifische Felder |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | Jurisdiktionsversionsnummer 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | Obligatorische Elemente (Felder) der Karte |
| [getNumberOfEntries()](#getNumberOfEntries--) | Nummer 00-99 der Unterdateien |
| [getOptionalElements()](#getOptionalElements--) | Optionale Elemente (Felder) der Karte |
| [getSubfileDesignator()](#getSubfileDesignator--) | Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | USA DL-Objekt aus Codetext initialisieren |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | Speichert in XML |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | AAMVA Versionsnummer 00‑99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | Diese Nummer identifiziert eindeutig die ausstellende Gerichtsbarkeit und kann durch Kontaktaufnahme mit der ISO Issuing Authority(AAMVA) erhalten werden. |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | Jurisdiktionsspezifische Felder |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | Jurisdiktionsversionsnummer 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | Obligatorische Elemente (Felder) der Karte |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | Nummer 00-99 der Unterdateien |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
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


Gibt den Barcode-Typ des USA‑DL (Pdf417) zurück.

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
java.lang.String - Erstellter Codetext
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


Diese Nummer identifiziert eindeutig die ausstellende Gerichtsbarkeit und kann durch Kontaktaufnahme mit der ISO Issuing Authority(AAMVA) erhalten werden. Die vollständige 6‑stellige IIN sollte codiert werden.

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


Jurisdiktionsversionsnummer 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


Obligatorische Elemente (Felder) der Karte

**Returns:**
[MandatoryFields](../../com.aspose.barcode.complexbarcode/mandatoryfields)
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


Nummer 00-99 der Unterdateien

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


Optionale Elemente (Felder) der Karte

**Returns:**
[OptionalFields](../../com.aspose.barcode.complexbarcode/optionalfields)
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. Wichtig: Nur den Typ festlegen, Offset und Länge werden automatisch gesetzt.

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


USA DL-Objekt aus Codetext initialisieren

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Erzeugter Codetext |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | Stream zum Speichern |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


AAMVA Versionsnummer 00‑99

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


Diese Nummer identifiziert eindeutig die ausstellende Gerichtsbarkeit und kann durch Kontaktaufnahme mit der ISO Issuing Authority(AAMVA) erhalten werden. Die vollständige 6‑stellige IIN sollte codiert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


Jurisdiktionsspezifische Felder

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


Jurisdiktionsversionsnummer 00-99

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


Obligatorische Elemente (Felder) der Karte

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MandatoryFields](../../com.aspose.barcode.complexbarcode/mandatoryfields) |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


Nummer 00-99 der Unterdateien

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


Optionale Elemente (Felder) der Karte

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [OptionalFields](../../com.aspose.barcode.complexbarcode/optionalfields) |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. Wichtig: Nur den Typ festlegen, Offset und Länge werden automatisch gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
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
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

