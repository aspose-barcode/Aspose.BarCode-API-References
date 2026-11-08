---
title: "Aspose::BarCode::Generation::QrParameters class"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::QrParameters klass. QR-parametrar i C++."
type: docs
weight: 4400
url: /sv/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


QR-parametrar.

```cpp
class QrParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Den nuvarande implementeringen består av alla välkända teckenuppsättningskodningar. Stöds inte av MicroQR. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | QR-symbologi typ för [BarCode](../../aspose.barcode/)'s kodningsläge. Standardvärde: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | Nivå för Reed-Solomon felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. Se QRErrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Version av MicroQR-kod. Från version M1 till version M4. Standardvärde är [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärde är [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | QR strukturerade tilläggsparametrar. Strukturerat tilläggsläge stöds inte av MicroQR- och RectMicroQR-streckkoder. |
| [get_Version](./get_version/)() const | Version av QR-kod. Från Version1 till Version40. Standardvärde är [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Den nuvarande implementeringen består av alla välkända teckenuppsättningskodningar. Stöds inte av MicroQR. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | QR-symbologi typ för [BarCode](../../aspose.barcode/)'s kodningsläge. Standardvärde: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | Nivå för Reed-Solomon felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. Se QRErrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | Version av MicroQR-kod. Från version M1 till version M4. Standardvärde är [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärde är [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | QR strukturerade tilläggsparametrar. Strukturerat tilläggsläge stöds inte av MicroQR- och RectMicroQR-streckkoder. |
| [set_Version](./set_version/)(QRVersion) | Version av QR-kod. Från Version1 till Version40. Standardvärde är [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [QrParameters](./). |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
