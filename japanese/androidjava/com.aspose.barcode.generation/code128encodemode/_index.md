---
title: Code128EncodeMode
second_title: Aspose.BarCode for Android via Java API Reference
description: Code128 バーコードのエンコーディングモード。
type: docs
weight: 80
url: /ja/androidjava/com.aspose.barcode.generation/code128encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Code128EncodeMode extends Enum<Code128EncodeMode>
```

Code128 バーコードのエンコーディングモードです。  Code 128 の仕様。

--------------------

> ```
> Following code demonstrates how to generate code 128 with different encodings
>  
> 
>  //Generate code 128 with ISO 15417 encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO);
>  generator.save(filePath, BarCodeImageFormat.PNG);
> 
>  //Generate code 128 only with Codeset A encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A);
>  generator.save(filePath, BarCodeImageFormat.PNG);
> ```
## フィールド

| フィールド | Description |
| --- | --- |
| [AUTO](#AUTO) | コードテキストを従来の ISO 15417 モードでエンコードします。 |
| [CODE_A](#CODE-A) | コードテキストを 128A コードセットのみでエンコードします。 |
| [CODE_AB](#CODE-AB) | コードテキストを 128A と 128B のコードセットのみでエンコードします。 |
| [CODE_AC](#CODE-AC) | コードテキストを 128A と 128C のコードセットのみでエンコードします。 |
| [CODE_B](#CODE-B) | コードテキストを 128B コードセットのみでエンコードします。 |
| [CODE_BC](#CODE-BC) | コードテキストを 128B と 128C のコードセットのみでエンコードします。 |
| [CODE_C](#CODE-C) | コードテキストを 128C コードセットのみでエンコードします。 |
## Methods

| Method | Description |
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
| [valueOf(int value)](#valueOf-int-) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final Code128EncodeMode AUTO
```


コードテキストを従来の ISO 15417 モードでエンコードします。このモードはすべての通常の場合に使用すべきです。

### CODE_A {#CODE-A}
```
public static final Code128EncodeMode CODE_A
```


コードテキストを 128A コードセットのみでエンコードします。

### CODE_AB {#CODE-AB}
```
public static final Code128EncodeMode CODE_AB
```


コードテキストを 128A と 128B のコードセットのみでエンコードします。

### CODE_AC {#CODE-AC}
```
public static final Code128EncodeMode CODE_AC
```


コードテキストを 128A と 128C のコードセットのみでエンコードします。

### CODE_B {#CODE-B}
```
public static final Code128EncodeMode CODE_B
```


コードテキストを 128B コードセットのみでエンコードします。

### CODE_BC {#CODE-BC}
```
public static final Code128EncodeMode CODE_BC
```


コードテキストを 128B と 128C のコードセットのみでエンコードします。

### CODE_C {#CODE-C}
```
public static final Code128EncodeMode CODE_C
```


コードテキストを 128C コードセットのみでエンコードします。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
### valueOf(int value) {#valueOf-int-}
```
public static Code128EncodeMode valueOf(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Code128EncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### values() {#values--}
```
public static Code128EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Code128EncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

