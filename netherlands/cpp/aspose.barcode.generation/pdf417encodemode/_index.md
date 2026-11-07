---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. Pdf417 barcode-coderingsmodus in C++."
type: docs
weight: 7900
url: /nl/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Pdf417 barcode coderingsmodus

```cpp
enum class Pdf417EncodeMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | 0 | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode‑tekens worden opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. |
| Binary | 1 | In de Binary-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | 2 | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. |
| Extended | 3 |  |

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
