---
title: CameraProcessingFragmentSettings
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Ρυθμίσεις για το CameraProcessingFragment
type: docs
weight: 20
url: /el/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

Ρυθμίσεις για το CameraProcessingFragment
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | Λαμβάνει τη λειτουργία χρήσης της κάμερας. |
| [getCameraResolution()](#getCameraResolution--) | Λαμβάνει την τρέχουσα ανάλυση της κάμερας. Η προεπιλογή είναι η ελάχιστη ανάλυση. |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | Λαμβάνει το ContentDescriptionText του PreferencesButtonContent |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | Λαμβάνει τη ρύθμιση που σχετίζεται με το δείκτη περιοχής αναγνώρισης |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | Λαμβάνει το ContentDescriptionText του RecognitionButton |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | Λαμβάνει το μέγεθος του RecognizeButton |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | Λαμβάνει το μέγεθος του PreferencesButton |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | Επιστρέφει true, εάν η λυχνία είναι ενεργοποιημένη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO Προσθήκη στις ιδιότητες; Ορίζει τη λειτουργία χρήσης της κάμερας. |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | Ορίζει την ανάλυση της κάμερας. Η προεπιλογή είναι η ελάχιστη ανάλυση. |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | Ορίζει την ενεργοποίηση της λυχνίας. Κατάλληλο μόνο με CameraMode.PHOTO. Η προεπιλογή είναι true. |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | Ορίζει το ContentDescriptionText του PreferencesButtonContent |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | Ορίζει τη ρύθμιση που σχετίζεται με το δείκτη περιοχής αναγνώρισης. |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | Ορίζει το ContentDescriptionText του RecognitionButton |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | Ορίζει το μέγεθος του RecognizeButton |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | Ορίζει το μέγεθος του PreferencesButton |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel parcel, int i)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<CameraProcessingFragmentSettings> CREATOR
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


Λαμβάνει τη λειτουργία χρήσης της κάμερας. Προς το παρόν υποστηρίζει δύο λειτουργίες = PHOTO και SNAPSHOT

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


Λαμβάνει την τρέχουσα ανάλυση της κάμερας. Η προεπιλογή είναι η ελάχιστη ανάλυση.

**Returns:**
android.util.Size -
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPreferencesButtonContentDescriptionText() {#getPreferencesButtonContentDescriptionText--}
```
public String getPreferencesButtonContentDescriptionText()
```


Λαμβάνει το ContentDescriptionText του PreferencesButtonContent

**Returns:**
java.lang.String - ContentDescriptionText του PreferencesButtonContent
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


Λαμβάνει τη ρύθμιση που σχετίζεται με το δείκτη περιοχής αναγνώρισης

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


Λαμβάνει το ContentDescriptionText του RecognitionButton

**Returns:**
java.lang.String - ContentDescriptionText του RecognitionButton
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


Λαμβάνει το μέγεθος του RecognizeButton

**Returns:**
int - μέγεθος του RecognizeButton
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


Λαμβάνει το μέγεθος του PreferencesButton

**Returns:**
int - μέγεθος του PreferencesButton
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFlashEnabled() {#isFlashEnabled--}
```
public boolean isFlashEnabled()
```


Επιστρέφει true, αν το flash είναι ενεργοποιημένο. Κατάλληλο μόνο με CameraMode.PHOTO. Η προεπιλογή είναι true

**Returns:**
boolean -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCameraProcessingMode(CameraMode cameraProcessingMode) {#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-}
```
public void setCameraProcessingMode(CameraMode cameraProcessingMode)
```


TODO Προσθήκη στις ιδιότητες; Ορίζει τη λειτουργία χρήσης της κάμερας. Προς το παρόν υποστηρίζει δύο λειτουργίες = PHOTO και SNAPSHOT

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


Ορίζει την ανάλυση της κάμερας. Η προεπιλογή είναι η ελάχιστη ανάλυση.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


Ορίζει την ενεργοποίηση της λυχνίας. Κατάλληλο μόνο με CameraMode.PHOTO. Η προεπιλογή είναι true.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


Ορίζει το ContentDescriptionText του PreferencesButtonContent

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | ContentDescriptionText του PreferencesButtonContent |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


Ορίζει τη ρύθμιση που σχετίζεται με το δείκτη περιοχής αναγνώρισης.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


Ορίζει το ContentDescriptionText του RecognitionButton

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | ContentDescriptionText του RecognitionButton |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


Ορίζει το μέγεθος του RecognizeButton

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| recognizeImageButtonSize | int | μέγεθος του RecognizeButton |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


Ορίζει το μέγεθος του PreferencesButton

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | μέγεθος του PreferencesButton |

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

