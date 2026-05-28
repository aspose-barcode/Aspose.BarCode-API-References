---
title: BaseGenerationParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres de génération d'image de code-barres.
type: docs
weight: 17
url: /fr/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Paramètres de génération d'image de code-barres.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Spécifie les différents types de modes de dimensionnement automatique. |
| [getBackColor()](#getBackColor--) | Couleur d'arrière-plan de l'image du code-barres. |
| [getBarcode()](#getBarcode--) | Obtient les  BarcodeParameters  qui contiennent toutes les propriétés du code-barres. |
| [getBorder()](#getBorder--) | Obtient les  BorderParameters  qui contiennent toutes les propriétés de configuration pour la bordure du code-barres. |
| [getCaptionAbove()](#getCaptionAbove--) | Légende au-dessus de l'image BarCode. |
| [getCaptionBelow()](#getCaptionBelow--) | Légende en dessous de l'image BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Paramètres d'image. |
| [getImageHeight()](#getImageHeight--) | Hauteur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | Largeur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Obtient la résolution de l'image BarCode. |
| [getRotationAngle()](#getRotationAngle--) | Angle de rotation de l'image BarCode, mesuré en degrés, p. ex. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Obtient une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Spécifie les différents types de modes de dimensionnement automatique. |
| [setBackColor(int value)](#setBackColor-int-) | Couleur d'arrière-plan de l'image du code-barres. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Hauteur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Largeur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Définit la résolution de l'image BarCode. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Angle de rotation de l'image BarCode, mesuré en degrés, p. ex. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Définit une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Spécifie les différents types de modes de dimensionnement automatique. Valeur par défaut : AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Couleur d'arrière-plan de l'image du code-barres. Valeur par défaut : Color.White. Voir Color.

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Obtient les  BarcodeParameters  qui contiennent toutes les propriétés du code-barres.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Obtient les  BorderParameters  qui contiennent toutes les propriétés de configuration pour la bordure du code-barres.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


Légende au-dessus de l'image BarCode. Voir CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Légende en dessous de l'image BarCode. Voir CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getImage() {#getImage--}
```
public ImageParameters getImage()
```


Paramètres d'image. Voir .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Hauteur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Largeur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Obtient la résolution de l'image BarCode. Une valeur pour les deux dimensions. Valeur par défaut : 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Angle de rotation de l'image BarCode, mesuré en degrés, p. ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si RotationAngle n'est PAS égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image. Valeur par défaut : 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Returns:**
float
### getUseAntiAlias() {#getUseAntiAlias--}
```
public boolean getUseAntiAlias()
```


Obtient une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image.

**Returns:**
boolean
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




### setAutoSizeMode(AutoSizeMode value) {#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-}
```
public void setAutoSizeMode(AutoSizeMode value)
```


Spécifie les différents types de modes de dimensionnement automatique. Valeur par défaut : AutoSizeMode.NONE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Couleur d'arrière-plan de l'image du code-barres. Valeur par défaut : Color.White. Voir Color.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Hauteur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Largeur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Définit la résolution de l'image BarCode. Une valeur pour les deux dimensions. Valeur par défaut : 96 dpi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Angle de rotation de l'image BarCode, mesuré en degrés, p. ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si RotationAngle n'est PAS égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image. Valeur par défaut : 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Définit une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

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

