---
title: "BarcodeSvmDetectorSettings"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "バーコード検出器設定。"
type: docs
weight: 21
url: /ja/java/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeSvmDetectorSettings
```

バーコード検出器設定。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | 高性能検出プリセットです。 |
| [getHighQuality()](#getHighQuality--) | 高品質検出プリセットです。 |
| [getMaxQuality()](#getMaxQuality--) | 最大品質検出プリセットです。 |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | メディアン平滑化のウィンドウサイズです。 |
| [getNormalQuality()](#getNormalQuality--) | 標準品質検出プリセットです。 |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | バーコードを含む可能性のある検出領域のしきい値を設定します。 |
| [getScanWindowSizes()](#getScanWindowSizes--) | ピクセル単位のスキャンウィンドウサイズです。 |
| [getSimilarityCoef()](#getSimilarityCoef--) | 類似係数はバーコードの均一性に依存します。 |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | 検出器が斜めのバーコードの検索をスキップできるようにします。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | メディアン平滑化のウィンドウサイズです。 |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | バーコードを含む可能性のある検出領域のしきい値を設定します。 |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | ピクセル単位のスキャンウィンドウサイズです。 |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | 類似係数はバーコードの均一性に依存します。 |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | 検出器が斜めのバーコードの検索をスキップできるようにします。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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


高性能検出プリセットです。

QualitySettings.PresetType.HighPerformance のデフォルト

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


高品質検出プリセットです。

QualitySettings.PresetType.HighQualityDetection と QualitySettings.PresetType.HighQuality のデフォルト

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


最大品質検出プリセットです。

QualitySettings.PresetType.MaxQualityDetection と QualitySettings.PresetType.MaxBarCodes のデフォルト

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


メディアン平滑化のウィンドウサイズです。

典型的な値は 3 または 4 です。0 は中央値平滑化なしを意味します。デフォルト値は 0 です。中央値フィルタのウィンドウサイズは [0, 10] の間でなければなりません。

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


標準品質検出プリセットです。

QualitySettings.PresetType.NormalQuality のデフォルト

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


バーコードを含む可能性のある検出領域のしきい値を設定します。

値 0.7 は、可能な領域の下位 70% が除外され、さらに処理されないことを意味します。領域の尤度閾値は [0.05, 0.9] の間でなければなりません。バーコードが少ないクリアな画像には高い値を使用してください。バーコードが多数ある画像やノイズの多い画像には低い値を使用してください。低い値は認識時間の増加につながる可能性があります。

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


ピクセル単位のスキャンウィンドウサイズです。

許容サイズは 10、15、20、25、30 です。小さいウィンドウサイズでスキャンすると時間がかかりますが、精度が向上します。ただし、非常に大きなバーコードの検出に失敗する可能性があります。複数のウィンドウサイズを組み合わせることで検出品質を向上させることができます。

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


類似係数はバーコードの均一性に依存します。

クリアなバーコードには高い値を使用してください。部分的に損傷している、または均一に照明されていないバーコードを検出するには低い値を使用してください。類似係数は [0.5, 0.9] の間でなければなりません。

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


検出器が斜めのバーコードの検索をスキップできるようにします。

false に設定すると検出時間が増加しますが、他の場合に見逃される可能性のある斜めのバーコードを検出できるようになります。斜め検索を有効にすると検出時間がさらに長くなります。

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


メディアン平滑化のウィンドウサイズです。

典型的な値は 3 または 4 です。0 は中央値平滑化なしを意味します。デフォルト値は 0 です。中央値フィルタのウィンドウサイズは [0, 10] の間でなければなりません。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


バーコードを含む可能性のある検出領域のしきい値を設定します。

値 0.7 は、可能な領域の下位 70% が除外され、さらに処理されないことを意味します。領域の尤度閾値は [0.05, 0.9] の間でなければなりません。バーコードが少ないクリアな画像には高い値を使用してください。バーコードが多数ある画像やノイズの多い画像には低い値を使用してください。低い値は認識時間の増加につながる可能性があります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


ピクセル単位のスキャンウィンドウサイズです。

許容サイズは 10、15、20、25、30 です。小さいウィンドウサイズでスキャンすると時間がかかりますが、精度が向上します。ただし、非常に大きなバーコードの検出に失敗する可能性があります。複数のウィンドウサイズを組み合わせることで検出品質を向上させることができます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


類似係数はバーコードの均一性に依存します。

クリアなバーコードには高い値を使用してください。部分的に損傷している、または均一に照明されていないバーコードを検出するには低い値を使用してください。類似係数は [0.5, 0.9] の間でなければなりません。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


検出器が斜めのバーコードの検索をスキップできるようにします。

false に設定すると検出時間が増加しますが、他の場合に見逃される可能性のある斜めのバーコードを検出できるようになります。斜め検索を有効にすると検出時間がさらに長くなります。

**Parameters:**
| パラメータ | 型 | 説明 |
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
public final native void wait(long arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

