---
title: BarcodeSvmDetectorSettings
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 条码检测器设置。
type: docs
weight: 22
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

条码检测器设置。
## 字段

| 字段 | 描述 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | 高性能检测预设。 |
| [getHighQuality()](#getHighQuality--) | 高质量检测预设。 |
| [getMaxQuality()](#getMaxQuality--) | 最高质量检测预设。 |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | 中值平滑的窗口大小。 |
| [getNormalQuality()](#getNormalQuality--) | 普通质量检测预设。 |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | 设置可能包含条形码的检测区域阈值。 |
| [getScanWindowSizes()](#getScanWindowSizes--) | 扫描窗口大小（像素）。 |
| [getSimilarityCoef()](#getSimilarityCoef--) | 相似系数取决于条形码的同质程度。 |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | 允许检测器跳过对斜向条形码的搜索。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | 中值平滑的窗口大小。 |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | 设置可能包含条形码的检测区域阈值。 |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | 扫描窗口大小（像素）。 |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | 相似系数取决于条形码的同质程度。 |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | 允许检测器跳过对斜向条形码的搜索。 |
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
| Parameter | Type | 描述 |
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


高性能检测预设。

默认值为 QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


高质量检测预设。

默认值为 QualitySettings.PresetType.HighQualityDetection 和 QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


最高质量检测预设。

默认值为 QualitySettings.PresetType.MaxQualityDetection 和 QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


中值平滑的窗口大小。

典型值为 3 或 4。0 表示不进行中值平滑。默认值为 0。中值滤波窗口大小必须在 [0, 10] 之间。

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


普通质量检测预设。

默认值为 QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


设置可能包含条形码的检测区域阈值。

值 0.7 表示将底部 70% 的可能区域过滤掉，不再进一步处理。区域可能性阈值必须在 [0.05, 0.9] 之间。对条码较少且图像清晰的情况使用较高的值。对条码较多或噪声较大的图像使用较低的值。较低的值可能导致更长的识别时间。

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


扫描窗口大小（像素）。

允许的尺寸为 10、15、20、25、30。使用较小窗口尺寸扫描会耗时更长并提供更高的准确性，但可能无法检测到非常大的条形码。组合多种窗口尺寸可以提升检测质量。

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


相似系数取决于条形码的同质程度。

对清晰的条码使用较高的值。对部分损坏或光照不均的条码使用较低的值。相似系数必须在 [0.5, 0.9] 之间。

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


允许检测器跳过对斜向条形码的搜索。

将其设置为 false 会增加检测时间，但可以发现否则可能被遗漏的斜向条码。启用斜向搜索会导致更长的检测时间。

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


中值平滑的窗口大小。

典型值为 3 或 4。0 表示不进行中值平滑。默认值为 0。中值滤波窗口大小必须在 [0, 10] 之间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


设置可能包含条形码的检测区域阈值。

值 0.7 表示将底部 70% 的可能区域过滤掉，不再进一步处理。区域可能性阈值必须在 [0.05, 0.9] 之间。对条码较少且图像清晰的情况使用较高的值。对条码较多或噪声较大的图像使用较低的值。较低的值可能导致更长的识别时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


扫描窗口大小（像素）。

允许的尺寸为 10、15、20、25、30。使用较小窗口尺寸扫描会耗时更长并提供更高的准确性，但可能无法检测到非常大的条形码。组合多种窗口尺寸可以提升检测质量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


相似系数取决于条形码的同质程度。

对清晰的条码使用较高的值。对部分损坏或光照不均的条码使用较低的值。相似系数必须在 [0.5, 0.9] 之间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


允许检测器跳过对斜向条形码的搜索。

将其设置为 false 会增加检测时间，但可以发现否则可能被遗漏的斜向条码。启用斜向搜索会导致更长的检测时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| 标志 | int |  |

