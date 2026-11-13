---
title: "QualitySettings"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance.<br/>            Vous pouvez configurer rapidement QualitySettings avec les préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxQuality ou vous pouvez configurer manuellement des options séparées.<br/>            La valeur par défaut de QualitySettings est NormalQuality.

Le type QualitySettings expose les membres suivants :
## Properties
| Name | Description |
| :- | :- |
| high_performance | Préréglage de qualité de reconnaissance HighPerformance. Les codes-barres de haute qualité sont bien reconnus dans ce mode. |
| normal_quality | Préréglage de qualité de reconnaissance NormalQuality. Convient à la plupart des codes-barres |
| high_quality | Préréglage de qualité de reconnaissance HighQuality. Ce préréglage est développé pour les codes-barres de faible qualité. Permet de détecter les codes-barres fortement endommagés. |
| max_quality | Préréglage de qualité de reconnaissance MaxQuality. Ce préréglage est développé pour reconnaître tous les codes-barres possibles, même les codes-barres incorrects. |
| x_dimension | Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre. |
| minimal_x_dimension | Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension. |
| barcode_quality | Mode qui active les méthodes permettant de reconnaître les éléments du code-barres avec la qualité sélectionnée. Un élément de code-barres de qualité inférieure nécessite des méthodes plus lourdes, ce qui ralentit la reconnaissance. |
| deconvolution | Mode de déconvolution (restauration d'image) qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction qui peut restaurer une image dégradée <br/>            (convoluée) par toute fonction naturelle comme le flou, lors de la capture de l'image par la caméra. Comme nous ne pouvons pas détecter la fonction d'image qui corrompt l'image, <br/>            nous devons vérifier les fonctions les mieux connues comme le net ou la morphologie mathématique. |
| inverse_image | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images avec des couleurs inversées (luminance). |
| complex_background | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur. |
| allow_incorrect_barcodes | Permet au moteur de reconnaître les codes-barres qui ont une somme de contrôle ou des valeurs incorrectes. Le mode peut être utilisé pour reconnaître les codes-barres endommagés avec un texte incorrect. |

### Voir aussi

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

