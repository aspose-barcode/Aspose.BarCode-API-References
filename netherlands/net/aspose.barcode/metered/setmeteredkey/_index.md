---
title: "Metered.SetMeteredKey"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Metered-methode. Stelt de openbare en privé‑sleutel van metered in. Als u een metered‑licentie aanschaft wanneer u de applicatie start, moet deze API normaal gesproken worden aangeroepen; dit is voldoende. Als het echter steeds mislukt om verbruiksgegevens te uploaden en de 24‑uur limiet wordt overschreden, wordt de licentie op evaluatiestatus gezet. Om zo’n geval te voorkomen, moet u regelmatig de licentiestatus controleren; als deze evaluatiestatus is, roept u deze API opnieuw aan."
type: docs
weight: 30
url: /nl/net/aspose.barcode/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Stelt de openbare en private metered‑sleutel in. Als u een metered‑licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen; normaal gesproken is dit voldoende. Als het echter steeds mislukt om consumptiegegevens te uploaden en de 24‑uurgrens wordt overschreden, wordt de licentie op evaluatiestatus gezet. Om dit te voorkomen, dient u regelmatig de licentiestatus te controleren; als deze op evaluatiestatus staat, roept u deze API opnieuw aan.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| publicKey | String | openbare sleutel |
| privateKey | String | privé sleutel |

### Zie ook

* class [Metered](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)


