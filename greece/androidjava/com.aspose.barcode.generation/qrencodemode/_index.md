---
title: "QREncodeMode"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Λειτουργία κωδικοποίησης για γραμμικούς κώδικες QR."
type: docs
weight: 102
url: /el/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

Λειτουργία κωδικοποίησης για QR barcode. Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε και να αποθηκεύσετε QR barcode με επεκταμένες μορφές δεδομένων.

```
{@code
 //This sample shows how to use ECI encoding and save a BarCode image.

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText("12345TEXT");
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
 generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
 generator.save("test.png");

 //This sample shows how to use FNC1 first position in Extended Mode.
 Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes.
 It is better to use QrExtCodetextBuilder for extended codetext generation.
 Use Display2DText property to set visible text by removing managing characters.
 Encoding Principles:
 All symbols "\" must be doubled "\\" in the codetext.
 FNC1 in first position is set in codetext as "<FNC1>".
 FNC1 in second position is set in codetext as "<FNC1(value)>". The value must be a single character from a-z or A-Z, or a two-digit number from 00 to 99.
 Group Separator for FNC1 modes is set as 0x1D character ''.
 If you need to insert "<FNC1>" string into barcode write it as "<\FNC1>".
 ECI identifiers are set as single slash and six digits identifier, for example "\000026" for UTF8 ECI identifier.
 The default ECI mode is ISO/IEC 8859-1 ECI identifier "\000003". It does not need to be encoded at the beginning of the codetext.
 To switch from another ECI mode to the default ECI mode, use "\000003".
 All unicode characters after ECI identifier are automatically encoded into correct character codeset.
 QR compaction mode selectors are set as single slash and mode name: "\auto", "\num", "\alnum", "\byte", "\kanji".
 "\auto" sets automatic compaction mode, "\num" sets Numeric mode, "\alnum" sets AlphaNumeric mode, "\byte" sets Bytes mode, and "\kanji" sets Kanji mode.
 The default compaction mode is "\auto".
 Compaction mode selectors define the encoding mode for the following data until the next compaction mode selector or ECI identifier is found.
 If the data cannot be encoded in the selected compaction mode, an ArgumentException is thrown.
 This mode is not supported by MicroQR barcodes.

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");

 //This sample shows how to use FNC1 second position in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");

 //This sample shows how to use multi ECI mode in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
 textBuilder.addPlainCodetext"t\e\\st");
 textBuilder.addAlphaNumericCodetext("ASPOSE2001");
 textBuilder.addNumericCodetext(@"20012026");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.getExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text";
 generator.save("test.png");
```
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [AUTO](#AUTO) | Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. |
| [BINARY](#BINARY) | Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. |
| [ECI](#ECI) | Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά με την καθορισμένη κωδικοποίηση ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI. |
| [EXTENDED](#EXTENDED) | Εκτεταμένη λειτουργία καναλιού που υποστηρίζει τη θέση FNC1 πρώτης θέσης, τη θέση FNC1 δεύτερης θέσης και πολλαπλές λειτουργίες ECI. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final QREncodeMode AUTO
```


Στη λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Οι χαρακτήρες Unicode κωδικοποιούνται σε λειτουργία kanji εάν είναι δυνατόν, ή κωδικοποιούνται ξανά με την κωδικοποίηση που καθορίζεται από το ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Εάν βρεθεί χαρακτήρας Unicode, ρίχνεται εξαίρεση.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


Στη λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά με την κωδικοποίηση που καθορίζεται από το ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. Παρακαλούμε σημειώστε ότι ορισμένα παλιά (πριν το 2006) σαρωτές ενδέχεται να μην υποστηρίζουν αυτή τη λειτουργία. Αυτή η λειτουργία δεν υποστηρίζεται από τα MicroQR barcode.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


Εκτεταμένη λειτουργία καναλιού που υποστηρίζει τη θέση FNC1 πρώτης θέσης, τη θέση FNC1 δεύτερης θέσης και πολλαπλές λειτουργίες ECI. Συνιστάται η χρήση του QrExtCodetextBuilder για δημιουργία εκτεταμένου κειμένου κωδικοποίησης. Χρησιμοποιήστε την ιδιότητα Display2DText για να ορίσετε το ορατό κείμενο αφαιρώντας χαρακτήρες διαχείρισης. Αρχές κωδικοποίησης: Όλα τα σύμβολα "\\" πρέπει να διπλασιαστούν σε "\\\\" στο κείμενο κωδικοποίησης. Το FNC1 στην πρώτη θέση ορίζεται στο κείμενο ως "<FNC1>". Το FNC1 στη δεύτερη θέση ορίζεται ως "<FNC1(value)>". Η τιμή πρέπει να είναι ένας μόνο χαρακτήρας από a‑z ή A‑Z, ή ένας διψήφιος αριθμός από 00 έως 99. Ο διαχωριστής ομάδας για τις λειτουργίες FNC1 ορίζεται ως χαρακτήρας 0x1D '\u001d'. Εάν χρειάζεται να εισάγετε τη συμβολοσειρά "<FNC1>" στο barcode, γράψτε την ως "<\\FNC1>". Τα αναγνωριστικά ECI ορίζονται ως μονή κάθετος και εξάψιφιος αναγνωριστής, για παράδειγμα "\\000026" για το αναγνωριστικό ECI UTF8. Η προεπιλεγμένη λειτουργία ECI είναι το αναγνωριστικό ISO/IEC 8859-1 ECI "\\000003". Δεν χρειάζεται να κωδικοποιηθεί στην αρχή του κειμένου κωδικοποίησης. Για αλλαγή από άλλη λειτουργία ECI στην προεπιλεγμένη, χρησιμοποιήστε "\\000003". Όλοι οι χαρακτήρες Unicode μετά το αναγνωριστικό ECI κωδικοποιούνται αυτόματα στο σωστό σύνολο χαρακτήρων. Οι επιλογείς λειτουργίας συμπίεσης QR ορίζονται ως μονή κάθετος και όνομα λειτουργίας: "\\auto", "\\num", "\\alnum", "\\byte", "\\kanji". Το "\\auto" ορίζει αυτόματη λειτουργία συμπίεσης, το "\\num" ορίζει αριθμητική λειτουργία, το "\\alnum" ορίζει αλφαριθμητική λειτουργία, το "\\byte" ορίζει λειτουργία byte, και το "\\kanji" ορίζει λειτουργία kanji. Η προεπιλεγμένη λειτουργία συμπίεσης είναι "\\auto". Οι επιλογείς λειτουργίας συμπίεσης ορίζουν τη λειτουργία κωδικοποίησης για τα επόμενα δεδομένα μέχρι να βρεθεί ο επόμενος επιλογέας λειτουργίας συμπίεσης ή αναγνωριστικό ECI. Εάν τα δεδομένα δεν μπορούν να κωδικοποιηθούν στην επιλεγμένη λειτουργία συμπίεσης, ρίχνεται ArgumentException. Αυτή η λειτουργία δεν υποστηρίζεται από τα MicroQR barcode.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QREncodeMode fromValue(int value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static QREncodeMode valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### values() {#values--}
```
public static QREncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.QREncodeMode[]
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

