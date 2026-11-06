---
title: "DataMatrixEncodeMode"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Η προεπιλεγμένη λειτουργία κωδικοποίησης των κωδικοποιητών DataMatrix είναι Auto."
type: docs
weight: 82
url: /el/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

Λειτουργία κωδικοποίησης του κωδικοποιητή DataMatrix, προεπιλογή Auto

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ANSIX12](#ANSIX12) | Χρησιμοποιεί κωδικοποίηση ANSI X12. |
| [ASCII](#ASCII) | Κωδικοποιεί έναν αλφαριθμητικό ή δύο αριθμητικούς χαρακτήρες ανά byte. |
| [AUTO](#AUTO) | Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. |
| [BASE_256](#BASE-256) | Κωδικοποίηση τιμών 8 bit. |
| [BINARY](#BINARY) | Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. |
| [C40](#C40) | Χρησιμοποιεί κωδικοποίηση C40. |
| [ECI](#ECI) | Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά με την καθορισμένη κωδικοποίηση ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI. |
| [EDIFACT](#EDIFACT) | Χρησιμοποιεί κωδικοποίηση EDIFACT. |
| [EXTENDED](#EXTENDED) | Η λειτουργία ExtendedCodetext επιτρέπει την χειροκίνητη εναλλαγή των σχημάτων κωδικοποίησης και των κωδικοποιήσεων ECI στο codetext. |
| [TEXT](#TEXT) | Χρησιμοποιεί κωδικοποίηση Text. |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


Χρησιμοποιεί κωδικοποίηση ANSI X12.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Κωδικοποιεί έναν αλφαριθμητικό ή δύο αριθμητικούς χαρακτήρες ανά byte.

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Οι χαρακτήρες Unicode κωδικοποιούνται ξανά στην κωδικοποίηση που καθορίζεται από το ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Κωδικοποίηση τιμών 8 bit.

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Εάν βρεθεί χαρακτήρας Unicode, ρίχνεται εξαίρεση.

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Χρησιμοποιεί κωδικοποίηση C40. Κωδικοποιεί αλφαριθμητικούς κεφαλαίους, πεζούς και ειδικούς χαρακτήρες.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά στην κωδικοποίηση που καθορίζεται από το ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. Παρακαλούμε σημειώστε ότι ορισμένοι παλαιοί (πριν το 2006) σαρωτές ενδέχεται να μην υποστηρίζουν αυτή τη λειτουργία.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Χρησιμοποιεί κωδικοποίηση EDIFACT. Χρησιμοποιεί έξι bits ανά χαρακτήρα, κωδικοποιεί ψηφία, κεφαλαία γράμματα και πολλά σημεία στίξης, αλλά δεν υποστηρίζει πεζά γράμματα.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


Η λειτουργία ExtendedCodetext επιτρέπει την χειροκίνητη εναλλαγή σχημάτων κωδικοποίησης και κωδικοποιήσεων ECI στο codetext. Συνιστάται να χρησιμοποιήσετε το DataMatrixExtCodetextBuilder για δημιουργία εκτεταμένου codetext. Χρησιμοποιήστε την ιδιότητα Display2DText για να ορίσετε το ορατό κείμενο αφαιρώντας διαχειριστικούς χαρακτήρες. Τα αναγνωριστικά ECI ορίζονται ως μονή κάθετος και αναγνωριστικό έξι ψηφίων \"\\000026\" - αναγνωριστικό UTF8 ECI. Όλοι οι χαρακτήρες Unicode μετά το αναγνωριστικό ECI κωδικοποιούνται αυτόματα στο σωστό σύνολο χαρακτήρων. Τα σχήματα κωδικοποίησης ορίζονται στην ακόλουθη μορφή : \"\\Encodation\\_scheme\\_name:text\\Encodation\\_scheme\\_name:text\". Τα επιτρεπόμενα σχήματα κωδικοποίησης είναι: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Όλες οι ανάποδες καθέτους (\\) πρέπει να διπλασιάζονται στο κείμενο.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Χρησιμοποιεί κωδικοποίηση Text. Κωδικοποιεί αλφαριθμητικούς πεζούς, κεφαλαίους και ειδικούς χαρακτήρες.

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
public static DataMatrixEncodeMode fromValue(int value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

