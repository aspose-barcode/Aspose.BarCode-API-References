---
title: "BarcodeSvmDetectorSettings"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Barkod algılayıcı ayarları."
type: docs
weight: 21
url: /tr/java/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeSvmDetectorSettings
```

Barkod algılayıcı ayarları.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Yüksek performanslı algılama ön ayarı. |
| [getHighQuality()](#getHighQuality--) | Yüksek kalite algılama ön ayarı. |
| [getMaxQuality()](#getMaxQuality--) | Maksimum kalite algılama ön ayarı. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Orta değer düzeltmesi için pencere boyutu. |
| [getNormalQuality()](#getNormalQuality--) | Normal kalite algılama ön ayarı. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Barkod içerebilecek tespit edilen bölgeler için eşik değerini ayarlar. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Tarama pencere boyutları piksel cinsinden. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Benzerlik katsayısı, barkodların ne kadar homojen olduğuna bağlıdır. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Algılayıcının çapraz barkodları aramayı atlamasına izin verir. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Orta değer düzeltmesi için pencere boyutu. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Barkod içerebilecek tespit edilen bölgeler için eşik değerini ayarlar. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Tarama pencere boyutları piksel cinsinden. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Benzerlik katsayısı, barkodların ne kadar homojen olduğuna bağlıdır. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Algılayıcının çapraz barkodları aramayı atlamasına izin verir. |
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

QualitySettings.PresetType.HighPerformance için varsayılan

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Yüksek kalite algılama ön ayarı.

QualitySettings.PresetType.HighQualityDetection ve QualitySettings.PresetType.HighQuality için varsayılan

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Maksimum kalite algılama ön ayarı.

QualitySettings.PresetType.MaxQualityDetection ve QualitySettings.PresetType.MaxBarCodes için varsayılan

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Orta değer düzeltmesi için pencere boyutu.

Tipik değerler 3 veya 4'tür. 0, medyan yumuşatmanın olmadığını gösterir. Varsayılan değer 0'dır. Medyan filtre pencere boyutu [0, 10] arasında olmalıdır.

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Normal kalite algılama ön ayarı.

QualitySettings.PresetType.NormalQuality için varsayılan

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Barkod içerebilecek tespit edilen bölgeler için eşik değerini ayarlar.

0.7 değeri, olası bölgelerin alt %70'inin filtrelendiği ve daha fazla işlenmediği anlamına gelir. Bölge olasılık eşiği [0.05, 0.9] arasında olmalıdır. Az barkodlu net görüntüler için yüksek değerler kullanın. Çok barkodlu veya gürültülü görüntüler için düşük değerler kullanın. Düşük değer, daha uzun tanıma süresine yol açabilir.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Tarama pencere boyutları piksel cinsinden.

İzin verilen boyutlar 10, 15, 20, 25, 30'dur. Küçük pencere boyutuyla tarama daha fazla zaman alır ve daha yüksek doğruluk sağlar ancak çok büyük barkodların tespitinde başarısız olabilir. Birkaç pencere boyutunun birleştirilmesi tespit kalitesini artırabilir.

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


Algılayıcının çapraz barkodları aramayı atlamasına izin verir.

Bunu false olarak ayarlamak tespit süresini artırır ancak aksi takdirde kaçırılabilecek çapraz barkodların bulunmasına izin verir. Çapraz aramanın etkinleştirilmesi daha uzun tespit süresine yol açar.

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


Orta değer düzeltmesi için pencere boyutu.

Tipik değerler 3 veya 4'tür. 0, medyan yumuşatmanın olmadığını gösterir. Varsayılan değer 0'dır. Medyan filtre pencere boyutu [0, 10] arasında olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Barkod içerebilecek tespit edilen bölgeler için eşik değerini ayarlar.

0.7 değeri, olası bölgelerin alt %70'inin filtrelendiği ve daha fazla işlenmediği anlamına gelir. Bölge olasılık eşiği [0.05, 0.9] arasında olmalıdır. Az barkodlu net görüntüler için yüksek değerler kullanın. Çok barkodlu veya gürültülü görüntüler için düşük değerler kullanın. Düşük değer, daha uzun tanıma süresine yol açabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Tarama pencere boyutları piksel cinsinden.

İzin verilen boyutlar 10, 15, 20, 25, 30'dur. Küçük pencere boyutuyla tarama daha fazla zaman alır ve daha yüksek doğruluk sağlar ancak çok büyük barkodların tespitinde başarısız olabilir. Birkaç pencere boyutunun birleştirilmesi tespit kalitesini artırabilir.

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


Algılayıcının çapraz barkodları aramayı atlamasına izin verir.

Bunu false olarak ayarlamak tespit süresini artırır ancak aksi takdirde kaçırılabilecek çapraz barkodların bulunmasına izin verir. Çapraz aramanın etkinleştirilmesi daha uzun tespit süresine yol açar.

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

