---
title: "Methode"
linktitle: "Erstellen"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Erstellt einen GS1 Digital Link, indem alle Elemente aus dem GS1-Codetext kopiert und der einzige verfügbare Primärschlüssel in C++ ausgewählt wird."
type: docs
weight: 2100
url: /de/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


Erstellt einen GS1 Digital Link, indem alle Elemente aus dem GS1‑Codetext kopiert und der einzige verfügbare Primärschlüssel ausgewählt werden.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriStem | System::String | Absoluter HTTP- oder HTTPS-URI-Präfix vor dem Primärschlüssel. |
| codetext | System::SharedPtr\<GS1Codetext\> | GS1-Codetext, dessen Elemente kopiert werden. |

### ReturnValue

Ein GS1 Digital Link, das die kopierten Elemente enthält.

## Siehe auch

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


Erstellt einen GS1 Digital Link, indem alle Elemente aus dem GS1‑Codetext kopiert und der angegebene Primärschlüssel verwendet werden.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriStem | System::String | Absoluter HTTP- oder HTTPS-URI-Präfix vor dem Primärschlüssel. |
| codetext | System::SharedPtr\<GS1Codetext\> | GS1-Codetext, dessen Elemente kopiert werden. |
| primaryApplicationIdentifier | System::String | Primärschlüssel-AI. |

### ReturnValue

Ein GS1 Digital Link, das die kopierten Elemente enthält.

## Siehe auch

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
