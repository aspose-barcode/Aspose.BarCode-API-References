---
title: "classe Aspose::BarCode::Generation::DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "classe Aspose::BarCode::Generation::DotCodeParameters. Parametri DotCode in C++."
type: docs
weight: 2200
url: /it/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


Parametri DotCode.

```cpp
class DotCodeParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [get_Columns](./get_columns/)() const | Identifica il conteggio delle colonne. La somma del numero di righe più il numero di colonne di un simbolo DotCode deve essere dispari. Il numero di colonne deve essere almeno 5. Valore predefinito: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | Identifica la codifica ECI. Utilizzata quando DotCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Identifica la modalità di codifica DotCode. Valore predefinito: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false. |
| [get_Rows](./get_rows/)() const | Identifica il conteggio delle righe. La somma del numero di righe più il numero di colonne di un simbolo DotCode deve essere dispari. Il numero di righe deve essere almeno 5. Valore predefinito: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Identifica l'ID del codice a barre in modalità di aggiunta strutturata DotCode. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Identifica il conteggio dei codici a barre in modalità di aggiunta strutturata DotCode. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. |
| [set_AspectRatio](./set_aspectratio/)(float) | Rapporto Altezza/Larghezza del modulo [BarCode](../../aspose.barcode/) 2D. |
| [set_Columns](./set_columns/)(int32_t) | Identifica il conteggio delle colonne. La somma del numero di righe più il numero di colonne di un simbolo DotCode deve essere dispari. Il numero di colonne deve essere almeno 5. Valore predefinito: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identifica la codifica ECI. Utilizzata quando DotCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | Identifica la modalità di codifica DotCode. Valore predefinito: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false. |
| [set_Rows](./set_rows/)(int32_t) | Identifica il conteggio delle righe. La somma del numero di righe più il numero di colonne di un simbolo DotCode deve essere dispari. Il numero di righe deve essere almeno 5. Valore predefinito: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Identifica l'ID del codice a barre in modalità di aggiunta strutturata DotCode. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Identifica il conteggio dei codici a barre in modalità di aggiunta strutturata DotCode. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile da un umano di questo [DotCodeParameters](./). |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
