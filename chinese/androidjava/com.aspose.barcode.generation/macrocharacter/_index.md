---
title: MacroCharacter
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。
type: docs
weight: 94
url: /zh/androidjava/com.aspose.barcode.generation/macrocharacter/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MacroCharacter extends Enum<MacroCharacter>
```

宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。05 宏字符被转换为 "[)>\u001e05\u001d" 作为解码数据头部，"\u001e\u0004" 作为解码数据尾部。06 宏字符被转换为 "[)>\u001e06\u001d" 作为解码数据头部，"\u001e\u0004" 作为解码数据尾部。

```
hese samples show how to encode Macro Characters in MicroPdf417 and DataMatrix
 

 //to generate autoidentified GS1 message like this "(10)123ABC(10)123ABC" in ISO 15434 format you need:
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "10123ABC10123ABC");
 generator.getParameters().getBarcode().getDataMatrix().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS1DataMatrix);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println("BarCode CodeText: " + result.getCodeText());

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println(result.getCodeText());
```
## 字段

| 字段 | 描述 |
| --- | --- |
| [MACRO_05](#MACRO-05) | 05 宏字符被添加到条形码数据的首位。 |
| [MACRO_06](#MACRO-06) | 在条形码数据的首位添加了 06 宏字符。 |
| [NONE](#NONE) | 未在条形码数据中添加任何宏字符。 |
## Methods

| Method | 描述 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
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
### MACRO_05 {#MACRO-05}
```
public static final MacroCharacter MACRO_05
```


在条形码数据的首位添加了 05 宏字符。GS1 数据标识符 ISO 15434 字符被翻译为 "[)>05" 作为解码数据头部，"" 作为解码数据尾部。

### MACRO_06 {#MACRO-06}
```
public static final MacroCharacter MACRO_06
```


在条形码数据的首位添加了 06 宏字符。ASC MH10 数据标识符 ISO 15434 字符被翻译为 "[)>06" 作为解码数据头部，"" 作为解码数据尾部。

### NONE {#NONE}
```
public static final MacroCharacter NONE
```


未在条形码数据中添加任何宏字符。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static MacroCharacter fromValue(int value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
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
public static MacroCharacter valueOf(String name)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### values() {#values--}
```
public static MacroCharacter[] values()
```




**Returns:**
com.aspose.barcode.generation.MacroCharacter[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

