---
title: BarcodeSvmDetectorSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: 바코드 감지기 설정입니다.
type: docs
weight: 22
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

바코드 감지기 설정입니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | 고성능 감지 사전 설정. |
| [getHighQuality()](#getHighQuality--) | 고품질 감지 사전 설정. |
| [getMaxQuality()](#getMaxQuality--) | 최대 품질 감지 사전 설정. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | 중간값 평활화를 위한 창 크기. |
| [getNormalQuality()](#getNormalQuality--) | 보통 품질 감지 사전 설정. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | 바코드를 포함할 수 있는 감지된 영역에 대한 임계값을 설정합니다. |
| [getScanWindowSizes()](#getScanWindowSizes--) | 픽셀 단위의 스캔 창 크기. |
| [getSimilarityCoef()](#getSimilarityCoef--) | 유사도 계수는 바코드의 균일성에 따라 달라집니다. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | 감지기가 대각선 바코드 검색을 건너뛰도록 허용합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | 중간값 평활화를 위한 창 크기. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | 바코드를 포함할 수 있는 감지된 영역에 대한 임계값을 설정합니다. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | 픽셀 단위의 스캔 창 크기. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | 유사도 계수는 바코드의 균일성에 따라 달라집니다. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | 감지기가 대각선 바코드 검색을 건너뛰도록 허용합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<BarcodeSvmDetectorSettings> CREATOR
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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHighPerformance() {#getHighPerformance--}
```
public static BarcodeSvmDetectorSettings getHighPerformance()
```


고성능 감지 사전 설정.

QualitySettings.PresetType.HighPerformance의 기본값

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


고품질 감지 사전 설정.

QualitySettings.PresetType.HighQualityDetection 및 QualitySettings.PresetType.HighQuality의 기본값

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


최대 품질 감지 사전 설정.

QualitySettings.PresetType.MaxQualityDetection 및 QualitySettings.PresetType.MaxBarCodes의 기본값

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


중간값 평활화를 위한 창 크기.

일반적인 값은 3 또는 4입니다. 0은 중간값 평활화가 없음을 의미합니다. 기본값은 0이며, 중간값 필터 창 크기는 [0, 10] 사이여야 합니다.

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


보통 품질 감지 사전 설정.

QualitySettings.PresetType.NormalQuality의 기본값

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


바코드를 포함할 수 있는 감지된 영역에 대한 임계값을 설정합니다.

값 0.7은 가능한 영역의 하위 70%가 필터링되어 더 이상 처리되지 않음을 의미합니다. 영역 가능성 임계값은 [0.05, 0.9] 사이여야 합니다. 바코드가 적은 선명한 이미지에는 높은 값을 사용하고, 바코드가 많거나 노이즈가 있는 이미지에는 낮은 값을 사용하십시오. 낮은 값은 인식 시간이 더 길어질 수 있습니다.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


픽셀 단위의 스캔 창 크기.

허용되는 크기는 10, 15, 20, 25, 30입니다. 작은 창 크기로 스캔하면 시간이 더 많이 걸리고 정확도가 높아지지만 매우 큰 바코드를 감지하지 못할 수 있습니다. 여러 창 크기를 결합하면 감지 품질을 향상시킬 수 있습니다.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


유사도 계수는 바코드의 균일성에 따라 달라집니다.

선명한 바코드에는 높은 값을 사용하십시오. 부분적으로 손상되었거나 고르게 밝히지 않은 바코드를 감지하려면 낮은 값을 사용하십시오. 유사도 계수는 [0.5, 0.9] 사이여야 합니다.

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


감지기가 대각선 바코드 검색을 건너뛰도록 허용합니다.

false로 설정하면 감지 시간이 증가하지만 그렇지 않으면 놓칠 수 있는 대각선 바코드를 찾을 수 있습니다. 대각선 검색을 활성화하면 감지 시간이 더 길어집니다.

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




### setMedianFilterWindowSize(int value) {#setMedianFilterWindowSize-int-}
```
public void setMedianFilterWindowSize(int value)
```


중간값 평활화를 위한 창 크기.

일반적인 값은 3 또는 4입니다. 0은 중간값 평활화가 없음을 의미합니다. 기본값은 0이며, 중간값 필터 창 크기는 [0, 10] 사이여야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


바코드를 포함할 수 있는 감지된 영역에 대한 임계값을 설정합니다.

값 0.7은 가능한 영역의 하위 70%가 필터링되어 더 이상 처리되지 않음을 의미합니다. 영역 가능성 임계값은 [0.05, 0.9] 사이여야 합니다. 바코드가 적은 선명한 이미지에는 높은 값을 사용하고, 바코드가 많거나 노이즈가 있는 이미지에는 낮은 값을 사용하십시오. 낮은 값은 인식 시간이 더 길어질 수 있습니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


픽셀 단위의 스캔 창 크기.

허용되는 크기는 10, 15, 20, 25, 30입니다. 작은 창 크기로 스캔하면 시간이 더 많이 걸리고 정확도가 높아지지만 매우 큰 바코드를 감지하지 못할 수 있습니다. 여러 창 크기를 결합하면 감지 품질을 향상시킬 수 있습니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


유사도 계수는 바코드의 균일성에 따라 달라집니다.

선명한 바코드에는 높은 값을 사용하십시오. 부분적으로 손상되었거나 고르게 밝히지 않은 바코드를 감지하려면 낮은 값을 사용하십시오. 유사도 계수는 [0.5, 0.9] 사이여야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


감지기가 대각선 바코드 검색을 건너뛰도록 허용합니다.

false로 설정하면 감지 시간이 증가하지만 그렇지 않으면 놓칠 수 있는 대각선 바코드를 찾을 수 있습니다. 대각선 검색을 활성화하면 감지 시간이 더 길어집니다.

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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

