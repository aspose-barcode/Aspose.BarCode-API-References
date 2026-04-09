---
title: CameraProcessingFragmentSettings
second_title: Справочник API Aspose.BarCode для Android через Java
description: Настройки для CameraProcessingFragment
type: docs
weight: 20
url: /ru/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

Настройки для CameraProcessingFragment
## Поля

| Поле | Описание |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | Получает режим использования камеры. |
| [getCameraResolution()](#getCameraResolution--) | Получает текущую разрешающую способность камеры. По умолчанию — минимальное разрешение |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | Получает ContentDescriptionText свойства PreferencesButtonContent |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | Получает настройку, связанную с маркером области распознавания |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | Получает ContentDescriptionText свойства RecognitionButton |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | Получает размер RecognizeButton |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | Получает размер PreferencesButton |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | Возвращает true, если вспышка включена. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO Добавить в свойства? Устанавливает режим использования камеры. |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | Устанавливает разрешение камеры. По умолчанию — минимальное разрешение |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | Включает вспышку. Подходит только для CameraMode.PHOTO. По умолчанию — true |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | Устанавливает ContentDescriptionText свойства PreferencesButtonContent |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | Устанавливает настройку, связанную с маркером области распознавания |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | Устанавливает ContentDescriptionText свойства RecognitionButton |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | Устанавливает размер RecognizeButton |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | Устанавливает размер PreferencesButton |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel parcel, int i)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<CameraProcessingFragmentSettings> CREATOR
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


Получает режим использования камеры. В настоящее время поддерживаются два режима = PHOTO и SNAPSHOT

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


Получает текущую разрешающую способность камеры. По умолчанию — минимальное разрешение

**Returns:**
android.util.Size -
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPreferencesButtonContentDescriptionText() {#getPreferencesButtonContentDescriptionText--}
```
public String getPreferencesButtonContentDescriptionText()
```


Получает ContentDescriptionText свойства PreferencesButtonContent

**Returns:**
java.lang.String - Текст описания содержимого PreferencesButtonContent
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


Получает настройку, связанную с маркером области распознавания

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


Получает ContentDescriptionText свойства RecognitionButton

**Returns:**
java.lang.String - Текст описания содержимого RecognitionButton
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


Получает размер RecognizeButton

**Returns:**
int - размер RecognizeButton
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


Получает размер PreferencesButton

**Returns:**
int - размер PreferencesButton
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFlashEnabled() {#isFlashEnabled--}
```
public boolean isFlashEnabled()
```


Возвращает true, если вспышка включена. Подходит только с CameraMode.PHOTO. По умолчанию true

**Returns:**
boolean -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCameraProcessingMode(CameraMode cameraProcessingMode) {#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-}
```
public void setCameraProcessingMode(CameraMode cameraProcessingMode)
```


TODO Добавить в свойства? Устанавливает режим использования камеры. В настоящее время поддерживаются два режима = PHOTO и SNAPSHOT

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


Устанавливает разрешение камеры. По умолчанию — минимальное разрешение

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


Включает вспышку. Подходит только для CameraMode.PHOTO. По умолчанию — true

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


Устанавливает ContentDescriptionText свойства PreferencesButtonContent

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | Текст описания содержимого PreferencesButtonContent |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


Устанавливает настройку, связанную с маркером области распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


Устанавливает ContentDescriptionText свойства RecognitionButton

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | Текст описания содержимого RecognitionButton |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


Устанавливает размер RecognizeButton

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognizeImageButtonSize | int | размер RecognizeButton |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


Устанавливает размер PreferencesButton

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | размер PreferencesButton |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

