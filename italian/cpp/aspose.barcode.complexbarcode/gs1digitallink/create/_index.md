---
title: "method"
linktitle: "Crea"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Crea un GS1 Digital Link copiando tutti gli elementi dal codetext GS1 e selezionando l'unica chiave primaria disponibile in C++."
type: docs
weight: 2100
url: /it/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


Crea un GS1 Digital Link copiando tutti gli elementi dal codetext GS1 e selezionando l'unica chiave primaria disponibile.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| uriStem | System::String | Prefisso URI assoluto HTTP o HTTPS prima della chiave primaria. |
| codetext | System::SharedPtr\<GS1Codetext\> | Codetext GS1 i cui elementi sono copiati. |

### ReturnValue

Un GS1 Digital Link contenente gli elementi copiati.

## Vedi anche

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


Crea un GS1 Digital Link copiando tutti gli elementi dal codetext GS1 e utilizzando la chiave primaria specificata.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| uriStem | System::String | Prefisso URI assoluto HTTP o HTTPS prima della chiave primaria. |
| codetext | System::SharedPtr\<GS1Codetext\> | Codetext GS1 i cui elementi sono copiati. |
| primaryApplicationIdentifier | System::String | AI della chiave primaria. |

### ReturnValue

Un GS1 Digital Link contenente gli elementi copiati.

## Vedi anche

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
