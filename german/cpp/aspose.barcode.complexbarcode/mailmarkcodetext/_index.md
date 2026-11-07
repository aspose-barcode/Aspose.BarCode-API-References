---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext Klasse"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext Klasse. Klasse zum Kodieren und Dekodieren des in den 4‑Stufen Royal Mailmark‑Code eingebetteten Textes in C++."
type: docs
weight: 1500
url: /de/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


Klasse zum Codieren und Dekodieren des im 4‑stufigen Royal Mailmark-Code eingebetteten Textes.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Nutzung) "5" - Deferred (Einzelhandel) "6" - Air (Einzelhandel) (für potenzielle zukünftige Nutzung) "7" - Surface (Einzelhandel) (für potenzielle zukünftige Nutzung) "8" - Premium (Netzwerkzugriff) "9" - Standard (Netzwerkzugriff) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | PC und DP müssen dem PAF-Format entsprechen. Neunstelliges Zeichenkette, die den internationalen "XY11     " (beachten Sie die 5 nachfolgenden Leerzeichen) bezeichnet, oder ein Muster von Zeichen, das einen inländischen Sortiercode bezeichnet. Ein inländischer Sortiercode besteht aus einer äußeren Postleitzahl, einer inneren Postleitzahl und einem Delivery Point Suffix. |
| [get_Format](./get_format/)() const | "0" – Null oder Test "1" – Brief "2" – Großbrief |
| [get_ItemID](./get_itemid/)() const | Maximalwert ist 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | Maximalwerte sind 99 für Barcode C und 999999 für Barcode L. |
| [get_VersionID](./get_versionid/)() const | Derzeit "1" – Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z für zukünftige Verwendung reserviert) |
| [GetBarcodeType](./getbarcodetype/)() override | Liest den Barcode-Typ. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Kodetext aus Mailmark-Daten erstellen. |
| [InitFromString](./initfromstring/)(System::String) override | Initialisiert Mailmark-Daten aus dem erstellten Kodetext. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Initialisiert eine neue Instanz der Klasse [MailmarkCodetext](./). |
| [set_Class](./set_class/)(System::String) | "0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Nutzung) "5" - Deferred (Einzelhandel) "6" - Air (Einzelhandel) (für potenzielle zukünftige Nutzung) "7" - Surface (Einzelhandel) (für potenzielle zukünftige Nutzung) "8" - Premium (Netzwerkzugriff) "9" - Standard (Netzwerkzugriff) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | PC und DP müssen dem PAF-Format entsprechen. Neunstelliges Zeichenkette, die den internationalen "XY11     " (beachten Sie die 5 nachfolgenden Leerzeichen) bezeichnet, oder ein Muster von Zeichen, das einen inländischen Sortiercode bezeichnet. Ein inländischer Sortiercode besteht aus einer äußeren Postleitzahl, einer inneren Postleitzahl und einem Delivery Point Suffix. |
| [set_Format](./set_format/)(int32_t) | "0" – Null oder Test "1" – Brief "2" – Großbrief |
| [set_ItemID](./set_itemid/)(int32_t) | Maximalwert ist 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Maximalwerte sind 99 für Barcode C und 999999 für Barcode L. |
| [set_VersionID](./set_versionid/)(int32_t) | Derzeit "1" – Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z für zukünftige Verwendung reserviert) |
## Siehe auch

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
