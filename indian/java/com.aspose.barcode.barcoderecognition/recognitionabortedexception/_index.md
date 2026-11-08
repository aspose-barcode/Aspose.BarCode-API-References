---
title: "RecognitionAbortedException"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "BarCodeReader के साथ पहचान के दौरान टाइमआउट अधिक होने पर फेंकी जाने वाली पहचान समाप्ति अपवाद को दर्शाता है।"
type: docs
weight: 42
url: /hi/java/com.aspose.barcode.barcoderecognition/recognitionabortedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.aspose.barcode.barcoderecognition.BarCodeRecognitionException](../../com.aspose.barcode.barcoderecognition/barcoderecognitionexception)

**All Implemented Interfaces:**
java.io.Serializable
```
public class RecognitionAbortedException extends BarCodeRecognitionException implements Serializable
```

BarCodeReader के साथ पहचान के दौरान टाइमआउट अधिक होने पर फेंकी जाने वाली पहचान समाप्ति अपवाद को दर्शाता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [RecognitionAbortedException()](#RecognitionAbortedException--) | निर्दिष्ट मान्यता रद्द संदेश के साथ क्लास की नई इंस्टेंस को प्रारंभ करता है। |
| [RecognitionAbortedException(int executionTime)](#RecognitionAbortedException-int-) | निर्दिष्ट मान्यता रद्द संदेश के साथ क्लास की नई इंस्टेंस को प्रारंभ करता है। |
| [RecognitionAbortedException(String message, int executionTime)](#RecognitionAbortedException-java.lang.String-int-) | निर्दिष्ट मान्यता रद्द संदेश के साथ क्लास की नई इंस्टेंस को प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getExecutionTime()](#getExecutionTime--) | वर्तमान मान्यता सत्र का निष्पादन समय प्राप्त करता है |
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
| [setExecutionTime(int value)](#setExecutionTime-int-) | वर्तमान मान्यता सत्र का निष्पादन समय सेट करता है |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RecognitionAbortedException() {#RecognitionAbortedException--}
```
public RecognitionAbortedException()
```


निर्दिष्ट मान्यता रद्द संदेश के साथ क्लास की नई इंस्टेंस को प्रारंभ करता है।

### RecognitionAbortedException(int executionTime) {#RecognitionAbortedException-int-}
```
public RecognitionAbortedException(int executionTime)
```


निर्दिष्ट मान्यता रद्द संदेश के साथ क्लास की नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| executionTime | int | वर्तमान मान्यता सत्र का निष्पादन समय। |

### RecognitionAbortedException(String message, int executionTime) {#RecognitionAbortedException-java.lang.String-int-}
```
public RecognitionAbortedException(String message, int executionTime)
```


निर्दिष्ट मान्यता रद्द संदेश के साथ क्लास की नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | अपवाद का त्रुटि संदेश। |
| executionTime | int | वर्तमान मान्यता सत्र का निष्पादन समय। |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


वर्तमान मान्यता सत्र का निष्पादन समय प्राप्त करता है

**Returns:**
int - वर्तमान मान्यता सत्र का निष्पादन समय
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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setExecutionTime(int value) {#setExecutionTime-int-}
```
public void setExecutionTime(int value)
```


वर्तमान मान्यता सत्र का निष्पादन समय सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | वर्तमान मान्यता सत्र का निष्पादन समय |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

