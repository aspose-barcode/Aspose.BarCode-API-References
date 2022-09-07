---
title: BarCodeReader
second_title: Référence de l'API Aspose.BarCode pour .NET
description: BarCodeReader encapsule une image pouvant contenir un ou plusieurs codes-barres il peut alors effectuer lopération ReadBarCodes pour détecter les codes-barres.
type: docs
weight: 60
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader encapsule une image pouvant contenir un ou plusieurs codes-barres, il peut alors effectuer l'opération ReadBarCodes pour détecter les codes-barres.

```csharp
public class BarCodeReader : Component
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [BarCodeReader](barcodereader#constructor)() | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe avec les valeurs par défaut. Nécessite de définir l'image (SetBitmapImage()) avant d'appeler la méthode ReadBarCodes(). |
| [BarCodeReader](barcodereader#constructor_1)(Bitmap) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe à partir d'une image. |
| [BarCodeReader](barcodereader#constructor_8)(Stream) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_11)(string) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe du fichier. |
| [BarCodeReader](barcodereader#constructor_2)(Bitmap, BaseDecodeType) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_3)(Bitmap, params BaseDecodeType[]) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_9)(Stream, BaseDecodeType) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_10)(Stream, params BaseDecodeType[]) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_12)(string, BaseDecodeType) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_13)(string, params BaseDecodeType[]) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |
| [BarCodeReader](barcodereader#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Initialise une nouvelle instance du[`BarCodeReader`](../barcodereader) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings) { get; } | Les principaux paramètres de décodage BarCode. Contient des paramètres qui ont une influence sur les données reconnues. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes) { get; } | Est reconnu[`BarCodeResult`](../barcoderesult)tableau de s |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount) { get; } | Obtient le nombre de codes-barres reconnus |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings) { get; set; } | QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings par des préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxBarCodes ou vous pouvez configurer manuellement des options distinctes. La valeur par défaut de QualitySettings est NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout) { get; set; } | Obtient ou définit le délai d'expiration du processus de reconnaissance en millisecondes. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings) { get; } | Obtient les paramètres d'utilisation des cœurs de processeur. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml)(Stream) | Importe les propriétés BarCode du flux xml spécifié et les applique à l'instance actuelle de BarCodeReader. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml_1)(string) | Importe les propriétés BarCode du fichier xml spécifié et les applique à l'instance actuelle de BarCodeReader. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort)() | La fonction demande la fin de la session de reconnaissance en cours à partir d'un autre thread. Abort est une méthode non bloquable et renvoie le contrôle juste après l'appel. La méthode doit être utilisée lorsque le processus de reconnaissance est trop long. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml)(Stream) | Exporte les propriétés du code-barres vers le flux xml spécifié |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml_1)(string) | Exporte les propriétés du code-barres vers le fichier xml spécifié |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes)() | Lectures[`BarCodeResult`](../barcoderesult) s de l'image. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage)(Bitmap) | Définit l'image bitmap pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_3)(Stream) | Définit le flux d'images pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_4)(string) | Définit le fichier image pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_1)(Bitmap, Rectangle) | Définit l'image bitmap et la zone de reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_2)(Bitmap, Rectangle[]) | Définit l'image bitmap et les zones de reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype)(BaseDecodeType) | Définit le type de décodage pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype_1)(params SingleDecodeType[]) | Ensembles[`SingleDecodeType`](../singledecodetype) tableau de type pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* espace de noms [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
