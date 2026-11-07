---
title: "method"
linktitle: "Create"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Создает GS1 Digital Link, копируя все элементы из GS1 codetext и выбирая единственный доступный первичный ключ в C++."
type: docs
weight: 2100
url: /ru/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


Создаёт GS1 Digital Link, копируя все элементы из GS1 codetext и выбирая единственный доступный основной ключ.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| uriStem | System::String | Абсолютный префикс HTTP или HTTPS URI перед первичным ключом. |
| codetext | System::SharedPtr\<GS1Codetext\> | GS1 codetext, элементы которого копируются. |

### ReturnValue

GS1 Digital Link, содержащий скопированные элементы.

## См. также

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


Создаёт GS1 Digital Link, копируя все элементы из GS1 codetext и используя указанный основной ключ.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| uriStem | System::String | Абсолютный префикс HTTP или HTTPS URI перед первичным ключом. |
| codetext | System::SharedPtr\<GS1Codetext\> | GS1 codetext, элементы которого копируются. |
| primaryApplicationIdentifier | System::String | AI первичного ключа. |

### ReturnValue

GS1 Digital Link, содержащий скопированные элементы.

## См. также

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
