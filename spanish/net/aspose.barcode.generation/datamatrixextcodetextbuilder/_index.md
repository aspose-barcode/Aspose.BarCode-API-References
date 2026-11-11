---
title: "Clase DataMatrixExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder. Generador de codetexto extendido para códigos de barras 2D DataMatrix en el modo ExtendedCodetext de EncodeMode."
type: docs
weight: 1210
url: /es/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

Generador de codetexto extendido para códigos de barras 2D DataMatrix para ExtendedCodetext Mode de EncodeMode

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Agrega codetexto con modo de codificación definido a los elementos de codetexto extendido |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Agrega codetexto con Identificador de Canal Extendido |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Agrega codetexto con Identificador de Canal Extendido con modo de codificación definido |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Agrega codetexto simple a los elementos de codetexto extendido |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Borra los elementos de codetexto extendido |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Genera codetexto extendido a partir de la lista de codetexto extendido. |

## Ejemplos

```csharp
[C#]
//Modo codetext Extendido

//crear codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//generar codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Ver también

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


