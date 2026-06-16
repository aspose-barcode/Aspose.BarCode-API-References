---
title: AztecEncodeMode
second_title: Справочник API Aspose.BarCode для Android через Java
description: Режим кодирования для штрихкодов Aztec.
type: docs
weight: 73
url: /ru/androidjava/com.aspose.barcode.generation/aztecencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecEncodeMode extends Enum<AztecEncodeMode>
```

Режим кодирования для штрихкодов Aztec.

--------------------

> ```
> String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
>  generator.getParameters().getBarcode().getAztec().setECIEncoding(ECIEncodings.UTF_8);
>  generator.save("test.bmp");
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.BINARY);
>  generator.save("test.bmp");
> 
>  //Extended mode
>  //create codetext
>  AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
>  generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.EXTENDED);
>  generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>  generator.save("test.bmp");
> ```
## Поля

| Поле | Описание |
| --- | --- |
| [AUTO](#AUTO) | В режиме Auto текст кода (CodeText) кодируется с максимальной плотностью данных. |
| [BINARY](#BINARY) | В режиме Binary текст кода (CodeText) кодируется с максимальной плотностью данных. |
| [BYTES](#BYTES) | Кодировать текст кода как обычные байты. |
| [ECI](#ECI) | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. |
| [EXTENDED](#EXTENDED) |  |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
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
public static final AztecEncodeMode AUTO
```


В режиме Auto кодтекст кодируется с максимальной компактностью данных. Символы Unicode перекодируются в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение.

### BINARY {#BINARY}
```
public static final AztecEncodeMode BINARY
```


В режиме Binary кодтекст кодируется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение.

### BYTES {#BYTES}
```
public static final AztecEncodeMode BYTES
```


Кодировать текст кода как обычные байты. Если обнаруживается любой символ Unicode, он будет закодирован в два байта, сначала младший байт.

### ECI {#ECI}
```
public static final AztecEncodeMode ECI
```


В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые (до 2006 года) сканеры могут не поддерживать этот режим.

### EXTENDED {#EXTENDED}
```
public static final AztecEncodeMode EXTENDED
```


Расширенный режим, поддерживающий несколько режимов ECI.

Лучше использовать AztecExtCodetextBuilder для генерации расширенного текста кода.

Используйте свойство Display2DText, чтобы установить видимый текст, удаляя управляющие символы.

Идентификаторы ECI задаются как один слеш и шестизначный идентификатор "\\000026" — UTF8‑идентификатор ECI.

Все символы Unicode после идентификатора ECI автоматически кодируются в правильный набор символов.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final AztecEncodeMode EXTENDED_CODETEXT
```


Расширенный режим, поддерживающий несколько режимов ECI.

Лучше использовать AztecExtCodetextBuilder для генерации расширенного текста кода.

Используйте свойство Display2DText, чтобы установить видимый текст, удаляя управляющие символы.

Идентификаторы ECI задаются как один слеш и шестизначный идентификатор "\\000026" — UTF8‑идентификатор ECI.

Все символы Unicode после идентификатора ECI автоматически кодируются в правильный набор символов.

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
public static AztecEncodeMode valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode
### values() {#values--}
```
public static AztecEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AztecEncodeMode[]
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

