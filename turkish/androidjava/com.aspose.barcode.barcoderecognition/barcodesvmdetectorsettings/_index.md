---
title: "BarcodeSvmDetectorSettings"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Barkod algılayıcı ayarları."
type: docs
weight: 21
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

Barkod algılayıcı ayarları.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Yüksek performanslı algılama ön ayarı. |
| [getHighQuality()](#getHighQuality--) | Yüksek kalite algılama ön ayarı. |
| [getMaxQuality()](#getMaxQuality--) | Maksimum kalite algılama ön ayarı. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Orta değer yumuşatması için pencere boyutu. |
| [getNormalQuality()](#getNormalQuality--) | Normal kalite algılama ön ayarı. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Barkod içerebilecek algılanan bölgeler için eşik değerini ayarlar. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Tarama pencere boyutları piksel cinsinden. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Benzerlik katsayısı, barkodların ne kadar homojen olduğuna bağlıdır. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Algılayıcının çapraz barkod aramasını atlamasına izin verir. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Orta değer yumuşatması için pencere boyutu. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Barkod içerebilecek algılanan bölgeler için eşik değerini ayarlar. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Tarama pencere boyutları piksel cinsinden. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Benzerlik katsayısı, barkodların ne kadar homojen olduğuna bağlıdır. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Algılayıcının çapraz barkod aramasını atlamasına izin verir. |
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
| Parametre | Tür | Açıklama |
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


Yüksek performanslı algılama ön ayarı.

Default for  QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Yüksek kalite algılama ön ayarı.

Default for  QualitySettings.PresetType.HighQualityDetection  and  QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Maksimum kalite algılama ön ayarı.

Default for  QualitySettings.PresetType.MaxQualityDetection  and  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Orta değer yumuşatması için pencere boyutu.

Tipik değerler 3 veya 4'tür. 0, orta değer yumuşatması olmadığını gösterir. Varsayılan değer 0'dır. Ortalama filtre pencere boyutu [0, 10] arasında olmalıdır.

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Normal kalite algılama ön ayarı.

Default for  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Barkod içerebilecek algılanan bölgeler için eşik değerini ayarlar.

0.7 değeri, olası bölgelerin alt %70'inin filtrelendiği ve daha fazla işlenmediği anlamına gelir. Bölge olasılık eşiği [0.05, 0.9] arasında olmalıdır. Az sayıda barkod bulunan net görüntüler için yüksek değerler kullanın. Çok sayıda barkod veya gürültülü görüntüler için düşük değerler kullanın. Düşük değer, daha uzun tanıma süresine yol açabilir.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Tarama pencere boyutları piksel cinsinden.

İzin verilen boyutlar 10, 15, 20, 25, 30'dur. Küçük pencere boyutuyla tarama daha fazla zaman alır ve daha yüksek doğruluk sağlar ancak çok büyük barkodların algılanmasında başarısız olabilir. Birden fazla pencere boyutunun birleştirilmesi algılama kalitesini artırabilir.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Benzerlik katsayısı, barkodların ne kadar homojen olduğuna bağlıdır.

Net barkodlar için yüksek değer kullanın. Kısmen hasar görmüş veya eşit aydınlatılmamış barkodları tespit etmek için düşük değerler kullanın. Benzerlik katsayısı [0.5, 0.9] arasında olmalıdır.

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Algılayıcının çapraz barkod aramasını atlamasına izin verir.

False olarak ayarlandığında algılama süresi artar ancak aksi takdirde kaçırılabilecek çapraz barkodların bulunmasını sağlar. Çapraz aramanın etkinleştirilmesi daha uzun bir algılama süresine yol açar.

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


Orta değer yumuşatması için pencere boyutu.

Tipik değerler 3 veya 4'tür. 0, orta değer yumuşatması olmadığını gösterir. Varsayılan değer 0'dır. Ortalama filtre pencere boyutu [0, 10] arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Barkod içerebilecek algılanan bölgeler için eşik değerini ayarlar.

0.7 değeri, olası bölgelerin alt %70'inin filtrelendiği ve daha fazla işlenmediği anlamına gelir. Bölge olasılık eşiği [0.05, 0.9] arasında olmalıdır. Az sayıda barkod bulunan net görüntüler için yüksek değerler kullanın. Çok sayıda barkod veya gürültülü görüntüler için düşük değerler kullanın. Düşük değer, daha uzun tanıma süresine yol açabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Tarama pencere boyutları piksel cinsinden.

İzin verilen boyutlar 10, 15, 20, 25, 30'dur. Küçük pencere boyutuyla tarama daha fazla zaman alır ve daha yüksek doğruluk sağlar ancak çok büyük barkodların algılanmasında başarısız olabilir. Birden fazla pencere boyutunun birleştirilmesi algılama kalitesini artırabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Benzerlik katsayısı, barkodların ne kadar homojen olduğuna bağlıdır.

Net barkodlar için yüksek değer kullanın. Kısmen hasar görmüş veya eşit aydınlatılmamış barkodları tespit etmek için düşük değerler kullanın. Benzerlik katsayısı [0.5, 0.9] arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Algılayıcının çapraz barkod aramasını atlamasına izin verir.

False olarak ayarlandığında algılama süresi artar ancak aksi takdirde kaçırılabilecek çapraz barkodların bulunmasını sağlar. Çapraz aramanın etkinleştirilmesi daha uzun bir algılama süresine yol açar.

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
public final void wait(long arg0)
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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

