---
title: "Classe Aspose::BarCode::Generation::AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Classe Aspose::BarCode::Generation::AztecParameters. Parametri Aztec in C++."
type: docs
weight: 300
url: /it/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Parametri Aztec.

```cpp
class AztecParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [get_ECIEncoding](./get_eciencoding/)() const | Ottiene la codifica ECI. Utilizzata quando AztecEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Ottiene una modalità di codifica Aztec. Valore predefinito: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Livello di correzione degli errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere compreso tra 5 e 95. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [get_LayersCount](./get_layerscount/)() const | Ottiene il conteggio dei livelli del simbolo Aztec. Il conteggio dei livelli dovrebbe essere compreso tra 1 e 3 per la modalità Compattta e tra 1 e 32 per la modalità a gamma completa. Valore predefinito: 0 (auto). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | ID del codice a barre per la modalità Structured Append del codice a barre Aztec. L'ID del codice a barre dovrebbe essere compreso tra 1 e il numero di codici a barre. Valore predefinito: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Numero di codici a barre per la modalità Structured Append del codice a barre Aztec. Il numero di codici a barre dovrebbe essere compreso tra 1 e 26. Valore predefinito: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | ID file per la modalità Structured Append del codice a barre Aztec (campo opzionale). L'ID file non dovrebbe contenere spazi. Valore predefinito: stringa vuota |
| [get_SymbolMode](./get_symbolmode/)() const | Ottiene una modalità del simbolo Aztec. Valore predefinito: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Imposta la codifica ECI. Usata quando AztecEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Imposta una modalità di codifica Aztec. Valore predefinito: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Livello di correzione degli errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere compreso tra 5 e 95. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Imposta il conteggio dei livelli del simbolo Aztec. Il conteggio dei livelli dovrebbe essere compreso tra 1 e 3 per la modalità Compattta e tra 1 e 32 per la modalità a gamma completa. Valore predefinito: 0 (auto). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | ID del codice a barre per la modalità Structured Append del codice a barre Aztec. L'ID del codice a barre dovrebbe essere compreso tra 1 e il numero di codici a barre. Valore predefinito: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Numero di codici a barre per la modalità Structured Append del codice a barre Aztec. Il numero di codici a barre dovrebbe essere compreso tra 1 e 26. Valore predefinito: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | ID file per la modalità Structured Append del codice a barre Aztec (campo opzionale). L'ID file non dovrebbe contenere spazi. Valore predefinito: stringa vuota |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Imposta una modalità del simbolo Aztec. Valore predefinito: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [AztecParameters](./). |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
