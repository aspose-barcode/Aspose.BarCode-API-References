---
title: "Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder clase"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar la clase Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder en C++."
type: docs
weight: 3500
url: /es/cpp/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class




```cpp
class MaxiCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Agrega texto de código con Identificador de Canal Extendido |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Agrega texto de código simple a los elementos de texto de código extendido |
| virtual [Clear](../extcodetextbuilder/clear/)() | Borra los elementos de texto de código extendido |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genera texto de código extendido a partir de la lista de texto de código extendido. |
## Observaciones


Generador de texto de código extendido para códigos de barras MaxiCode para el modo ExtendedCodetext de MaxiCodeEncodeMode

Use la propiedad TwoDDisplayText de [BarcodeGenerator](../barcodegenerator/) para establecer el texto visible al eliminar caracteres de gestión.

Este ejemplo muestra cómo usar [MaxiCodeExtCodetextBuilder](./) en modo extendido.
```cpp
[C#]
//crear texto de código
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generar texto de código
string codetext = textBuilder.GetExtendedCodetext();

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Ver también

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
