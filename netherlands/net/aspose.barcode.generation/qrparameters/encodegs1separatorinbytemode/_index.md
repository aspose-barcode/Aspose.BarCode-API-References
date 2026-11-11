---
title: "QrParameters.EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "QrParameters eigenschap. Haalt een waarde op of stelt deze in die aangeeft of GS1-specialtekens moeten worden gecodeerd in Byte-modus voor QR- en RectMicroQR-streepjescodes."
type: docs
weight: 30
url: /nl/net/aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/
---
## QrParameters.EncodeGS1SeparatorInByteMode property

Haalt een waarde op of stelt deze in die aangeeft of GS1-specialtekens moeten worden gecodeerd in Byte-modus voor QR- en RectMicroQR-streepjescodes.

Als false, kunnen GS1-scheidingstekens worden gecodeerd als '%' in Alfanumerieke modus volgens de QR-specificatie.

Als true, worden GS1-groepsscheidingstekens gecodeerd in Byte-modus als het 0x1D-teken, en worden '%' tekens ook gecodeerd in Byte-modus om ze als gegevens te behouden.

Deze optie kan de compatibiliteit verbeteren met decoders die byte‑niveau GS1-groepsscheidingstekens verwachten en voorkomt dat '%' gegevenskarakters worden geïnterpreteerd als GS1-scheidingstekens.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Zie ook

* class [QrParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


