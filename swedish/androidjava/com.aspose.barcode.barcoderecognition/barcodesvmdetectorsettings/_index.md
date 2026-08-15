---
title: BarcodeSvmDetectorSettings
second_title: Aspose.BarCode for Android via Java API-referens
description: Inställningar för streckkoddetektor.
type: docs
weight: 22
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

Inställningar för streckkoddetektor.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Förinställning för högpresterande detektering. |
| [getHighQuality()](#getHighQuality--) | Förinställning för högkvalitativ detektering. |
| [getMaxQuality()](#getMaxQuality--) | Förinställning för maximal kvalitetsdetektering. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Fönsterstorlek för medianutjämning. |
| [getNormalQuality()](#getNormalQuality--) | Förinställning för normal kvalitetsdetektering. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Ställer in tröskelvärde för upptäckta regioner som kan innehålla streckkoder. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Skanningsfönsterstorlekar i pixlar. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Likhetskoefficienten beror på hur homogena streckkoderna är. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Tillåter detektorn att hoppa över sökning efter diagonala streckkoder. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Fönsterstorlek för medianutjämning. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Ställer in tröskelvärde för upptäckta regioner som kan innehålla streckkoder. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Skanningsfönsterstorlekar i pixlar. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Likhetskoefficienten beror på hur homogena streckkoderna är. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Tillåter detektorn att hoppa över sökning efter diagonala streckkoder. |
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
| Parameter | Type | Beskrivning |
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


Förinställning för högpresterande detektering.

Standard för QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Förinställning för högkvalitativ detektering.

Standard för QualitySettings.PresetType.HighQualityDetection och QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Förinställning för maximal kvalitetsdetektering.

Standard för QualitySettings.PresetType.MaxQualityDetection och QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Fönsterstorlek för medianutjämning.

Typiska värden är 3 eller 4. 0 betyder ingen medianutjämning. Standardvärdet är 0. Medianfilterfönsterstorlek måste vara mellan [0, 10]

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Förinställning för normal kvalitetsdetektering.

Standard för QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Ställer in tröskelvärde för upptäckta regioner som kan innehålla streckkoder.

Värdet 0,7 betyder att de nedersta 70 % av möjliga regioner filtreras bort och inte bearbetas vidare. Tröskelvärde för regionsannolikhet måste vara mellan [0,05, 0,9]. Använd höga värden för tydliga bilder med få streckkoder. Använd låga värden för bilder med många streckkoder eller för brusiga bilder. Lågt värde kan leda till längre igenkänningstid.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Skanningsfönsterstorlekar i pixlar.

Tillåtna storlekar är 10, 15, 20, 25, 30. Skanning med liten fönsterstorlek tar mer tid och ger högre noggrannhet men kan misslyckas med att upptäcka mycket stora streckkoder. Kombinering av flera fönsterstorlekar kan förbättra detekteringskvaliteten.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Likhetskoefficienten beror på hur homogena streckkoderna är.

Använd högt värde för tydliga streckkoder. Använd låga värden för att upptäcka streckkoder som är delvis skadade eller inte upplysta jämnt. Likhetskoefficienten måste vara mellan [0,5, 0,9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Tillåter detektorn att hoppa över sökning efter diagonala streckkoder.

Att sätta den till false ökar detekteringstiden men möjliggör att hitta diagonala streckkoder som annars kan missas. Aktivering av diagonal sökning leder till längre detekteringstid.

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


Fönsterstorlek för medianutjämning.

Typiska värden är 3 eller 4. 0 betyder ingen medianutjämning. Standardvärdet är 0. Medianfilterfönsterstorlek måste vara mellan [0, 10]

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Ställer in tröskelvärde för upptäckta regioner som kan innehålla streckkoder.

Värdet 0,7 betyder att de nedersta 70 % av möjliga regioner filtreras bort och inte bearbetas vidare. Tröskelvärde för regionsannolikhet måste vara mellan [0,05, 0,9]. Använd höga värden för tydliga bilder med få streckkoder. Använd låga värden för bilder med många streckkoder eller för brusiga bilder. Lågt värde kan leda till längre igenkänningstid.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Skanningsfönsterstorlekar i pixlar.

Tillåtna storlekar är 10, 15, 20, 25, 30. Skanning med liten fönsterstorlek tar mer tid och ger högre noggrannhet men kan misslyckas med att upptäcka mycket stora streckkoder. Kombinering av flera fönsterstorlekar kan förbättra detekteringskvaliteten.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Likhetskoefficienten beror på hur homogena streckkoderna är.

Använd högt värde för tydliga streckkoder. Använd låga värden för att upptäcka streckkoder som är delvis skadade eller inte upplysta jämnt. Likhetskoefficienten måste vara mellan [0,5, 0,9]

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Tillåter detektorn att hoppa över sökning efter diagonala streckkoder.

Att sätta den till false ökar detekteringstiden men möjliggör att hitta diagonala streckkoder som annars kan missas. Aktivering av diagonal sökning leder till längre detekteringstid.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

