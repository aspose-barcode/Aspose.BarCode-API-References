---
title: BarcodeSvmDetectorSettings
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Barcode-Detektoreinstellungen.
type: docs
weight: 22
url: /de/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

Barcode-Detektoreinstellungen.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Voreinstellung für Hochleistungs‑Erkennung. |
| [getHighQuality()](#getHighQuality--) | Voreinstellung für Hochqualitäts‑Erkennung. |
| [getMaxQuality()](#getMaxQuality--) | Voreinstellung für Maximalqualitäts‑Erkennung. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Fenstergröße für Median‑Glättung. |
| [getNormalQuality()](#getNormalQuality--) | Voreinstellung für Normalqualitäts‑Erkennung. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Legt den Schwellenwert für erkannte Regionen fest, die Barcodes enthalten können. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Scan‑Fenstergrößen in Pixeln. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Der Ähnlichkeitskoeffizient hängt davon ab, wie homogen die Barcodes sind. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Erlaubt dem Detektor, die Suche nach diagonalen Barcodes zu überspringen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Fenstergröße für Median‑Glättung. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Legt den Schwellenwert für erkannte Regionen fest, die Barcodes enthalten können. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Scan‑Fenstergrößen in Pixeln. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Der Ähnlichkeitskoeffizient hängt davon ab, wie homogen die Barcodes sind. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Erlaubt dem Detektor, die Suche nach diagonalen Barcodes zu überspringen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<BarcodeSvmDetectorSettings> CREATOR
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
| Parameter | Type | Beschreibung |
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


Voreinstellung für Hochleistungs‑Erkennung.

Standard für  QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Voreinstellung für Hochqualitäts‑Erkennung.

Standard für  QualitySettings.PresetType.HighQualityDetection  und  QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Voreinstellung für Maximalqualitäts‑Erkennung.

Standard für  QualitySettings.PresetType.MaxQualityDetection  und  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Fenstergröße für Median‑Glättung.

Typische Werte sind 3 oder 4. 0 bedeutet keine Median‑Glättung. Standardwert ist 0. Die Fenstergröße des Medianfilters muss zwischen [0, 10] liegen.

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Voreinstellung für Normalqualitäts‑Erkennung.

Standard für  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Legt den Schwellenwert für erkannte Regionen fest, die Barcodes enthalten können.

Der Wert 0,7 bedeutet, dass die unteren 70 % der möglichen Regionen herausgefiltert und nicht weiter verarbeitet werden. Der Schwellenwert für die Regionswahrscheinlichkeit muss zwischen [0,05, 0,9] liegen. Verwenden Sie hohe Werte für klare Bilder mit wenigen Barcodes. Verwenden Sie niedrige Werte für Bilder mit vielen Barcodes oder für verrauschte Bilder. Ein niedriger Wert kann zu einer längeren Erkennungszeit führen.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Scan‑Fenstergrößen in Pixeln.

Erlaubte Größen sind 10, 15, 20, 25, 30. Das Scannen mit kleiner Fenstergröße dauert länger und liefert höhere Genauigkeit, kann jedoch bei sehr großen Barcodes fehlschlagen. Die Kombination mehrerer Fenstergrößen kann die Erkennungsqualität verbessern.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Der Ähnlichkeitskoeffizient hängt davon ab, wie homogen die Barcodes sind.

Verwenden Sie hohe Werte für klare Barcodes. Verwenden Sie niedrige Werte, um Barcodes zu erkennen, die teilweise beschädigt oder nicht gleichmäßig beleuchtet sind. Der Ähnlichkeitskoeffizient muss zwischen [0,5, 0,9] liegen.

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Erlaubt dem Detektor, die Suche nach diagonalen Barcodes zu überspringen.

Wenn Sie es auf false setzen, erhöht sich die Erkennungszeit, aber es können diagonale Barcodes gefunden werden, die sonst übersehen werden. Das Aktivieren der diagonalen Suche führt zu einer längeren Erkennungszeit.

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


Fenstergröße für Median‑Glättung.

Typische Werte sind 3 oder 4. 0 bedeutet keine Median‑Glättung. Standardwert ist 0. Die Fenstergröße des Medianfilters muss zwischen [0, 10] liegen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Legt den Schwellenwert für erkannte Regionen fest, die Barcodes enthalten können.

Der Wert 0,7 bedeutet, dass die unteren 70 % der möglichen Regionen herausgefiltert und nicht weiter verarbeitet werden. Der Schwellenwert für die Regionswahrscheinlichkeit muss zwischen [0,05, 0,9] liegen. Verwenden Sie hohe Werte für klare Bilder mit wenigen Barcodes. Verwenden Sie niedrige Werte für Bilder mit vielen Barcodes oder für verrauschte Bilder. Ein niedriger Wert kann zu einer längeren Erkennungszeit führen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Scan‑Fenstergrößen in Pixeln.

Erlaubte Größen sind 10, 15, 20, 25, 30. Das Scannen mit kleiner Fenstergröße dauert länger und liefert höhere Genauigkeit, kann jedoch bei sehr großen Barcodes fehlschlagen. Die Kombination mehrerer Fenstergrößen kann die Erkennungsqualität verbessern.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Der Ähnlichkeitskoeffizient hängt davon ab, wie homogen die Barcodes sind.

Verwenden Sie hohe Werte für klare Barcodes. Verwenden Sie niedrige Werte, um Barcodes zu erkennen, die teilweise beschädigt oder nicht gleichmäßig beleuchtet sind. Der Ähnlichkeitskoeffizient muss zwischen [0,5, 0,9] liegen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Erlaubt dem Detektor, die Suche nach diagonalen Barcodes zu überspringen.

Wenn Sie es auf false setzen, erhöht sich die Erkennungszeit, aber es können diagonale Barcodes gefunden werden, die sonst übersehen werden. Das Aktivieren der diagonalen Suche führt zu einer längeren Erkennungszeit.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

