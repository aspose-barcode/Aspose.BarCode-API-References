---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita in C++."
type: docs
weight: 400
url: /it/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Converte la rappresentazione stringa di un [SingleDecodeType](../../singledecodetype/) nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | System::String | Una stringa contenente un [SingleDecodeType](../../singledecodetype/) nel formato "EAN8" o "EAN13" o "CodaBar"... da convertire. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Viene restituito un [SingleDecodeType](../../singledecodetype/) reale, quando la conversione è terminata con successo; altrimenti restituisce il tipo indefinito: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Vedi anche

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Converte la rappresentazione stringa di un [MultiDecodeType](../../multidecodetype/) nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | System::String | Una stringa contenente una rappresentazione di [MultiDecodeType](../../multidecodetype/) da convertire. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Viene restituito un [MultiDecodeType](../../multidecodetype/) reale, quando la conversione è terminata con successo; altrimenti restituisce il tipo indefinito: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Vedi anche

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Converte la rappresentazione stringa di un [BaseDecodeType](../) nella sua istanza, avendo determinato il tipo concreto. Un valore di ritorno indica se la conversione è riuscita o è fallita.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | System::String | Una stringa contenente una rappresentazione di [MultiDecodeType](../../multidecodetype/) da convertire. |
| result | System::SharedPtr\<BaseDecodeType\>\& | Viene restituito un [MultiDecodeType](../../multidecodetype/) reale, quando la conversione è terminata con successo; altrimenti restituisce il tipo indefinito: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Vedi anche

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
