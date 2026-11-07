---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Converte la rappresentazione stringa di un BaseEncodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o meno in C++."
type: docs
weight: 400
url: /it/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


Converte la rappresentazione stringa di un [BaseEncodeType](../../baseencodetype/) nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o meno.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | System::String | Una stringa nel formato "Index:-1; Name:None" da convertire. |
| result | System::SharedPtr\<BaseEncodeType\>\& | Un SingleEncodeType reale viene restituito, quando la conversione è completata con successo; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Osservazioni



altrimenti restituisce null.

## Vedi anche

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
