---
title: "BarcodeSvmDetectorSettings"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Configuración del detector de códigos de barras."
type: docs
weight: 21
url: /es/java/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeSvmDetectorSettings
```

Configuración del detector de códigos de barras.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Preajuste de detección de alto rendimiento. |
| [getHighQuality()](#getHighQuality--) | Preajuste de detección de alta calidad. |
| [getMaxQuality()](#getMaxQuality--) | Preajuste de detección de máxima calidad. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Tamaño de ventana para suavizado mediano. |
| [getNormalQuality()](#getNormalQuality--) | Preajuste de detección de calidad normal. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Establece el umbral para regiones detectadas que pueden contener códigos de barras. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Tamaños de ventana de escaneo en píxeles. |
| [getSimilarityCoef()](#getSimilarityCoef--) | El coeficiente de similitud depende de cuán homogéneos son los códigos de barras. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Permite que el detector omita la búsqueda de códigos de barras diagonales. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Tamaño de ventana para suavizado mediano. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Establece el umbral para regiones detectadas que pueden contener códigos de barras. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Tamaños de ventana de escaneo en píxeles. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | El coeficiente de similitud depende de cuán homogéneos son los códigos de barras. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Permite que el detector omita la búsqueda de códigos de barras diagonales. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Preajuste de detección de alto rendimiento.

Valor predeterminado para  QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Preajuste de detección de alta calidad.

Valor predeterminado para  QualitySettings.PresetType.HighQualityDetection  y  QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Preajuste de detección de máxima calidad.

Valor predeterminado para  QualitySettings.PresetType.MaxQualityDetection  y  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Tamaño de ventana para suavizado mediano.

Los valores típicos son 3 o 4. 0 significa sin suavizado mediano. El valor predeterminado es 0. El tamaño de la ventana del filtro mediano debe estar entre [0, 10]

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Preajuste de detección de calidad normal.

Valor predeterminado para  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Establece el umbral para regiones detectadas que pueden contener códigos de barras.

El valor 0.7 indica que el 70 % inferior de las regiones posibles se filtran y no se procesan más. El umbral de probabilidad de la región debe estar entre [0.05, 0.9]. Use valores altos para imágenes claras con pocos códigos de barras. Use valores bajos para imágenes con muchos códigos de barras o para imágenes ruidosas. Un valor bajo puede generar un tiempo de reconocimiento mayor.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Tamaños de ventana de escaneo en píxeles.

Los tamaños permitidos son 10, 15, 20, 25, 30. Escanear con una ventana pequeña lleva más tiempo y brinda mayor precisión, pero puede fallar al detectar códigos de barras muy grandes. Combinar varios tamaños de ventana puede mejorar la calidad de detección.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


El coeficiente de similitud depende de cuán homogéneos son los códigos de barras.

Use valores altos para códigos de barras claros. Use valores bajos para detectar códigos de barras que están parcialmente dañados o no están iluminados uniformemente. El coeficiente de similitud debe estar entre [0.5, 0.9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Permite que el detector omita la búsqueda de códigos de barras diagonales.

Establecerlo en false aumentará el tiempo de detección pero permitirá encontrar códigos de barras diagonales que de otro modo se podrían pasar por alto. Habilitar la búsqueda diagonal conlleva un mayor tiempo de detección.

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


Tamaño de ventana para suavizado mediano.

Los valores típicos son 3 o 4. 0 significa sin suavizado mediano. El valor predeterminado es 0. El tamaño de la ventana del filtro mediano debe estar entre [0, 10]

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Establece el umbral para regiones detectadas que pueden contener códigos de barras.

El valor 0.7 indica que el 70 % inferior de las regiones posibles se filtran y no se procesan más. El umbral de probabilidad de la región debe estar entre [0.05, 0.9]. Use valores altos para imágenes claras con pocos códigos de barras. Use valores bajos para imágenes con muchos códigos de barras o para imágenes ruidosas. Un valor bajo puede generar un tiempo de reconocimiento mayor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Tamaños de ventana de escaneo en píxeles.

Los tamaños permitidos son 10, 15, 20, 25, 30. Escanear con una ventana pequeña lleva más tiempo y brinda mayor precisión, pero puede fallar al detectar códigos de barras muy grandes. Combinar varios tamaños de ventana puede mejorar la calidad de detección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


El coeficiente de similitud depende de cuán homogéneos son los códigos de barras.

Use valores altos para códigos de barras claros. Use valores bajos para detectar códigos de barras que están parcialmente dañados o no están iluminados uniformemente. El coeficiente de similitud debe estar entre [0.5, 0.9]

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Permite que el detector omita la búsqueda de códigos de barras diagonales.

Establecerlo en false aumentará el tiempo de detección pero permitirá encontrar códigos de barras diagonales que de otro modo se podrían pasar por alto. Habilitar la búsqueda diagonal conlleva un mayor tiempo de detección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

