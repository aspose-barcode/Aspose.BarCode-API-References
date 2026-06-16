---
title: RecognitionProcessingFragmentSettings
second_title: Справочник API Aspose.BarCode для Android через Java
description: 
type: docs
weight: 27
url: /ru/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Поля

| Поле | Описание |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Получает фон, который будет отображаться во время процесса распознавания |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Получает цвет индикатора прогресса, отображаемого во время распознавания |
| [getProgressBarSize()](#getProgressBarSize--) | Получает размер индикатора прогресса, отображаемого во время распознавания |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Получает смещение от правой границы кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Получает текст кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Получает цвет кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Получает размер текста кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Получает видимость кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Получает текст TextView, отображаемого над индикатором прогресса во время распознавания |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Получает цвет TextView, отображаемого над индикатором прогресса во время распознавания |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Получает размер текста TextView, отображаемого над индикатором прогресса во время распознавания |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Получает цвет TextView, отображаемого над индикатором прогресса во время распознавания |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Импортирует настройки |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Устанавливает фон, который будет отображаться во время процесса распознавания |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Устанавливает цвет индикатора прогресса, отображаемого во время распознавания |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Устанавливает смещение от правой границы кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Устанавливает текст кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Устанавливает цвет кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Устанавливает размер текста кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Устанавливает видимость кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Устанавливает текст TextView, отображаемого над индикатором прогресса во время распознавания |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Устанавливает цвет TextView, отображаемого над индикатором прогресса во время распознавания |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Устанавливает размер текста TextView, отображаемого над индикатором прогресса во время распознавания |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Устанавливает цвет TextView, отображаемого над индикатором прогресса во время распознавания |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Устанавливает размер индикатора прогресса, отображаемого во время распознавания |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Получает фон, который будет отображаться во время процесса распознавания

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - фон, который будет отображаться во время процесса распознавания
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


Получает цвет индикатора прогресса, отображаемого во время распознавания

**Returns:**
int - цвет индикатора прогресса
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Получает размер индикатора прогресса, отображаемого во время распознавания

**Returns:**
int - размер индикатора прогресса
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Получает смещение от правой границы кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Returns:**
int - смещение от правой границы кнопки "Cancel"
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Получает текст кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Returns:**
java.lang.String - текст кнопки "Cancel", отображаемой под индикатором прогресса
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Получает цвет кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Returns:**
int - цвет кнопки "Cancel", отображаемой под индикатором прогресса
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Получает размер текста кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Returns:**
float - размер текста кнопки "Cancel", отображаемой под индикатором
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Получает видимость кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Returns:**
boolean - видимость кнопки "Cancel"
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Получает текст TextView, отображаемого над индикатором прогресса во время распознавания

**Returns:**
java.lang.String - текст TextView, отображаемого над индикатором прогресса
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Получает цвет TextView, отображаемого над индикатором прогресса во время распознавания

**Returns:**
int - цвет TextView, отображаемого над индикатором прогресса
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Получает размер текста TextView, отображаемого над индикатором прогресса во время распознавания

**Returns:**
float - размер текста TextView, отображаемого над индикатором прогресса
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Получает цвет TextView, отображаемого над индикатором прогресса во время распознавания

**Returns:**
boolean - цвет TextView, отображаемого над индикатором прогресса
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


Импортирует настройки

**Parameters:**
| Параметр | Тип | Описание |
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


Устанавливает фон, который будет отображаться во время процесса распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | фон, который будет отображаться во время процесса распознавания |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Устанавливает цвет индикатора прогресса, отображаемого во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| progressBarColor | int | цвет индикатора прогресса |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Устанавливает смещение от правой границы кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | смещение от правой границы кнопки "Cancel" |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Устанавливает текст кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | текст кнопки "Cancel", отображаемой под индикатором прогресса |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Устанавливает цвет кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | цвет кнопки "Cancel", отображаемой под индикатором прогресса |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Устанавливает размер текста кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | размер текста кнопки "Cancel", отображаемой ниже прогресса |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Устанавливает видимость кнопки "Cancel", отображаемой под индикатором прогресса во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | видимость кнопки "Cancel" |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Устанавливает текст TextView, отображаемого над индикатором прогресса во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | текст TextView, отображаемый над индикатором прогресса |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Устанавливает цвет TextView, отображаемого над индикатором прогресса во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | цвет TextView, отображаемый над индикатором прогресса |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Устанавливает размер текста TextView, отображаемого над индикатором прогресса во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | размер текста TextView, отображаемый над индикатором прогресса |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Устанавливает цвет TextView, отображаемого над индикатором прогресса во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | цвет TextView, отображаемый над индикатором прогресса |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Устанавливает размер индикатора прогресса, отображаемого во время распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| progressBarSize | int | размер индикатора прогресса |

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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

