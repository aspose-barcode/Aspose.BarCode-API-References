---
title: "Aspose::BarCode::ComplexBarcode::PrimaryData class"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::PrimaryData class. Classe per memorizzare i dati primari HIBC LIC in C++."
type: docs
weight: 2500
url: /it/cpp/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class


Classe per l'archiviazione dei dati primari HIBC LIC.

```cpp
class PrimaryData : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [PrimaryData](./) specificato. |
| [get_LabelerIdentificationCode](./get_labeleridentificationcode/)() const | Identifica la data del codice di identificazione del etichettatore. Il codice di identificazione del etichettatore deve essere una stringa alfanumerica di 4 simboli, con il primo carattere sempre alfabetico. |
| [get_ProductOrCatalogNumber](./get_productorcatalognumber/)() const | Identifica il numero di prodotto o di catalogo. Il numero di prodotto o di catalogo deve essere una stringa alfanumerica di lunghezza fino a 18 simboli. |
| [get_UnitOfMeasureID](./get_unitofmeasureid/)() const | Identifica l'ID dell'unità di misura. L'ID dell'unità di misura deve essere un valore intero da 0 a 9. |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ParseFromString](./parsefromstring/)(System::String) | Istanzia i dati primari dal formato stringa secondo la specifica HIBC LIC. |
| [PrimaryData](./primarydata/)() |  |
| [set_LabelerIdentificationCode](./set_labeleridentificationcode/)(System::String) | Identifica la data del codice di identificazione del etichettatore. Il codice di identificazione del etichettatore deve essere una stringa alfanumerica di 4 simboli, con il primo carattere sempre alfabetico. |
| [set_ProductOrCatalogNumber](./set_productorcatalognumber/)(System::String) | Identifica il numero di prodotto o di catalogo. Il numero di prodotto o di catalogo deve essere una stringa alfanumerica di lunghezza fino a 18 simboli. |
| [set_UnitOfMeasureID](./set_unitofmeasureid/)(int32_t) | Identifica l'ID dell'unità di misura. L'ID dell'unità di misura deve essere un valore intero da 0 a 9. |
| [ToString](./tostring/)() const override | Converte i dati in formato stringa secondo la specifica HIBC LIC. |
## Vedi anche

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
