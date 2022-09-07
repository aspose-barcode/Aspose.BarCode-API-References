---
title: BarCodeReader
second_title: Riferimento all'API Aspose.BarCode per .NET
description: BarCodeReader incapsula unimmagine che può contenere uno o più codici a barre quindi può eseguire loperazione ReadBarCodes per rilevare i codici a barre.
type: docs
weight: 60
url: /it/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader incapsula un'immagine che può contenere uno o più codici a barre, quindi può eseguire l'operazione ReadBarCodes per rilevare i codici a barre.

```csharp
public class BarCodeReader : Component
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BarCodeReader](barcodereader#constructor)() | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe con valori predefiniti. Richiede di impostare l'immagine (SetBitmapImage()) prima di chiamare il metodo ReadBarCodes(). |
| [BarCodeReader](barcodereader#constructor_1)(Bitmap) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe da un'immagine. |
| [BarCodeReader](barcodereader#constructor_8)(Stream) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_11)(string) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe dal file. |
| [BarCodeReader](barcodereader#constructor_2)(Bitmap, BaseDecodeType) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_3)(Bitmap, params BaseDecodeType[]) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_9)(Stream, BaseDecodeType) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_10)(Stream, params BaseDecodeType[]) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_12)(string, BaseDecodeType) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_13)(string, params BaseDecodeType[]) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Inizializza una nuova istanza di[`BarCodeReader`](../barcodereader) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings) { get; } | I principali parametri di decodifica del codice a barre. Contiene parametri che influenzano i dati riconosciuti. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes) { get; } | Viene riconosciuto[`BarCodeResult`](../barcoderesult)matrice di s |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount) { get; } | Ottiene il conteggio dei codici a barre riconosciuti |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings) { get; set; } | QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings tramite i preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure è possibile configurare manualmente opzioni separate. Il valore predefinito di QualitySettings è NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout) { get; set; } | Ottiene o imposta il timeout del processo di riconoscimento in millisecondi. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings) { get; } | Ottiene le impostazioni per l'utilizzo dei core del processore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml)(Stream) | Importa le proprietà BarCode dal flusso xml specificato e le applica all'istanza BarCodeReader corrente. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml_1)(string) | Importa le proprietà BarCode dal file xml specificato e le applica all'istanza BarCodeReader corrente. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort)() | La funzione richiede la terminazione della sessione di riconoscimento corrente da un altro thread. Abort è un metodo non bloccabile e restituisce il controllo subito dopo la chiamata. Il metodo dovrebbe essere utilizzato quando il processo di riconoscimento è troppo lungo. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml)(Stream) | Esporta le proprietà del codice a barre nel flusso xml specificato |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml_1)(string) | Esporta le proprietà del codice a barre nel file xml specificato |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes)() | legge[`BarCodeResult`](../barcoderesult) s dall'immagine. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage)(Bitmap) | Imposta l'immagine bitmap per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_3)(Stream) | Imposta il flusso di immagini per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_4)(string) | Imposta il file immagine per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_1)(Bitmap, Rectangle) | Imposta l'immagine bitmap e l'area per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_2)(Bitmap, Rectangle[]) | Imposta l'immagine bitmap e le aree per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype)(BaseDecodeType) | Imposta il tipo di decodifica per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype_1)(params SingleDecodeType[]) | Set[`SingleDecodeType`](../singledecodetype) digitare array per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes(). |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Guarda anche

* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
