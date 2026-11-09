---
title: "BarcodeSvmDetectorSettings"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Instellingen voor barcode‑detector."
type: docs
weight: 21
url: /nl/java/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeSvmDetectorSettings
```

Instellingen voor barcode‑detector.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Voorinstelling voor hoge prestaties detectie. |
| [getHighQuality()](#getHighQuality--) | Voorinstelling voor hoge kwaliteit detectie. |
| [getMaxQuality()](#getMaxQuality--) | Voorinstelling voor maximale kwaliteit detectie. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Venstergrootte voor median smoothing. |
| [getNormalQuality()](#getNormalQuality--) | Voorinstelling voor normale kwaliteit detectie. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Stelt drempel in voor gedetecteerde regio's die barcodes kunnen bevatten. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Scanvenstergroottes in pixels. |
| [getSimilarityCoef()](#getSimilarityCoef--) | De similariteitscoëfficiënt hangt af van hoe homogeen barcodes zijn. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Staat de detector toe om de zoekopdracht naar diagonale barcodes over te slaan. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Venstergrootte voor median smoothing. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Stelt drempel in voor gedetecteerde regio's die barcodes kunnen bevatten. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Scanvenstergroottes in pixels. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | De similariteitscoëfficiënt hangt af van hoe homogeen barcodes zijn. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Staat de detector toe om de zoekopdracht naar diagonale barcodes over te slaan. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Voorinstelling voor hoge prestaties detectie.

Standaard voor  QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Voorinstelling voor hoge kwaliteit detectie.

Standaard voor  QualitySettings.PresetType.HighQualityDetection  en  QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Voorinstelling voor maximale kwaliteit detectie.

Standaard voor  QualitySettings.PresetType.MaxQualityDetection  en  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Venstergrootte voor median smoothing.

Typische waarden zijn 3 of 4. 0 betekent geen mediaanfiltering. Standaardwaarde is 0. De venstergrootte van het medianfilter moet tussen [0, 10] liggen.

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Voorinstelling voor normale kwaliteit detectie.

Standaard voor  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Stelt drempel in voor gedetecteerde regio's die barcodes kunnen bevatten.

Waarde 0.7 betekent dat de onderste 70 % van mogelijke regio's wordt gefilterd en niet verder wordt verwerkt. Drempel voor regio‑waarschijnlijkheid moet tussen [0.05, 0.9] liggen. Gebruik hoge waarden voor duidelijke afbeeldingen met weinig barcodes. Gebruik lage waarden voor afbeeldingen met veel barcodes of voor ruisende afbeeldingen. Een lage waarde kan leiden tot een langere herkenningstijd.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Scanvenstergroottes in pixels.

Toegestane groottes zijn 10, 15, 20, 25, 30. Scannen met een kleine venstergrootte kost meer tijd en biedt meer nauwkeurigheid, maar kan falen bij het detecteren van zeer grote barcodes. Het combineren van meerdere venstergroottes kan de detectiekwaliteit verbeteren.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


De similariteitscoëfficiënt hangt af van hoe homogeen barcodes zijn.

Gebruik een hoge waarde voor duidelijke barcodes. Gebruik lage waarden om barcodes te detecteren die gedeeltelijk beschadigd zijn of niet gelijkmatig verlicht. De similariteitscoëfficiënt moet tussen [0.5, 0.9] liggen.

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Staat de detector toe om de zoekopdracht naar diagonale barcodes over te slaan.

Als je het op false zet, zal de detectietijd toenemen, maar kun je diagonale barcodes vinden die anders gemist kunnen worden. Het inschakelen van diagonale zoekopdracht leidt tot een langere detectietijd.

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


Venstergrootte voor median smoothing.

Typische waarden zijn 3 of 4. 0 betekent geen mediaanfiltering. Standaardwaarde is 0. De venstergrootte van het medianfilter moet tussen [0, 10] liggen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Stelt drempel in voor gedetecteerde regio's die barcodes kunnen bevatten.

Waarde 0.7 betekent dat de onderste 70 % van mogelijke regio's wordt gefilterd en niet verder wordt verwerkt. Drempel voor regio‑waarschijnlijkheid moet tussen [0.05, 0.9] liggen. Gebruik hoge waarden voor duidelijke afbeeldingen met weinig barcodes. Gebruik lage waarden voor afbeeldingen met veel barcodes of voor ruisende afbeeldingen. Een lage waarde kan leiden tot een langere herkenningstijd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Scanvenstergroottes in pixels.

Toegestane groottes zijn 10, 15, 20, 25, 30. Scannen met een kleine venstergrootte kost meer tijd en biedt meer nauwkeurigheid, maar kan falen bij het detecteren van zeer grote barcodes. Het combineren van meerdere venstergroottes kan de detectiekwaliteit verbeteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


De similariteitscoëfficiënt hangt af van hoe homogeen barcodes zijn.

Gebruik een hoge waarde voor duidelijke barcodes. Gebruik lage waarden om barcodes te detecteren die gedeeltelijk beschadigd zijn of niet gelijkmatig verlicht. De similariteitscoëfficiënt moet tussen [0.5, 0.9] liggen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Staat de detector toe om de zoekopdracht naar diagonale barcodes over te slaan.

Als je het op false zet, zal de detectietijd toenemen, maar kun je diagonale barcodes vinden die anders gemist kunnen worden. Het inschakelen van diagonale zoekopdracht leidt tot een langere detectietijd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

