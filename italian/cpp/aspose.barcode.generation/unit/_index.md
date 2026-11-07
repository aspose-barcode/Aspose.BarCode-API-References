---
title: "Aspose::BarCode::Generation::Unit classe"
linktitle: "Unit"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::Unit class. Specifica il valore di dimensione in diverse unità (Pixel, Pollici, ecc.) in C++."
type: docs
weight: 5000
url: /it/cpp/aspose.barcode.generation/unit/
---
## Unit class


Specifica il valore di dimensione in diverse unità (Pixel, Pollici, ecc.).

```cpp
class Unit : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determina se questa istanza e un oggetto specificato, che deve essere anche un oggetto [Unit](./), hanno lo stesso valore. |
| [get_Document](./get_document/)() | Ottiene il valore di dimensione nelle unità del documento. |
| [get_Inches](./get_inches/)() | Ottiene il valore di dimensione in pollici. |
| [get_Millimeters](./get_millimeters/)() | Ottiene il valore di dimensione in millimetri. |
| [get_Pixels](./get_pixels/)() | Ottiene il valore di dimensione in pixel. |
| [get_Point](./get_point/)() | Ottiene il valore di dimensione in punti. |
| [get_Resolution](./get_resolution/)() const | Risoluzione |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questo oggetto. |
| [set_Document](./set_document/)(float) | Imposta il valore di dimensione nelle unità del documento. |
| [set_Inches](./set_inches/)(float) | Imposta il valore di dimensione in pollici. |
| [set_Millimeters](./set_millimeters/)(float) | Imposta il valore di dimensione in millimetri. |
| [set_Pixels](./set_pixels/)(float) | Imposta il valore di dimensione in pixel. |
| [set_Point](./set_point/)(float) | Imposta il valore di dimensione in punti. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [Unit](./). |
## Osservazioni


Questo esempio mostra come creare e salvare un'immagine [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
