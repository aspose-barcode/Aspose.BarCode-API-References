---
title: "Aspose::BarCode::Generation::HanXinParameters classe"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::HanXinParameters classe. Parametri Han Xin in C++."
type: docs
weight: 2900
url: /it/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Parametri Han Xin.

```cpp
class HanXinParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per codificare i dati nel simbolo. L'implementazione corrente contiene tutte le codifiche di charset ben note. |
| [get_EncodeMode](./get_encodemode/)() const | Modalità di codifica HanXin. Valore predefinito: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Livello di correzione errori Reed-Solomon per il codice a barre Han Xin. Da basso a alto: L1, L2, L3, L4. Vedi ErrorLevel. |
| [get_Version](./get_version/)() const | Versione del codice HanXin. Da Version01 a Version84 per il codice Han Xin. Il valore predefinito è [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per codificare i dati nel simbolo. L'implementazione corrente contiene tutte le codifiche di charset ben note. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | Modalità di codifica HanXin. Valore predefinito: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Livello di correzione errori Reed-Solomon per il codice a barre Han Xin. Da basso a alto: L1, L2, L3, L4. Vedi ErrorLevel. |
| [set_Version](./set_version/)(HanXinVersion) | Versione del codice HanXin. Da Version01 a Version84 per il codice Han Xin. Il valore predefinito è [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [HanXinParameters](./). |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
