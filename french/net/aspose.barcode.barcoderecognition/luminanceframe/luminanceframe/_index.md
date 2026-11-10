---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Constructeur LuminanceFrame. Initialise une nouvelle instance de la classe LuminanceFrame sans remplissage entre les lignes. La distance entre les lignes adjacentes est égale à la largeur"
type: docs
weight: 10
url: /fr/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Initialise une nouvelle instance de la classe [`LuminanceFrame`](../) sans remplissage entre les lignes. La distance entre les lignes adjacentes est égale à *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| data | Byte[] | Les données de luminance contenant un octet par pixel. |
| width | Int32 | La largeur du cadre en pixels. |
| height | Int32 | La hauteur du cadre en pixels. |
| rotationDegrees | Int32 | La rotation horaire requise pour afficher le cadre à l'endroit. Les valeurs prises en charge sont 0, 90, 180 et 270. La valeur par défaut est 0. |

### Voir aussi

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Initialise une nouvelle instance de la classe [`LuminanceFrame`](../) avec le row stride spécifié.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| data | Byte[] | Les données de luminance contenant un octet par pixel. |
| width | Int32 | La largeur du cadre en pixels. |
| height | Int32 | La hauteur du cadre en pixels. |
| rowStride | Int32 | La distance en octets entre les débuts de deux lignes adjacentes. La valeur ne peut pas être inférieure à *width*. |
| rotationDegrees | Int32 | La rotation horaire requise pour afficher le cadre à l'endroit. Les valeurs prises en charge sont 0, 90, 180 et 270. |

### Voir aussi

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


