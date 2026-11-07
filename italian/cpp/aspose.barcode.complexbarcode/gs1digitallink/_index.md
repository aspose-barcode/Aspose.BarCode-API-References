---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Classe Aspose::BarCode::ComplexBarcode::GS1DigitalLink. Rappresenta il codetext GS1 Digital Link per la codifica e la decodifica come sequenza ordinata di elementi Application Identifier. L'ordine di origine e gli Application Identifier ripetuti sono conservati. Il codetext costruito è un URI GS1 Digital Link non compresso. I parametri di query non GS1 e i frammenti URI sono ignorati durante il parsing in C++."
type: docs
weight: 600
url: /it/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


Rappresenta il codetext GS1 Digital Link per la codifica e decodifica come una sequenza ordinata di elementi Identificatore di Applicazione. L'ordine di origine e gli Identificatori di Applicazione ripetuti sono conservati. Il codetext costruito è un URI GS1 Digital Link non compresso. I parametri di query e i frammenti URI non GS1 vengono ignorati durante l'analisi.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Aggiunge un elemento Application Identifier convalidato. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | Crea un GS1 Digital Link copiando tutti gli elementi dal codetext GS1 e selezionando l'unica chiave primaria disponibile. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | Crea un GS1 Digital Link copiando tutti gli elementi dal codetext GS1 e utilizzando la chiave primaria specificata. |
| [get_BarcodeType](./get_barcodetype/)() const | Restituisce il tipo di codice a barre utilizzato per codificare questo GS1 Digital Link. I tipi supportati sono QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF e Code128. Il valore predefinito è QR. |
| [get_Count](./get_count/)() | Restituisce il numero di elementi Application Identifier. |
| [get_Elements](./get_elements/)() | Restituisce una copia di tutti gli elementi nell'ordine di origine. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Restituisce l'Application Identifier utilizzato come chiave primaria del Digital Link. Null indica che la chiave primaria viene selezionata automaticamente quando l'URI è costruito. |
| [get_UriStem](./get_uristem/)() const | Restituisce il prefisso URI assoluto prima del segmento di percorso della chiave primaria GS1. Il tronco non contiene una stringa di query o un frammento. |
| [GetAll](./getall/)(System::String) | Restituisce tutti i valori per un Identificatore di Applicazione nell'ordine di origine. |
| [GetBarcodeType](./getbarcodetype/)() override | Restituisce il tipo di codice a barre utilizzato per codificare questo GS1 Digital Link. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Costruisce l'URI non compresso di GS1 Digital Link. |
| [GetFirst](./getfirst/)(System::String) | Restituisce il primo valore per un Identificatore di Applicazione. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Inizializza un GS1 Digital Link vuoto con il segmento URI specificato. La chiave primaria viene selezionata automaticamente quando è presente esattamente un candidato chiave primaria. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Inizializza un GS1 Digital Link vuoto con il segmento URI specificato e la chiave primaria. |
| [idx_get](./idx_get/)(int32_t) | Restituisce un elemento in base alla sua posizione nella sequenza ordinata. |
| [InitFromString](./initfromstring/)(System::String) override | Inizializza questa istanza da un URI non compresso di GS1 Digital Link. Lo stato esistente viene sostituito solo dopo che l'URI fornito è stato analizzato con successo. Il tipo di codice a barre selezionato viene conservato. |
| static [Parse](./parse/)(System::String) | Analizza un URI non compresso di GS1 Digital Link. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Imposta il tipo di codice a barre utilizzato per codificare questo GS1 Digital Link. I tipi supportati sono QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF e Code128. Il valore predefinito è QR. |
| [ToGS1Codetext](./togs1codetext/)() | Crea un codetext GS1 indipendente contenente gli elementi GS1 correnti. Le informazioni solo URI non sono incluse. |
| [ToString](./tostring/)() const override | Restituisce l'URI non compresso di GS1 Digital Link. |
| [ToUriString](./touristring/)() | Formatta lo stato corrente dell'oggetto come un URI non compresso di GS1 Digital Link. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Tenta di analizzare un URI non compresso di GS1 Digital Link e restituisce errori di validazione strutturati. |
| static [Validate](./validate/)(System::String) | Convalida un URI non compresso di GS1 Digital Link senza costruire un oggetto. |
## Vedi anche

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
