---
title: "BarcodeSvmDetectorSettings"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Pengaturan detektor barcode."
type: docs
weight: 21
url: /id/java/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeSvmDetectorSettings
```

Pengaturan detektor barcode.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Preset deteksi kinerja tinggi. |
| [getHighQuality()](#getHighQuality--) | Preset deteksi kualitas tinggi. |
| [getMaxQuality()](#getMaxQuality--) | Preset deteksi kualitas maksimum. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Ukuran jendela untuk perataan median. |
| [getNormalQuality()](#getNormalQuality--) | Preset deteksi kualitas normal. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Mengatur ambang batas untuk wilayah terdeteksi yang mungkin berisi barcode. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Ukuran jendela pemindaian dalam piksel. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Koefisien kemiripan tergantung pada seberapa homogen barcode. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Memungkinkan detektor untuk melewatkan pencarian barcode diagonal. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Ukuran jendela untuk perataan median. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Mengatur ambang batas untuk wilayah terdeteksi yang mungkin berisi barcode. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Ukuran jendela pemindaian dalam piksel. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Koefisien kemiripan tergantung pada seberapa homogen barcode. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Memungkinkan detektor untuk melewatkan pencarian barcode diagonal. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Preset deteksi kinerja tinggi.

Default untuk  QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Preset deteksi kualitas tinggi.

Default untuk  QualitySettings.PresetType.HighQualityDetection  dan  QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Preset deteksi kualitas maksimum.

Default untuk  QualitySettings.PresetType.MaxQualityDetection  dan  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Ukuran jendela untuk perataan median.

Nilai tipikal adalah 3 atau 4. 0 berarti tidak ada median smoothing. Nilai default adalah 0. Ukuran jendela filter median harus antara [0, 10]

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Preset deteksi kualitas normal.

Default untuk  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Mengatur ambang batas untuk wilayah terdeteksi yang mungkin berisi barcode.

Nilai 0.7 berarti bahwa 70% bagian bawah dari wilayah yang mungkin disaring dan tidak diproses lebih lanjut. Ambang batas kemungkinan wilayah harus antara [0.05, 0.9]. Gunakan nilai tinggi untuk gambar yang jelas dengan sedikit barcode. Gunakan nilai rendah untuk gambar dengan banyak barcode atau untuk gambar berisik. Nilai rendah dapat menyebabkan waktu pengenalan yang lebih lama.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Ukuran jendela pemindaian dalam piksel.

Ukuran yang diizinkan adalah 10, 15, 20, 25, 30. Pemindaian dengan ukuran jendela kecil memakan waktu lebih lama dan memberikan akurasi lebih tinggi tetapi dapat gagal mendeteksi barcode yang sangat besar. Menggabungkan beberapa ukuran jendela dapat meningkatkan kualitas deteksi.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Koefisien kemiripan tergantung pada seberapa homogen barcode.

Gunakan nilai tinggi untuk barcode yang jelas. Gunakan nilai rendah untuk mendeteksi barcode yang sebagian rusak atau tidak diterangi secara merata. Koefisien kemiripan harus antara [0.5, 0.9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Memungkinkan detektor untuk melewatkan pencarian barcode diagonal.

Mengaturnya ke false akan meningkatkan waktu deteksi tetapi memungkinkan menemukan barcode diagonal yang mungkin terlewat sebaliknya. Mengaktifkan pencarian diagonal menyebabkan waktu deteksi yang lebih lama.

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


Ukuran jendela untuk perataan median.

Nilai tipikal adalah 3 atau 4. 0 berarti tidak ada median smoothing. Nilai default adalah 0. Ukuran jendela filter median harus antara [0, 10]

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Mengatur ambang batas untuk wilayah terdeteksi yang mungkin berisi barcode.

Nilai 0.7 berarti bahwa 70% bagian bawah dari wilayah yang mungkin disaring dan tidak diproses lebih lanjut. Ambang batas kemungkinan wilayah harus antara [0.05, 0.9]. Gunakan nilai tinggi untuk gambar yang jelas dengan sedikit barcode. Gunakan nilai rendah untuk gambar dengan banyak barcode atau untuk gambar berisik. Nilai rendah dapat menyebabkan waktu pengenalan yang lebih lama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Ukuran jendela pemindaian dalam piksel.

Ukuran yang diizinkan adalah 10, 15, 20, 25, 30. Pemindaian dengan ukuran jendela kecil memakan waktu lebih lama dan memberikan akurasi lebih tinggi tetapi dapat gagal mendeteksi barcode yang sangat besar. Menggabungkan beberapa ukuran jendela dapat meningkatkan kualitas deteksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Koefisien kemiripan tergantung pada seberapa homogen barcode.

Gunakan nilai tinggi untuk barcode yang jelas. Gunakan nilai rendah untuk mendeteksi barcode yang sebagian rusak atau tidak diterangi secara merata. Koefisien kemiripan harus antara [0.5, 0.9]

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Memungkinkan detektor untuk melewatkan pencarian barcode diagonal.

Mengaturnya ke false akan meningkatkan waktu deteksi tetapi memungkinkan menemukan barcode diagonal yang mungkin terlewat sebaliknya. Mengaktifkan pencarian diagonal menyebabkan waktu deteksi yang lebih lama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

