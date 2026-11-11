---
title: "Clase AztecExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.AztecExtCodetextBuilder. Generador de codetexto extendido para códigos de barras Aztec en el modo ExtendedCodetext de AztecEncodeMode."
type: docs
weight: 950
url: /es/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

Generador de texto de código extendido para códigos de barras Aztec para el modo ExtendedCodetext de AztecEncodeMode

Utilice la propiedad TwoDDisplayText de BarcodeGenerator para establecer el texto visible eliminando los caracteres de gestión.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Agrega codetexto con Identificador de Canal Extendido |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Agrega codetexto simple a los elementos de codetexto extendido |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Borra los elementos de codetexto extendido |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | Genera codetexto extendido a partir de la lista de codetexto extendido. |

## Ejemplos

Este ejemplo muestra cómo usar AztecExtCodetextBuilder en modo Extendido.

```csharp
[C#]
//crear codetext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generar codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Ver también

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


