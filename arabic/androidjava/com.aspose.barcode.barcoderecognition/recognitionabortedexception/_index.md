---
title: RecognitionAbortedException
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يمثل استثناء إلغاء التعرف الذي يُرمى عند تجاوز مهلة الوقت أثناء التعرف باستخدام BarCodeReader.
type: docs
weight: 46
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/recognitionabortedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.aspose.barcode.barcoderecognition.BarCodeRecognitionException](../../com.aspose.barcode.barcoderecognition/barcoderecognitionexception)

**All Implemented Interfaces:**
java.io.Serializable
```
public class RecognitionAbortedException extends BarCodeRecognitionException implements Serializable
```

يمثل استثناء إلغاء التعرف الذي يُرمى عند تجاوز مهلة الوقت أثناء التعرف باستخدام BarCodeReader.
## Constructors

| Constructor | الوصف |
| --- | --- |
| [RecognitionAbortedException()](#RecognitionAbortedException--) | ينشئ كائنًا جديدًا من الفئة مع رسالة إلغاء التعرف المحددة. |
| [RecognitionAbortedException(int executionTime)](#RecognitionAbortedException-int-) | ينشئ كائنًا جديدًا من الفئة مع رسالة إلغاء التعرف المحددة. |
| [RecognitionAbortedException(String message, int executionTime)](#RecognitionAbortedException-java.lang.String-int-) | ينشئ كائنًا جديدًا من الفئة مع رسالة إلغاء التعرف المحددة. |
## Methods

| Method | الوصف |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getExecutionTime()](#getExecutionTime--) | يحصل على وقت تنفيذ جلسة التعرف الحالية |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressed()](#getSuppressed--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setExecutionTime(int value)](#setExecutionTime-int-) | يضبط وقت تنفيذ جلسة التعرف الحالية |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RecognitionAbortedException() {#RecognitionAbortedException--}
```
public RecognitionAbortedException()
```


ينشئ كائنًا جديدًا من الفئة مع رسالة إلغاء التعرف المحددة.

### RecognitionAbortedException(int executionTime) {#RecognitionAbortedException-int-}
```
public RecognitionAbortedException(int executionTime)
```


ينشئ كائنًا جديدًا من الفئة مع رسالة إلغاء التعرف المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| executionTime | int | وقت تنفيذ جلسة التعرف الحالية. |

### RecognitionAbortedException(String message, int executionTime) {#RecognitionAbortedException-java.lang.String-int-}
```
public RecognitionAbortedException(String message, int executionTime)
```


ينشئ كائنًا جديدًا من الفئة مع رسالة إلغاء التعرف المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| message | java.lang.String | رسالة الخطأ الخاصة بالاستثناء. |
| executionTime | int | وقت تنفيذ جلسة التعرف الحالية. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

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
### fillInStackTrace() {#fillInStackTrace--}
```
public synchronized Throwable fillInStackTrace()
```




**Returns:**
java.lang.Throwable
### getCause() {#getCause--}
```
public synchronized Throwable getCause()
```




**Returns:**
java.lang.Throwable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExecutionTime() {#getExecutionTime--}
```
public int getExecutionTime()
```


يحصل على وقت تنفيذ جلسة التعرف الحالية

**Returns:**
int - وقت تنفيذ جلسة التعرف الحالية
### getLocalizedMessage() {#getLocalizedMessage--}
```
public String getLocalizedMessage()
```




**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public String getMessage()
```




**Returns:**
java.lang.String
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**Returns:**
java.lang.StackTraceElement[]
### getSuppressed() {#getSuppressed--}
```
public final synchronized Throwable[] getSuppressed()
```




**Returns:**
java.lang.Throwable[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initCause(Throwable arg0) {#initCause-java.lang.Throwable-}
```
public synchronized Throwable initCause(Throwable arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

**Returns:**
java.lang.Throwable
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### printStackTrace() {#printStackTrace--}
```
public void printStackTrace()
```




### printStackTrace(PrintStream arg0) {#printStackTrace-java.io.PrintStream-}
```
public void printStackTrace(PrintStream arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setExecutionTime(int value) {#setExecutionTime-int-}
```
public void setExecutionTime(int value)
```


يضبط وقت تنفيذ جلسة التعرف الحالية

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int | وقت تنفيذ جلسة التعرف الحالية |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

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

