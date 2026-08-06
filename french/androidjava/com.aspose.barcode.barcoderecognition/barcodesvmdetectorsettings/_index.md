---
title: BarcodeSvmDetectorSettings
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres du détecteur de code-barres.
type: docs
weight: 22
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

Paramètres du détecteur de code-barres.
## Champs

| Champ | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Préréglage de détection haute performance. |
| [getHighQuality()](#getHighQuality--) | Préréglage de détection haute qualité. |
| [getMaxQuality()](#getMaxQuality--) | Préréglage de détection qualité maximale. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Taille de la fenêtre pour le lissage médian. |
| [getNormalQuality()](#getNormalQuality--) | Préréglage de détection qualité normale. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Définit le seuil pour les régions détectées pouvant contenir des codes-barres. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Tailles de la fenêtre de numérisation en pixels. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Le coefficient de similarité dépend de l'homogénéité des codes-barres. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Autorise le détecteur à ignorer la recherche de codes-barres diagonaux. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Taille de la fenêtre pour le lissage médian. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Définit le seuil pour les régions détectées pouvant contenir des codes-barres. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Tailles de la fenêtre de numérisation en pixels. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Le coefficient de similarité dépend de l'homogénéité des codes-barres. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Autorise le détecteur à ignorer la recherche de codes-barres diagonaux. |
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
| Paramètre | Type | Description |
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


Préréglage de détection haute performance.

Valeur par défaut pour  QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Préréglage de détection haute qualité.

Valeur par défaut pour  QualitySettings.PresetType.HighQualityDetection  et  QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Préréglage de détection qualité maximale.

Valeur par défaut pour  QualitySettings.PresetType.MaxQualityDetection  et  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Taille de la fenêtre pour le lissage médian.

Les valeurs typiques sont 3 ou 4. 0 signifie aucun lissage médian. La valeur par défaut est 0. La taille de la fenêtre du filtre médian doit être comprise entre [0, 10]

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Préréglage de détection qualité normale.

Valeur par défaut pour  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Définit le seuil pour les régions détectées pouvant contenir des codes-barres.

La valeur 0,7 signifie que les 70 % inférieurs des régions possibles sont filtrés et ne sont pas traités davantage. Le seuil de probabilité de région doit être compris entre [0,05, 0,9]. Utilisez des valeurs élevées pour des images claires avec peu de codes-barres. Utilisez des valeurs faibles pour des images contenant de nombreux codes-barres ou pour des images bruitées. Une valeur faible peut entraîner un temps de reconnaissance plus long.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Tailles de la fenêtre de numérisation en pixels.

Les tailles autorisées sont 10, 15, 20, 25, 30. Le numérisation avec une petite taille de fenêtre prend plus de temps et offre une plus grande précision mais peut échouer à détecter des codes-barres très grands. La combinaison de plusieurs tailles de fenêtre peut améliorer la qualité de détection.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Le coefficient de similarité dépend de l'homogénéité des codes-barres.

Utilisez une valeur élevée pour des codes-barres clairs. Utilisez des valeurs faibles pour détecter des codes-barres partiellement endommagés ou mal éclairés uniformément. Le coefficient de similarité doit être compris entre [0,5, 0,9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Autorise le détecteur à ignorer la recherche de codes-barres diagonaux.

Le définir sur false augmentera le temps de détection mais permettra de trouver des codes-barres diagonaux qui pourraient autrement être manqués. L'activation de la recherche diagonale entraîne un temps de détection plus long.

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


Taille de la fenêtre pour le lissage médian.

Les valeurs typiques sont 3 ou 4. 0 signifie aucun lissage médian. La valeur par défaut est 0. La taille de la fenêtre du filtre médian doit être comprise entre [0, 10]

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Définit le seuil pour les régions détectées pouvant contenir des codes-barres.

La valeur 0,7 signifie que les 70 % inférieurs des régions possibles sont filtrés et ne sont pas traités davantage. Le seuil de probabilité de région doit être compris entre [0,05, 0,9]. Utilisez des valeurs élevées pour des images claires avec peu de codes-barres. Utilisez des valeurs faibles pour des images contenant de nombreux codes-barres ou pour des images bruitées. Une valeur faible peut entraîner un temps de reconnaissance plus long.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Tailles de la fenêtre de numérisation en pixels.

Les tailles autorisées sont 10, 15, 20, 25, 30. Le numérisation avec une petite taille de fenêtre prend plus de temps et offre une plus grande précision mais peut échouer à détecter des codes-barres très grands. La combinaison de plusieurs tailles de fenêtre peut améliorer la qualité de détection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Le coefficient de similarité dépend de l'homogénéité des codes-barres.

Utilisez une valeur élevée pour des codes-barres clairs. Utilisez des valeurs faibles pour détecter des codes-barres partiellement endommagés ou mal éclairés uniformément. Le coefficient de similarité doit être compris entre [0,5, 0,9]

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Autorise le détecteur à ignorer la recherche de codes-barres diagonaux.

Le définir sur false augmentera le temps de détection mais permettra de trouver des codes-barres diagonaux qui pourraient autrement être manqués. L'activation de la recherche diagonale entraîne un temps de détection plus long.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

