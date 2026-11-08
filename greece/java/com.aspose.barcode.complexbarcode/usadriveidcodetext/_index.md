---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα PDF417 της άδειας οδήγησης ΗΠΑ."
type: docs
weight: 37
url: /el/java/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα PDF417 της άδειας οδήγησης ΗΠΑ.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | Κατασκευαστής προεπιλογής |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | Αριθμός έκδοσης AAMVA 00-99 |
| [getBarcodeType()](#getBarcodeType--) | Επιστρέφει τον τύπο barcode του USA DL (Pdf417) |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Δημιουργήστε κείμενο κώδικα από τα δεδομένα USA DL |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | Αυτός ο αριθμός αναγνωρίζει μοναδικά τη δικαιοδοσία έκδοσης και μπορεί να ληφθεί επικοινωνώντας με την Αρχή Έκδοσης ISO (AAMVA). |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | Πεδία συγκεκριμένα για τη δικαιοδοσία |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | Αριθμός έκδοσης δικαιοδοσίας 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | Υποχρεωτικά στοιχεία (πεδία) της κάρτας |
| [getNumberOfEntries()](#getNumberOfEntries--) | Αριθμός υποαρχείων 00-99 |
| [getOptionalElements()](#getOptionalElements--) | Προαιρετικά στοιχεία (πεδία) της κάρτας |
| [getSubfileDesignator()](#getSubfileDesignator--) | Περιέχει πληροφορίες σχετικά με τα παρακάτω υποαρχεία, τύπους, μετατοπίσεις και μήκη. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Αρχικοποιήστε το αντικείμενο USA DL από το κείμενο κώδικα |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | Αποθηκεύει σε XML |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | Αριθμός έκδοσης AAMVA 00-99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | Αυτός ο αριθμός αναγνωρίζει μοναδικά τη δικαιοδοσία έκδοσης και μπορεί να ληφθεί επικοινωνώντας με την Αρχή Έκδοσης ISO (AAMVA). |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | Πεδία συγκεκριμένα για τη δικαιοδοσία |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | Αριθμός έκδοσης δικαιοδοσίας 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | Υποχρεωτικά στοιχεία (πεδία) της κάρτας |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | Αριθμός υποαρχείων 00-99 |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | Προαιρετικά στοιχεία (πεδία) της κάρτας |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | Περιέχει πληροφορίες σχετικά με τα παρακάτω υποαρχεία, τύπους, μετατοπίσεις και μήκη. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


Κατασκευαστής προεπιλογής

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
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


Αριθμός έκδοσης AAMVA 00-99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Επιστρέφει τον τύπο barcode του USA DL (Pdf417)

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


Δημιουργήστε κείμενο κώδικα από τα δεδομένα USA DL

**Returns:**
java.lang.String - Κατασκευασμένο κείμενο κώδικα
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


Αυτός ο αριθμός αναγνωρίζει μοναδικά τη δικαιοδοσία έκδοσης και μπορεί να ληφθεί επικοινωνώντας με την Αρχή Έκδοσης ISO (AAMVA). Το πλήρες 6-ψήφιο IIN πρέπει να κωδικοποιηθεί.

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


Πεδία συγκεκριμένα για τη δικαιοδοσία

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


Αριθμός έκδοσης δικαιοδοσίας 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


Υποχρεωτικά στοιχεία (πεδία) της κάρτας

**Returns:**
[MandatoryFields](../../com.aspose.barcode.complexbarcode/mandatoryfields)
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


Αριθμός υποαρχείων 00-99

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


Προαιρετικά στοιχεία (πεδία) της κάρτας

**Returns:**
[OptionalFields](../../com.aspose.barcode.complexbarcode/optionalfields)
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


Περιέχει πληροφορίες σχετικά με τα παρακάτω υποαρχεία, τύπους, μετατοπίσεις και μήκη. Σημαντικό: ορίστε μόνο τον τύπο, η μετατόπιση και το μήκος θα οριστούν αυτόματα.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


Αρχικοποιήστε το αντικείμενο USA DL από το κείμενο κώδικα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Δημιουργημένο κείμενο κώδικα |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


Αποθηκεύει σε XML

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | java.io.OutputStream | Ροή για αποθήκευση |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


Αριθμός έκδοσης AAMVA 00-99

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


Αυτός ο αριθμός αναγνωρίζει μοναδικά τη δικαιοδοσία έκδοσης και μπορεί να ληφθεί επικοινωνώντας με την Αρχή Έκδοσης ISO (AAMVA). Το πλήρες 6-ψήφιο IIN πρέπει να κωδικοποιηθεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


Πεδία συγκεκριμένα για τη δικαιοδοσία

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


Αριθμός έκδοσης δικαιοδοσίας 00-99

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


Υποχρεωτικά στοιχεία (πεδία) της κάρτας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MandatoryFields](../../com.aspose.barcode.complexbarcode/mandatoryfields) |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


Αριθμός υποαρχείων 00-99

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


Προαιρετικά στοιχεία (πεδία) της κάρτας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [OptionalFields](../../com.aspose.barcode.complexbarcode/optionalfields) |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


Περιέχει πληροφορίες σχετικά με τα παρακάτω υποαρχεία, τύπους, μετατοπίσεις και μήκη. Σημαντικό: ορίστε μόνο τον τύπο, η μετατόπιση και το μήκος θα οριστούν αυτόματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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

