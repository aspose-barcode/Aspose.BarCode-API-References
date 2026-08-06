---
title: DeconvolutionMode
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: 
type: docs
weight: 55
url: /el/androidjava/com.aspose.barcode.barcoderecognition/deconvolutionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DeconvolutionMode extends Enum<DeconvolutionMode>
```

Deconvolution (image restorations) λειτουργία που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά, η αποσύνθεση είναι μια λειτουργία που μπορεί να αποκαταστήσει μια εικόνα που έχει υποβαθμιστεί (συνυφαστεί) από οποιαδήποτε φυσική λειτουργία όπως η θόλωση, κατά τη λήψη της εικόνας με την κάμερα. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία της εικόνας που τη διαφθείρει, πρέπει να εξετάσουμε τις πιο γνωστές λειτουργίες όπως η ευκρίνεια ή η μαθηματική μορφολογία.

--------------------

> ```
> This sample shows how to use Deconvolution mode
>   
>   BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setDeconvolution(DeconvolutionMode.SLOW);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [FAST](#FAST) | Ενεργοποιεί γρήγορες μεθόδους αποσύνθεσης για εικόνες υψηλής ποιότητας. |
| [NORMAL](#NORMAL) | Ενεργοποιεί κανονικές μεθόδους αποσύνθεσης για κοινές εικόνες. |
| [SLOW](#SLOW) | Ενεργοποιεί αργές μεθόδους αποσύνθεσης για εικόνες χαμηλής ποιότητας. |
## Methods

| Method | Περιγραφή |
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
### FAST {#FAST}
```
public static final DeconvolutionMode FAST
```


Ενεργοποιεί γρήγορες μεθόδους αποσύνθεσης για εικόνες υψηλής ποιότητας.

### NORMAL {#NORMAL}
```
public static final DeconvolutionMode NORMAL
```


Ενεργοποιεί κανονικές μεθόδους αποσύνθεσης για κοινές εικόνες.

### SLOW {#SLOW}
```
public static final DeconvolutionMode SLOW
```


Ενεργοποιεί αργές μεθόδους αποσύνθεσης για εικόνες χαμηλής ποιότητας.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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
| Parameter | Type | Περιγραφή |
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static DeconvolutionMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
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
public static DeconvolutionMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### values() {#values--}
```
public static DeconvolutionMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.DeconvolutionMode[]
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

