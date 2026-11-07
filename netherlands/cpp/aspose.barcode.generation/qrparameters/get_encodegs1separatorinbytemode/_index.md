---
title: "methode"
linktitle: "get_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je de get_EncodeGS1SeparatorInByteMode-methode van de Aspose::BarCode::Generation::QrParameters-klasse in C++."
type: docs
weight: 1700
url: /nl/cpp/aspose.barcode.generation/qrparameters/get_encodegs1separatorinbytemode/
---
## QrParameters::get_EncodeGS1SeparatorInByteMode method




```cpp
bool Aspose::BarCode::Generation::QrParameters::get_EncodeGS1SeparatorInByteMode() const
```

## Opmerkingen


Haalt een waarde op die aangeeft of GS1-specialtekens moeten worden gecodeerd in Byte-modus voor QR- en RectMicroQR-barcodes.

Als false, kunnen GS1-scheidingstekens worden gecodeerd als '' in alfanumerieke modus volgens de QR-specificatie.

Als true, worden GS1-groepscheidingstekens gecodeerd in Byte-modus als het 0x1D-teken, en worden ''-tekens ook gecodeerd in Byte-modus om ze als gegevens te behouden.

Deze optie kan de compatibiliteit verbeteren met decoders die byte-niveau GS1-groepscheidingstekens verwachten en voorkomt dat ''-datatekens worden geïnterpreteerd als GS1-scheidingstekens.
## Zie ook

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
