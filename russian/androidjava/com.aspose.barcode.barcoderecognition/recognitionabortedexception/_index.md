---
title: RecognitionAbortedException
second_title: Справочник API Aspose.BarCode для Android через Java
description: Представляет исключение прерывания распознавания, которое выбрасывается при превышении тайм‑аута во время распознавания с BarCodeReader.
type: docs
weight: 46
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/recognitionabortedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.aspose.barcode.barcoderecognition.BarCodeRecognitionException](../../com.aspose.barcode.barcoderecognition/barcoderecognitionexception)

**All Implemented Interfaces:**
java.io.Serializable
```
public class RecognitionAbortedException extends BarCodeRecognitionException implements Serializable
```

Представляет исключение прерывания распознавания, которое выбрасывается при превышении тайм‑аута во время распознавания с BarCodeReader.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RecognitionAbortedException()](#RecognitionAbortedException--) | Инициализирует новый экземпляр класса с указанным сообщением об отмене распознавания. |
| [RecognitionAbortedException(int executionTime)](#RecognitionAbortedException-int-) | Инициализирует новый экземпляр класса с указанным сообщением об отмене распознавания. |
| [RecognitionAbortedException(String message, int executionTime)](#RecognitionAbortedException-java.lang.String-int-) | Инициализирует новый экземпляр класса с указанным сообщением об отмене распознавания. |
## Методы

| Метод | Описание |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getExecutionTime()](#getExecutionTime--) | Получает время выполнения текущей сессии распознавания |
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
| [setExecutionTime(int value)](#setExecutionTime-int-) | Устанавливает время выполнения текущей сессии распознавания |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RecognitionAbortedException() {#RecognitionAbortedException--}
```
public RecognitionAbortedException()
```


Инициализирует новый экземпляр класса с указанным сообщением об отмене распознавания.

### RecognitionAbortedException(int executionTime) {#RecognitionAbortedException-int-}
```
public RecognitionAbortedException(int executionTime)
```


Инициализирует новый экземпляр класса с указанным сообщением об отмене распознавания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| executionTime | int | Время выполнения текущей сессии распознавания. |

### RecognitionAbortedException(String message, int executionTime) {#RecognitionAbortedException-java.lang.String-int-}
```
public RecognitionAbortedException(String message, int executionTime)
```


Инициализирует новый экземпляр класса с указанным сообщением об отмене распознавания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Сообщение об ошибке исключения. |
| executionTime | int | Время выполнения текущей сессии распознавания. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Получает время выполнения текущей сессии распознавания

**Returns:**
int - Время выполнения текущей сессии распознавания
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setExecutionTime(int value) {#setExecutionTime-int-}
```
public void setExecutionTime(int value)
```


Устанавливает время выполнения текущей сессии распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Время выполнения текущей сессии распознавания |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

