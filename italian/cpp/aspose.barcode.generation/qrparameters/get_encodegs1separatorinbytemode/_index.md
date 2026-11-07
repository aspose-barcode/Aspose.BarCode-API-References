---
title: "method"
linktitle: "get_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare il metodo get_EncodeGS1SeparatorInByteMode della classe Aspose::BarCode::Generation::QrParameters in C++."
type: docs
weight: 1700
url: /it/cpp/aspose.barcode.generation/qrparameters/get_encodegs1separatorinbytemode/
---
## QrParameters::get_EncodeGS1SeparatorInByteMode method




```cpp
bool Aspose::BarCode::Generation::QrParameters::get_EncodeGS1SeparatorInByteMode() const
```

## Osservazioni


Restituisce un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici a barre QR e RectMicroQR.

Se false, i separatori GS1 possono essere codificati come '' in modalità Alfanumerica secondo la specifica QR.

Se true, i separatori di gruppo GS1 sono codificati in modalità Byte come carattere 0x1D, e i caratteri '' sono anch'essi codificati in modalità Byte per preservarli come dati.

Questa opzione può migliorare la compatibilità con i decoder che si aspettano separatori di gruppo GS1 a livello di byte e impedisce che i caratteri dati '' vengano interpretati come separatori GS1.
## Vedi anche

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
