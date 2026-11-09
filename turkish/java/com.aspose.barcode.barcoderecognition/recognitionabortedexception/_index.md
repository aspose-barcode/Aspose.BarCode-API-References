---
title: "RecognitionAbortedException"
second_title: "Aspose.BarCode for Java API Referansı"
description: "BarCodeReader ile tanıma sırasında zaman aşımı aşıldığında atılan tanıma iptal istisnasını temsil eder."
type: docs
weight: 42
url: /tr/java/com.aspose.barcode.barcoderecognition/recognitionabortedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.aspose.barcode.barcoderecognition.BarCodeRecognitionException](../../com.aspose.barcode.barcoderecognition/barcoderecognitionexception)

**All Implemented Interfaces:**
java.io.Serializable
```
public class RecognitionAbortedException extends BarCodeRecognitionException implements Serializable
```

BarCodeReader ile tanıma sırasında zaman aşımı aşıldığında atılan tanıma iptal istisnasını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RecognitionAbortedException()](#RecognitionAbortedException--) | Belirtilen tanıma iptal mesajı ile sınıfın yeni bir örneğini başlatır. |
| [RecognitionAbortedException(int executionTime)](#RecognitionAbortedException-int-) | Belirtilen tanıma iptal mesajı ile sınıfın yeni bir örneğini başlatır. |
| [RecognitionAbortedException(String message, int executionTime)](#RecognitionAbortedException-java.lang.String-int-) | Belirtilen tanıma iptal mesajı ile sınıfın yeni bir örneğini başlatır. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getExecutionTime()](#getExecutionTime--) | Geçerli tanıma oturumunun yürütme süresini alır |
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
| [setExecutionTime(int value)](#setExecutionTime-int-) | Geçerli tanıma oturumunun yürütme süresini ayarlar |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RecognitionAbortedException() {#RecognitionAbortedException--}
```
public RecognitionAbortedException()
```


Belirtilen tanıma iptal mesajı ile sınıfın yeni bir örneğini başlatır.

### RecognitionAbortedException(int executionTime) {#RecognitionAbortedException-int-}
```
public RecognitionAbortedException(int executionTime)
```


Belirtilen tanıma iptal mesajı ile sınıfın yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| executionTime | int | Geçerli tanıma oturumunun yürütme süresi. |

### RecognitionAbortedException(String message, int executionTime) {#RecognitionAbortedException-java.lang.String-int-}
```
public RecognitionAbortedException(String message, int executionTime)
```


Belirtilen tanıma iptal mesajı ile sınıfın yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İstisnanın hata mesajı. |
| executionTime | int | Geçerli tanıma oturumunun yürütme süresi. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

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


Geçerli tanıma oturumunun yürütme süresini alır

**Returns:**
int - Geçerli tanıma oturumunun yürütme süresi
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setExecutionTime(int value) {#setExecutionTime-int-}
```
public void setExecutionTime(int value)
```


Geçerli tanıma oturumunun yürütme süresini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Geçerli tanıma oturumunun yürütme süresi |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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

