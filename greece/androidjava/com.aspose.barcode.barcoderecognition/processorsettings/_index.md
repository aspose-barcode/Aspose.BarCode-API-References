---
title: "ProcessorSettings"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Το ProcessorSettings επιτρέπει την αναγνώριση barcode με πολυνηματική βελτίωση της απόδοσης"
type: docs
weight: 39
url: /el/androidjava/com.aspose.barcode.barcoderecognition/processorsettings/
---
**Inheritance:**
java.lang.Object
```
public class ProcessorSettings
```

Το ProcessorSettings επιτρέπει την αναγνώριση barcode με πολυνηματική βελτίωση της απόδοσης

--------------------

> ```
> This sample shows how to use ProcessorSettings to add maximum multi-threaded performnce
>  
>  BarCodeReader.getProcessorSettings().setMaxAdditionalAllowedThreads(Environment.getProcessorCount()* 2);
>  //this allows to use all cores for single BarCodeReader call
>  BarCodeReader.getProcessorSettings().setUseAllCores(true);
>  //this allows to use current count of cores
>  BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxAdditionalAllowedThreads()](#getMaxAdditionalAllowedThreads--) | Καθορίστε τον μέγιστο αριθμό πρόσθετων νημάτων για εκτέλεση κώδικα παράλληλα |
| [getUseAllCores()](#getUseAllCores--) | Απαιτείται για χρήση όλων των πυρήνων. |
| [getUseOnlyThisCoresCount()](#getUseOnlyThisCoresCount--) | Καθορίστε τον αριθμό των πυρήνων που θα χρησιμοποιηθούν. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxAdditionalAllowedThreads(int value)](#setMaxAdditionalAllowedThreads-int-) | Καθορίστε τον μέγιστο αριθμό πρόσθετων νημάτων για εκτέλεση κώδικα παράλληλα |
| [setUseAllCores(boolean value)](#setUseAllCores-boolean-) | Απαιτείται για χρήση όλων των πυρήνων. |
| [setUseOnlyThisCoresCount(int value)](#setUseOnlyThisCoresCount-int-) | Καθορίστε τον αριθμό των πυρήνων που θα χρησιμοποιηθούν. |
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
### getMaxAdditionalAllowedThreads() {#getMaxAdditionalAllowedThreads--}
```
public int getMaxAdditionalAllowedThreads()
```


Καθορίστε τον μέγιστο αριθμό πρόσθετων νημάτων για εκτέλεση κώδικα παράλληλα

--------------------

> ```
> BarCodeReader.getProcessorSettings().setMaxAdditionalAllowedThreads(Environment.getProcessorCount() * 2);
> ```

**Returns:**
int
### getUseAllCores() {#getUseAllCores--}
```
public boolean getUseAllCores()
```


Απαιτείται για χρήση όλων των πυρήνων.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(true);
> ```

**Returns:**
boolean
### getUseOnlyThisCoresCount() {#getUseOnlyThisCoresCount--}
```
public int getUseOnlyThisCoresCount()
```


Καθορίστε τον αριθμό των πυρήνων που θα χρησιμοποιηθούν. Πρέπει να αλλάξετε την ιδιότητα "UseAllCores" σε "false".

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```

**Returns:**
int
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




### setMaxAdditionalAllowedThreads(int value) {#setMaxAdditionalAllowedThreads-int-}
```
public void setMaxAdditionalAllowedThreads(int value)
```


Καθορίστε τον μέγιστο αριθμό πρόσθετων νημάτων για εκτέλεση κώδικα παράλληλα

--------------------

> ```
> BarCodeReader.getProcessorSettings().setMaxAdditionalAllowedThreads(Environment.getProcessorCount() * 2);
> ```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setUseAllCores(boolean value) {#setUseAllCores-boolean-}
```
public void setUseAllCores(boolean value)
```


Απαιτείται για χρήση όλων των πυρήνων.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(true);
> ```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setUseOnlyThisCoresCount(int value) {#setUseOnlyThisCoresCount-int-}
```
public void setUseOnlyThisCoresCount(int value)
```


Καθορίστε τον αριθμό των πυρήνων που θα χρησιμοποιηθούν. Πρέπει να αλλάξετε την ιδιότητα "UseAllCores" σε "false".

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

