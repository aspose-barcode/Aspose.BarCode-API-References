---
title: "método"
linktitle: "Crear"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Crea un Enlace Digital GS1 copiando todos los elementos del codetext GS1 y seleccionando la única clave primaria disponible en C++."
type: docs
weight: 2100
url: /es/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


Crea un GS1 Digital Link copiando todos los elementos del texto de código GS1 y seleccionando la única clave primaria disponible.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriStem | System::String | Prefijo de URI HTTP o HTTPS absoluto antes de la clave primaria. |
| codetext | System::SharedPtr\<GS1Codetext\> | Codetext GS1 cuyos elementos son copiados. |

### ReturnValue

Un GS1 Digital Link que contiene los elementos copiados.

## Ver también

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


Crea un GS1 Digital Link copiando todos los elementos del texto de código GS1 y usando la clave primaria especificada.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriStem | System::String | Prefijo de URI HTTP o HTTPS absoluto antes de la clave primaria. |
| codetext | System::SharedPtr\<GS1Codetext\> | Codetext GS1 cuyos elementos son copiados. |
| primaryApplicationIdentifier | System::String | AI de clave primaria. |

### ReturnValue

Un GS1 Digital Link que contiene los elementos copiados.

## Ver también

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
