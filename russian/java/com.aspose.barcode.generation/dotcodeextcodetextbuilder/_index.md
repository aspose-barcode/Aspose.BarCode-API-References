---
title: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Reference"
description: 
type: docs
weight: 33
url: /ru/java/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Генератор расширенного кодтекста для 2D штрих‑кодов DotCode в режиме ExtendedCodetext режима DotCodeEncodeMode.

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Добавляет codetext с Extended Channel Identifier. |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Добавляет идентификатор формата FNC1 к элементам расширенного кодтекста. |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Добавляет инициализацию считывателя FNC3 к элементам расширенного кодтекста. |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Добавляет разделитель символов FNC3 к элементам расширенного кодтекста. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Добавляет простой codetext к элементам расширенного codetext. |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Добавляет режим структурированного добавления к элементам расширенного кодтекста. |
| [clear()](#clear--) | Очищает элементы расширенного codetext. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Генерирует Extended codetext из списка расширенного codetext. |
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


Добавляет codetext с Extended Channel Identifier.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Codetext в Unicode для добавления как элемент расширенного codetext с Extended Channel Identifier. |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


Добавляет идентификатор формата FNC1 к элементам расширенного кодтекста.

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


Добавляет инициализацию считывателя FNC3 к элементам расширенного кодтекста.

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


Добавляет разделитель символов FNC3 к элементам расширенного кодтекста.

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Добавляет простой codetext к элементам расширенного codetext.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| codetext | java.lang.String | Codetext в Unicode для добавления в качестве расширенного элемента Codetext |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Добавляет режим структурированного добавления к элементам расширенного кодтекста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| barcodeId | int | Идентификатор штрих‑кода |
| barcodesCount | int | Количество штрих‑кодов |

### clear() {#clear--}
```
public void clear()
```


Очищает элементы расширенного codetext.

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


Генерирует Extended codetext из списка расширенного codetext.

**Returns:**
java.lang.String - Расширенный Codetext в виде строки
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

