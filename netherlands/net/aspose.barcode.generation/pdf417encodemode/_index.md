---
title: "Enum Pdf417EncodeMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode enum. Encodeermodus voor Pdf417-streepjescodes"
type: docs
weight: 1540
url: /nl/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Pdf417-streepjescode coderingsmodus

```csharp
public enum Pdf417EncodeMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode‑tekens worden opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. |
| Binary | `1` | In de Binaire-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als er een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | `2` | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. |
| Extended | `3` | Uitgebreide modus die meerdere ECI‑modi ondersteunt. |

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


