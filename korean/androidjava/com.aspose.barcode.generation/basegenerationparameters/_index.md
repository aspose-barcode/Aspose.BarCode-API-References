---
title: BaseGenerationParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: 바코드 이미지 생성 매개변수.
type: docs
weight: 17
url: /ko/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

바코드 이미지 생성 매개변수.
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | 자동 크기 조정 모드의 다양한 유형을 지정합니다. |
| [getBackColor()](#getBackColor--) | 바코드 이미지의 배경 색상. |
| [getBarcode()](#getBarcode--) | 모든 바코드 속성을 포함하는 BarcodeParameters를 가져옵니다. |
| [getBorder()](#getBorder--) | 바코드 테두리의 모든 구성 속성을 포함하는 BorderParameters를 가져옵니다. |
| [getCaptionAbove()](#getCaptionAbove--) | BarCode 이미지 위의 캡션. |
| [getCaptionBelow()](#getCaptionBelow--) | BarCode 이미지 아래의 캡션. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | 이미지 매개변수. |
| [getImageHeight()](#getImageHeight--) | AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 높이. |
| [getImageWidth()](#getImageWidth--) | AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 너비. |
| [getResolution()](#getResolution--) | BarCode 이미지의 해상도를 가져옵니다. |
| [getRotationAngle()](#getRotationAngle--) | BarCode 이미지 회전 각도(도 단위), 예: |
| [getUseAntiAlias()](#getUseAntiAlias--) | 이미지를 렌더링할 때 안티앨리어싱 모드가 사용되는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | 자동 크기 조정 모드의 다양한 유형을 지정합니다. |
| [setBackColor(int value)](#setBackColor-int-) | 바코드 이미지의 배경 색상. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 높이. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 너비. |
| [setResolution(float value)](#setResolution-float-) | BarCode 이미지의 해상도를 설정합니다. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | BarCode 이미지 회전 각도(도 단위), 예: |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | 이미지를 렌더링할 때 안티앨리어싱 모드가 사용되는지 여부를 나타내는 값을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


바코드 이미지의 배경 색상. 기본값: Color.White. 자세히 보기: Color.

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


모든 바코드 속성을 포함하는 BarcodeParameters를 가져옵니다.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


바코드 테두리의 모든 구성 속성을 포함하는 BorderParameters를 가져옵니다.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


BarCode 이미지 위의 캡션. 자세히 보기: CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


BarCode 이미지 아래의 캡션. 자세히 보기: CaptionParameters.

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


이미지 매개변수. 자세히 보기.

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 높이.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 너비.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


BarCode 이미지의 해상도를 가져옵니다. 두 차원 모두에 적용되는 하나의 값. 기본값: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


BarCode 이미지 회전 각도(도 단위), 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. RotationAngle가 90, 180, 270 또는 0이 아닌 경우 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값: 0.

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


이미지를 렌더링할 때 안티앨리어싱 모드가 사용되는지 여부를 나타내는 값을 가져옵니다.

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


자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값: AutoSizeMode.NONE.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


바코드 이미지의 배경 색상. 기본값: Color.White. 자세히 보기: Color.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 높이.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 너비.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


BarCode 이미지의 해상도를 설정합니다. 두 차원 모두에 적용되는 하나의 값. 기본값: 96 dpi.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


BarCode 이미지 회전 각도(도 단위), 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. RotationAngle가 90, 180, 270 또는 0이 아닌 경우 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


이미지를 렌더링할 때 안티앨리어싱 모드가 사용되는지 여부를 나타내는 값을 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

