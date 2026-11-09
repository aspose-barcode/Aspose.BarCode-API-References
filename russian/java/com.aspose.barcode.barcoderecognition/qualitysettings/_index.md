---
title: "QualitySettings"
second_title: "Aspose.BarCode for Java API Reference"
description: "QualitySettings позволяют вручную настраивать качество и скорость распознавания."
type: docs
weight: 40
url: /ru/java/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object
```
public final class QualitySettings
```

QualitySettings позволяет вручную настраивать качество распознавания и скорость. Вы можете быстро установить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxQuality, либо вручную настроить отдельные параметры. Значение по умолчанию для QualitySettings — NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Позволяет движку распознавать штрихкоды с некорректной контрольной суммой или неверными значениями. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| [getDeconvolution()](#getDeconvolution--) | Режим деконволюции (восстановление изображения), определяющий уровень деградации изображения. |
| [getHighPerformance()](#getHighPerformance--) | Предустановка качества распознавания HighPerformance. |
| [getHighQuality()](#getHighQuality--) | Предустановка качества распознавания HighQuality. |
| [getInverseImage()](#getInverseImage--) | Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркость). |
| [getMaxQuality()](#getMaxQuality--) | Предустановка качества распознавания MaxQuality. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | Предустановка качества распознавания NormalQuality. |
| [getXDimension()](#getXDimension--) | Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Позволяет движку распознавать штрихкоды с некорректной контрольной суммой или неверными значениями. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Режим деконволюции (восстановление изображения), определяющий уровень деградации изображения. |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркость). |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Позволяет движку распознавать штрихкоды с некорректной контрольной суммой или неверными значениями. Режим может использоваться для распознавания повреждённых штрихкодов с некорректным текстом.

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


Режим деконволюции (восстановление изображения), определяющий уровень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, ухудшенное (свёрнутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология.

Значение: Режим деконволюции, определяющий уровень деградации изображения.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


Предустановка качества распознавания HighPerformance. Штрихкоды высокого качества распознаются хорошо в этом режиме.

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

Значение: предустановка качества распознавания HighPerformance.

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


Предустановка качества распознавания MaxQuality. Эта предустановка разработана для распознавания всех возможных штрихкодов, даже некорректных.

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

Значение: Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


Предустановка качества распознавания NormalQuality. Подходит для большинства штрихкодов.

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


Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса.

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


Позволяет движку распознавать штрихкоды с некорректной контрольной суммой или неверными значениями. Режим может использоваться для распознавания повреждённых штрихкодов с некорректным текстом.

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


Режим деконволюции (восстановление изображения), определяющий уровень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, ухудшенное (свёрнутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология.

Значение: Режим деконволюции, определяющий уровень деградации изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

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

Значение: Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса.

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
public final native void wait(long arg0)
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

