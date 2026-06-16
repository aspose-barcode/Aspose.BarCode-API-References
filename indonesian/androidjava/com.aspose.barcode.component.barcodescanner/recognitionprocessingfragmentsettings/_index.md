---
title: RecognitionProcessingFragmentSettings
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: 
type: docs
weight: 27
url: /id/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Mendapatkan latar belakang yang akan dirender selama proses recogntion |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Mendapatkan warna bilah kemajuan yang dirender selama pengenalan |
| [getProgressBarSize()](#getProgressBarSize--) | Mendapatkan ukuran bilah kemajuan yang dirender selama pengenalan |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Mendapatkan offset dari batas kanan tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Mendapatkan teks tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Mendapatkan warna tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Mendapatkan ukuran teks tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Mendapatkan visibilitas tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Mendapatkan teks TextView yang dirender di atas bilah kemajuan selama pengenalan |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Mendapatkan warna TextView yang dirender di atas bilah kemajuan selama pengenalan |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Mendapatkan ukuran teks TextView yang dirender di atas bilah kemajuan selama pengenalan |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Mendapatkan warna TextView yang dirender di atas bilah kemajuan selama pengenalan |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Mengimpor pengaturan |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Mengatur latar belakang yang akan dirender selama proses recogntion |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Mengatur warna bilah kemajuan yang dirender selama pengenalan |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Mengatur offset dari batas kanan tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Mengatur teks tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Mengatur warna tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Mengatur ukuran teks tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Mengatur visibilitas tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Mengatur teks TextView yang dirender di atas bilah kemajuan selama pengenalan |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Mengatur warna TextView yang dirender di atas bilah kemajuan selama pengenalan |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Mengatur ukuran teks TextView yang dirender di atas bilah kemajuan selama pengenalan |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Mengatur warna TextView yang dirender di atas bilah kemajuan selama pengenalan |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Mengatur ukuran bilah kemajuan yang dirender selama pengenalan |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<RecognitionProcessingFragmentSettings> CREATOR
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Mendapatkan latar belakang yang akan dirender selama proses recogntion

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - latar belakang yang akan dirender selama proses recogntion
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getProgressBarColor() {#getProgressBarColor--}
```
public int getProgressBarColor()
```


Mendapatkan warna bilah kemajuan yang dirender selama pengenalan

**Returns:**
int - warna bilah kemajuan
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Mendapatkan ukuran bilah kemajuan yang dirender selama pengenalan

**Returns:**
int - ukuran bilah kemajuan
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Mendapatkan offset dari batas kanan tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Returns:**
int - offset dari tepi kanan tombol "Cancel"
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Mendapatkan teks tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Returns:**
java.lang.String - teks tombol "Cancel" yang ditampilkan di bawah bilah kemajuan
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Mendapatkan warna tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Returns:**
int - warna tombol "Cancel" yang ditampilkan di bawah bilah kemajuan
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Mendapatkan ukuran teks tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Returns:**
float - ukuran teks tombol "Cancel" yang ditampilkan di bawah bilah kemajuan
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Mendapatkan visibilitas tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Returns:**
boolean - visibilitas tombol "Cancel"
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Mendapatkan teks TextView yang dirender di atas bilah kemajuan selama pengenalan

**Returns:**
java.lang.String - teks TextView yang ditampilkan di atas bilah kemajuan
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Mendapatkan warna TextView yang dirender di atas bilah kemajuan selama pengenalan

**Returns:**
int - warna TextView yang ditampilkan di atas bilah kemajuan
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Mendapatkan ukuran teks TextView yang dirender di atas bilah kemajuan selama pengenalan

**Returns:**
float - ukuran teks TextView yang ditampilkan di atas bilah kemajuan
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Mendapatkan warna TextView yang dirender di atas bilah kemajuan selama pengenalan

**Returns:**
boolean - warna TextView yang ditampilkan di atas bilah kemajuan
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings) {#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-}
```
public void importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)
```


Mengimpor pengaturan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionProcessingFragmentSettings | com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage) {#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-}
```
public void setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)
```


Mengatur latar belakang yang akan dirender selama proses recogntion

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | latar belakang yang akan ditampilkan selama proses pengenalan |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Mengatur warna bilah kemajuan yang dirender selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| progressBarColor | int | warna bilah kemajuan |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Mengatur offset dari batas kanan tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | offset dari tepi kanan tombol "Cancel" |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Mengatur teks tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | teks tombol "Cancel" yang ditampilkan di bawah bilah kemajuan |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Mengatur warna tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | warna tombol "Cancel" yang ditampilkan di bawah bilah kemajuan |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Mengatur ukuran teks tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | ukuran teks tombol "Cancel" yang dirender di bawah progres |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Mengatur visibilitas tombol "Cancel" yang dirender di bawah bilah kemajuan selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | visibilitas tombol "Cancel" |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Mengatur teks TextView yang dirender di atas bilah kemajuan selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | teks TextView yang dirender di atas bilah progres |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Mengatur warna TextView yang dirender di atas bilah kemajuan selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | warna TextView yang dirender di atas bilah progres |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Mengatur ukuran teks TextView yang dirender di atas bilah kemajuan selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | ukuran teks TextView yang dirender di atas bilah progres |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Mengatur warna TextView yang dirender di atas bilah kemajuan selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | warna TextView yang dirender di atas bilah progres |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Mengatur ukuran bilah kemajuan yang dirender selama pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| progressBarSize | int | ukuran bilah progres |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

