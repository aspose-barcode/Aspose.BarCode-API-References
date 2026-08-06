---
title: BaseGenerationParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Barcode image generation parameters.
type: docs
weight: 17
url: /ja/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Barcode image generation parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | 自動サイズモードのさまざまなタイプを指定します。 |
| [getBackColor()](#getBackColor--) | バーコード画像の背景色。 |
| [getBarcode()](#getBarcode--) | すべてのバーコードプロパティを含む BarcodeParameters を取得します。 |
| [getBorder()](#getBorder--) | バーコード境界のすべての構成プロパティを含む BorderParameters を取得します。 |
| [getCaptionAbove()](#getCaptionAbove--) | バーコード画像の上のキャプション。 |
| [getCaptionBelow()](#getCaptionBelow--) | バーコード画像の下のキャプション。 |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | 画像パラメータ。 |
| [getImageHeight()](#getImageHeight--) | AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合のバーコード画像の高さ。 |
| [getImageWidth()](#getImageWidth--) | AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合のバーコード画像の幅。 |
| [getResolution()](#getResolution--) | バーコード画像の解像度を取得します。 |
| [getRotationAngle()](#getRotationAngle--) | バーコード画像の回転角度（度単位）、例: |
| [getUseAntiAlias()](#getUseAntiAlias--) | 画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | 自動サイズモードのさまざまなタイプを指定します。 |
| [setBackColor(int value)](#setBackColor-int-) | バーコード画像の背景色。 |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合のバーコード画像の高さ。 |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合のバーコード画像の幅。 |
| [setResolution(float value)](#setResolution-float-) | バーコード画像の解像度を設定します。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | バーコード画像の回転角度（度単位）、例: |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | 画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかを示す値を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


自動サイズモードのさまざまなタイプを指定します。既定値: AutoSizeMode.NONE。

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


バーコード画像の背景色。既定値: Color.White。参照: Color。

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


すべてのバーコードプロパティを含む BarcodeParameters を取得します。

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


バーコード境界のすべての構成プロパティを含む BorderParameters を取得します。

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


バーコード画像の上のキャプション。参照: CaptionParameters。

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


バーコード画像の下のキャプション。参照: CaptionParameters。

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


画像パラメータ。参照:。

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合のバーコード画像の高さ。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合のバーコード画像の幅。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


バーコード画像の解像度を取得します。両方の次元に対して同じ値です。既定値: 96 dpi。

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


バーコード画像の回転角度（度単位）、例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。RotationAngle が 90、180、270、または 0 以外の場合、スキャナーが画像を読み取る難易度が上がる可能性があります。既定値: 0。

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


画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかを示す値を取得します。

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


自動サイズモードのさまざまなタイプを指定します。既定値: AutoSizeMode.NONE。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


バーコード画像の背景色。既定値: Color.White。参照: Color。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合のバーコード画像の高さ。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


AutoSizeMode プロパティが AutoSizeMode.NEAREST または AutoSizeMode.INTERPOLATION に設定されている場合のバーコード画像の幅。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


バーコード画像の解像度を設定します。両方の次元に対して同じ値です。既定値: 96 dpi。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


バーコード画像の回転角度（度単位）、例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。RotationAngle が 90、180、270、または 0 以外の場合、スキャナーが画像を読み取る難易度が上がる可能性があります。既定値: 0。

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかを示す値を設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

