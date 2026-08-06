---
title: RecognitionProcessingFragmentSettings
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: 
type: docs
weight: 27
url: /fr/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Champs

| Champ | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Obtient l'arrière-plan qui sera rendu pendant le processus de reconnaissance |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Obtient la couleur de la barre de progression qui est rendue pendant la reconnaissance |
| [getProgressBarSize()](#getProgressBarSize--) | Obtient la taille de la barre de progression qui est rendue pendant la reconnaissance |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Obtient le décalage depuis la bordure droite du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Obtient le texte du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Obtient la couleur du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Obtient la taille du texte du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Obtient la visibilité du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Obtient le texte de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Obtient la couleur de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Obtient la taille du texte de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Obtient la couleur de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Importe les paramètres |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Définit l'arrière-plan qui sera rendu pendant le processus de reconnaissance |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Définit la couleur de la barre de progression qui est rendue pendant la reconnaissance |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Définit le décalage depuis la bordure droite du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Définit le texte du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Définit la couleur du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Définit la taille du texte du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Définit la visibilité du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Définit le texte de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Définit la couleur de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Définit la taille du texte de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Définit la couleur de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Définit la taille de la barre de progression qui est rendue pendant la reconnaissance |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<RecognitionProcessingFragmentSettings> CREATOR
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
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Obtient l'arrière-plan qui sera rendu pendant le processus de reconnaissance

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - l'arrière-plan qui sera rendu pendant le processus de reconnaissance
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getProgressBarColor() {#getProgressBarColor--}
```
public int getProgressBarColor()
```


Obtient la couleur de la barre de progression qui est rendue pendant la reconnaissance

**Returns:**
int - couleur de la barre de progression
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Obtient la taille de la barre de progression qui est rendue pendant la reconnaissance

**Returns:**
int - taille de la barre de progression
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Obtient le décalage depuis la bordure droite du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Returns:**
int - décalage depuis la bordure droite du bouton "Cancel"
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Obtient le texte du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Returns:**
java.lang.String - texte du bouton "Cancel" affiché sous la barre de progression
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Obtient la couleur du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Returns:**
int - couleur du bouton "Cancel" affiché sous la barre de progression
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Obtient la taille du texte du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Returns:**
float - taille du texte du bouton "Cancel" affiché sous la progression
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Obtient la visibilité du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Returns:**
boolean - visibilité du bouton "Cancel"
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Obtient le texte de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance

**Returns:**
java.lang.String - texte du TextView affiché au-dessus de la barre de progression
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Obtient la couleur de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance

**Returns:**
int - couleur du TextView affiché au-dessus de la barre de progression
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Obtient la taille du texte de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance

**Returns:**
float - taille du texte du TextView affiché au-dessus de la barre de progression
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Obtient la couleur de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance

**Returns:**
boolean - couleur du TextView affiché au-dessus de la barre de progression
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings) {#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-}
```
public void importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)
```


Importe les paramètres

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionProcessingFragmentSettings | com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage) {#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-}
```
public void setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)
```


Définit l'arrière-plan qui sera rendu pendant le processus de reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | l'arrière-plan qui sera affiché pendant le processus de reconnaissance |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Définit la couleur de la barre de progression qui est rendue pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| progressBarColor | int | couleur de la barre de progression |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Définit le décalage depuis la bordure droite du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | décalage depuis la bordure droite du bouton "Cancel" |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Définit le texte du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | texte du bouton "Cancel" affiché sous la barre de progression |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Définit la couleur du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | couleur du bouton "Cancel" affiché sous la barre de progression |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Définit la taille du texte du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | taille du texte du bouton "Cancel" qui est rendu sous la progression |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Définit la visibilité du bouton "Cancel" qui est rendu sous la barre de progression pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | visibilité du bouton "Cancel" |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Définit le texte de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | texte du TextView qui est rendu au-dessus de la barre de progression |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Définit la couleur de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | couleur du TextView qui est rendu au-dessus de la barre de progression |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Définit la taille du texte de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | taille du texte du TextView qui est rendu au-dessus de la barre de progression |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Définit la couleur de TextView qui est rendu au-dessus de la barre de progression pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | couleur du TextView qui est rendu au-dessus de la barre de progression |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Définit la taille de la barre de progression qui est rendue pendant la reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| progressBarSize | int | taille de la barre de progression |

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

