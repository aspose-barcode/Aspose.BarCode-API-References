---
title: "Aspose::BarCode::Generation::HanXinParameters class"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::HanXinParameters class. Han Xin-parametrar i C++."
type: docs
weight: 2900
url: /sv/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Parametrar för Han Xin.

```cpp
class HanXinParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Utökade kanalinterpretationsidentifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Nuvarande implementation innehåller alla välkända teckenuppsättningskodningar. |
| [get_EncodeMode](./get_encodemode/)() const | HanXin-kodningsläge. Standardvärde: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Nivå för Reed-Solomon-felkorrigering för Han Xin-streckkod. Från låg till hög: L1, L2, L3, L4. se ErrorLevel. |
| [get_Version](./get_version/)() const | Version av HanXin-kod. Från Version01 till Version84 för Han Xin-kod. Standardvärde är [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Utökade kanalinterpretationsidentifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Nuvarande implementation innehåller alla välkända teckenuppsättningskodningar. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | HanXin-kodningsläge. Standardvärde: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Nivå för Reed-Solomon-felkorrigering för Han Xin-streckkod. Från låg till hög: L1, L2, L3, L4. se ErrorLevel. |
| [set_Version](./set_version/)(HanXinVersion) | Version av HanXin-kod. Från Version01 till Version84 för Han Xin-kod. Standardvärde är [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [HanXinParameters](./). |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
