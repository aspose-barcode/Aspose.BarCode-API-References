---
title: "ProcessorSettings"
second_title: "Aspose.BarCode for Java API Referansı"
description: "ProcessorSettings, çok iş parçacıklı performans artışıyla barkodları tanımaya olanak tanır"
type: docs
weight: 37
url: /tr/java/com.aspose.barcode.barcoderecognition/processorsettings/
---
**Inheritance:**
java.lang.Object
```
public class ProcessorSettings
```

ProcessorSettings, çok iş parçacıklı performans artışıyla barkodları tanımaya olanak tanır

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
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxAdditionalAllowedThreads()](#getMaxAdditionalAllowedThreads--) | Kodun paralel olarak çalıştırılması için ek iş parçacıklarının azami sayısını belirtin |
| [getUseAllCores()](#getUseAllCores--) | Tüm çekirdeklerin kullanılabilmesi için gereklidir. |
| [getUseOnlyThisCoresCount()](#getUseOnlyThisCoresCount--) | Kullanılacak çekirdek sayısını belirtin. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxAdditionalAllowedThreads(int value)](#setMaxAdditionalAllowedThreads-int-) | Kodun paralel olarak çalıştırılması için ek iş parçacıklarının azami sayısını belirtin |
| [setUseAllCores(boolean value)](#setUseAllCores-boolean-) | Tüm çekirdeklerin kullanılabilmesi için gereklidir. |
| [setUseOnlyThisCoresCount(int value)](#setUseOnlyThisCoresCount-int-) | Kullanılacak çekirdek sayısını belirtin. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Kodun paralel olarak çalıştırılması için ek iş parçacıklarının azami sayısını belirtin

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


Tüm çekirdeklerin kullanılabilmesi için gereklidir.

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


Kullanılacak çekirdek sayısını belirtin. "UseAllCores" özelliğini "false" olarak değiştirmeniz gerekir.

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


Kodun paralel olarak çalıştırılması için ek iş parçacıklarının azami sayısını belirtin

--------------------

> ```
> BarCodeReader.getProcessorSettings().setMaxAdditionalAllowedThreads(Environment.getProcessorCount() * 2);
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setUseAllCores(boolean value) {#setUseAllCores-boolean-}
```
public void setUseAllCores(boolean value)
```


Tüm çekirdeklerin kullanılabilmesi için gereklidir.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(true);
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setUseOnlyThisCoresCount(int value) {#setUseOnlyThisCoresCount-int-}
```
public void setUseOnlyThisCoresCount(int value)
```


Kullanılacak çekirdek sayısını belirtin. "UseAllCores" özelliğini "false" olarak değiştirmeniz gerekir.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

