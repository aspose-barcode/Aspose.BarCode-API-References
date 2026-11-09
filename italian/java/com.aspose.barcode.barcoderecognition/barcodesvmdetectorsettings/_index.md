---
title: "BarcodeSvmDetectorSettings"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Impostazioni del rilevatore di codici a barre."
type: docs
weight: 21
url: /it/java/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeSvmDetectorSettings
```

Impostazioni del rilevatore di codici a barre.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Preset di rilevamento ad alte prestazioni. |
| [getHighQuality()](#getHighQuality--) | Preset di rilevamento ad alta qualità. |
| [getMaxQuality()](#getMaxQuality--) | Preset di rilevamento di massima qualità. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Dimensione della finestra per la levigatura mediana. |
| [getNormalQuality()](#getNormalQuality--) | Preset di rilevamento di qualità normale. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Imposta la soglia per le regioni rilevate che possono contenere codici a barre. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Dimensioni della finestra di scansione in pixel. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Il coefficiente di similarità dipende da quanto sono omogenei i codici a barre. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Consente al rilevatore di saltare la ricerca di codici a barre diagonali. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Dimensione della finestra per la levigatura mediana. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Imposta la soglia per le regioni rilevate che possono contenere codici a barre. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Dimensioni della finestra di scansione in pixel. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Il coefficiente di similarità dipende da quanto sono omogenei i codici a barre. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Consente al rilevatore di saltare la ricerca di codici a barre diagonali. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Preset di rilevamento ad alte prestazioni.

Predefinito per  QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Preset di rilevamento ad alta qualità.

Predefinito per  QualitySettings.PresetType.HighQualityDetection  e  QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Preset di rilevamento di massima qualità.

Predefinito per  QualitySettings.PresetType.MaxQualityDetection  e  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Dimensione della finestra per la levigatura mediana.

I valori tipici sono 3 o 4. 0 significa nessuna levigatura mediana. Il valore predefinito è 0. La dimensione della finestra del filtro mediano deve essere compresa tra [0, 10]

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Preset di rilevamento di qualità normale.

Predefinito per  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Imposta la soglia per le regioni rilevate che possono contenere codici a barre.

Il valore 0.7 indica che il 70% inferiore delle regioni possibili viene filtrato e non elaborato ulteriormente. La soglia di probabilità della regione deve essere compresa tra [0.05, 0.9]. Usa valori alti per immagini nitide con pochi codici a barre. Usa valori bassi per immagini con molti codici a barre o per immagini rumorose. Un valore basso può portare a un tempo di riconoscimento più lungo.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Dimensioni della finestra di scansione in pixel.

Le dimensioni consentite sono 10, 15, 20, 25, 30. La scansione con una finestra piccola richiede più tempo e fornisce maggiore precisione, ma può fallire nel rilevare codici a barre molto grandi. La combinazione di diverse dimensioni della finestra può migliorare la qualità del rilevamento.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Il coefficiente di similarità dipende da quanto sono omogenei i codici a barre.

Usa valori alti per codici a barre chiari. Usa valori bassi per rilevare codici a barre parzialmente danneggiati o non illuminati uniformemente. Il coefficiente di similarità deve essere compreso tra [0.5, 0.9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Consente al rilevatore di saltare la ricerca di codici a barre diagonali.

Impostarlo su false aumenterà il tempo di rilevamento ma consentirà di trovare codici a barre diagonali che altrimenti potrebbero essere persi. L'abilitazione della ricerca diagonale porta a un tempo di rilevamento più lungo.

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


Dimensione della finestra per la levigatura mediana.

I valori tipici sono 3 o 4. 0 significa nessuna levigatura mediana. Il valore predefinito è 0. La dimensione della finestra del filtro mediano deve essere compresa tra [0, 10]

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Imposta la soglia per le regioni rilevate che possono contenere codici a barre.

Il valore 0.7 indica che il 70% inferiore delle regioni possibili viene filtrato e non elaborato ulteriormente. La soglia di probabilità della regione deve essere compresa tra [0.05, 0.9]. Usa valori alti per immagini nitide con pochi codici a barre. Usa valori bassi per immagini con molti codici a barre o per immagini rumorose. Un valore basso può portare a un tempo di riconoscimento più lungo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Dimensioni della finestra di scansione in pixel.

Le dimensioni consentite sono 10, 15, 20, 25, 30. La scansione con una finestra piccola richiede più tempo e fornisce maggiore precisione, ma può fallire nel rilevare codici a barre molto grandi. La combinazione di diverse dimensioni della finestra può migliorare la qualità del rilevamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Il coefficiente di similarità dipende da quanto sono omogenei i codici a barre.

Usa valori alti per codici a barre chiari. Usa valori bassi per rilevare codici a barre parzialmente danneggiati o non illuminati uniformemente. Il coefficiente di similarità deve essere compreso tra [0.5, 0.9]

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Consente al rilevatore di saltare la ricerca di codici a barre diagonali.

Impostarlo su false aumenterà il tempo di rilevamento ma consentirà di trovare codici a barre diagonali che altrimenti potrebbero essere persi. L'abilitazione della ricerca diagonale porta a un tempo di rilevamento più lungo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

