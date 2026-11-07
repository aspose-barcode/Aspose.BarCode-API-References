---
title: "Aspose::BarCode::Generation::DataMatrixParameters class"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::DataMatrixParameters class. Parametri DataMatrix in C++."
type: docs
weight: 2000
url: /it/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


Parametri DataMatrix.

```cpp
class DataMatrixParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [get_EccType](./get_ecctype/)() const | Ottiene un tipo ECC DataMatrix. Valore predefinito: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Ottiene la codifica ECI. Utilizzata quando EncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Modalità di codifica del codice a barre Datamatrix. Valore predefinito: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. Valore predefinito: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con [DataMatrixEccType.Ecc200](../datamatrixecctype/) o [DataMatrixEccType.EccAuto](../datamatrixecctype/). Non possono essere usati con [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) Valore predefinito: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | ID file per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0 |
| [get_Version](./get_version/)() const | Ottiene la dimensione del simbolo Datamatrix. Valore predefinito: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Imposta il tipo ECC del Datamatrix. Valore predefinito: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Imposta la codifica ECI. Utilizzata quando EncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Modalità di codifica del codice a barre Datamatrix. Valore predefinito: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. Valore predefinito: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Possono essere usati solo con [DataMatrixEccType.Ecc200](../datamatrixecctype/) o [DataMatrixEccType.EccAuto](../datamatrixecctype/). Non possono essere usati con [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) Valore predefinito: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | ID del codice a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Conteggio dei codici a barre per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | ID file per la modalità Structured Append del codice a barre Datamatrix. Valore predefinito: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Imposta la dimensione del simbolo Datamatrix. Valore predefinito: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [DataMatrixParameters](./). |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
