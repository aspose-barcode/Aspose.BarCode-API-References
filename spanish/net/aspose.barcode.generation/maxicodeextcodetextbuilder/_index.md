---
title: "Clase MaxiCodeExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.MaxiCodeExtCodetextBuilder. Generador de texto extendido para códigos de barras MaxiCode en el modo ExtendedCodetext de MaxiCodeEncodeMode"
type: docs
weight: 1470
url: /es/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

Generador de codetexto extendido para códigos de barras MaxiCode para ExtendedCodetext Mode de MaxiCodeEncodeMode

Utilice la propiedad TwoDDisplayText de BarcodeGenerator para establecer el texto visible eliminando los caracteres de gestión.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Agrega codetexto con Identificador de Canal Extendido |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Agrega codetexto simple a los elementos de codetexto extendido |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Borra los elementos de codetexto extendido |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | Genera codetexto extendido a partir de la lista de codetexto extendido. |

## Ejemplos

Este ejemplo muestra cómo usar MaxiCodeExtCodetextBuilder en modo extendido.

```csharp
[C#]
//crear codetext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generar codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Ver también

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


