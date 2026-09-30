---
title:  method
linktitle: Create
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Creates a GS1 Digital Link by copying all elements from GS1 codetext and selecting the only available primary key in C++.'
type: docs
weight: 2100
url: /cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


Creates a GS1 Digital Link by copying all elements from GS1 codetext and selecting the only available primary key.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uriStem | System::String | Absolute HTTP or HTTPS URI prefix before the primary key. |
| codetext | System::SharedPtr\<GS1Codetext\> | GS1 codetext whose elements are copied. |

### ReturnValue

A GS1 Digital Link containing the copied elements.

## See Also

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


Creates a GS1 Digital Link by copying all elements from GS1 codetext and using the specified primary key.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uriStem | System::String | Absolute HTTP or HTTPS URI prefix before the primary key. |
| codetext | System::SharedPtr\<GS1Codetext\> | GS1 codetext whose elements are copied. |
| primaryApplicationIdentifier | System::String | Primary key AI. |

### ReturnValue

A GS1 Digital Link containing the copied elements.

## See Also

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
