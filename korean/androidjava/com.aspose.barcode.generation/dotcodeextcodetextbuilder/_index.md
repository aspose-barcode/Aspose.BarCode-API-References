---
title: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: 
type: docs
weight: 34
url: /ko/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

DotCodeEncodeMode의 ExtendedCodetext 모드용 2D DotCode 바코드에 대한 확장 코드텍스트 생성기

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier와 함께 codetext를 추가합니다. |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | 확장 코드텍스트 항목에 FNC1 형식 식별자를 추가합니다. |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | 확장 코드텍스트 항목에 FNC3 리더 초기화를 추가합니다. |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | 확장 코드텍스트 항목에 FNC3 심볼 구분자를 추가합니다. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | 확장 codetext 항목에 일반 codetext를 추가합니다. |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | 확장 코드텍스트 항목에 구조적 추가 모드를 추가합니다. |
| [clear()](#clear--) | 확장 codetext 항목을 삭제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 확장 codetext 목록에서 Extended codetext를 생성합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Extended Channel Identifier와 함께 codetext를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Extended Channel Identifier와 함께 확장 codetext 항목으로 추가할 유니코드 codetext |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


확장 코드텍스트 항목에 FNC1 형식 식별자를 추가합니다.

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


확장 코드텍스트 항목에 FNC3 리더 초기화를 추가합니다.

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


확장 코드텍스트 항목에 FNC3 심볼 구분자를 추가합니다.

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


확장 codetext 항목에 일반 codetext를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| codetext | java.lang.String | 확장 codetext 항목으로 추가할 유니코드 codetext |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


확장 코드텍스트 항목에 구조적 추가 모드를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| barcodeId | int | 바코드 ID |
| barcodesCount | int | 바코드 수 |

### clear() {#clear--}
```
public void clear()
```


확장 codetext 항목을 삭제합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


확장 codetext 목록에서 Extended codetext를 생성합니다.

**Returns:**
java.lang.String - 문자열 형태의 Extended codetext
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
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

