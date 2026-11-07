---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext classe"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext classe. Rappresenta il codetext GS1 per la codifica e la decodifica come una sequenza ordinata di elementi Identificatore di Applicazione. L'ordine di origine e gli Identificatori di Applicazione ripetuti sono conservati. La rappresentazione tra parentesi ha la forma (AI)valore(AI)valore. Una parentesi di apertura letterale ''('' all'interno di un valore deve essere scritta come (; questa è l'unica sequenza di escape supportata. Una parentesi di chiusura '')'' all'interno di un valore non richiede escape in C++."
type: docs
weight: 500
url: /it/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


Rappresenta il codetext GS1 per la codifica e decodifica come una sequenza ordinata di elementi Identificatore di Applicazione. L'ordine di origine e gli Identificatori di Applicazione ripetuti sono conservati. La rappresentazione tra parentesi ha la forma (AI)valore(AI)valore. Una parentesi aperta letterale '(' all'interno di un valore deve essere scritta come (; questa è l'unica sequenza di escape supportata. Una parentesi chiusa ')' all'interno di un valore non richiede escape.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Aggiunge un elemento Application Identifier convalidato. |
| [get_BarcodeType](./get_barcodetype/)() const | Restituisce il tipo di codice a barre utilizzato per codificare questo codetext GS1. I tipi supportati sono GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR e i tipi GS1 DataBar. Il valore predefinito è GS1Code128. |
| [get_Count](./get_count/)() | Restituisce il numero di elementi Application Identifier. |
| [get_Elements](./get_elements/)() | Restituisce una copia di tutti gli elementi nell'ordine di origine. |
| [GetAll](./getall/)(System::String) | Restituisce tutti i valori per un Identificatore di Applicazione nell'ordine di origine. |
| [GetBarcodeType](./getbarcodetype/)() override | Restituisce il tipo di codice a barre utilizzato per codificare questo codetext GS1. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Costruisce il codetext GS1 tra parentesi nella forma (AI)valore(AI)valore. Le parentesi di apertura letterali nei valori sono escape come (. |
| [GetFirst](./getfirst/)(System::String) | Restituisce il primo valore per un Identificatore di Applicazione. |
| [GS1Codetext](./gs1codetext/)() | Inizializza un codetext GS1 vuoto. |
| [idx_get](./idx_get/)(int32_t) | Restituisce un elemento in base alla sua posizione nella sequenza ordinata. |
| [InitFromString](./initfromstring/)(System::String) override | Inizializza questa istanza da un codetext GS1 tra parentesi nella forma (AI)valore(AI)valore. Gli elementi esistenti vengono sostituiti solo dopo che il codetext fornito è stato analizzato con successo. |
| static [Parse](./parse/)(System::String) | Analizza una stringa di elemento GS1 tra parentesi nella forma (AI)valore(AI)valore. Un '(' letterale all'interno di un valore deve essere scritto come (; non è supportata alcun'altra sequenza di escape, e ')' non richiede escape. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Imposta il tipo di codice a barre utilizzato per codificare questo codetext GS1. I tipi supportati sono GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR e i tipi GS1 DataBar. Il valore predefinito è GS1Code128. |
| [ToString](./tostring/)() const override | Restituisce la rappresentazione GS1 tra parentesi nella forma (AI)valore(AI)valore. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Tenta di analizzare una stringa di elemento GS1 tra parentesi nella forma (AI)valore(AI)valore e restituisce errori di convalida strutturati. Un '(' letterale all'interno di un valore deve essere scritto come (; nessun'altra sequenza di escape è supportata, e ')' non richiede escape. |
| static [Validate](./validate/)(System::String) | Convalida una stringa di elemento GS1 tra parentesi nella forma (AI)valore(AI)valore senza costruire un oggetto. Un '(' letterale all'interno di un valore deve essere scritto come (; nessun'altra sequenza di escape è supportata, e ')' non richiede escape. |
## Vedi anche

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
