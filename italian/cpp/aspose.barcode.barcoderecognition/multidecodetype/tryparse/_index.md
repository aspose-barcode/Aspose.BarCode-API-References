---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " method. Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o meno in C++."
type: docs
weight: 1100
url: /it/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


Converte la rappresentazione stringa di un [MultiDecodeType](../) nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o meno.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | System::String | Una stringa nel formato "AllSupportedTypes" o "EAN8,EAN13,CodaBar" da convertire. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Viene restituito un vero [MultiDecodeType](../) quando la conversione è completata con successo; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Osservazioni



altrimenti restituisce un tipo indefinito.

o [MultiDecodeType](../) ("None").

## Vedi anche

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
