---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::ITFParameters class. Παράμετροι ITF σε C++."
type: docs
weight: 3300
url: /el/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


Παράμετροι ITF.

```cpp
class ITFParameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | Λαμβάνει το πάχος του περιγράμματος ITF (bearer bar) σε τιμή [Unit](../unit/). Προεπιλεγμένη τιμή: 12pt. |
| [get_BorderType](./get_bordertype/)() const | Τύπος περιγράμματος του barcode ITF. Προεπιλεγμένη τιμή: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | Μέγεθος των ήσυχων ζωνών σε xDimension. Προεπιλεγμένη τιμή: 10, που σημαίνει ότι αν xDimension = 2px τότε οι ήσυχες ζώνες θα είναι 20px. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | Ορίζει το πάχος του περιγράμματος ITF (γραμμή φορέα) σε τιμή [Unit](../unit/). Προεπιλεγμένη τιμή: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | Τύπος περιγράμματος του barcode ITF. Προεπιλεγμένη τιμή: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | Μέγεθος των ήσυχων ζωνών σε xDimension. Προεπιλεγμένη τιμή: 10, που σημαίνει ότι αν xDimension = 2px τότε οι ήσυχες ζώνες θα είναι 20px. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το [ITFParameters](./). |
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
