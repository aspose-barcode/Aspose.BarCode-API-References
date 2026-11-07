---
title: "classe Aspose::BarCode::Generation::QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "classe Aspose::BarCode::Generation::QrParameters. Parametri QR in C++."
type: docs
weight: 4400
url: /it/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


Parametri QR.

```cpp
class QrParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [get_ECIEncoding](./get_eciencoding/)() const | Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione attuale comprende tutte le codifiche di set di caratteri conosciute. Non supportato da MicroQR. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | Tipo di simbologia QR della modalità di codifica di [BarCode](../../aspose.barcode/). Valore predefinito: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. Da basso a alto: LevelL, LevelM, LevelQ, LevelH. Vedi QERrrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Versione del MicroQR Code. Dalla versione M1 alla versione M4. Il valore predefinito è [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | Versione del RectMicroQR Code. Dalla versione R7x59 alla versione R17x139. Il valore predefinito è [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | Parametri di aggiunta strutturata QR. La modalità di aggiunta strutturata non è supportata dai codici a barre MicroQR e RectMicroQR. |
| [get_Version](./get_version/)() const | Versione del QR Code. Dalla Versione1 alla Versione40. Il valore predefinito è [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione attuale comprende tutte le codifiche di set di caratteri conosciute. Non supportato da MicroQR. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | Tipo di simbologia QR della modalità di codifica di [BarCode](../../aspose.barcode/). Valore predefinito: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR. Da basso a alto: LevelL, LevelM, LevelQ, LevelH. Vedi QERrrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | Versione del MicroQR Code. Dalla versione M1 alla versione M4. Il valore predefinito è [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | Versione del RectMicroQR Code. Dalla versione R7x59 alla versione R17x139. Il valore predefinito è [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | Parametri di aggiunta strutturata QR. La modalità di aggiunta strutturata non è supportata dai codici a barre MicroQR e RectMicroQR. |
| [set_Version](./set_version/)(QRVersion) | Versione del QR Code. Dalla Versione1 alla Versione40. Il valore predefinito è [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [QrParameters](./). |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
