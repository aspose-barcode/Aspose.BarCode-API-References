---
title: "metod"
linktitle: "Skapa"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Skapar en GS1 Digital Link genom att kopiera alla element från GS1 kodtext och välja den enda tillgängliga primära nyckeln i C++."
type: docs
weight: 2100
url: /sv/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


Skapar en GS1 Digital Link genom att kopiera alla element från GS1-kodtext och välja den enda tillgängliga primära nyckeln.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriStem | System::String | Absolut HTTP- eller HTTPS-URI-prefix före den primära nyckeln. |
| kodtext | System::SharedPtr\<GS1Codetext\> | GS1-kodtext vars element kopieras. |

### ReturnValue

En GS1 Digital Link som innehåller de kopierade elementen.

## Se även

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


Skapar en GS1 Digital Link genom att kopiera alla element från GS1-kodtext och använda den angivna primära nyckeln.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriStem | System::String | Absolut HTTP- eller HTTPS-URI-prefix före den primära nyckeln. |
| kodtext | System::SharedPtr\<GS1Codetext\> | GS1-kodtext vars element kopieras. |
| primaryApplicationIdentifier | System::String | Primärnyckel AI. |

### ReturnValue

En GS1 Digital Link som innehåller de kopierade elementen.

## Se även

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
