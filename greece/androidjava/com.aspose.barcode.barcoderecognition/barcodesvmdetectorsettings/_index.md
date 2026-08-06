---
title: BarcodeSvmDetectorSettings
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Ρυθμίσεις ανιχνευτή Barcode.
type: docs
weight: 22
url: /el/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

Ρυθμίσεις ανιχνευτή Barcode.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Προεπιλογή ανίχνευσης υψηλής απόδοσης. |
| [getHighQuality()](#getHighQuality--) | Προεπιλογή ανίχνευσης υψηλής ποιότητας. |
| [getMaxQuality()](#getMaxQuality--) | Προεπιλογή ανίχνευσης μέγιστης ποιότητας. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Μέγεθος παραθύρου για διαμεσολαβητική εξομάλυνση. |
| [getNormalQuality()](#getNormalQuality--) | Προεπιλογή ανίχνευσης κανονικής ποιότητας. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Ορίζει το όριο για τις ανιχνευθείσες περιοχές που μπορεί να περιέχουν γραμμωτούς κώδικες. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Μεγέθη παραθύρων σάρωσης σε εικονοστοιχεία. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Ο συντελεστής ομοιότητας εξαρτάται από το πόσο ομοιογενείς είναι οι γραμμωτοί κώδικες. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Επιτρέπει στον ανιχνευτή να παραλείψει την αναζήτηση διαγώνιων γραμμωτών κωδίκων. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Μέγεθος παραθύρου για διαμεσολαβητική εξομάλυνση. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Ορίζει το όριο για τις ανιχνευθείσες περιοχές που μπορεί να περιέχουν γραμμωτούς κώδικες. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Μεγέθη παραθύρων σάρωσης σε εικονοστοιχεία. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Ο συντελεστής ομοιότητας εξαρτάται από το πόσο ομοιογενείς είναι οι γραμμωτοί κώδικες. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Επιτρέπει στον ανιχνευτή να παραλείψει την αναζήτηση διαγώνιων γραμμωτών κωδίκων. |
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
| Parameter | Type | Περιγραφή |
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


Προεπιλογή ανίχνευσης υψηλής απόδοσης.

Προεπιλογή για QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Προεπιλογή ανίχνευσης υψηλής ποιότητας.

Προεπιλογή για QualitySettings.PresetType.HighQualityDetection και QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Προεπιλογή ανίχνευσης μέγιστης ποιότητας.

Προεπιλογή για QualitySettings.PresetType.MaxQualityDetection και QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Μέγεθος παραθύρου για διαμεσολαβητική εξομάλυνση.

Τυπικές τιμές είναι 3 ή 4. Το 0 σημαίνει χωρίς διαμεσολαβητική εξομάλυνση. Η προεπιλεγμένη τιμή είναι 0. Το μέγεθος παραθύρου του διαμεσολαβητικού φίλτρου πρέπει να είναι μεταξύ [0, 10]

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Προεπιλογή ανίχνευσης κανονικής ποιότητας.

Προεπιλογή για QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Ορίζει το όριο για τις ανιχνευθείσες περιοχές που μπορεί να περιέχουν γραμμωτούς κώδικες.

Η τιμή 0.7 σημαίνει ότι το κάτω 70% των πιθανών περιοχών φιλτράρεται και δεν επεξεργάζεται περαιτέρω. Το όριο πιθανοφάνειας περιοχής πρέπει να είναι μεταξύ [0.05, 0.9]. Χρησιμοποιήστε υψηλές τιμές για καθαρές εικόνες με λίγους γραμμωτούς κώδικες. Χρησιμοποιήστε χαμηλές τιμές για εικόνες με πολλούς γραμμωτούς κώδικες ή για θορυβώδεις εικόνες. Η χαμηλή τιμή μπορεί να οδηγήσει σε μεγαλύτερο χρόνο αναγνώρισης.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Μεγέθη παραθύρων σάρωσης σε εικονοστοιχεία.

Οι επιτρεπόμενα μεγέθη είναι 10, 15, 20, 25, 30. Η σάρωση με μικρό μέγεθος παραθύρου απαιτεί περισσότερο χρόνο και παρέχει μεγαλύτερη ακρίβεια, αλλά μπορεί να αποτύχει στην ανίχνευση πολύ μεγάλων γραμμωτών κωδίκων. Ο συνδυασμός πολλαπλών μεγεθών παραθύρου μπορεί να βελτιώσει την ποιότητα ανίχνευσης.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Ο συντελεστής ομοιότητας εξαρτάται από το πόσο ομοιογενείς είναι οι γραμμωτοί κώδικες.

Χρησιμοποιήστε υψηλή τιμή για καθαρούς γραμμωτούς κώδικες. Χρησιμοποιήστε χαμηλές τιμές για την ανίχνευση γραμμωτών κωδίκων που είναι εν μέρει κατεστραμμένοι ή δεν φωτίζονται ομοιόμορφα. Ο συντελεστής ομοιότητας πρέπει να είναι μεταξύ [0.5, 0.9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Επιτρέπει στον ανιχνευτή να παραλείψει την αναζήτηση διαγώνιων γραμμωτών κωδίκων.

Ο ορισμός του σε false θα αυξήσει το χρόνο ανίχνευσης, αλλά θα επιτρέψει την εύρεση διαγώνιων γραμμωτών κωδίκων που διαφορετικά μπορεί να παραλειφθούν. Η ενεργοποίηση της διαγώνιας αναζήτησης οδηγεί σε μεγαλύτερο χρόνο ανίχνευσης.

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


Μέγεθος παραθύρου για διαμεσολαβητική εξομάλυνση.

Τυπικές τιμές είναι 3 ή 4. Το 0 σημαίνει χωρίς διαμεσολαβητική εξομάλυνση. Η προεπιλεγμένη τιμή είναι 0. Το μέγεθος παραθύρου του διαμεσολαβητικού φίλτρου πρέπει να είναι μεταξύ [0, 10]

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Ορίζει το όριο για τις ανιχνευθείσες περιοχές που μπορεί να περιέχουν γραμμωτούς κώδικες.

Η τιμή 0.7 σημαίνει ότι το κάτω 70% των πιθανών περιοχών φιλτράρεται και δεν επεξεργάζεται περαιτέρω. Το όριο πιθανοφάνειας περιοχής πρέπει να είναι μεταξύ [0.05, 0.9]. Χρησιμοποιήστε υψηλές τιμές για καθαρές εικόνες με λίγους γραμμωτούς κώδικες. Χρησιμοποιήστε χαμηλές τιμές για εικόνες με πολλούς γραμμωτούς κώδικες ή για θορυβώδεις εικόνες. Η χαμηλή τιμή μπορεί να οδηγήσει σε μεγαλύτερο χρόνο αναγνώρισης.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Μεγέθη παραθύρων σάρωσης σε εικονοστοιχεία.

Οι επιτρεπόμενα μεγέθη είναι 10, 15, 20, 25, 30. Η σάρωση με μικρό μέγεθος παραθύρου απαιτεί περισσότερο χρόνο και παρέχει μεγαλύτερη ακρίβεια, αλλά μπορεί να αποτύχει στην ανίχνευση πολύ μεγάλων γραμμωτών κωδίκων. Ο συνδυασμός πολλαπλών μεγεθών παραθύρου μπορεί να βελτιώσει την ποιότητα ανίχνευσης.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Ο συντελεστής ομοιότητας εξαρτάται από το πόσο ομοιογενείς είναι οι γραμμωτοί κώδικες.

Χρησιμοποιήστε υψηλή τιμή για καθαρούς γραμμωτούς κώδικες. Χρησιμοποιήστε χαμηλές τιμές για την ανίχνευση γραμμωτών κωδίκων που είναι εν μέρει κατεστραμμένοι ή δεν φωτίζονται ομοιόμορφα. Ο συντελεστής ομοιότητας πρέπει να είναι μεταξύ [0.5, 0.9]

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Επιτρέπει στον ανιχνευτή να παραλείψει την αναζήτηση διαγώνιων γραμμωτών κωδίκων.

Ο ορισμός του σε false θα αυξήσει το χρόνο ανίχνευσης, αλλά θα επιτρέψει την εύρεση διαγώνιων γραμμωτών κωδίκων που διαφορετικά μπορεί να παραλειφθούν. Η ενεργοποίηση της διαγώνιας αναζήτησης οδηγεί σε μεγαλύτερο χρόνο ανίχνευσης.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

