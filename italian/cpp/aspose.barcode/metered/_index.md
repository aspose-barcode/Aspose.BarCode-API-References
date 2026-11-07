---
title: "classe Aspose::BarCode::Metered"
linktitle: "Metered"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "classe Aspose::BarCode::Metered. Fornisce metodi per impostare la chiave metered in C++."
type: docs
weight: 500
url: /it/cpp/aspose.barcode/metered/
---
## Metered class


Fornisce metodi per impostare la chiave a consumo.

```cpp
class Metered : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Ottiene il credito di consumo |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Ottiene la dimensione del file di consumo |
| [GetProductName](./getproductname/)() | Ottiene il nome del prodotto con licenza |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Verifica se il metered è licenziato |
| [Metered](./metered/)() | Inizializza una nuova istanza di questa classe. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Imposta la chiave pubblica e privata metered. Se acquisti una licenza metered, all'avvio dell'applicazione, questa API dovrebbe essere chiamata; normalmente è sufficiente. Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata su stato di valutazione; per evitare tale caso, dovresti controllare regolarmente lo stato della licenza e, se è in stato di valutazione, chiamare nuovamente questa API. |
## Osservazioni


In questo esempio, verrà effettuato un tentativo di impostare la chiave pubblica e privata metered

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> il file jar del componente:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## Vedi anche

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
