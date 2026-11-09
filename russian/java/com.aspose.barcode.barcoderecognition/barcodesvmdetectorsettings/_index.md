---
title: "BarcodeSvmDetectorSettings"
second_title: "Aspose.BarCode for Java API Reference"
description: "Настройки детектора штрих-кодов."
type: docs
weight: 21
url: /ru/java/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeSvmDetectorSettings
```

Настройки детектора штрих-кодов.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Предустановка высокопроизводительного обнаружения. |
| [getHighQuality()](#getHighQuality--) | Предустановка высокого качества обнаружения. |
| [getMaxQuality()](#getMaxQuality--) | Предустановка максимального качества обнаружения. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Размер окна для медианной фильтрации. |
| [getNormalQuality()](#getNormalQuality--) | Предустановка обычного качества обнаружения. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Устанавливает порог для обнаруженных областей, которые могут содержать штрихкоды. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Размеры сканирующего окна в пикселях. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Коэффициент сходства зависит от того, насколько однородны штрихкоды. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Позволяет детектору пропустить поиск диагональных штрихкодов. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Размер окна для медианной фильтрации. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Устанавливает порог для обнаруженных областей, которые могут содержать штрихкоды. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Размеры сканирующего окна в пикселях. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Коэффициент сходства зависит от того, насколько однородны штрихкоды. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Позволяет детектору пропустить поиск диагональных штрихкодов. |
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


Предустановка высокопроизводительного обнаружения.

По умолчанию для  QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Предустановка высокого качества обнаружения.

По умолчанию для  QualitySettings.PresetType.HighQualityDetection  и  QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Предустановка максимального качества обнаружения.

По умолчанию для  QualitySettings.PresetType.MaxQualityDetection  и  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Размер окна для медианной фильтрации.

Типичные значения — 3 или 4. 0 означает отсутствие медианной сглаживания. Значение по умолчанию — 0. Размер окна медианного фильтра должен быть в диапазоне [0, 10]

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Предустановка обычного качества обнаружения.

По умолчанию для  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Устанавливает порог для обнаруженных областей, которые могут содержать штрихкоды.

Значение 0.7 означает, что нижние 70% возможных областей отфильтровываются и не обрабатываются дальше. Порог вероятности области должен быть в диапазоне [0.05, 0.9]. Используйте высокие значения для чистых изображений с небольшим количеством штрихкодов. Используйте низкие значения для изображений с большим количеством штрихкодов или шумных изображений. Низкое значение может привести к увеличению времени распознавания.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Размеры сканирующего окна в пикселях.

Допустимые размеры — 10, 15, 20, 25, 30. Сканирование с небольшим размером окна занимает больше времени и обеспечивает большую точность, но может не обнаружить очень большие штрихкоды. Комбинация нескольких размеров окна может улучшить качество обнаружения.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Коэффициент сходства зависит от того, насколько однородны штрихкоды.

Используйте высокое значение для чистых штрихкодов. Используйте низкие значения для обнаружения штрихкодов, которые частично повреждены или неравномерно освещены. Коэффициент сходства должен быть в диапазоне [0.5, 0.9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Позволяет детектору пропустить поиск диагональных штрихкодов.

Установка значения false увеличит время обнаружения, но позволит находить диагональные штрихкоды, которые иначе могут быть пропущены. Включение диагонального поиска приводит к увеличенному времени обнаружения.

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


Размер окна для медианной фильтрации.

Типичные значения — 3 или 4. 0 означает отсутствие медианной сглаживания. Значение по умолчанию — 0. Размер окна медианного фильтра должен быть в диапазоне [0, 10]

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Устанавливает порог для обнаруженных областей, которые могут содержать штрихкоды.

Значение 0.7 означает, что нижние 70% возможных областей отфильтровываются и не обрабатываются дальше. Порог вероятности области должен быть в диапазоне [0.05, 0.9]. Используйте высокие значения для чистых изображений с небольшим количеством штрихкодов. Используйте низкие значения для изображений с большим количеством штрихкодов или шумных изображений. Низкое значение может привести к увеличению времени распознавания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Размеры сканирующего окна в пикселях.

Допустимые размеры — 10, 15, 20, 25, 30. Сканирование с небольшим размером окна занимает больше времени и обеспечивает большую точность, но может не обнаружить очень большие штрихкоды. Комбинация нескольких размеров окна может улучшить качество обнаружения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Коэффициент сходства зависит от того, насколько однородны штрихкоды.

Используйте высокое значение для чистых штрихкодов. Используйте низкие значения для обнаружения штрихкодов, которые частично повреждены или неравномерно освещены. Коэффициент сходства должен быть в диапазоне [0.5, 0.9]

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Позволяет детектору пропустить поиск диагональных штрихкодов.

Установка значения false увеличит время обнаружения, но позволит находить диагональные штрихкоды, которые иначе могут быть пропущены. Включение диагонального поиска приводит к увеличенному времени обнаружения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

