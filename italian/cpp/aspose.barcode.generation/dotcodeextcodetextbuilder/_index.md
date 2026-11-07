---
title: "classe Aspose::BarCode::Generation::DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare la classe Aspose::BarCode::Generation::DotCodeExtCodetextBuilder in C++."
type: docs
weight: 2100
url: /it/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Aggiunge codetext con Identificatore di Canale Esteso |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Aggiunge l'identificatore di formato FNC1 agli elementi di codetext esteso |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Aggiunge l'inizializzazione del lettore FNC3 agli elementi di codetext esteso |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Aggiunge il separatore di simboli FNC3 agli elementi di codetext esteso |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Aggiunge codetext semplice agli elementi di codetext estesi |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Aggiunge la modalità di aggiunta strutturata agli elementi di codetext esteso |
| virtual [Clear](../extcodetextbuilder/clear/)() | Cancella gli elementi di codetext estesi |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genera codetext esteso dall'elenco di codetext estesi. |
## Osservazioni


Generatore di codetext esteso per codici a barre 2D DotCode per la modalità ExtendedCodetext di DotCodeEncodeMode


```cpp
[C#]
//Modalità codetext estesa
//crea codetext
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

//genera codetext
string codetext = textBuilder.GetExtendedCodetext();

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Vedi anche

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
