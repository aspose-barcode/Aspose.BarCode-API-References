---
title: "classe Aspose::BarCode::Generation::QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare la classe Aspose::BarCode::Generation::QrExtCodetextBuilder in C++."
type: docs
weight: 4300
url: /it/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | Aggiunge il testo del codice con la modalità di compattazione QR specificata agli elementi di testo del codice esteso. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Aggiunge codetext con Identificatore di Canale Esteso |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | Imposta FNC1 nella prima posizione. Se un altro modo FNC1 era stato impostato prima, viene sostituito. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Aggiunge il separatore di gruppo (GS - '\u001D') agli elementi di codetext estesi |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | Imposta FNC1 nella seconda posizione. Se un altro modo FNC1 era stato impostato prima, viene sostituito. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Aggiunge codetext semplice agli elementi di codetext estesi |
| [Clear](./clear/)() override | Cancella gli elementi di codetext estesi |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genera codetext esteso dall'elenco di codetext estesi. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## Osservazioni


Generatore di codetext esteso per codici QR 2D per la modalità ExtendedCodetext di EncodeMode

Usa la proprietà TwoDDisplayText di [BarcodeGenerator](../barcodegenerator/) per impostare il testo visibile rimuovendo i caratteri di gestione.

Questo esempio mostra come utilizzare la prima posizione FNC1 in Modalità Estesa.
```cpp
[C#]
//crea codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//genera codetext
string codetext = TextBuilder.GetExtendedCodetext();

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Questo esempio mostra come utilizzare la seconda posizione FNC1 in Modalità Estesa.
```cpp
[C#]
//crea codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//genera codetext
string codetext = TextBuilder.GetExtendedCodetext();

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Questo esempio mostra come utilizzare la modalità multi ECI in Modalità Estesa.
```cpp
[C#]
//crea codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//genera codetext
string codetext = TextBuilder.GetExtendedCodetext();

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Vedi anche

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
