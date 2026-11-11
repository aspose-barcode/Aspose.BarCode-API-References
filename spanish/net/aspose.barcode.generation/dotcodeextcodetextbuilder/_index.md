---
title: "Clase DotCodeExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.DotCodeExtCodetextBuilder. Generador de codetexto extendido para códigos de barras 2D DotCode en modo ExtendedCodetext de DotCodeEncodeMode"
type: docs
weight: 1250
url: /es/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

Generador de codetexto extendido para códigos de barras 2D DotCode para ExtendedCodetext Mode de DotCodeEncodeMode

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Agrega codetexto con Identificador de Canal Extendido |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | Añade el identificador de formato FNC1 a los elementos de codetexto extendido |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | Añade la inicialización del lector FNC3 a los elementos de codetexto extendido |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | Añade el separador de símbolo FNC3 a los elementos de codetexto extendido |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Agrega codetexto simple a los elementos de codetexto extendido |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | Añade el modo de anexado estructurado a los elementos de codetexto extendido |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Borra los elementos de codetexto extendido |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | Genera codetexto extendido a partir de la lista de codetexto extendido. |

## Ejemplos

```csharp
[C#]
//Modo codetext Extendido
//crear codetext
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

//generar codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Ver también

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


