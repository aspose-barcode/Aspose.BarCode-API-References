---
title: "BarcodeSvmDetectorSettings"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: "Barcode-detectorinstellingen."
type: docs
weight: 21
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

Barcode-detectorinstellingen.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Voorinstelling voor hoge prestatiesdetectie. |
| [getHighQuality()](#getHighQuality--) | Voorinstelling voor hoge kwaliteit detectie. |
| [getMaxQuality()](#getMaxQuality--) | Maximale kwaliteitsdetectie‑preset. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Venstergrootte voor mediaan‑vervaging. |
| [getNormalQuality()](#getNormalQuality--) | Normale kwaliteitsdetectie‑preset. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Stelt de drempel in voor gedetecteerde gebieden die barcodes kunnen bevatten. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Scanvenstergroottes in pixels. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Similariteitscoëfficiënt hangt af van hoe homogeen de barcodes zijn. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Staat de detector toe om de zoekopdracht naar diagonale barcodes over te slaan. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Venstergrootte voor mediaan‑vervaging. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Stelt de drempel in voor gedetecteerde gebieden die barcodes kunnen bevatten. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Scanvenstergroottes in pixels. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Similariteitscoëfficiënt hangt af van hoe homogeen de barcodes zijn. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Staat de detector toe om de zoekopdracht naar diagonale barcodes over te slaan. |
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


Voorinstelling voor hoge prestatiesdetectie.

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


Maximale kwaliteitsdetectie‑preset.

Standaard voor  QualitySettings.PresetType.MaxQualityDetection  en  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Venstergrootte voor mediaan‑vervaging.

Typische waarden zijn 3 of 4. 0 betekent geen mediaan‑vervaging. Standaardwaarde is 0. Venstergrootte van het mediaanfilter moet tussen [0, 10] liggen.

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Normale kwaliteitsdetectie‑preset.

Standaard voor  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Stelt de drempel in voor gedetecteerde gebieden die barcodes kunnen bevatten.

Waarde 0.7 betekent dat de onderste 70% van mogelijke gebieden wordt gefilterd en niet verder wordt verwerkt. Drempel voor waarschijnlijkheid van het gebied moet tussen [0.05, 0.9] liggen. Gebruik hoge waarden voor duidelijke afbeeldingen met weinig barcodes. Gebruik lage waarden voor afbeeldingen met veel barcodes of voor ruisende afbeeldingen. Een lage waarde kan leiden tot een langere herkenningstijd.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Scanvenstergroottes in pixels.

Toegestane groottes zijn 10, 15, 20, 25, 30. Scannen met een kleine venstergrootte kost meer tijd en biedt meer nauwkeurigheid, maar kan falen bij het detecteren van zeer grote barcodes. Het combineren van verschillende venstergroottes kan de detectiekwaliteit verbeteren.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Similariteitscoëfficiënt hangt af van hoe homogeen de barcodes zijn.

Gebruik een hoge waarde voor duidelijke barcodes. Gebruik lage waarden om barcodes te detecteren die gedeeltelijk beschadigd zijn of niet gelijkmatig verlicht. Similariteitscoëfficiënt moet tussen [0.5, 0.9] liggen.

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Staat de detector toe om de zoekopdracht naar diagonale barcodes over te slaan.

Instellen op false zal de detectietijd verhogen, maar maakt het mogelijk diagonale barcodes te vinden die anders gemist kunnen worden. Het inschakelen van diagonale zoekopdracht leidt tot een langere detectietijd.

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


Venstergrootte voor mediaan‑vervaging.

Typische waarden zijn 3 of 4. 0 betekent geen mediaan‑vervaging. Standaardwaarde is 0. Venstergrootte van het mediaanfilter moet tussen [0, 10] liggen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Stelt de drempel in voor gedetecteerde gebieden die barcodes kunnen bevatten.

Waarde 0.7 betekent dat de onderste 70% van mogelijke gebieden wordt gefilterd en niet verder wordt verwerkt. Drempel voor waarschijnlijkheid van het gebied moet tussen [0.05, 0.9] liggen. Gebruik hoge waarden voor duidelijke afbeeldingen met weinig barcodes. Gebruik lage waarden voor afbeeldingen met veel barcodes of voor ruisende afbeeldingen. Een lage waarde kan leiden tot een langere herkenningstijd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Scanvenstergroottes in pixels.

Toegestane groottes zijn 10, 15, 20, 25, 30. Scannen met een kleine venstergrootte kost meer tijd en biedt meer nauwkeurigheid, maar kan falen bij het detecteren van zeer grote barcodes. Het combineren van verschillende venstergroottes kan de detectiekwaliteit verbeteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Similariteitscoëfficiënt hangt af van hoe homogeen de barcodes zijn.

Gebruik een hoge waarde voor duidelijke barcodes. Gebruik lage waarden om barcodes te detecteren die gedeeltelijk beschadigd zijn of niet gelijkmatig verlicht. Similariteitscoëfficiënt moet tussen [0.5, 0.9] liggen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Staat de detector toe om de zoekopdracht naar diagonale barcodes over te slaan.

Instellen op false zal de detectietijd verhogen, maar maakt het mogelijk diagonale barcodes te vinden die anders gemist kunnen worden. Het inschakelen van diagonale zoekopdracht leidt tot een langere detectietijd.

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
public final void wait(long arg0)
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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

