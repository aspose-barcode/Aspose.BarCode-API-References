---
title: BarCodeRecognitionException
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: BarCodeReader द्वारा फेंका गया सामान्य अपवाद, जो BarCodeException से विरासत में मिला है
type: docs
weight: 16
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/barcoderecognitionexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class BarCodeRecognitionException extends RuntimeException
```

BarCodeReader द्वारा उत्पन्न सामान्य अपवाद, BarCodeException से विरासत में मिला हुआ
## Constructors

| Constructor | विवरण |
| --- | --- |
| [BarCodeRecognitionException()](#BarCodeRecognitionException--) | BarCodeRecognitionException क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [BarCodeRecognitionException(String message)](#BarCodeRecognitionException-java.lang.String-) | BarCodeRecognitionException क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [BarCodeRecognitionException(String message, Exception innerException)](#BarCodeRecognitionException-java.lang.String-java.lang.Exception-) | निर्दिष्ट त्रुटि संदेश और वर्तमान अपवाद के साथ BarCodeRecognitionException क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## Methods

| Method | विवरण |
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


BarCodeRecognitionException क्लास का एक नया इंस्टेंस प्रारंभ करता है।

### BarCodeRecognitionException(String message) {#BarCodeRecognitionException-java.lang.String-}
```
public BarCodeRecognitionException(String message)
```


BarCodeRecognitionException क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| message | java.lang.String | त्रुटि संदेश |

### BarCodeRecognitionException(String message, Exception innerException) {#BarCodeRecognitionException-java.lang.String-java.lang.Exception-}
```
public BarCodeRecognitionException(String message, Exception innerException)
```


निर्दिष्ट त्रुटि संदेश और वर्तमान अपवाद के साथ BarCodeRecognitionException क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| message | java.lang.String | अपवाद का त्रुटि संदेश। |
| innerException | java.lang.Exception | वर्तमान अपवाद फेंका गया है। |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

