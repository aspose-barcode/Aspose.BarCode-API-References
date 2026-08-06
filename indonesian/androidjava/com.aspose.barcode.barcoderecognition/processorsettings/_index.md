---
title: ProcessorSettings
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: ProcessorSettings memungkinkan mengenali kode batang dengan peningkatan kinerja multi‑thread
type: docs
weight: 41
url: /id/androidjava/com.aspose.barcode.barcoderecognition/processorsettings/
---
**Inheritance:**
java.lang.Object
```
public class ProcessorSettings
```

ProcessorSettings memungkinkan mengenali kode batang dengan peningkatan kinerja multi‑thread

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
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxAdditionalAllowedThreads()](#getMaxAdditionalAllowedThreads--) | Tentukan jumlah maksimal thread tambahan untuk menjalankan kode secara paralel |
| [getUseAllCores()](#getUseAllCores--) | Diperlukan untuk menggunakan semua core. |
| [getUseOnlyThisCoresCount()](#getUseOnlyThisCoresCount--) | Tentukan jumlah core yang akan digunakan. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxAdditionalAllowedThreads(int value)](#setMaxAdditionalAllowedThreads-int-) | Tentukan jumlah maksimal thread tambahan untuk menjalankan kode secara paralel |
| [setUseAllCores(boolean value)](#setUseAllCores-boolean-) | Diperlukan untuk menggunakan semua core. |
| [setUseOnlyThisCoresCount(int value)](#setUseOnlyThisCoresCount-int-) | Tentukan jumlah core yang akan digunakan. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
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


Tentukan jumlah maksimal thread tambahan untuk menjalankan kode secara paralel

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


Diperlukan untuk menggunakan semua core.

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


Tentukan jumlah core yang akan digunakan. Anda perlu mengubah properti "UseAllCores" menjadi "false".

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


Tentukan jumlah maksimal thread tambahan untuk menjalankan kode secara paralel

--------------------

> ```
> BarCodeReader.getProcessorSettings().setMaxAdditionalAllowedThreads(Environment.getProcessorCount() * 2);
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setUseAllCores(boolean value) {#setUseAllCores-boolean-}
```
public void setUseAllCores(boolean value)
```


Diperlukan untuk menggunakan semua core.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(true);
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setUseOnlyThisCoresCount(int value) {#setUseOnlyThisCoresCount-int-}
```
public void setUseOnlyThisCoresCount(int value)
```


Tentukan jumlah core yang akan digunakan. Anda perlu mengubah properti "UseAllCores" menjadi "false".

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

