---
title: "Aspose::BarCode::Generation::BarcodeGenerator classe"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::BarcodeGenerator classe. BarcodeGenerator per la generazione di immagini di codici a barre backend in C++."
type: docs
weight: 400
url: /it/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Crea un'istanza di [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Crea un'istanza di [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Libera tutte le risorse in uso. |
| [ExportToXml](./exporttoxml/)(System::String) | Esporta le proprietà di [BarCode](../../aspose.barcode/) nel file XML specificato |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Esporta le proprietà di [BarCode](../../aspose.barcode/) nello stream XML specificato |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Genera l'immagine del codice a barre con le impostazioni correnti. |
| [get_BarcodeType](./get_barcodetype/)() | Tipo di simbologia del codice a barre. |
| [get_CodeText](./get_codetext/)() | Testo da codificare. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) parametri. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importa le proprietà di [BarCode](../../aspose.barcode/) dal file XML specificato e crea un'istanza di [BarcodeGenerator](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importa le proprietà di [BarCode](../../aspose.barcode/) dallo stream XML specificato e crea un'istanza di [BarcodeGenerator](./). |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Salva l'immagine del codice a barre nello stream in un formato specifico. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Salva l'immagine del codice a barre in un file specifico in un formato specifico. |
| [Save](./save/)(System::String) | Salva l'immagine del codice a barre in un file specifico. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Tipo di simbologia del codice a barre. |
| [set_CodeText](./set_codetext/)(System::String) | Testo da codificare. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Imposta il testo del codice come sequenza di byte. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Osservazioni


simboli supportati: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

Questo esempio mostra come creare e salvare un'immagine di codice a barre.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
