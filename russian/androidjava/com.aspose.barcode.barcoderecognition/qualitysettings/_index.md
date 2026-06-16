---
title: QualitySettings
second_title: Справочник API Aspose.BarCode для Android через Java
description: QualitySettings позволяет вручную настраивать качество и скорость распознавания.
type: docs
weight: 44
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings позволяет вручную настраивать качество распознавания и скорость. Вы можете быстро настроить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxQuality, или вручную настроить отдельные параметры. Значение по умолчанию для QualitySettings — NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | Конструктор QualitySettings |
## Поля

| Поле | Описание |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Позволяет движку распознавать штрихкоды с неправильной контрольной суммой или некорректными значениями. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| [getDeconvolution()](#getDeconvolution--) | Режим деконволюции (восстановление изображения), определяющий степень деградации изображения. |
| [getHighPerformance()](#getHighPerformance--) | Предустановка качества распознавания HighPerformance. |
| [getHighQuality()](#getHighQuality--) | Предустановка качества распознавания HighQuality. |
| [getImageScalingMode()](#getImageScalingMode--) | Позволяет масштабировать изображение с использованием конкретного ImageScaleMode. |
| [getInverseImage()](#getInverseImage--) | Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркость). |
| [getMaxQuality()](#getMaxQuality--) | Предустановка качества распознавания MaxQuality. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | Предустановка качества распознавания NormalQuality. |
| [getXDimension()](#getXDimension--) | Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейки матрицы или полосы. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Позволяет движку распознавать штрихкоды с неправильной контрольной суммой или некорректными значениями. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Режим деконволюции (восстановление изображения), определяющий степень деградации изображения. |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | Позволяет масштабировать изображение с использованием конкретного ImageScaleMode. Значение: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркость). |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейки матрицы или полосы. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


Конструктор QualitySettings

### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<QualitySettings> CREATOR
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
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Позволяет движку распознавать штрихкоды с неправильной контрольной суммой или некорректными значениями. Этот режим можно использовать для распознавания повреждённых штрихкодов с неверным текстом.

Значение: Позволяет движку распознавать некорректные штрихкоды.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. Элемент штрихкода более низкого качества требует более сложных методов, что замедляет распознавание.

Значение: Режим, который включает методы распознавания элементов штрихкода с выбранным качеством.

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplexBackground() {#getComplexBackground--}
```
public ComplexBackgroundMode getComplexBackground()
```


Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях.

Значение: Дополнительное распознавание цветных штрихкодов на цветных изображениях.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Режим деконволюции (восстановление изображения), определяющий степень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, испорченное (свернутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология.

Значение: Режим деконволюции, определяющий степень деградации изображения.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


Предустановка качества распознавания HighPerformance. Штрихкоды высокого качества хорошо распознаются в этом режиме.

--------------------

> ```
> This sample shows how to use HighPerformance mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighPerformance());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Значение: Предустановка качества распознавания HighPerformance.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


Предустановка качества распознавания HighQuality. Эта предустановка разработана для штрихкодов низкого качества. Позволяет обнаруживать сильно повреждённые штрихкоды.

--------------------

> ```
> This sample shows how to use HighQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Значение: предустановка качества распознавания HighQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


Позволяет масштабировать изображение с использованием конкретного ImageScaleMode.

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркость).

Значение: Дополнительное распознавание штрихкодов на изображениях с инвертированными цветами

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


Предустановка качества распознавания MaxQuality. Эта предустановка разработана для распознавания всех возможных штрихкодов, даже некорректных штрихкодов.

--------------------

> ```
> This sample shows how to use MaxQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getMaxQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Значение: предустановка качества распознавания MaxQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension.

Значение: Минимальный размер XDimension в пикселях, который используется с UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


Предустановка качества распознавания NormalQuality. Подходит для большинства штрихкодов

--------------------

> ```
> This sample shows how to use NormalQuality mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getNormalQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Значение: предустановка качества распознавания NormalQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейки матрицы или полосы.

Значение: размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса.

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
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




### setAllowIncorrectBarcodes(boolean value) {#setAllowIncorrectBarcodes-boolean-}
```
public void setAllowIncorrectBarcodes(boolean value)
```


Позволяет движку распознавать штрихкоды с неправильной контрольной суммой или некорректными значениями. Этот режим можно использовать для распознавания повреждённых штрихкодов с неверным текстом.

Значение: Позволяет движку распознавать некорректные штрихкоды.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. Элемент штрихкода более низкого качества требует более сложных методов, что замедляет распознавание.

Значение: Режим, который включает методы распознавания элементов штрихкода с выбранным качеством.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях.

Значение: Дополнительное распознавание цветных штрихкодов на цветных изображениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Режим деконволюции (восстановление изображения), определяющий степень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, испорченное (свернутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология.

Значение: Режим деконволюции, определяющий степень деградации изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


Позволяет масштабировать изображение с использованием конкретного ImageScaleMode. Значение:

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.barcode.barcoderecognition.ImageScalingMode | Значение ImageScalingMode |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркость).

Значение: Дополнительное распознавание штрихкодов на изображениях с инвертированными цветами

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension.

Значение: Минимальный размер XDimension в пикселях, который используется с UseMinimalXDimension.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейки матрицы или полосы.

Значение: размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

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

