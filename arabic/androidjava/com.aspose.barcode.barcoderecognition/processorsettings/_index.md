---
title: ProcessorSettings
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: تسمح ProcessorSettings بالتعرف على الباركودات مع تحسين الأداء عبر تعدد الخيوط
type: docs
weight: 41
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/processorsettings/
---
**Inheritance:**
java.lang.Object
```
public class ProcessorSettings
```

تسمح ProcessorSettings بالتعرف على الباركودات مع تحسين الأداء عبر تعدد الخيوط

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

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxAdditionalAllowedThreads()](#getMaxAdditionalAllowedThreads--) | حدد الحد الأقصى لعدد الخيوط الإضافية لتشغيل الشيفرة بالتوازي |
| [getUseAllCores()](#getUseAllCores--) | مطلوب لاستخدام جميع الأنوية. |
| [getUseOnlyThisCoresCount()](#getUseOnlyThisCoresCount--) | حدد عدد الأنوية المراد استخدامها. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxAdditionalAllowedThreads(int value)](#setMaxAdditionalAllowedThreads-int-) | حدد الحد الأقصى لعدد الخيوط الإضافية لتشغيل الشيفرة بالتوازي |
| [setUseAllCores(boolean value)](#setUseAllCores-boolean-) | مطلوب لاستخدام جميع الأنوية. |
| [setUseOnlyThisCoresCount(int value)](#setUseOnlyThisCoresCount-int-) | حدد عدد الأنوية المراد استخدامها. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
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


حدد الحد الأقصى لعدد الخيوط الإضافية لتشغيل الشيفرة بالتوازي

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


مطلوب لاستخدام جميع الأنوية.

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


حدد عدد الأنوية المراد استخدامها. تحتاج إلى تغيير الخاصية "UseAllCores" إلى "false".

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


حدد الحد الأقصى لعدد الخيوط الإضافية لتشغيل الشيفرة بالتوازي

--------------------

> ```
> BarCodeReader.getProcessorSettings().setMaxAdditionalAllowedThreads(Environment.getProcessorCount() * 2);
> ```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setUseAllCores(boolean value) {#setUseAllCores-boolean-}
```
public void setUseAllCores(boolean value)
```


مطلوب لاستخدام جميع الأنوية.

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(true);
> ```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setUseOnlyThisCoresCount(int value) {#setUseOnlyThisCoresCount-int-}
```
public void setUseOnlyThisCoresCount(int value)
```


حدد عدد الأنوية المراد استخدامها. تحتاج إلى تغيير الخاصية "UseAllCores" إلى "false".

--------------------

> ```
> BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

