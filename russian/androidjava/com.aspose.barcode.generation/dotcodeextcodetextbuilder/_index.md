---
title: "DotCodeExtCodetextBuilder"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: 
type: docs
weight: 34
url: /ru/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Генератор расширенного кодового текста для двумерных штрих‑кодов DotCode в режиме ExtendedCodetext режима DotCodeEncodeMode

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
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Добавляет кодтекст с расширенным идентификатором канала |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Добавляет идентификатор формата FNC1 к элементам расширенного кодового текста |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Добавляет инициализацию считывателя FNC3 к элементам расширенного кодового текста |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Добавляет разделитель символов FNC3 к элементам расширенного кодового текста |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Добавляет обычный кодтекст в элементы расширенного кодтекста |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Добавляет режим структурированного добавления к элементам расширенного кодового текста |
| [clear()](#clear--) | Очищает элементы расширенного кодтекста |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Генерирует расширенный кодтекст из списка расширенного кодтекста. |
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


Добавляет кодтекст с расширенным идентификатором канала

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ECIEncoding | int | Расширенный идентификатор канала |
| кодтекст | java.lang.String | Кодтекст в Unicode, который добавляется как элемент расширенного кодтекста с расширенным идентификатором канала |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


Добавляет идентификатор формата FNC1 к элементам расширенного кодового текста

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


Добавляет инициализацию считывателя FNC3 к элементам расширенного кодового текста

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


Добавляет разделитель символов FNC3 к элементам расширенного кодового текста

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Добавляет обычный кодтекст в элементы расширенного кодтекста

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| кодтекст | java.lang.String | Кодтекст в Unicode, который добавляется как элемент расширенного кодтекста |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Добавляет режим структурированного добавления к элементам расширенного кодового текста

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| barcodeId | int | Идентификатор штрих‑кода |
| barcodesCount | int | Количество штрих‑кодов |

### clear() {#clear--}
```
public void clear()
```


Очищает элементы расширенного кодтекста

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


Генерирует расширенный кодтекст из списка расширенного кодтекста.

**Returns:**
java.lang.String — расширенный кодтекст в виде строки
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

