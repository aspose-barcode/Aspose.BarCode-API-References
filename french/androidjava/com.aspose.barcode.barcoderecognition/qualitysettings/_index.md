---
title: QualitySettings
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance.
type: docs
weight: 44
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez rapidement configurer QualitySettings avec des préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxQuality ou vous pouvez configurer manuellement des options séparées. La valeur par défaut de QualitySettings est NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | Constructeur QualitySettings |
## Champs

| Champ | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Permet au moteur de reconnaître les codes-barres qui ont un checksumm incorrect ou des valeurs incorrectes. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur. |
| [getDeconvolution()](#getDeconvolution--) | Mode Deconvolution (image restorations) qui définit le niveau de dégradation de l'image. |
| [getHighPerformance()](#getHighPerformance--) | Préréglage de qualité de reconnaissance HighPerformance. |
| [getHighQuality()](#getHighQuality--) | Préréglage de qualité de reconnaissance HighQuality. |
| [getImageScalingMode()](#getImageScalingMode--) | Permet de mettre à l'échelle l'image avec le ImageScaleMode spécifique. |
| [getInverseImage()](#getInverseImage--) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images à couleurs inversées (luminance). |
| [getMaxQuality()](#getMaxQuality--) | Préréglage de qualité de reconnaissance MaxQuality. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | Préréglage de qualité de reconnaissance NormalQuality. |
| [getXDimension()](#getXDimension--) | Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Permet au moteur de reconnaître les codes-barres qui ont un checksumm incorrect ou des valeurs incorrectes. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Mode Deconvolution (image restorations) qui définit le niveau de dégradation de l'image. |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | Permet de mettre à l'échelle l'image avec le ImageScaleMode spécifique Valeur : |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images à couleurs inversées (luminance). |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


Constructeur QualitySettings

### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<QualitySettings> CREATOR
```


### describeContents() {#describeContents--}
```
public int describeContents()
```




**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Permet au moteur de reconnaître les codes-barres qui ont un checksumm incorrect ou des valeurs incorrectes. Le mode peut être utilisé pour reconnaître les codes-barres endommagés avec un texte incorrect.

Valeur : Permet au moteur de reconnaître les codes-barres incorrects.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée. Un élément de code-barres de qualité inférieure nécessite des méthodes plus complexes, ce qui ralentit la reconnaissance.

Valeur : Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée.

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplexBackground() {#getComplexBackground--}
```
public ComplexBackgroundMode getComplexBackground()
```


Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur.

Valeur : Reconnaissance supplémentaire des codes-barres couleur sur des images couleur.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Mode Deconvolution (image restorations) qui définit le niveau de dégradation de l'image. À l'origine, la Deconvolution est une fonction qui peut restaurer une image dégradée (convoluée) par n'importe quelle fonction naturelle comme le flou, lors de la capture de l'image par une caméra. Comme nous ne pouvons pas détecter la fonction d'image qui corrompt l'image, nous devons examiner les fonctions les mieux connues comme le sharp ou la morphologie mathématique.

Valeur : Mode Deconvolution qui définit le niveau de dégradation de l'image.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


Préréglage de qualité de reconnaissance HighPerformance. Les codes-barres de haute qualité sont bien reconnus dans ce mode.

--------------------

> ```
> This sample shows how to use HighPerformance mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighPerformance());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Valeur : Préréglage de qualité de reconnaissance HighPerformance.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


Préréglage de qualité de reconnaissance HighQuality. Ce préréglage est développé pour les codes-barres de faible qualité. Permet de détecter les codes-barres fortement endommagés.

--------------------

> ```
> This sample shows how to use HighQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Valeur : préréglage de qualité de reconnaissance HighQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


Permet de mettre à l'échelle l'image avec le ImageScaleMode spécifique.

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images à couleurs inversées (luminance).

Valeur : reconnaissance supplémentaire des codes-barres sur des images avec des couleurs inversées

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


Préréglage de qualité de reconnaissance MaxQuality. Ce préréglage est développé pour reconnaître tous les codes-barres possibles, même les codes-barres incorrects.

--------------------

> ```
> This sample shows how to use MaxQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getMaxQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Valeur : préréglage de qualité de reconnaissance MaxQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension.

Valeur : taille minimale de XDimension en pixels qui est utilisée avec UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


Préréglage de qualité de reconnaissance NormalQuality. Convient à la plupart des codes-barres

--------------------

> ```
> This sample shows how to use NormalQuality mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getNormalQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Valeur : préréglage de qualité de reconnaissance NormalQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre.

Valeur : taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre.

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAllowIncorrectBarcodes(boolean value) {#setAllowIncorrectBarcodes-boolean-}
```
public void setAllowIncorrectBarcodes(boolean value)
```


Permet au moteur de reconnaître les codes-barres qui ont un checksumm incorrect ou des valeurs incorrectes. Le mode peut être utilisé pour reconnaître les codes-barres endommagés avec un texte incorrect.

Valeur : Permet au moteur de reconnaître les codes-barres incorrects.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée. Un élément de code-barres de qualité inférieure nécessite des méthodes plus complexes, ce qui ralentit la reconnaissance.

Valeur : Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur.

Valeur : Reconnaissance supplémentaire des codes-barres couleur sur des images couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Mode Deconvolution (image restorations) qui définit le niveau de dégradation de l'image. À l'origine, la Deconvolution est une fonction qui peut restaurer une image dégradée (convoluée) par n'importe quelle fonction naturelle comme le flou, lors de la capture de l'image par une caméra. Comme nous ne pouvons pas détecter la fonction d'image qui corrompt l'image, nous devons examiner les fonctions les mieux connues comme le sharp ou la morphologie mathématique.

Valeur : Mode Deconvolution qui définit le niveau de dégradation de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


Permet de mettre à l'échelle l'image avec le ImageScaleMode spécifique Valeur :

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.barcode.barcoderecognition.ImageScalingMode | valeur ImageScalingMode |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images à couleurs inversées (luminance).

Valeur : reconnaissance supplémentaire des codes-barres sur des images avec des couleurs inversées

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension.

Valeur : taille minimale de XDimension en pixels qui est utilisée avec UseMinimalXDimension.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre.

Valeur : taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

