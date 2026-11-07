---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita in C++."
type: docs
weight: 500
url: /it/cpp/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## DecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Converte la rappresentazione stringa di un [SingleDecodeType](../../singledecodetype/) nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | System::String | Una stringa contenente un [SingleDecodeType](../../singledecodetype/) nel formato "EAN8" o "EAN13" o "CodaBar"... da convertire. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Un vero [SingleDecodeType](../../singledecodetype/) restituisce, quando la conversione è completata con successo; altrimenti restituisce il tipo indefinito: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Vedi anche

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## DecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Converte la rappresentazione stringa di un [MultiDecodeType](../../multidecodetype/) nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | System::String | Una stringa nel formato "AllSupportedTypes" o "EAN8,EAN13,CodaBar" da convertire. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Un vero [MultiDecodeType](../../multidecodetype/) viene restituito, quando la conversione è completata con successo; altrimenti restituisce il tipo indefinito: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Vedi anche

* Class [MultiDecodeType](../../multidecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
