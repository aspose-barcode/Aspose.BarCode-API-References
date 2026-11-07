---
title: "Aspose::BarCode::Generation::QrParameters klasse"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::QrParameters klasse. QR-parameters in C++."
type: docs
weight: 4400
url: /nl/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


QR-parameters.

```cpp
class QrParameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bevat alle bekende charset‑coderingen. Niet ondersteund door MicroQR. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | QR-symbologie type van de coderingsmodus van [BarCode](../../aspose.barcode/). Standaardwaarde: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | Niveau van Reed‑Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. Zie QERrrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Versie van MicroQR‑code. Van versie M1 tot versie M4. Standaardwaarde is [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | Versie van RectMicroQR‑code. Van versie R7x59 tot versie R17x139. Standaardwaarde is [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | QR-gestructureerde-append-parameters. Gestructureerde-append-modus wordt niet ondersteund door MicroQR- en RectMicroQR-barcodes. |
| [get_Version](./get_version/)() const | Versie van QR‑code. Van Version1 tot Version40. Standaardwaarde is [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bevat alle bekende charset‑coderingen. Niet ondersteund door MicroQR. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | QR-symbologie type van de coderingsmodus van [BarCode](../../aspose.barcode/). Standaardwaarde: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | Niveau van Reed‑Solomon-foutcorrectie voor QR-, MicroQR- en RectMicroQR-barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. Zie QERrrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | Versie van MicroQR‑code. Van versie M1 tot versie M4. Standaardwaarde is [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | Versie van RectMicroQR‑code. Van versie R7x59 tot versie R17x139. Standaardwaarde is [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | QR-gestructureerde-append-parameters. Gestructureerde-append-modus wordt niet ondersteund door MicroQR- en RectMicroQR-barcodes. |
| [set_Version](./set_version/)(QRVersion) | Versie van QR‑code. Van Version1 tot Version40. Standaardwaarde is [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [QrParameters](./). |
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
