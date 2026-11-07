---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. Classe per la memorizzazione dei dati secondari e aggiuntivi HIBC LIC in C++."
type: docs
weight: 2600
url: /it/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


Classe per l'archiviazione dei dati secondari e aggiuntivi HIBC LIC.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di [SecondaryAndAdditionalData](./). |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Identifica la data di produzione. La data di produzione può essere impostata a DateTime.MinValue per non utilizzare questo campo. Valore predefinito: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Identifica la data di scadenza. Verrà utilizzata se ExpiryDateFormat non è impostato su None. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Identifica il formato della data di scadenza. |
| [get_LotNumber](./get_lotnumber/)() const | Identifica il numero di lotto o batch. Il numero di lotto/batch deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. |
| [get_Quantity](./get_quantity/)() const | Identifica la quantità, deve essere un valore intero da 0 a 500. La quantità può essere impostata a -1 per non utilizzare questo campo. Valore predefinito: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | Identifica il numero di serie. Il numero di serie deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [ParseFromString](./parsefromstring/)(System::String) | Istanzia i dati supplementari secondari e aggiuntivi dal formato stringa secondo la specifica HIBC LIC. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Identifica la data di produzione. La data di produzione può essere impostata a DateTime.MinValue per non utilizzare questo campo. Valore predefinito: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Identifica la data di scadenza. Verrà utilizzata se ExpiryDateFormat non è impostato su None. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Identifica il formato della data di scadenza. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Identifica il numero di lotto o batch. Il numero di lotto/batch deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. |
| [set_Quantity](./set_quantity/)(int32_t) | Identifica la quantità, deve essere un valore intero da 0 a 500. La quantità può essere impostata a -1 per non utilizzare questo campo. Valore predefinito: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Identifica il numero di serie. Il numero di serie deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. |
| [ToString](./tostring/)() const override | Converte i dati in formato stringa secondo la specifica HIBC LIC. |
## Vedi anche

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
