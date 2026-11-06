---
title: "QualitySettings"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας της αναγνώρισης."
type: docs
weight: 42
url: /el/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

Το QualitySettings επιτρέπει τη ρύθμιση της ποιότητας και της ταχύτητας αναγνώρισης χειροκίνητα. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings με ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxQuality ή μπορείτε να ρυθμίσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | Κατασκευαστής QualitySettings |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Επιτρέπει στη μηχανή να αναγνωρίζει barcode που έχουν λανθασμένο checksumm ή λανθασμένες τιμές. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Λειτουργία που ενεργοποιεί τις μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |
| [getDeconvolution()](#getDeconvolution--) | Λειτουργία αποσύνθεσης (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. |
| [getHighPerformance()](#getHighPerformance--) | Προεπιλογή ποιότητας αναγνώρισης HighPerformance. |
| [getHighQuality()](#getHighQuality--) | Προεπιλογή ποιότητας αναγνώρισης HighQuality. |
| [getImageScalingMode()](#getImageScalingMode--) | Επιτρέπει την κλιμάκωση της εικόνας με το συγκεκριμένο ImageScaleMode |
| [getInverseImage()](#getInverseImage--) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση barcodes σε εικόνες με ανεστραμμένα χρώματα (λαμπρότητα). |
| [getMaxQuality()](#getMaxQuality--) | Προεπιλογή ποιότητας αναγνώρισης MaxQuality. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | Προεπιλογή ποιότητας αναγνώρισης NormalQuality. |
| [getXDimension()](#getXDimension--) | Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου barcode: κελί πλέγματος ή γραμμή. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Επιτρέπει στη μηχανή να αναγνωρίζει barcode που έχουν λανθασμένο checksumm ή λανθασμένες τιμές. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Λειτουργία που ενεργοποιεί τις μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Λειτουργία αποσύνθεσης (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | Επιτρέπει την κλιμάκωση της εικόνας με το συγκεκριμένο ImageScaleMode Value: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση barcodes σε εικόνες με ανεστραμμένα χρώματα (λαμπρότητα). |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου barcode: κελί πλέγματος ή γραμμή. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


Κατασκευαστής QualitySettings

### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<QualitySettings> CREATOR
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Επιτρέπει στη μηχανή να αναγνωρίζει barcodes που έχουν εσφαλμένο checksumm ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για την αναγνώριση κατεστραμμένων barcode με εσφαλμένο κείμενο.

Τιμή: Επιτρέπει στη μηχανή να αναγνωρίζει λανθασμένα barcodes.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. Ένα στοιχείο barcode χαμηλότερης ποιότητας απαιτεί πιο απαιτητικές μεθόδους, κάτι που επιβραδύνει την αναγνώριση.

Τιμή: Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα.

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplexBackground() {#getComplexBackground--}
```
public ComplexBackgroundMode getComplexBackground()
```


Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες.

Τιμή: Πρόσθετη αναγνώριση χρωματικών barcodes σε χρωματικές εικόνες.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Λειτουργία Deconvolution (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά, η Deconvolution είναι μια λειτουργία που μπορεί να αποκαταστήσει μια εικόνα που έχει υποστεί υποβάθμιση (συνελικτική) από οποιαδήποτε φυσική λειτουργία όπως η θόλωση, κατά τη λήψη της εικόνας με την κάμερα. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία της εικόνας που τη διαφθείρει, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως η ευκρίνεια ή η μαθηματική μορφολογία.

Τιμή: Λειτουργία Deconvolution που ορίζει το επίπεδο υποβάθμισης της εικόνας.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


Προεπιλογή ποιότητας αναγνώρισης HighPerformance. Τα υψηλής ποιότητας barcodes αναγνωρίζονται καλά σε αυτή τη λειτουργία.

--------------------

> ```
> This sample shows how to use HighPerformance mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighPerformance());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Τιμή: Προεπιλογή ποιότητας αναγνώρισης HighPerformance.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


Προεπιλογή ποιότητας αναγνώρισης HighQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για barcodes χαμηλής ποιότητας. Επιτρέπει τον εντοπισμό πολύ κατεστραμμένων barcode.

--------------------

> ```
> This sample shows how to use HighQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Τιμή: Προεπιλογή ποιότητας αναγνώρισης HighQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


Επιτρέπει την κλιμάκωση της εικόνας με το συγκεκριμένο ImageScaleMode

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση barcodes σε εικόνες με ανεστραμμένα χρώματα (λαμπρότητα).

Τιμή: Πρόσθετη αναγνώριση barcode σε εικόνες με αντίστροφα χρώματα

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


Προεπιλογή ποιότητας αναγνώρισης MaxQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για την αναγνώριση όλων των δυνατών barcode, ακόμη και λανθασμένων barcode.

--------------------

> ```
> This sample shows how to use MaxQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getMaxQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Τιμή: Προεπιλογή ποιότητας αναγνώρισης MaxQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension.

Τιμή: Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


Προεπιλογή ποιότητας αναγνώρισης NormalQuality. Κατάλληλη για τα περισσότερα barcode.

--------------------

> ```
> This sample shows how to use NormalQuality mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getNormalQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Τιμή: Προεπιλογή ποιότητας αναγνώρισης NormalQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου barcode: κελί πλέγματος ή γραμμή.

Τιμή: μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου barcode: κελί πλέγματος ή γραμμή.

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
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




### setAllowIncorrectBarcodes(boolean value) {#setAllowIncorrectBarcodes-boolean-}
```
public void setAllowIncorrectBarcodes(boolean value)
```


Επιτρέπει στη μηχανή να αναγνωρίζει barcodes που έχουν εσφαλμένο checksumm ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για την αναγνώριση κατεστραμμένων barcode με εσφαλμένο κείμενο.

Τιμή: Επιτρέπει στη μηχανή να αναγνωρίζει λανθασμένα barcodes.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. Ένα στοιχείο barcode χαμηλότερης ποιότητας απαιτεί πιο απαιτητικές μεθόδους, κάτι που επιβραδύνει την αναγνώριση.

Τιμή: Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες.

Τιμή: Πρόσθετη αναγνώριση χρωματικών barcodes σε χρωματικές εικόνες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Λειτουργία Deconvolution (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά, η Deconvolution είναι μια λειτουργία που μπορεί να αποκαταστήσει μια εικόνα που έχει υποστεί υποβάθμιση (συνελικτική) από οποιαδήποτε φυσική λειτουργία όπως η θόλωση, κατά τη λήψη της εικόνας με την κάμερα. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία της εικόνας που τη διαφθείρει, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως η ευκρίνεια ή η μαθηματική μορφολογία.

Τιμή: Λειτουργία Deconvolution που ορίζει το επίπεδο υποβάθμισης της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


Επιτρέπει την κλιμάκωση της εικόνας με το συγκεκριμένο ImageScaleMode Value:

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.barcode.barcoderecognition.ImageScalingMode | Τιμή ImageScalingMode |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση barcodes σε εικόνες με ανεστραμμένα χρώματα (λαμπρότητα).

Τιμή: Πρόσθετη αναγνώριση barcode σε εικόνες με αντίστροφα χρώματα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension.

Τιμή: Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου barcode: κελί πλέγματος ή γραμμή.

Τιμή: μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου barcode: κελί πλέγματος ή γραμμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

