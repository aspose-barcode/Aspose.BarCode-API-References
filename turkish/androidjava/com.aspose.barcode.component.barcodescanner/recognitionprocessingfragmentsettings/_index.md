---
title: "RecognitionProcessingFragmentSettings"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: 
type: docs
weight: 27
url: /tr/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Tanıma işlemi sırasında renderlanacak arka planı alır |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Tanıma sırasında renderlanan ilerleme çubuğunun rengini alır |
| [getProgressBarSize()](#getProgressBarSize--) | Tanıma sırasında renderlanan ilerleme çubuğunun boyutunu alır |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Tanıma sırasında ilerleme çubuğunun altında renderlanan "Cancel" düğmesinin sağ kenardan ofsetini alır |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | "Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan metnini alır |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | "Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan rengini alır |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | "Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan metin boyutunu alır |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | "Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan görünürlüğünü alır |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in metnini alır |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in rengini alır |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in metin boyutunu alır |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in rengini alır |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Ayarları içe aktarır |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Tanıma işlemi sırasında renderlanacak arka planı ayarlar |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Tanıma sırasında renderlanan ilerleme çubuğunun rengini ayarlar |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Tanıma sırasında ilerleme çubuğunun altında renderlanan "Cancel" düğmesinin sağ kenardan ofsetini ayarlar |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | "Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan metnini ayarlar |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | "Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan rengini ayarlar |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | "Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan metin boyutunu ayarlar |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | "Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan görünürlüğünü ayarlar |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in metnini ayarlar |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in rengini ayarlar |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in metin boyutunu ayarlar |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in rengini ayarlar |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Tanıma sırasında renderlanan ilerleme çubuğunun boyutunu ayarlar |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Tanıma işlemi sırasında renderlanacak arka planı alır

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - tanıma işlemi sırasında renderlanacak arka plan
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


Tanıma sırasında renderlanan ilerleme çubuğunun rengini alır

**Returns:**
int - ilerleme çubuğunun rengi
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Tanıma sırasında renderlanan ilerleme çubuğunun boyutunu alır

**Returns:**
int - ilerleme çubuğunun boyutu
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Tanıma sırasında ilerleme çubuğunun altında renderlanan "Cancel" düğmesinin sağ kenardan ofsetini alır

**Returns:**
int - "Cancel" Düğmesinin sağ kenarından ofset
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


"Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan metnini alır

**Returns:**
java.lang.String - ilerleme çubuğunun altında görüntülenen "Cancel" Düğmesinin metni
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


"Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan rengini alır

**Returns:**
int - ilerleme çubuğunun altında görüntülenen "Cancel" Düğmesinin rengi
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


"Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan metin boyutunu alır

**Returns:**
float - ilerleme çubuğunun altında görüntülenen "Cancel" Düğmesinin metin boyutu
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


"Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan görünürlüğünü alır

**Returns:**
boolean - "Cancel" Düğmesinin görünürlüğü
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in metnini alır

**Returns:**
java.lang.String - ilerleme çubuğunun üzerinde görüntülenen TextView'in metni
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in rengini alır

**Returns:**
int - ilerleme çubuğunun üzerinde görüntülenen TextView'in rengi
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in metin boyutunu alır

**Returns:**
float - ilerleme çubuğunun üzerinde görüntülenen TextView'in metin boyutu
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in rengini alır

**Returns:**
boolean - ilerleme çubuğunun üzerinde görüntülenen TextView'in rengi
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


Ayarları içe aktarır

**Parameters:**
| Parametre | Tür | Açıklama |
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


Tanıma işlemi sırasında renderlanacak arka planı ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | tanıma işlemi sırasında görüntülenecek arka plan |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Tanıma sırasında renderlanan ilerleme çubuğunun rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| progressBarColor | int | ilerleme çubuğunun rengi |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Tanıma sırasında ilerleme çubuğunun altında renderlanan "Cancel" düğmesinin sağ kenardan ofsetini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | "Cancel" Düğmesinin sağ kenarından ofset |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


"Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan metnini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | ilerleme çubuğunun altında görüntülenen "Cancel" Düğmesinin metni |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


"Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | ilerleme çubuğunun altında görüntülenen "Cancel" Düğmesinin rengi |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


"Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan metin boyutunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | ilerleme çubuğunun altında görüntülenen "Cancel" Düğmesinin metin boyutu |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


"Cancel" düğmesinin tanıma sırasında ilerleme çubuğunun altında renderlanan görünürlüğünü ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | İptal düğmesinin görünürlüğü |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in metnini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | İlerleme çubuğunun üzerinde render edilen TextView'in metni |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | İlerleme çubuğunun üzerinde render edilen TextView'in rengi |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in metin boyutunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | İlerleme çubuğunun üzerinde render edilen TextView'in metin boyutu |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Tanıma sırasında ilerleme çubuğunun üzerinde renderlanan TextView'in rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | İlerleme çubuğunun üzerinde render edilen TextView'in rengi |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Tanıma sırasında renderlanan ilerleme çubuğunun boyutunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| progressBarSize | int | ilerleme çubuğunun boyutu |

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

