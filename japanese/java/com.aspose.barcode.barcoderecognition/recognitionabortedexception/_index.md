---
title: "RecognitionAbortedException"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "BarCodeReader での認識中にタイムアウトが超過した際にスローされる、認識中止例外を表します"
type: docs
weight: 42
url: /ja/java/com.aspose.barcode.barcoderecognition/recognitionabortedexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, [com.aspose.barcode.barcoderecognition.BarCodeRecognitionException](../../com.aspose.barcode.barcoderecognition/barcoderecognitionexception)

**All Implemented Interfaces:**
java.io.Serializable
```
public class RecognitionAbortedException extends BarCodeRecognitionException implements Serializable
```

BarCodeReader での認識中にタイムアウトが超過した際にスローされる、認識中止例外を表します
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RecognitionAbortedException()](#RecognitionAbortedException--) | 指定された認識中止メッセージでクラスの新しいインスタンスを初期化します。 |
| [RecognitionAbortedException(int executionTime)](#RecognitionAbortedException-int-) | 指定された認識中止メッセージでクラスの新しいインスタンスを初期化します。 |
| [RecognitionAbortedException(String message, int executionTime)](#RecognitionAbortedException-java.lang.String-int-) | 指定された認識中止メッセージでクラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getExecutionTime()](#getExecutionTime--) | 現在の認識セッションの実行時間を取得します |
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
| [setExecutionTime(int value)](#setExecutionTime-int-) | 現在の認識セッションの実行時間を設定します |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RecognitionAbortedException() {#RecognitionAbortedException--}
```
public RecognitionAbortedException()
```


指定された認識中止メッセージでクラスの新しいインスタンスを初期化します。

### RecognitionAbortedException(int executionTime) {#RecognitionAbortedException-int-}
```
public RecognitionAbortedException(int executionTime)
```


指定された認識中止メッセージでクラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| executionTime | int | 現在の認識セッションの実行時間です。 |

### RecognitionAbortedException(String message, int executionTime) {#RecognitionAbortedException-java.lang.String-int-}
```
public RecognitionAbortedException(String message, int executionTime)
```


指定された認識中止メッセージでクラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | 例外のエラーメッセージです。 |
| executionTime | int | 現在の認識セッションの実行時間です。 |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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


現在の認識セッションの実行時間を取得します

**Returns:**
int - 現在の認識セッションの実行時間
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
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setExecutionTime(int value) {#setExecutionTime-int-}
```
public void setExecutionTime(int value)
```


現在の認識セッションの実行時間を設定します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 現在の認識セッションの実行時間 |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

