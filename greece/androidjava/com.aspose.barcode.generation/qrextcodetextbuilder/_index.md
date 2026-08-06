---
title: QrExtCodetextBuilder
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Εκτεταμένος γεννήτρια κωδικού κειμένου για δισδιάστατους κώδικες QR για τη λειτουργία ExtendedCodetext του QrEncodeMode. Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του BarcodeGenerator για να ορίσετε το εμφανιζόμενο κείμενο αφαιρώντας διαχειριστικούς χαρακτήρες.
type: docs
weight: 63
url: /el/androidjava/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QrEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set visible text to removing managing characters. This sample shows how to use FNC1 first position in Extended Mode: QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); lTextBuilder.addFNC1FirstPosition(); lTextBuilder.addPlainCodetext("000%89%%0"); lTextBuilder.addFNC1GroupSeparator(); lTextBuilder.addPlainCodetext("12345<FNC1>"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setQrErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); This sample shows how to use FNC1 second position in Extended Mode. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addFNC1SecondPosition("12"); TextBuilder.addPlainCodetext("TRUE3456"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); This sample shows how to use multi ECI mode in Extended Mode. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); TextBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); TextBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); TextBuilder.addPlainCodetext(@"t\\e\\\\st"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp");
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Adds codetext with Extended Channel Identifier |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Adds FNC1 in first position to the extended codetext items |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Adds Group Separator (GS - '\\\\u001D') to the extended codetext items |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Adds FNC1 in second position to the extended codetext items |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Προσθέτει απλό κείμενο κώδικα στα στοιχεία εκτεταμένου κειμένου κώδικα |
| [clear()](#clear--) | Καθαρίζει τα στοιχεία εκτεταμένου κειμένου κώδικα |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Δημιουργεί εκτεταμένο κείμενο κώδικα από τη λίστα εκτεταμένου κειμένου κώδικα. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Ελέγχει την ανάγκη προστασίας του προηγούμενου στοιχείου με "\\000000" |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Adds codetext with Extended Channel Identifier

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ECIEncoding | int | Εκτεταμένος Αναγνωριστής Καναλιού |
| codetext | java.lang.String | Κείμενο κώδικα σε unicode για προσθήκη ως στοιχείο εκτεταμένου κειμένου κώδικα με Εκτεταμένο Αναγνωριστή Καναλιού |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public void addFNC1FirstPosition()
```


Adds FNC1 in first position to the extended codetext items

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public void addFNC1GroupSeparator()
```


Adds Group Separator (GS - '\\\\u001D') to the extended codetext items

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public void addFNC1SecondPosition(String codetext)
```


Adds FNC1 in second position to the extended codetext items

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| codetext | java.lang.String | Τιμή του FNC1 στη δεύτερη θέση |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Προσθέτει απλό κείμενο κώδικα στα στοιχεία εκτεταμένου κειμένου κώδικα

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| codetext | java.lang.String | Κείμενο κώδικα σε unicode για προσθήκη ως στοιχείο εκτεταμένου κειμένου κώδικα |

### clear() {#clear--}
```
public void clear()
```


Καθαρίζει τα στοιχεία εκτεταμένου κειμένου κώδικα

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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Δημιουργεί εκτεταμένο κείμενο κώδικα από τη λίστα εκτεταμένου κειμένου κώδικα.

**Returns:**
java.lang.String - Εκτεταμένο κείμενο κώδικα ως συμβολοσειρά
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


Ελέγχει την ανάγκη προστασίας του προηγούμενου στοιχείου με "\\000000"

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| Δείκτης | int | Δείκτης στο m\_List |

**Returns:**
boolean - Ανάγκη προστασίας
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

