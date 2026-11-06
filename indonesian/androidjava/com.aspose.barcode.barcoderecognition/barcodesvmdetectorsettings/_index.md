---
title: "BarcodeSvmDetectorSettings"
second_title: "Referensi API Aspose.BarCode untuk Android via Java"
description: "Pengaturan detektor kode batang."
type: docs
weight: 21
url: /id/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

Pengaturan detektor kode batang.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Preset deteksi kinerja tinggi. |
| [getHighQuality()](#getHighQuality--) | Preset deteksi kualitas tinggi. |
| [getMaxQuality()](#getMaxQuality--) | Preset deteksi kualitas maksimum. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Ukuran jendela untuk perataan median. |
| [getNormalQuality()](#getNormalQuality--) | Preset deteksi kualitas normal. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Menetapkan ambang batas untuk wilayah yang terdeteksi yang mungkin berisi kode batang. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Ukuran jendela pemindaian dalam piksel. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Koefisien kemiripan tergantung pada seberapa homogen kode batang. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Mengizinkan detektor melewatkan pencarian kode batang diagonal. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Ukuran jendela untuk perataan median. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Menetapkan ambang batas untuk wilayah yang terdeteksi yang mungkin berisi kode batang. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Ukuran jendela pemindaian dalam piksel. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Koefisien kemiripan tergantung pada seberapa homogen kode batang. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Mengizinkan detektor melewatkan pencarian kode batang diagonal. |
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

Nilai tipikal adalah 3 atau 4. 0 berarti tidak ada perataan median. Nilai default adalah 0. Ukuran jendela filter median harus berada di antara [0, 10]

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


Menetapkan ambang batas untuk wilayah yang terdeteksi yang mungkin berisi kode batang.

Nilai 0.7 berarti bahwa 70% bagian bawah dari wilayah yang mungkin disaring dan tidak diproses lebih lanjut. Ambang batas kemungkinan wilayah harus berada di antara [0.05, 0.9]. Gunakan nilai tinggi untuk gambar yang jelas dengan sedikit kode batang. Gunakan nilai rendah untuk gambar dengan banyak kode batang atau untuk gambar berisik. Nilai rendah dapat menyebabkan waktu pengenalan yang lebih lama.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Ukuran jendela pemindaian dalam piksel.

Ukuran yang diizinkan adalah 10, 15, 20, 25, 30. Pemindaian dengan ukuran jendela kecil memakan lebih banyak waktu dan memberikan akurasi lebih tinggi tetapi dapat gagal mendeteksi kode batang yang sangat besar. Menggabungkan beberapa ukuran jendela dapat meningkatkan kualitas deteksi.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Koefisien kemiripan tergantung pada seberapa homogen kode batang.

Gunakan nilai tinggi untuk kode batang yang jelas. Gunakan nilai rendah untuk mendeteksi kode batang yang sebagian rusak atau tidak terang secara merata. Koefisien kemiripan harus berada di antara [0.5, 0.9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Mengizinkan detektor melewatkan pencarian kode batang diagonal.

Mengaturnya ke false akan meningkatkan waktu deteksi tetapi memungkinkan menemukan kode batang diagonal yang mungkin terlewat sebaliknya. Mengaktifkan pencarian diagonal menyebabkan waktu deteksi yang lebih lama.

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

Nilai tipikal adalah 3 atau 4. 0 berarti tidak ada perataan median. Nilai default adalah 0. Ukuran jendela filter median harus berada di antara [0, 10]

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Menetapkan ambang batas untuk wilayah yang terdeteksi yang mungkin berisi kode batang.

Nilai 0.7 berarti bahwa 70% bagian bawah dari wilayah yang mungkin disaring dan tidak diproses lebih lanjut. Ambang batas kemungkinan wilayah harus berada di antara [0.05, 0.9]. Gunakan nilai tinggi untuk gambar yang jelas dengan sedikit kode batang. Gunakan nilai rendah untuk gambar dengan banyak kode batang atau untuk gambar berisik. Nilai rendah dapat menyebabkan waktu pengenalan yang lebih lama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Ukuran jendela pemindaian dalam piksel.

Ukuran yang diizinkan adalah 10, 15, 20, 25, 30. Pemindaian dengan ukuran jendela kecil memakan lebih banyak waktu dan memberikan akurasi lebih tinggi tetapi dapat gagal mendeteksi kode batang yang sangat besar. Menggabungkan beberapa ukuran jendela dapat meningkatkan kualitas deteksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Koefisien kemiripan tergantung pada seberapa homogen kode batang.

Gunakan nilai tinggi untuk kode batang yang jelas. Gunakan nilai rendah untuk mendeteksi kode batang yang sebagian rusak atau tidak terang secara merata. Koefisien kemiripan harus berada di antara [0.5, 0.9]

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Mengizinkan detektor melewatkan pencarian kode batang diagonal.

Mengaturnya ke false akan meningkatkan waktu deteksi tetapi memungkinkan menemukan kode batang diagonal yang mungkin terlewat sebaliknya. Mengaktifkan pencarian diagonal menyebabkan waktu deteksi yang lebih lama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

