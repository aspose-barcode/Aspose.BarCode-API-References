---
title: "Classe DataMatrixExtCodetextBuilder"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder. Generatore di codetext esteso per codici a barre DataMatrix 2D per la modalità ExtendedCodetext di EncodeMode"
type: docs
weight: 1210
url: /it/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

Generatore di codetext esteso per codici a barre DataMatrix 2D per la modalità ExtendedCodetext di EncodeMode

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Aggiunge il codetext con modalità di codifica definita agli elementi di codetext esteso |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Aggiunge il codetext con Identificatore di Canale Esteso |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Aggiunge il codetext con Identificatore di Canale Esteso con modalità di codifica definita |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Aggiunge il codetext semplice agli elementi di codetext esteso |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Cancella gli elementi di codetext esteso |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Genera il codetext esteso dall'elenco di codetext esteso. |

## Esempi

```csharp
[C#]
//Modalità codetext esteso

//crea codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//genera codetext
string codetext = textBuilder.GetExtendedCodetext();    

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Vedi anche

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


