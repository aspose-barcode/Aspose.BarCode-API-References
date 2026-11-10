---
title: "Classe BarCodeReader"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.BarCodeReader. BarCodeReader encapsule une image qui peut contenir un ou plusieurs codes-barres, puis peut exécuter l'opération ReadBarCodes pour détecter les codes-barres"
type: docs
weight: 70
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader encapsule une image pouvant contenir un ou plusieurs codes‑barres, puis peut exécuter l'opération ReadBarCodes pour détecter les codes‑barres.

```csharp
public class BarCodeReader : Component
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | Initialise une nouvelle instance de la classe `BarCodeReader` avec les valeurs par défaut. Il faut définir l'image (SetBitmapImage()) avant d'appeler la méthode ReadBarCodes(). |
| [BarCodeReader](barcodereader/#constructor_8)(Bitmap) | Initialise une nouvelle instance de la classe `BarCodeReader` à partir d'une image. |
| [BarCodeReader](barcodereader/#constructor_1)(LuminanceFrame) | Initialise une nouvelle instance de la classe `BarCodeReader` à partir d'une trame de luminance. |
| [BarCodeReader](barcodereader/#constructor_15)(Stream) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_18)(string) | Initialise une nouvelle instance de la classe `BarCodeReader` à partir d'un fichier. |
| [BarCodeReader](barcodereader/#constructor_9)(Bitmap, BaseDecodeType) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_10)(Bitmap, params BaseDecodeType[]) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_2)(LuminanceFrame, BaseDecodeType) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_3)(LuminanceFrame, params BaseDecodeType[]) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_16)(Stream, BaseDecodeType) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_17)(Stream, params BaseDecodeType[]) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_19)(string, BaseDecodeType) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_20)(string, params BaseDecodeType[]) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_11)(Bitmap, Rectangle, BaseDecodeType) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_12)(Bitmap, Rectangle, params BaseDecodeType[]) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_13)(Bitmap, Rectangle[], BaseDecodeType) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_14)(Bitmap, Rectangle[], params BaseDecodeType[]) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_4)(LuminanceFrame, Rectangle, BaseDecodeType) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_5)(LuminanceFrame, Rectangle, params BaseDecodeType[]) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_6)(LuminanceFrame, Rectangle[], BaseDecodeType) | Initialise une nouvelle instance de la classe `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_7)(LuminanceFrame, Rectangle[], params BaseDecodeType[]) | Initialise une nouvelle instance de la classe `BarCodeReader`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/) { get; set; } | Obtient ou définit le type de décodage du code-barres utilisé pour la reconnaissance. Doit être défini avant d'appeler [`ReadBarCodes`](./readbarcodes/). |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | Les principaux paramètres de décodage BarCode. Contient des paramètres qui influencent les données reconnues. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Obtient le tableau des [`BarCodeResult`](../barcoderesult/) reconnus |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Obtient le nombre de codes-barres reconnus |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings permet de configurer manuellement la qualité et la vitesse de la reconnaissance. Vous pouvez rapidement configurer QualitySettings à l'aide des préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxBarCodes ou vous pouvez configurer manuellement des options séparées. La valeur par défaut de QualitySettings est NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Obtient ou définit le délai d'attente du processus de reconnaissance en millisecondes. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | Obtient les paramètres d'utilisation des cœurs du processeur. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Importe les propriétés BarCode depuis le flux XML spécifié et les applique à l'instance actuelle de BarCodeReader. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Importe les propriétés BarCode depuis le fichier XML spécifié et les applique à l'instance actuelle de BarCodeReader. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | La fonction demande la terminaison de la session de reconnaissance en cours depuis un autre thread. Abort est une méthode non bloquable et rend le contrôle immédiatement après l'appel. Cette méthode doit être utilisée lorsque le processus de reconnaissance est trop long. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | Exporte les propriétés BarCode vers le flux XML spécifié |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | Exporte les propriétés BarCode vers le fichier XML spécifié |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | Lit les [`BarCodeResult`](../barcoderesult/) depuis l'image. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Bitmap) | Définit l'image bitmap pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(LuminanceFrame) | Définit le cadre de luminance pour la reconnaissance. Doit être appelé avant la méthode [`ReadBarCodes`](./readbarcodes/). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_6)(Stream) | Définit le flux d'image pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_7)(string) | Définit le fichier d'image pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(Bitmap, Rectangle) | Définit l'image bitmap et la zone pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_5)(Bitmap, Rectangle[]) | Définit l'image bitmap et les zones pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(LuminanceFrame, Rectangle) | Définit le cadre de luminance et la zone pour la reconnaissance. Doit être appelé avant la méthode [`ReadBarCodes`](./readbarcodes/). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(LuminanceFrame, Rectangle[]) | Définit le cadre de luminance et les zones pour la reconnaissance. Doit être appelé avant la méthode [`ReadBarCodes`](./readbarcodes/). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/)(params SingleDecodeType[]) | Définit le tableau de type [`SingleDecodeType`](../singledecodetype/) pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

```csharp
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

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


