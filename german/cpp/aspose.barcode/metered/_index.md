---
title: "Aspose::BarCode::Metered Klasse"
linktitle: "Metered"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Metered Klasse. Stellt Methoden zum Festlegen des metered-Schlüssels in C++ bereit."
type: docs
weight: 500
url: /de/cpp/aspose.barcode/metered/
---
## Metered class


Stellt Methoden zum Setzen des gemessenen Schlüssels bereit.

```cpp
class Metered : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Erhält Verbrauchsguthaben |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Erhält Verbrauchsdateigröße |
| [GetProductName](./getproductname/)() | Erhält Namen des lizenzierten Produkts |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Überprüfen, ob Metered lizenziert ist |
| [Metered](./metered/)() | Initialisiert eine neue Instanz dieser Klasse. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Setzt den öffentlichen und privaten Metered‑Schlüssel. Wenn Sie eine Metered‑Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Sollte jedoch das Hochladen der Verbrauchsdaten ständig fehlschlagen und 24 Stunden überschreiten, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf. |
## Hinweise


In diesem Beispiel wird versucht, den öffentlichen und privaten Metered‑Schlüssel zu setzen.

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

<java> die Komponenten‑Jar‑Datei:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## Siehe auch

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
