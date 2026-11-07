---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext class"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext class. Klasse zum Kodieren und Dekodieren des im Royal Mail 2D Mailmark-Code eingebetteten Textes in C++."
type: docs
weight: 1400
url: /de/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Klasse zum Codieren und Dekodieren des im Royal Mail 2D Mailmark-Code eingebetteten Textes.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_Class](./get_class/)() const | Identifiziert die Klasse des Elements. |
| [get_CustomerContent](./get_customercontent/)() const | Optionaler Speicherplatz für die Verwendung durch den Kunden. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Kodiermodus des Datamatrix-Barcodes. Standardwert: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | Der 2D Mailmark-Typ definiert die Größe des Data Matrix-Barcodes. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Enthält die Postleitzahl der Liefer-[Adresse](../address/) mit DPS. Wenn im Inland, enthält die Postleitzahl/DP die folgende Anzahl von Zeichen: Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen) Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen). Die Postleitzahl und DPS müssen einem gültigen PAF®‑Format entsprechen. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Identifiziert die Royal Mail Mailmark-Barcode-Nutzlast für jeden Produkttyp. |
| [get_ItemID](./get_itemid/)() const | Identifiziert das eindeutige Element innerhalb der Supply-Chain-ID. Jeder Mailmark-Barcode muss eine ID tragen, damit er mindestens 90 Tage lang eindeutig identifiziert werden kann. Maximalwert: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Enthält die Rücksende-Postleitzahl, jedoch keinen DPS. Die PLZ (ohne DPS) muss einem PAF®‑Format entsprechen. |
| [get_RTSFlag](./get_rtsflag/)() const | Flag, das angibt, welche Ebene des Rücksende-Services angefordert wird. |
| [get_SupplyChainID](./get_supplychainid/)() const | Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen. |
| [get_VersionID](./get_versionid/)() const | Identifiziert die Barcode-Version, die für jede Informations-Typ-ID relevant ist. |
| [GetBarcodeType](./getbarcodetype/)() override | Liest den Barcode-Typ. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Kodetext aus Mailmark-Daten erstellen. |
| [InitFromString](./initfromstring/)(System::String) override | Initialisiert Mailmark-Daten aus dem erstellten Kodetext. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Konstruktor. Erstellt eine Standardinstanz der Klasse [Mailmark2DCodetext](./). |
| [set_Class](./set_class/)(System::String) | Identifiziert die Klasse des Elements. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Optionaler Speicherplatz für die Verwendung durch den Kunden. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Kodiermodus des Datamatrix-Barcodes. Standardwert: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | Der 2D Mailmark-Typ definiert die Größe des Data Matrix-Barcodes. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Enthält die Postleitzahl der Liefer-[Adresse](../address/) mit DPS. Wenn im Inland, enthält die Postleitzahl/DP die folgende Anzahl von Zeichen: Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen) Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen). Die Postleitzahl und DPS müssen einem gültigen PAF®‑Format entsprechen. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Identifiziert die Royal Mail Mailmark-Barcode-Nutzlast für jeden Produkttyp. |
| [set_ItemID](./set_itemid/)(int32_t) | Identifiziert das eindeutige Element innerhalb der Supply-Chain-ID. Jeder Mailmark-Barcode muss eine ID tragen, damit er mindestens 90 Tage lang eindeutig identifiziert werden kann. Maximalwert: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Enthält die Rücksende-Postleitzahl, jedoch keinen DPS. Die PLZ (ohne DPS) muss einem PAF®‑Format entsprechen. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | Flag, das angibt, welche Ebene des Rücksende-Services angefordert wird. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen. |
| [set_VersionID](./set_versionid/)(System::String) | Identifiziert die Barcode-Version, die für jede Informations-Typ-ID relevant ist. |
## Siehe auch

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
