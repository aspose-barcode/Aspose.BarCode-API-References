---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Reference"
description: "Расширенный генератор codetext для штрихкодов MaxiCode в режиме ExtendedCodetext Mode (MaxiCodeEncodeMode). Используйте свойство TwoDDisplayText у BarcodeGenerator, чтобы задать видимый текст, удаляя управляющие символы."
type: docs
weight: 54
url: /ru/java/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Расширенный генератор кодового текста для штрихкодов MaxiCode в режиме ExtendedCodetext режима MaxiCodeEncodeMode. Используйте свойство TwoDDisplayText класса BarcodeGenerator, чтобы установить видимый текст, удаляя управляющие символы. Этот пример показывает, как использовать MaxiCodeExtCodetextBuilder в расширенном режиме.

```
//create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Добавляет codetext с Extended Channel Identifier. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Добавляет простой codetext к элементам расширенного codetext. |
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
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
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

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Добавляет простой codetext к элементам расширенного codetext.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| codetext | java.lang.String | Codetext в Unicode для добавления в качестве расширенного элемента Codetext |

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

