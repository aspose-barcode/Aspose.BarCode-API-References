---
title: "Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder class"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare la classe Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder in C++."
type: docs
weight: 3500
url: /it/cpp/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class




```cpp
class MaxiCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Aggiunge codetext con Identificatore di Canale Esteso |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Aggiunge codetext semplice agli elementi di codetext estesi |
| virtual [Clear](../extcodetextbuilder/clear/)() | Cancella gli elementi di codetext estesi |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genera codetext esteso dall'elenco di codetext estesi. |
## Osservazioni


Generatore di codetext esteso per i codici a barre MaxiCode per la modalità ExtendedCodetext di MaxiCodeEncodeMode

Usa la proprietà TwoDDisplayText di [BarcodeGenerator](../barcodegenerator/) per impostare il testo visibile rimuovendo i caratteri di gestione.

Questo esempio mostra come utilizzare [MaxiCodeExtCodetextBuilder](./) in Modalità Estesa.
```cpp
[C#]
//crea codetext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//genera codetext
string codetext = textBuilder.GetExtendedCodetext();

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Vedi anche

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
