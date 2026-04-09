---
title: HanXinEncodeMode
second_title: Справочник API Aspose.BarCode для Android через Java
description: Режим кодирования Han Xin Code.
type: docs
weight: 89
url: /ru/androidjava/com.aspose.barcode.generation/hanxinencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinEncodeMode extends Enum<HanXinEncodeMode>
```

Режим кодирования Han Xin Code. Рекомендуется использовать Auto с символами ASCII / китайскими или Unicode для символов Unicode.

--------------------

> ```
> // Auto mode
>   String codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.save("test.bmp");
> 
> 
>  // Binary mode
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN)
>  generator.setCodeText(encodedArr);
>  generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.BINARY);
>  generator.save("test.bmp");
> 
>   // ECI mode
>   String codetext = "\u0391\u0392\u0393\u0394\u0395";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.ECI);
>   generator.getParameters().getBarcode().getHanXin().setHanXinECIEncoding(ECIEncodings.ISO_8859_7);
>   generator.save("test.bmp");
> 
>   // URI mode
>   String codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.URI);
>   generator.save("test.bmp");
> 
> 
>   // Extended mode
>   String str = "\\gb180302b:\u6f04\\gb180304b:\u3401\\region1:\u5168\\region2:\u8785\\numeric:123\\text:qwe\\\\unicode:\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l" +
>       "\\000009:\u0391\u0392\u0393\u0394\u0395\\auto:abc\\binary:abc\\\\uri:backslashes_should_be_doubled\\\\000555:test";
> 
>   String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test";
> 
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HanXin, str);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>   generator.save("test.bmp");
> 
>   // Using HanXinExtCodetextBuilder for Extended mode (same codetext as in previous example)
>   //create codetext
>   HanXinExtCodetextBuilder codeTextBuilder = new HanXinExtCodetextBuilder();
>   codeTextBuilder.addGB18030TwoByte("\u6f04");
>   codeTextBuilder.addGB18030FourByte("\u3401");
>   codeTextBuilder.addCommonChineseRegionOne("\u5168");
>   codeTextBuilder.addCommonChineseRegionTwo("\u8785");
>   codeTextBuilder.addNumeric("123");
>   codeTextBuilder.addText("qwe");
>   codeTextBuilder.addUnicode("\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l");
>   codeTextBuilder.addECI("\u0391\u0392\u0393\u0394\u0395", 9);
>   codeTextBuilder.addAuto("abc");
>   codeTextBuilder.addBinary("abc");
>   codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test");
> 
>   String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test";
> 
>   //generate codetext
>   String str = codeTextBuilder.getExtendedCodetext();
> 
>   //generate
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HanXin, str);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>   generator.save("test.bmp");
> ```
## Поля

| Поле | Описание |
| --- | --- |
| [AUTO](#AUTO) | В режиме Auto текст кода (CodeText) кодируется с максимальной плотностью данных. |
| [BINARY](#BINARY) | В режиме Binary текст кода (CodeText) кодируется с максимальной плотностью данных. |
| [ECI](#ECI) | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. |
| [EXTENDED](#EXTENDED) | Расширенный режим позволяет комбинировать внутренние режимы: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. |
| [UNICODE](#UNICODE) | Режим Unicode разрабатывает способ представления любых текстовых данных, ссылающихся на кодировку/набор символов UTF8 в Han Xin Code. |
| [URI](#URI) | Режим URI указывает, что данные, представленные в Han Xin Code, являются ссылкой Uniform Resource Identifier (URI) согласно RFC 3986. |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final HanXinEncodeMode AUTO
```


В режиме Auto кодовый текст кодируется с максимальной компактностью данных. Символы Unicode кодируются с использованием кодировки GB18030 в соответствии со спецификацией штрих‑кода HanXin.

### BINARY {#BINARY}
```
public static final HanXinEncodeMode BINARY
```


В режиме Binary кодтекст кодируется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение.

### ECI {#ECI}
```
public static final HanXinEncodeMode ECI
```


В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые (до 2006 года) сканеры могут не поддерживать этот режим.

### EXTENDED {#EXTENDED}
```
public static final HanXinEncodeMode EXTENDED
```


Расширенный режим позволяет комбинировать внутренние режимы: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Кодовый текст можно создавать вручную с префиксами и удвоенными обратными слешами, например: @"\\auto:abc\\000009:\\u0391\\u0392\\u0393\\u0394\\u0395\\auto:ab\\\\c" или с помощью HanXinExtCodetextBuilder. Если кодовый текст содержит фрагмент ECI, то после фрагмента ECI в кодовом тексте могут использоваться только следующие режимы: Auto, Binary, Text, Numeric, URI, ECI.

### UNICODE {#UNICODE}
```
public static final HanXinEncodeMode UNICODE
```


Режим Unicode разрабатывает способ представления любых текстовых данных, ссылающихся на кодировку/набор символов UTF8 в Han Xin Code.

### URI {#URI}
```
public static final HanXinEncodeMode URI
```


Режим URI указывает, что данные, представленные в Han Xin Code, являются ссылкой Uniform Resource Identifier (URI) согласно RFC 3986.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static HanXinEncodeMode valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### values() {#values--}
```
public static HanXinEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinEncodeMode[]
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

