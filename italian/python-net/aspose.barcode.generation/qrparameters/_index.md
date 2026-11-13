---
title: "QrParameters"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

Parametri QR.

Il tipo QrParameters espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| eci_encoding | Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli<br/>            sui riferimenti usati per codificare i dati nel simbolo.<br/>            L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute.<br/>            Non supportato da MicroQR. |
| encode_mode | Tipo di simbologia QR della modalità di codifica del BarCode.<br/>            Valore predefinito: QREncodeMode.Auto. |
| error_level | Livello di correzione errori Reed-Solomon per i codici a barre QR, MicroQR e RectMicroQR.<br/>             Da basso a alto: LevelL, LevelM, LevelQ, LevelH. Vedi QRErrorLevel. |
| version | Versione del QR Code. Da Version1 a Version40.<br/>            Il valore predefinito è QRVersion.Auto. |
| micro_qr_version | Versione del MicroQR Code. Da versione M1 a versione M4.<br/>            Il valore predefinito è MicroQRVersion.Auto. |
| rect_micro_qr_version | Versione del RectMicroQR Code. Da versione R7x59 a versione R17x139.<br/>            Il valore predefinito è RectMicroQRVersion.Auto. |
| aspect_ratio | Rapporto altezza/larghezza del modulo 2D BarCode. |
| structured_append | Parametri di aggiunta strutturata QR.<br/>            La modalità di aggiunta strutturata non è supportata dai codici a barre MicroQR e RectMicroQR. |
| encode_gs1_separator_in_byte_mode |  |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

