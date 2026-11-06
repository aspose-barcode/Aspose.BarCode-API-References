---
title: "DotCodeExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: 
type: docs
weight: 34
url: /el/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Γεννήτρια εκτεταμένου κειμένου κώδικα για 2D barcode DotCode για τη λειτουργία ExtendedCodetext του DotCodeEncodeMode

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Προσθέτει codetext με Extended Channel Identifier |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Προσθέτει το αναγνωριστικό μορφής FNC1 στα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Προσθέτει την αρχικοποίηση αναγνώστη FNC3 στα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Προσθέτει το διαχωριστικό συμβόλου FNC3 στα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Προσθέτει απλό codetext στα στοιχεία του εκτεταμένου codetext |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Προσθέτει τη λειτουργία δομημένης προσθήκης στα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [clear()](#clear--) | Καθαρίζει τα στοιχεία του εκτεταμένου codetext |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Δημιουργεί Extended codetext από τη λίστα του εκτεταμένου codetext. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Προσθέτει codetext με Extended Channel Identifier

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Codetext σε unicode για προσθήκη ως στοιχείο εκτεταμένου codetext με Extended Channel Identifier |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


Προσθέτει το αναγνωριστικό μορφής FNC1 στα στοιχεία του εκτεταμένου κειμένου κώδικα

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


Προσθέτει την αρχικοποίηση αναγνώστη FNC3 στα στοιχεία του εκτεταμένου κειμένου κώδικα

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


Προσθέτει το διαχωριστικό συμβόλου FNC3 στα στοιχεία του εκτεταμένου κειμένου κώδικα

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Προσθέτει απλό codetext στα στοιχεία του εκτεταμένου codetext

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| codetext | java.lang.String | Codetext σε unicode για προσθήκη ως στοιχείο εκτεταμένου codetext |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Προσθέτει τη λειτουργία δομημένης προσθήκης στα στοιχεία του εκτεταμένου κειμένου κώδικα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| barcodeId | int | Αναγνωριστικό του barcode |
| barcodesCount | int | Αριθμός barcode |

### clear() {#clear--}
```
public void clear()
```


Καθαρίζει τα στοιχεία του εκτεταμένου codetext

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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Δημιουργεί Extended codetext από τη λίστα του εκτεταμένου codetext.

**Returns:**
java.lang.String - Extended codetext ως string
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

