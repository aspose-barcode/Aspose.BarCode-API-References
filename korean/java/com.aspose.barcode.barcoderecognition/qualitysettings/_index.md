---
title: "QualitySettings"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "QualitySettings는 인식 품질과 속도를 수동으로 구성하도록 허용합니다."
type: docs
weight: 40
url: /ko/java/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object
```
public final class QualitySettings
```

QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. HighPerformance, NormalQuality, HighQuality, MaxQuality와 같은 내장 프리셋으로 QualitySettings를 빠르게 설정하거나 개별 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | 엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. |
| [getBarcodeQuality()](#getBarcodeQuality--) | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [getDeconvolution()](#getDeconvolution--) | 이미지 복원(Deconvolution) 모드로, 이미지 손상 정도를 정의합니다. |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance 인식 품질 프리셋. |
| [getHighQuality()](#getHighQuality--) | HighQuality 인식 품질 프리셋. |
| [getInverseImage()](#getInverseImage--) | 색상이 반전된(휘도) 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality 인식 품질 프리셋. |
| [getMinimalXDimension()](#getMinimalXDimension--) | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 픽셀 크기. |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality 인식 품질 프리셋. |
| [getXDimension()](#getXDimension--) | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | 엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | 이미지 복원(Deconvolution) 모드로, 이미지 손상 정도를 정의합니다. |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | 색상이 반전된(휘도) 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 픽셀 크기. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. 이 모드는 텍스트가 잘못된 손상된 바코드를 인식하는 데 사용할 수 있습니다.

값: 엔진이 잘못된 바코드를 인식하도록 허용합니다.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. 품질이 낮은 바코드 요소는 더 많은 복잡한 메서드가 필요해 인식 속도가 느려집니다.

값: 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드.

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


컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

값: 컬러 이미지에서 컬러 바코드의 추가 인식.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Deconvolution (image restorations) 모드는 이미지 손상 정도를 정의합니다. 원래 Deconvolution은 카메라로 이미지를 촬영할 때 흐림과 같은 자연적인 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 우리는 샤프하거나 수학적 형태학과 같은 가장 잘 알려진 함수들을 확인해야 합니다.

값: 이미지 손상 수준을 정의하는 디컨볼루션 모드.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance 인식 품질 프리셋. 이 모드에서는 고품질 바코드가 잘 인식됩니다.

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

값: HighPerformance 인식 품질 프리셋.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality 인식 품질 프리셋. 이 프리셋은 저품질 바코드를 위해 개발되었습니다. 심하게 손상된 바코드도 감지할 수 있습니다.

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

값: HighQuality 인식 품질 프리셋.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


색상이 반전된(휘도) 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

값: 역색 이미지에서 바코드 추가 인식

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality 인식 품질 프리셋. 이 프리셋은 잘못된 바코드까지 모든 가능한 바코드를 인식하도록 개발되었습니다.

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

값: MaxQuality 인식 품질 프리셋.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


UseMinimalXDimension과 함께 사용되는 XDimension의 최소 픽셀 크기.

값: UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀).

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality 인식 품질 프리셋. 대부분의 바코드에 적합합니다.

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

값: NormalQuality 인식 품질 프리셋.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드.

값: 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지).

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


엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. 이 모드는 텍스트가 잘못된 손상된 바코드를 인식하는 데 사용할 수 있습니다.

값: 엔진이 잘못된 바코드를 인식하도록 허용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. 품질이 낮은 바코드 요소는 더 많은 복잡한 메서드가 필요해 인식 속도가 느려집니다.

값: 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

값: 컬러 이미지에서 컬러 바코드의 추가 인식.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Deconvolution (image restorations) 모드는 이미지 손상 정도를 정의합니다. 원래 Deconvolution은 카메라로 이미지를 촬영할 때 흐림과 같은 자연적인 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 우리는 샤프하거나 수학적 형태학과 같은 가장 잘 알려진 함수들을 확인해야 합니다.

값: 이미지 손상 수준을 정의하는 디컨볼루션 모드.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


색상이 반전된(휘도) 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

값: 역색 이미지에서 바코드 추가 인식

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


UseMinimalXDimension과 함께 사용되는 XDimension의 최소 픽셀 크기.

값: UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드.

값: 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지).

**Parameters:**
| 매개변수 | 유형 | 설명 |
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
public final native void wait(long arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

