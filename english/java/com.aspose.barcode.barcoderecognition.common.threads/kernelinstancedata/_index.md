---
title: KernelInstanceData
second_title: Aspose.BarCode for Java API Reference
description: Class contains data which is proceed to the kernel instance in multithreaded mode The data describes information about piece of work which must be proceed in current kernel instance
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.common.threads/kernelinstancedata/
---
**Inheritance:**
java.lang.Object
```
public class KernelInstanceData
```

Class contains data, which is proceed to the kernel instance in multithreaded mode The data describes information about piece of work which must be proceed in current kernel instance
## Constructors

| Constructor | Description |
| --- | --- |
| [KernelInstanceData(Object aKernelLock, int aThreadIndex, int aThreadCount)](#KernelInstanceData-java.lang.Object-int-int-) | Init class with kernel instance data |
## Fields

| Field | Description |
| --- | --- |
| [KernelLock](#KernelLock) | Lock object for the job |
| [ThreadCount](#ThreadCount) | Thread count |
| [ThreadIndex](#ThreadIndex) | Thread index |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KernelInstanceData(Object aKernelLock, int aThreadIndex, int aThreadCount) {#KernelInstanceData-java.lang.Object-int-int-}
```
public KernelInstanceData(Object aKernelLock, int aThreadIndex, int aThreadCount)
```


Init class with kernel instance data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aKernelLock | java.lang.Object | Lock object for the job |
| aThreadIndex | int | Thread index |
| aThreadCount | int | Thread count |

### KernelLock {#KernelLock}
```
public final Object KernelLock
```


Lock object for the job

### ThreadCount {#ThreadCount}
```
public int ThreadCount
```


Thread count

### ThreadIndex {#ThreadIndex}
```
public int ThreadIndex
```


Thread index

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
