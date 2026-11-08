---
title: "Clase Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar la clase Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Agrega codetext con modo de codificación definido a los elementos de codetext extendido |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Agrega texto de código con Identificador de Canal Extendido |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Agrega codetext con Identificador de Canal Extendido con modo de codificación definido |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Agrega texto de código simple a los elementos de texto de código extendido |
| virtual [Clear](../extcodetextbuilder/clear/)() | Borra los elementos de texto de código extendido |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genera texto de código extendido a partir de la lista de texto de código extendido. |
## Observaciones


Generador de codetext extendido para códigos de barras 2D DataMatrix para el modo ExtendedCodetext de EncodeMode


```cpp
[C#]
//Modo de texto de código extendido

//crear texto de código
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//generar texto de código
string codetext = textBuilder.GetExtendedCodetext();

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Ver también

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
