---
title: "Classe Aspose::BarCode::ComplexBarcode::Address"
linktitle: "Indirizzo"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Classe Aspose::BarCode::ComplexBarcode::Address. Indirizzo del creditore o del debitore in C++."
type: docs
weight: 100
url: /it/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Address](./address/)() | Crea un'istanza di [Address](./) |
| [Clear](./clear/)() | Cancella tutti i campi e imposta il tipo su [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determina se l'oggetto specificato è uguale all'oggetto corrente. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Determina se l'indirizzo specificato è uguale all'indirizzo corrente. |
| [get_AddressLine1](./get_addressline1/)() const | Ottiene la prima riga dell'indirizzo. |
| [get_AddressLine2](./get_addressline2/)() const | Ottiene la seconda riga dell'indirizzo. |
| [get_CountryCode](./get_countrycode/)() const | Ottiene il codice paese ISO a due lettere. |
| [get_HouseNo](./get_houseno/)() const | Ottiene il numero civico. |
| [get_Name](./get_name/)() const | Ottiene il nome, sia il nome e cognome di una persona fisica sia il nome dell'azienda di una persona giuridica. |
| [get_PostalCode](./get_postalcode/)() const | Ottiene il codice postale. |
| [get_Street](./get_street/)() const | Ottiene la via. |
| [get_Town](./get_town/)() const | Ottiene il comune o la città. |
| [get_Type](./get_type/)() const | Ottiene il tipo di indirizzo. |
| [GetHashCode](./gethashcode/)() const override | Ottiene il codice hash per questa istanza. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Imposta la prima riga dell'indirizzo. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Imposta la seconda riga dell'indirizzo. |
| [set_CountryCode](./set_countrycode/)(System::String) | Imposta il codice paese ISO a due lettere. |
| [set_HouseNo](./set_houseno/)(System::String) | Imposta il numero civico. |
| [set_Name](./set_name/)(System::String) | Imposta il nome, sia il nome e cognome di una persona fisica sia il nome dell'azienda di una persona giuridica. |
| [set_PostalCode](./set_postalcode/)(System::String) | Imposta il codice postale. |
| [set_Street](./set_street/)(System::String) | Imposta la via. |
| [set_Town](./set_town/)(System::String) | Imposta la città o il paese. |
## Osservazioni


Puoi impostare la via, il numero civico, il codice postale e la città (tipo *indirizzo strutturato*) oppure la riga indirizzo 1 e 2 (tipo *elementi di indirizzo combinati*). Il tipo viene impostato automaticamente non appena uno di questi campi è impostato. Prima di impostare i campi, il tipo di indirizzo è *indeterminato*. Se i campi di entrambi i tipi sono impostati, il tipo di indirizzo diventa *in conflitto*. Il nome e il codice paese devono sempre essere impostati a meno che tutti i campi siano vuoti.
## Vedi anche

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
