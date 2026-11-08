---
title: "BarCodeRecognitionException"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "استثناء عام يتم إلقاؤه بواسطة BarCodeReader الموروث من BarCodeException"
type: docs
weight: 15
url: /ar/java/com.aspose.barcode.barcoderecognition/barcoderecognitionexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class BarCodeRecognitionException extends RuntimeException
```

استثناء عام يُرمى من قبل BarCodeReader، موروث من BarCodeException
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [BarCodeRecognitionException()](#BarCodeRecognitionException--) | يقوم بتهيئة نسخة جديدة من الفئة BarCodeRecognitionException. |
| [BarCodeRecognitionException(String message)](#BarCodeRecognitionException-java.lang.String-) | يقوم بتهيئة نسخة جديدة من الفئة BarCodeRecognitionException. |
| [BarCodeRecognitionException(String message, Exception innerException)](#BarCodeRecognitionException-java.lang.String-java.lang.Exception-) | يقوم بتهيئة نسخة جديدة من الفئة BarCodeRecognitionException مع رسالة الخطأ المحددة والاستثناء الحالي. |
## الدوال

| دالة | الوصف |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
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
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeRecognitionException() {#BarCodeRecognitionException--}
```
public BarCodeRecognitionException()
```


يقوم بتهيئة نسخة جديدة من الفئة BarCodeRecognitionException.

### BarCodeRecognitionException(String message) {#BarCodeRecognitionException-java.lang.String-}
```
public BarCodeRecognitionException(String message)
```


يقوم بتهيئة نسخة جديدة من الفئة BarCodeRecognitionException.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة الخطأ |

### BarCodeRecognitionException(String message, Exception innerException) {#BarCodeRecognitionException-java.lang.String-java.lang.Exception-}
```
public BarCodeRecognitionException(String message, Exception innerException)
```


يقوم بتهيئة نسخة جديدة من الفئة BarCodeRecognitionException مع رسالة الخطأ المحددة والاستثناء الحالي.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة الخطأ الخاصة بالاستثناء. |
| innerException | java.lang.Exception | يتم إلقاء الاستثناء الحالي. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
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
| معامل | النوع | الوصف |
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
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
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
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

