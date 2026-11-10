---
title: "Klasse USADriveIdCodetext"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext Klasse. Klasse zum Codieren und Dekodieren des in den USA-Führerschein-PDF417-Code eingebetteten Textes."
type: docs
weight: 810
url: /de/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Klasse zum Codieren und Dekodieren des in den USA‑Führerschein‑PDF417‑Code eingebetteten Textes.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | AAMVA Versionsnummer 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Diese Nummer identifiziert eindeutig die ausstellende Jurisdiktion und kann durch Kontaktaufnahme mit der ISO-Ausstellungsbehörde (AAMVA) erhalten werden. Die vollständige 6-stellige IIN sollte codiert werden. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Jurisdiktionsspezifische Felder |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Jurisdiktionsversionsnummer 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Pflichtfelder (Felder) der Karte |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Anzahl 00-99 der Unterdateien |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Optionale Elemente (Felder) der Karte |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. Wichtig: Nur den Typ festlegen, Offset und Länge werden automatisch gesetzt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Gibt den Barcode-Typ von USA DL (Pdf417) zurück |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Erstellt Codetext aus USA DL-Daten |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Initialisiert USA DL-Objekt aus Codetext |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Speichert in XML |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Pflichtfelder (Felder) der Karte |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Optionale Elemente (Felder) der Karte |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | USA DL Subdateieigenschaften, Offset und Länge werden automatisch gesetzt. |

### Siehe auch

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


