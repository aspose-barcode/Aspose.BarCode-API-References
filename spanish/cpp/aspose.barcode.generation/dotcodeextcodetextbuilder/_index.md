---
title: "Clase Aspose::BarCode::Generation::DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar la clase Aspose::BarCode::Generation::DotCodeExtCodetextBuilder en C++."
type: docs
weight: 2100
url: /es/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Agrega texto de código con Identificador de Canal Extendido |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Agrega el identificador de formato FNC1 a los elementos de codetext extendido |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Agrega la inicialización del lector FNC3 a los elementos de codetext extendido |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Agrega el separador de símbolo FNC3 a los elementos de codetext extendido |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Agrega texto de código simple a los elementos de texto de código extendido |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Agrega el modo de anexado estructurado a los elementos de codetext extendido |
| virtual [Clear](../extcodetextbuilder/clear/)() | Borra los elementos de texto de código extendido |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genera texto de código extendido a partir de la lista de texto de código extendido. |
## Observaciones


Generador de codetext extendido para códigos de barras 2D DotCode para el modo ExtendedCodetext de DotCodeEncodeMode


```cpp
[C#]
//Modo de texto de código extendido
//crear texto de código
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//generar texto de código
string codetext = textBuilder.GetExtendedCodetext();

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Ver también

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
