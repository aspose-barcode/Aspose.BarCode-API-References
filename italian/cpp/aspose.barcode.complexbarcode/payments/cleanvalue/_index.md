---
title: "method"
linktitle: "CleanValue"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Pulisce un valore stringa per renderlo idoneo agli Swiss Payment Standards 2018 in C++."
type: docs
weight: 100
url: /it/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Pulisce un valore stringa per renderlo idoneo agli Standard di Pagamento Svizzeri 2018.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | System::String | Il valore stringa da pulire. |
| result | Payments::CleaningResult\& | Il risultato da riempire con la stringa pulita e il flag. |
## Osservazioni


I caratteri non supportati(secondo gli Swiss Payment Standards 2018, cap. 2.4.1 e appendice D) sono sostituiti con spazi(spazi bianchi non supportati) o punti (tutti gli altri caratteri non supportati). Gli spazi bianchi iniziali e finali vengono rimossi.

Se vengono rilevati caratteri oltre 0xff, la stringa viene prima normalizzata in modo che le lettere con umlaut o accenti espresse con due punti di codice vengano unite in un unico punto di codice (se possibile), alcuni dei quali potrebbero diventare validi.

Se la stringa risultante è composta solo da spazi bianchi, **null** viene restituito.

## Vedi anche

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
