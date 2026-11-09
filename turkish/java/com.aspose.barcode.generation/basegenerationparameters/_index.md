---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Barkod görüntüsü oluşturma parametreleri."
type: docs
weight: 17
url: /tr/java/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Barkod görüntüsü oluşturma parametreleri.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Otomatik boyutlandırma modlarının farklı türlerini belirtir. |
| [getBackColor()](#getBackColor--) | Barkod görüntüsünün arka plan rengi. |
| [getBarcode()](#getBarcode--) | Tüm barkod özelliklerini içeren  BarcodeParameters  nesnesini alır. |
| [getBorder()](#getBorder--) | Barkod kenarı için tüm yapılandırma özelliklerini içeren  BorderParameters  nesnesini alır. |
| [getCaptionAbove()](#getCaptionAbove--) | BarCode görüntüsünün üzerindeki başlık. |
| [getCaptionBelow()](#getCaptionBelow--) | BarCode görüntüsünün altındaki başlık. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Görüntü parametreleri. |
| [getImageHeight()](#getImageHeight--) | AutoSizeMode özelliği AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION olarak ayarlandığında BarCode görüntüsünün yüksekliği. |
| [getImageWidth()](#getImageWidth--) | AutoSizeMode özelliği AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION olarak ayarlandığında BarCode görüntüsünün genişliği. |
| [getResolution()](#getResolution--) | BarCode görüntüsünün çözünürlüğünü alır. |
| [getRotationAngle()](#getRotationAngle--) | BarCode görüntüsü dönüş açısı, derece cinsinden ölçülür, örn. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Görüntüyü işlemek için anti-aliasing modunun kullanılıp kullanılmadığını gösteren bir değeri alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Otomatik boyutlandırma modlarının farklı türlerini belirtir. |
| [setBackColor(Color value)](#setBackColor-java.awt.Color-) | Barkod görüntüsünün arka plan rengi. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | AutoSizeMode özelliği AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION olarak ayarlandığında BarCode görüntüsünün yüksekliği. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | AutoSizeMode özelliği AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION olarak ayarlandığında BarCode görüntüsünün genişliği. |
| [setResolution(float value)](#setResolution-float-) | BarCode görüntüsünün çözünürlüğünü ayarlar. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | BarCode görüntüsü dönüş açısı, derece cinsinden ölçülür, örn. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Görüntüyü renderlamak için anti-aliasing modunun kullanılıp kullanılmadığını gösteren bir değer ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Otomatik boyutlandırma modlarının farklı türlerini belirtir. Varsayılan değer: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public Color getBackColor()
```


Barkod görüntüsünün arka plan rengi. Varsayılan değer: Color.White. Bakınız Color.

**Returns:**
java.awt.Color
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Tüm barkod özelliklerini içeren  BarcodeParameters  nesnesini alır.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Barkod kenarı için tüm yapılandırma özelliklerini içeren  BorderParameters  nesnesini alır.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


BarCode görüntüsünün üzerindeki başlık. Bakınız CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


BarCode görüntüsünün altındaki başlık. Bakınız CaptionParameters.

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


Görüntü parametreleri. Bakınız.

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


AutoSizeMode özelliği AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION olarak ayarlandığında BarCode görüntüsünün yüksekliği.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


AutoSizeMode özelliği AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION olarak ayarlandığında BarCode görüntüsünün genişliği.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


BarCode görüntüsünün çözünürlüğünü alır. Her iki boyut için tek bir değer. Varsayılan değer: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


BarCode görüntüsünün döndürme açısı, derece cinsinden ölçülür, örn. RotationAngle = 0 veya RotationAngle = 360 döndürme olmadığını gösterir. RotationAngle 90, 180, 270 veya 0'a eşit değilse, tarayıcının görüntüyü okumasını zorlaştırabilir. Varsayılan değer: 0.

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


Görüntüyü işlemek için anti-aliasing modunun kullanılıp kullanılmadığını gösteren bir değeri alır.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
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


Otomatik boyutlandırma modlarının farklı türlerini belirtir. Varsayılan değer: AutoSizeMode.NONE.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(Color value) {#setBackColor-java.awt.Color-}
```
public void setBackColor(Color value)
```


Barkod görüntüsünün arka plan rengi. Varsayılan değer: Color.White. Bakınız Color.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


AutoSizeMode özelliği AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION olarak ayarlandığında BarCode görüntüsünün yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


AutoSizeMode özelliği AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION olarak ayarlandığında BarCode görüntüsünün genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


BarCode görüntüsünün çözünürlüğünü ayarlar. Her iki boyut için tek bir değer. Varsayılan değer: 96 dpi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


BarCode görüntüsünün döndürme açısı, derece cinsinden ölçülür, örn. RotationAngle = 0 veya RotationAngle = 360 döndürme olmadığını gösterir. RotationAngle 90, 180, 270 veya 0'a eşit değilse, tarayıcının görüntüyü okumasını zorlaştırabilir. Varsayılan değer: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Görüntüyü renderlamak için anti-aliasing modunun kullanılıp kullanılmadığını gösteren bir değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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
public final native void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

