---
title: "metod"
linktitle: "get_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder get_EncodeGS1SeparatorInByteMode-metoden i klassen Aspose::BarCode::Generation::QrParameters i C++."
type: docs
weight: 1700
url: /sv/cpp/aspose.barcode.generation/qrparameters/get_encodegs1separatorinbytemode/
---
## QrParameters::get_EncodeGS1SeparatorInByteMode method




```cpp
bool Aspose::BarCode::Generation::QrParameters::get_EncodeGS1SeparatorInByteMode() const
```

## Anmärkningar


Hämtar ett värde som indikerar om GS1-specialtecken ska kodas i byte-läge för QR- och RectMicroQR-streckkoder.

Om falskt kan GS1-separatorer kodas som '' i alfanumeriskt läge enligt QR-specifikationen.

Om sant kodas GS1-gruppseparatorer i byte-läge som tecknet 0x1D, och ''-tecken kodas också i byte-läge för att bevara dem som data.

Detta alternativ kan förbättra kompatibiliteten med avkodare som förväntar sig byte-nivå GS1-gruppseparatorer och förhindrar att ''-datatecken tolkas som GS1-separatorer.
## Se även

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
