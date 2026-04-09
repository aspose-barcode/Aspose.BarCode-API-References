---
title: DotCodeExtCodetextBuilder
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: 
type: docs
weight: 35
url: /el/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Γεννήτρια εκτεταμένου κειμένου κώδικα για 2D γραμμωτού κώδικα DotCode σε λειτουργία ExtendedCodetext του DotCodeEncodeMode.

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
>  {
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  	   generator.save("test.bmp");
>  }
> ```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Adds codetext with Extended Channel Identifier |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Προσθέτει το αναγνωριστικό μορφής FNC1 στα στοιχεία εκτεταμένου κειμένου κώδικα. |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Προσθέτει την αρχικοποίηση αναγνώστη FNC3 στα στοιχεία εκτεταμένου κειμένου κώδικα. |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Προσθέτει το διαχωριστικό συμβόλου FNC3 στα στοιχεία εκτεταμένου κειμένου κώδικα. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Προσθέτει απλό κείμενο κώδικα στα στοιχεία εκτεταμένου κειμένου κώδικα |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Προσθέτει τη λειτουργία δομημένης προσθήκης στα στοιχεία εκτεταμένου κειμένου κώδικα. |
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
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
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

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public void addFNC1FormatIdentifier()
```


Προσθέτει το αναγνωριστικό μορφής FNC1 στα στοιχεία εκτεταμένου κειμένου κώδικα.

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public void addFNC3ReaderInitialization()
```


Προσθέτει την αρχικοποίηση αναγνώστη FNC3 στα στοιχεία εκτεταμένου κειμένου κώδικα.

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public void addFNC3SymbolSeparator()
```


Προσθέτει το διαχωριστικό συμβόλου FNC3 στα στοιχεία εκτεταμένου κειμένου κώδικα.

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Προσθέτει απλό κείμενο κώδικα στα στοιχεία εκτεταμένου κειμένου κώδικα

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| codetext | java.lang.String | Κείμενο κώδικα σε unicode για προσθήκη ως στοιχείο εκτεταμένου κειμένου κώδικα |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Προσθέτει τη λειτουργία δομημένης προσθήκης στα στοιχεία εκτεταμένου κειμένου κώδικα.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| barcodeId | int | Αναγνωριστικό του γραμμωτού κώδικα. |
| barcodesCount | int | Αριθμός γραμμωτών κωδίκων. |

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

