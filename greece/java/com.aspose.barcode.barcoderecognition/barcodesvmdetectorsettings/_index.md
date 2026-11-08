---
title: "BarcodeSvmDetectorSettings"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Ρυθμίσεις ανιχνευτή Barcode."
type: docs
weight: 21
url: /el/java/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeSvmDetectorSettings
```

Ρυθμίσεις ανιχνευτή Barcode.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | Προεπιλογή ανίχνευσης υψηλής απόδοσης. |
| [getHighQuality()](#getHighQuality--) | Προεπιλογή ανίχνευσης υψηλής ποιότητας. |
| [getMaxQuality()](#getMaxQuality--) | Προεπιλογή ανίχνευσης μέγιστης ποιότητας. |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | Μέγεθος παραθύρου για μέση εξομάλυνση. |
| [getNormalQuality()](#getNormalQuality--) | Προεπιλογή ανίχνευσης κανονικής ποιότητας. |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | Ορίζει όριο για τις ανιχνευμένες περιοχές που μπορεί να περιέχουν barcodes. |
| [getScanWindowSizes()](#getScanWindowSizes--) | Μεγέθη παραθύρων σάρωσης σε εικονοστοιχεία. |
| [getSimilarityCoef()](#getSimilarityCoef--) | Συντελεστής ομοιότητας εξαρτάται από το πόσο ομοιογενείς είναι οι γραμμωτοί κώδικες. |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | Επιτρέπει στον ανιχνευτή να παραλείψει την αναζήτηση για διαγώνιους γραμμωτούς κώδικες. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | Μέγεθος παραθύρου για μέση εξομάλυνση. |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | Ορίζει όριο για τις ανιχνευμένες περιοχές που μπορεί να περιέχουν barcodes. |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | Μεγέθη παραθύρων σάρωσης σε εικονοστοιχεία. |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | Συντελεστής ομοιότητας εξαρτάται από το πόσο ομοιογενείς είναι οι γραμμωτοί κώδικες. |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | Επιτρέπει στον ανιχνευτή να παραλείψει την αναζήτηση για διαγώνιους γραμμωτούς κώδικες. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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

Προεπιλογή για  QualitySettings.PresetType.HighPerformance

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


Προεπιλογή ανίχνευσης υψηλής ποιότητας.

Προεπιλογή για  QualitySettings.PresetType.HighQualityDetection  και  QualitySettings.PresetType.HighQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


Προεπιλογή ανίχνευσης μέγιστης ποιότητας.

Προεπιλογή για  QualitySettings.PresetType.MaxQualityDetection  και  QualitySettings.PresetType.MaxBarCodes

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


Μέγεθος παραθύρου για μέση εξομάλυνση.

Τυπικές τιμές είναι 3 ή 4. 0 σημαίνει χωρίς μεσαίο εξομάλυνση. Η προεπιλεγμένη τιμή είναι 0. Το μέγεθος παραθύρου του median filter πρέπει να είναι μεταξύ [0, 10]

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


Προεπιλογή ανίχνευσης κανονικής ποιότητας.

Προεπιλογή για  QualitySettings.PresetType.NormalQuality

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


Ορίζει όριο για τις ανιχνευμένες περιοχές που μπορεί να περιέχουν barcodes.

Η τιμή 0.7 σημαίνει ότι το κάτω 70% των πιθανών περιοχών φιλτράρεται και δεν επεξεργάζεται περαιτέρω. Το όριο πιθανότητας περιοχής πρέπει να είναι μεταξύ [0.05, 0.9]. Χρησιμοποιήστε υψηλές τιμές για καθαρές εικόνες με λίγους γραμμωτούς κώδικες. Χρησιμοποιήστε χαμηλές τιμές για εικόνες με πολλούς γραμμωτούς κώδικες ή για θορυβώδεις εικόνες. Η χαμηλή τιμή μπορεί να οδηγήσει σε μεγαλύτερο χρόνο αναγνώρισης.

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


Μεγέθη παραθύρων σάρωσης σε εικονοστοιχεία.

Οι επιτρεπόμενα μεγέθη είναι 10, 15, 20, 25, 30. Η σάρωση με μικρό μέγεθος παραθύρου απαιτεί περισσότερο χρόνο και παρέχει μεγαλύτερη ακρίβεια, αλλά μπορεί να αποτύχει στον εντοπισμό πολύ μεγάλων γραμμωτών κωδίκων. Ο συνδυασμός πολλαπλών μεγεθών παραθύρου μπορεί να βελτιώσει την ποιότητα ανίχνευσης.

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


Συντελεστής ομοιότητας εξαρτάται από το πόσο ομοιογενείς είναι οι γραμμωτοί κώδικες.

Χρησιμοποιήστε υψηλή τιμή για καθαρούς γραμμωτούς κώδικες. Χρησιμοποιήστε χαμηλές τιμές για να εντοπίσετε γραμμωτούς κώδικες που είναι μερικώς κατεστραμμένοι ή δεν φωτίζονται ομοιόμορφα. Ο συντελεστής ομοιότητας πρέπει να είναι μεταξύ [0.5, 0.9]

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


Επιτρέπει στον ανιχνευτή να παραλείψει την αναζήτηση για διαγώνιους γραμμωτούς κώδικες.

Ο ορισμός του σε false θα αυξήσει το χρόνο ανίχνευσης αλλά θα επιτρέψει την εύρεση διαγώνιων γραμμωτών κωδίκων που διαφορετικά μπορεί να παραλειφθούν. Η ενεργοποίηση της διαγώνιας αναζήτησης οδηγεί σε μεγαλύτερο χρόνο ανίχνευσης.

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


Μέγεθος παραθύρου για μέση εξομάλυνση.

Τυπικές τιμές είναι 3 ή 4. 0 σημαίνει χωρίς μεσαίο εξομάλυνση. Η προεπιλεγμένη τιμή είναι 0. Το μέγεθος παραθύρου του median filter πρέπει να είναι μεταξύ [0, 10]

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


Ορίζει όριο για τις ανιχνευμένες περιοχές που μπορεί να περιέχουν barcodes.

Η τιμή 0.7 σημαίνει ότι το κάτω 70% των πιθανών περιοχών φιλτράρεται και δεν επεξεργάζεται περαιτέρω. Το όριο πιθανότητας περιοχής πρέπει να είναι μεταξύ [0.05, 0.9]. Χρησιμοποιήστε υψηλές τιμές για καθαρές εικόνες με λίγους γραμμωτούς κώδικες. Χρησιμοποιήστε χαμηλές τιμές για εικόνες με πολλούς γραμμωτούς κώδικες ή για θορυβώδεις εικόνες. Η χαμηλή τιμή μπορεί να οδηγήσει σε μεγαλύτερο χρόνο αναγνώρισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


Μεγέθη παραθύρων σάρωσης σε εικονοστοιχεία.

Οι επιτρεπόμενα μεγέθη είναι 10, 15, 20, 25, 30. Η σάρωση με μικρό μέγεθος παραθύρου απαιτεί περισσότερο χρόνο και παρέχει μεγαλύτερη ακρίβεια, αλλά μπορεί να αποτύχει στον εντοπισμό πολύ μεγάλων γραμμωτών κωδίκων. Ο συνδυασμός πολλαπλών μεγεθών παραθύρου μπορεί να βελτιώσει την ποιότητα ανίχνευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


Συντελεστής ομοιότητας εξαρτάται από το πόσο ομοιογενείς είναι οι γραμμωτοί κώδικες.

Χρησιμοποιήστε υψηλή τιμή για καθαρούς γραμμωτούς κώδικες. Χρησιμοποιήστε χαμηλές τιμές για να εντοπίσετε γραμμωτούς κώδικες που είναι μερικώς κατεστραμμένοι ή δεν φωτίζονται ομοιόμορφα. Ο συντελεστής ομοιότητας πρέπει να είναι μεταξύ [0.5, 0.9]

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


Επιτρέπει στον ανιχνευτή να παραλείψει την αναζήτηση για διαγώνιους γραμμωτούς κώδικες.

Ο ορισμός του σε false θα αυξήσει το χρόνο ανίχνευσης αλλά θα επιτρέψει την εύρεση διαγώνιων γραμμωτών κωδίκων που διαφορετικά μπορεί να παραλειφθούν. Η ενεργοποίηση της διαγώνιας αναζήτησης οδηγεί σε μεγαλύτερο χρόνο ανίχνευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
public final native void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

