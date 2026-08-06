---
title: Code128EncodeMode
second_title: Aspose.BarCode for Android via Java API Reference
description: Code128 바코드의 인코딩 모드입니다.
type: docs
weight: 80
url: /ko/androidjava/com.aspose.barcode.generation/code128encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Code128EncodeMode extends Enum<Code128EncodeMode>
```

Code128 바코드의 인코딩 모드.  Code 128 사양.

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
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | 클래식 ISO 15417 모드로 코드 텍스트를 인코딩합니다. |
| [CODE_A](#CODE-A) | 코드 텍스트를 128A 코드셋에서만 인코딩합니다. |
| [CODE_AB](#CODE-AB) | 코드 텍스트를 128A 및 128B 코드셋에서만 인코딩합니다. |
| [CODE_AC](#CODE-AC) | 코드 텍스트를 128A 및 128C 코드셋에서만 인코딩합니다. |
| [CODE_B](#CODE-B) | 코드 텍스트를 128B 코드셋에서만 인코딩합니다. |
| [CODE_BC](#CODE-BC) | 코드 텍스트를 128B 및 128C 코드셋에서만 인코딩합니다. |
| [CODE_C](#CODE-C) | 코드 텍스트를 128C 코드셋에서만 인코딩합니다. |
## Methods

| Method | 설명 |
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


클래식 ISO 15417 모드로 코드 텍스트를 인코딩합니다. 이 모드는 모든 일반적인 경우에 사용해야 합니다.

### CODE_A {#CODE-A}
```
public static final Code128EncodeMode CODE_A
```


코드 텍스트를 128A 코드셋에서만 인코딩합니다.

### CODE_AB {#CODE-AB}
```
public static final Code128EncodeMode CODE_AB
```


코드 텍스트를 128A 및 128B 코드셋에서만 인코딩합니다.

### CODE_AC {#CODE-AC}
```
public static final Code128EncodeMode CODE_AC
```


코드 텍스트를 128A 및 128C 코드셋에서만 인코딩합니다.

### CODE_B {#CODE-B}
```
public static final Code128EncodeMode CODE_B
```


코드 텍스트를 128B 코드셋에서만 인코딩합니다.

### CODE_BC {#CODE-BC}
```
public static final Code128EncodeMode CODE_BC
```


코드 텍스트를 128B 및 128C 코드셋에서만 인코딩합니다.

### CODE_C {#CODE-C}
```
public static final Code128EncodeMode CODE_C
```


코드 텍스트를 128C 코드셋에서만 인코딩합니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Code128EncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

