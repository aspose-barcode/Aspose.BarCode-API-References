---
title: "Classe Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare la classe Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder in C++."
type: docs
weight: 1900
url: /it/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Aggiunge codetext con modalità di codifica definita agli elementi di codetext estesi |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Aggiunge codetext con Identificatore di Canale Esteso |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Aggiunge codetext con Identificatore di Canale Esteso con modalità di codifica definita |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Aggiunge codetext semplice agli elementi di codetext estesi |
| virtual [Clear](../extcodetextbuilder/clear/)() | Cancella gli elementi di codetext estesi |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genera codetext esteso dall'elenco di codetext estesi. |
## Osservazioni


Generatore di codetext esteso per codici a barre 2D DataMatrix per la modalità ExtendedCodetext di EncodeMode


```cpp
[C#]
//Modalità codetext estesa

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

## Vedi anche

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
