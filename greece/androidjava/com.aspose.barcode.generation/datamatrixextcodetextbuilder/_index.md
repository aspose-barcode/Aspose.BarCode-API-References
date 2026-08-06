---
title: DataMatrixExtCodetextBuilder
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: 
type: docs
weight: 33
url: /el/androidjava/com.aspose.barcode.generation/datamatrixextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DataMatrixExtCodetextBuilder extends ExtCodetextBuilder
```

Εκτεταμένος δημιουργός codetext για 2D DataMatrix barcode για τη λειτουργία ExtendedCodetext του EncodeMode

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.BYTES, "World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [DataMatrixExtCodetextBuilder()](#DataMatrixExtCodetextBuilder--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)](#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Προσθέτει codetext με ορισμένη λειτουργία κωδικοποίησης στα στοιχεία του εκτεταμένου codetext |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Adds codetext with Extended Channel Identifier |
| [addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)](#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Προσθέτει codetext με Extended Channel Identifier με ορισμένη λειτουργία κωδικοποίησης |
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
### DataMatrixExtCodetextBuilder() {#DataMatrixExtCodetextBuilder--}
```
public DataMatrixExtCodetextBuilder()
```


### addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext) {#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public void addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)
```


Προσθέτει codetext με ορισμένη λειτουργία κωδικοποίησης στα στοιχεία του εκτεταμένου codetext

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Τιμή λειτουργίας κωδικοποίησης |
| codetext | java.lang.String | Κείμενο κώδικα σε unicode για προσθήκη ως στοιχείο εκτεταμένου κειμένου κώδικα |

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

### addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext) {#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public void addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)
```


Προσθέτει codetext με Extended Channel Identifier με ορισμένη λειτουργία κωδικοποίησης

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ECIEncoding | int | Εκτεταμένος Αναγνωριστής Καναλιού |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Τιμή λειτουργίας κωδικοποίησης |
| codetext | java.lang.String | Codetext σε unicode για προσθήκη ως στοιχείο εκτεταμένου codetext με Extended Channel Identifier και ορισμένη λειτουργία κωδικοποίησης |

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

