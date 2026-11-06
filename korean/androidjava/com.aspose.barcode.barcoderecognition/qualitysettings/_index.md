---
title: "QualitySettings"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다"
type: docs
weight: 42
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장된 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxQuality를 사용해 QualitySettings를 빠르게 설정하거나 개별 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다.

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
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | 엔진이 잘못된 checksumm 또는 잘못된 값을 가진 바코드를 인식하도록 허용합니다. |
| [getBarcodeQuality()](#getBarcodeQuality--) | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [getDeconvolution()](#getDeconvolution--) | 이미지 복원(Deconvolution) 모드로, 이미지 손상 수준을 정의합니다. |
| [getHighPerformance()](#getHighPerformance--) | 고성능 인식 품질 사전 설정. |
| [getHighQuality()](#getHighQuality--) | 고품질 인식 품질 사전 설정. |
| [getImageScalingMode()](#getImageScalingMode--) | 특정 ImageScaleMode로 이미지를 확대/축소하도록 허용합니다. |
| [getInverseImage()](#getInverseImage--) | 반전된 색상(휘도)의 이미지에서 바코드 추가 인식을 활성화하거나 비활성화하는 모드. |
| [getMaxQuality()](#getMaxQuality--) | 최대품질 인식 품질 사전 설정. |
| [getMinimalXDimension()](#getMinimalXDimension--) | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀). |
| [getNormalQuality()](#getNormalQuality--) | 보통품질 인식 품질 사전 설정. |
| [getXDimension()](#getXDimension--) | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | 엔진이 잘못된 checksumm 또는 잘못된 값을 가진 바코드를 인식하도록 허용합니다. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | 이미지 복원(Deconvolution) 모드로, 이미지 손상 수준을 정의합니다. |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | 특정 ImageScaleMode 값으로 이미지를 확대/축소하도록 허용합니다: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | 반전된 색상(휘도)의 이미지에서 바코드 추가 인식을 활성화하거나 비활성화하는 모드. |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀). |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


QualitySettings 생성자

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


잘못된 체크섬이나 값이 있는 바코드를 엔진이 인식하도록 허용합니다. 이 모드는 텍스트가 잘못된 손상된 바코드를 인식하는 데 사용할 수 있습니다.

값: 엔진이 잘못된 바코드를 인식하도록 허용합니다.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


선택된 품질로 바코드 요소를 인식하는 방법을 활성화하는 모드. 품질이 낮은 바코드 요소는 더 많은 복잡한 방법이 필요하여 인식 속도가 느려집니다.

값: 선택된 품질로 바코드 요소를 인식하는 방법을 활성화하는 모드.

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

값: 컬러 이미지에서 컬러 바코드 추가 인식.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


디컨볼루션(이미지 복원) 모드는 이미지 손상 정도를 정의합니다. 원래 디컨볼루션은 카메라로 이미지를 얻는 과정에서 흐림과 같은 자연 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 알 수 없기 때문에, 우리는 일반적으로 알려진 샤프 또는 수학적 형태학과 같은 함수를 검사해야 합니다.

값: 이미지 손상 정도를 정의하는 디컨볼루션 모드.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


고성능 인식 품질 사전 설정. 이 모드에서는 고품질 바코드를 잘 인식합니다.

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

값: 고성능 인식 품질 사전 설정.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


고품질 인식 품질 사전 설정. 이 사전 설정은 저품질 바코드를 위해 개발되었습니다. 심하게 손상된 바코드를 감지할 수 있습니다.

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

값: 고품질 인식 품질 사전 설정.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


특정 ImageScaleMode로 이미지를 확대/축소하도록 허용합니다.

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


반전된 색상(휘도)의 이미지에서 바코드 추가 인식을 활성화하거나 비활성화하는 모드.

값: 반전 색상의 이미지에서 바코드 추가 인식

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


최대품질 인식 품질 사전 설정. 이 사전 설정은 잘못된 바코드까지 모든 가능한 바코드를 인식하도록 개발되었습니다.

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

값: 최대품질 인식 품질 사전 설정.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀).

값: UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀).

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality 인식 품질 사전 설정. 대부분의 바코드에 적합합니다.

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

값: NormalQuality 인식 품질 사전 설정.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드.

값: 바코드 최소 요소의 크기(1부터 무한대까지): 매트릭스 셀 또는 바.

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


잘못된 체크섬이나 값이 있는 바코드를 엔진이 인식하도록 허용합니다. 이 모드는 텍스트가 잘못된 손상된 바코드를 인식하는 데 사용할 수 있습니다.

값: 엔진이 잘못된 바코드를 인식하도록 허용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


선택된 품질로 바코드 요소를 인식하는 방법을 활성화하는 모드. 품질이 낮은 바코드 요소는 더 많은 복잡한 방법이 필요하여 인식 속도가 느려집니다.

값: 선택된 품질로 바코드 요소를 인식하는 방법을 활성화하는 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

값: 컬러 이미지에서 컬러 바코드 추가 인식.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


디컨볼루션(이미지 복원) 모드는 이미지 손상 정도를 정의합니다. 원래 디컨볼루션은 카메라로 이미지를 얻는 과정에서 흐림과 같은 자연 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 알 수 없기 때문에, 우리는 일반적으로 알려진 샤프 또는 수학적 형태학과 같은 함수를 검사해야 합니다.

값: 이미지 손상 정도를 정의하는 디컨볼루션 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


특정 ImageScaleMode 값으로 이미지를 확대/축소하도록 허용합니다:

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.barcode.barcoderecognition.ImageScalingMode | ImageScalingMode 값 |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


반전된 색상(휘도)의 이미지에서 바코드 추가 인식을 활성화하거나 비활성화하는 모드.

값: 반전 색상의 이미지에서 바코드 추가 인식

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀).

값: UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드.

값: 바코드 최소 요소의 크기(1부터 무한대까지): 매트릭스 셀 또는 바.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

