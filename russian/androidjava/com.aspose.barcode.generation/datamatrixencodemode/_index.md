---
title: DataMatrixEncodeMode
second_title: Справочник API Aspose.BarCode для Android через Java
description: Режим кодирования кодировщиков DataMatrix по умолчанию Auto.
type: docs
weight: 83
url: /ru/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

Режим кодирования кодировщика DataMatrix, по умолчанию Auto

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Поля

| Поле | Описание |
| --- | --- |
| [ANSIX12](#ANSIX12) | Использует кодировку ANSI X12. |
| [ASCII](#ASCII) | Кодирует один буквенно-цифровой или два числовых символа на байт. |
| [AUTO](#AUTO) | В режиме Auto текст кода (CodeText) кодируется с максимальной плотностью данных. |
| [BASE_256](#BASE-256) | Кодировать 8‑битные значения. |
| [BINARY](#BINARY) | В режиме Binary текст кода (CodeText) кодируется с максимальной плотностью данных. |
| [BYTES](#BYTES) | Кодировать 8‑битные значения. |
| [C40](#C40) | Использует кодировку C40. |
| [ECI](#ECI) | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. |
| [EDIFACT](#EDIFACT) | Использует кодировку EDIFACT. |
| [EXTENDED](#EXTENDED) | Режим ExtendedCodetext позволяет вручную переключать схемы кодирования и кодировки ECI в кодтексте. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Использует кодировку Text. |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


Использует кодировку ANSI X12.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Кодирует один буквенно-цифровой или два числовых символа на байт.

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


В режиме Auto кодтекст кодируется с максимальной компактностью данных. Символы Unicode перекодируются в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Кодировать 8‑битные значения.

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


В режиме Binary кодтекст кодируется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение.

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


Кодировать 8‑битные значения.

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Использует кодировку C40. Кодирует заглавные буквенно-цифровые символы, строчные и специальные символы.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые (до 2006 года) сканеры могут не поддерживать этот режим.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Использует кодировку EDIFACT. Использует шесть бит на символ, кодирует цифры, заглавные буквы и многие знаки пунктуации, но не поддерживает строчные буквы.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


Режим ExtendedCodetext позволяет вручную переключать схемы кодирования и кодировки ECI в кодтексте. Лучше использовать DataMatrixExtCodetextBuilder для генерации расширенного кодтекста. Используйте свойство Display2DText, чтобы установить видимый текст, удаляя управляющие символы. Идентификаторы ECI задаются как один слеш и шестизначный идентификатор "\\000026" — UTF8‑идентификатор ECI. Все символы Unicode после идентификатора ECI автоматически кодируются в правильный набор символов. Схемы кодирования задаются в следующем формате: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Допустимые схемы кодирования: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Все обратные слеши (\\) должны быть удвоены в тексте.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


Режим ExtendedCodetext позволяет вручную переключать схемы кодирования и кодировки ECI в кодтексте.

Лучше использовать DataMatrixExtCodetextBuilder для генерации расширенного кодтекста.

Используйте свойство Display2DText, чтобы установить видимый текст, удаляя управляющие символы.

Идентификаторы ECI задаются как один слеш и шестизначный идентификатор "\\000026" — UTF8‑идентификатор ECI.

Все символы Unicode после идентификатора ECI автоматически кодируются в правильный набор символов.

Схемы кодирования задаются в следующем формате: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text".

Допустимые схемы кодирования: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.

Все обратные слеши (\\) должны быть удвоены в тексте.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Использует кодировку Text. Кодирует строчные буквенно-цифровые символы, заглавные и специальные символы.

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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

