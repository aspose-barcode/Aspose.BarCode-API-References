---
title: ThreadsJobData
second_title: Aspose.BarCode for Java API Reference
description: Class contains data which is proceed to the every task for single job in multithreaded mode
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.common.threads/threadsjobdata/
---
**Inheritance:**
java.lang.Object
```
public class ThreadsJobData
```

Class contains data, which is proceed to the every task for single job in multithreaded mode
## Constructors

| Constructor | Description |
| --- | --- |
| [ThreadsJobData(Object aJobLock)](#ThreadsJobData-java.lang.Object-) | Init class with job for tasks list data |
## Fields

| Field | Description |
| --- | --- |
| [JobLock](#JobLock) | Lock object for the job |
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
### ThreadsJobData(Object aJobLock) {#ThreadsJobData-java.lang.Object-}
```
public ThreadsJobData(Object aJobLock)
```


Init class with job for tasks list data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aJobLock | java.lang.Object | Lock object for the job |

### JobLock {#JobLock}
```
public Object JobLock
```


Lock object for the job

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

