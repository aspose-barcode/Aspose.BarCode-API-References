---
title: "Methode"
linktitle: "CleanValue"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Bereinigt einen Zeichenkettenwert, um ihn für die Swiss Payment Standards 2018 in C++ nutzbar zu machen."
type: docs
weight: 100
url: /de/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Bereinigt einen Zeichenkettenwert, um ihn für die Schweizer Zahlungsstandards 2018 nutzbar zu machen.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | System::String | Der zu bereinigende Zeichenkettenwert. |
| Ergebnis | Payments::CleaningResult\& | Das Ergebnis, das mit bereinigter Zeichenkette und Flag gefüllt werden soll. |
## Hinweise


Nicht unterstützte Zeichen (gemäß Swiss Payment Standards 2018, Kap. 2.4.1 und Anhang D) werden durch Leerzeichen (nicht unterstützte Leerzeichen) oder Punkte (alle anderen nicht unterstützten Zeichen) ersetzt. Führende und nachfolgende Leerzeichen werden entfernt.

Wenn Zeichen über 0xff erkannt werden, wird die Zeichenkette zuerst normalisiert, sodass Buchstaben mit Umlauten oder Akzenten, die mit zwei Codepunkten dargestellt werden, zu einem einzelnen Codepunkt zusammengeführt werden (falls möglich); einige davon könnten gültig werden.

Wenn die resultierende Zeichenkette ausschließlich aus Leerzeichen besteht, wird **null** zurückgegeben.

## Siehe auch

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
