---
title: "Classe Aspose::BarCode::BarCodeRecognition::BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Classe Aspose::BarCode::BarCodeRecognition::BarCodeReader. BarCodeReader incapsula un'immagine che può contenere uno o più codici a barre, e può quindi eseguire l'operazione ReadBarCodes per rilevare i codici a barre in C++."
type: docs
weight: 500
url: /it/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Abort](./abort/)() | La funzione richiede la terminazione della sessione di riconoscimento corrente da un altro thread. Abort è un metodo non bloccabile e restituisce il controllo subito dopo la chiamata. Il metodo dovrebbe essere utilizzato quando il processo di riconoscimento è troppo lungo. |
| [BarCodeReader](./barcodereader/)() | Inizializza una nuova istanza della classe [BarCodeReader](./) con valori predefiniti. È necessario impostare l'immagine (SetBitmapImage()) prima di chiamare il metodo [ReadBarCodes()](./readbarcodes/). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Inizializza una nuova istanza della classe [BarCodeReader](./) a partire da un'immagine. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String) | Inizializza una nuova istanza della classe [BarCodeReader](./) da un file. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inizializza una nuova istanza della classe [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | Inizializza una nuova istanza della classe [BarCodeReader](./) da un frame di luminanza. |
| [Dispose](./dispose/)() override | Rilascia risorsa |
| [ExportToXml](./exporttoxml/)(System::String) | Esporta le proprietà di [BarCode](../../aspose.barcode/) nel file XML specificato |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Esporta le proprietà di [BarCode](../../aspose.barcode/) nello stream XML specificato |
| [get_BarCodeReadType](./get_barcodereadtype/)() | Ottiene il tipo di decodifica del codice a barre utilizzato per il riconoscimento. Deve essere impostato prima di chiamare [ReadBarCodes](./readbarcodes/). |
| [get_BarcodeSettings](./get_barcodesettings/)() | I principali parametri di decodifica di [BarCode](../../aspose.barcode/). Contiene parametri che influenzano i dati riconosciuti. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Ottiene l'array di [BarCodeResult](../barcoderesult/) riconosciuti |
| [get_FoundCount](./get_foundcount/)() | Ottiene il conteggio dei codici a barre riconosciuti |
| static [get_ProcessorSettings](./get_processorsettings/)() | Ottiene le impostazioni per l'uso dei core del processore. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente [QualitySettings](../qualitysettings/) tramite preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure configurare manualmente opzioni separate. Il valore predefinito di [QualitySettings](../qualitysettings/) è NormalQuality. |
| [get_Timeout](./get_timeout/)() | Ottiene il timeout del processo di riconoscimento in millisecondi. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importa le proprietà di [BarCode](../../aspose.barcode/) dal file XML specificato e le applica all'istanza corrente di [BarCodeReader](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importa le proprietà di [BarCode](../../aspose.barcode/) dallo stream XML specificato e le applica all'istanza corrente di [BarCodeReader](./). |
| [ReadBarCodes](./readbarcodes/)() | Legge i [BarCodeResult](../barcoderesult/) dall'immagine. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Imposta il tipo di decodifica del codice a barre utilizzato per il riconoscimento. Deve essere impostato prima di chiamare [ReadBarCodes](./readbarcodes/). |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente [QualitySettings](../qualitysettings/) tramite preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure configurare manualmente opzioni separate. Il valore predefinito di [QualitySettings](../qualitysettings/) è NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | Imposta il timeout del processo di riconoscimento in millisecondi. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Imposta l'immagine bitmap per il riconoscimento. Deve essere chiamato prima del metodo [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Imposta l'immagine bitmap e le aree per il riconoscimento. Deve essere chiamato prima del metodo [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Imposta l'immagine bitmap e l'area per il riconoscimento. Deve essere chiamato prima del metodo [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Imposta il file immagine per il riconoscimento. Deve essere chiamato prima del metodo [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Imposta lo stream immagine per il riconoscimento. Deve essere chiamato prima del metodo [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | Imposta il frame di luminanza e l'area per il riconoscimento. Deve essere chiamato prima del metodo [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Imposta il frame di luminanza e le aree per il riconoscimento. Deve essere chiamato prima del metodo [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | Imposta il frame di luminanza per il riconoscimento. Deve essere chiamato prima del metodo [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Imposta l'array di tipi [SingleDecodeType](../singledecodetype/) per il riconoscimento. Deve essere chiamato prima del metodo [ReadBarCodes()](./readbarcodes/). |
## Osservazioni


Questo esempio mostra come rilevare i codici a barre Code39 e Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
