---
title: Metered
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Fornisce i metodi per impostare la chiave misurata.
type: docs
weight: 1020
url: /it/net/aspose.barcode/metered/
---
## Metered class

Fornisce i metodi per impostare la chiave misurata.

```csharp
public class Metered
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Metered](metered)() | Default_Costruttore |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey)(string, string) | Imposta la chiave pubblica e privata misurata |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit)() | Ottiene credito di consumo |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity)() | Ottiene la dimensione del file di consumo |

### Esempi

In questo esempio, verrà effettuato un tentativo di impostare la chiave pubblica e privata misurata

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Guarda anche

* spazio dei nomi [Aspose.BarCode](../../aspose.barcode)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->