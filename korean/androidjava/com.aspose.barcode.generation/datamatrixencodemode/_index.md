---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode for Android via Java API Reference
description: DataMatrix 인코더의 인코딩 모드는 기본적으로 Auto입니다.
type: docs
weight: 83
url: /ko/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

DataMatrix 인코더의 인코딩 모드이며, 기본값은 자동입니다.

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
## 필드

| 필드 | 설명 |
| --- | --- |
| [ANSIX12](#ANSIX12) | ANSI X12 인코딩을 사용합니다. |
| [ASCII](#ASCII) | 바이트당 하나의 영문자(알파벳) 또는 두 개의 숫자 문자를 인코딩합니다. |
| [AUTO](#AUTO) | Auto 모드에서는 CodeText가 최대 데이터 압축도로 인코딩됩니다. |
| [BASE_256](#BASE-256) | 8비트 값을 인코딩합니다. |
| [BINARY](#BINARY) | Binary 모드에서는 CodeText가 최대 데이터 압축도로 인코딩됩니다. |
| [BYTES](#BYTES) | 8비트 값을 인코딩합니다. |
| [C40](#C40) | C40 인코딩을 사용합니다. |
| [ECI](#ECI) | ECI 모드에서는 전체 메시지가 ECIEncoding에서 지정한 인코딩으로 다시 인코딩되며, ECI 식별자가 삽입됩니다. |
| [EDIFACT](#EDIFACT) | EDIFACT 인코딩을 사용합니다. |
| [EXTENDED](#EXTENDED) | ExtendedCodetext 모드를 사용하면 코드텍스트에서 인코딩 스킴과 ECI 인코딩을 수동으로 전환할 수 있습니다. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Text 인코딩을 사용합니다. |
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
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


ANSI X12 인코딩을 사용합니다.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


바이트당 하나의 영문자(알파벳) 또는 두 개의 숫자 문자를 인코딩합니다.

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 ECIEncoding에서 지정한 인코딩으로 다시 인코딩되며, ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


8비트 값을 인코딩합니다.

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다.

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


8비트 값을 인코딩합니다.

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


C40 인코딩을 사용합니다. 대문자 알파벳·숫자, 소문자 및 특수 문자를 인코딩합니다.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


ECI 모드에서는 전체 메시지가 ECIEncoding에서 지정한 인코딩으로 다시 인코딩되며, ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있음을 유의하십시오.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


EDIFACT 인코딩을 사용합니다. 문자당 6비트를 사용하여 숫자, 대문자 및 다양한 구두점을 인코딩하지만 소문자는 지원하지 않습니다.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


ExtendedCodetext 모드를 사용하면 코드텍스트에서 인코딩 스킴과 ECI 인코딩을 수동으로 전환할 수 있습니다. 확장 코드텍스트 생성을 위해 DataMatrixExtCodetextBuilder를 사용하는 것이 좋습니다. 표시 텍스트를 설정하려면 Display2DText 속성을 사용하여 관리 문자를 제거합니다. ECI 식별자는 단일 슬래시와 6자리 식별자 "\\000026" - UTF8 ECI 식별자로 설정됩니다. ECI 식별자 이후의 모든 유니코드 문자는 자동으로 올바른 문자 코드셋으로 인코딩됩니다. 인코딩 스킴은 다음 형식으로 설정됩니다: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". 허용되는 인코딩 스킴은: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. 모든 역슬래시(\\)는 텍스트에서 두 번 사용해야 합니다.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


ExtendedCodetext 모드를 사용하면 코드텍스트에서 인코딩 스킴과 ECI 인코딩을 수동으로 전환할 수 있습니다.

확장 코드텍스트 생성을 위해 DataMatrixExtCodetextBuilder를 사용하는 것이 좋습니다.

표시 텍스트를 설정하려면 Display2DText 속성을 사용하여 관리 문자를 제거합니다.

ECI 식별자는 단일 슬래시와 6자리 식별자 "\\000026" - UTF8 ECI 식별자로 설정됩니다.

ECI 식별자 이후의 모든 유니코드 문자는 자동으로 올바른 문자 코드셋으로 인코딩됩니다.

인코딩 스킴은 다음 형식으로 설정됩니다: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text".

허용되는 인코딩 스킴은: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.

텍스트에서 모든 역슬래시(\\)는 두 번 사용해야 합니다.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Text 인코딩을 사용합니다. 소문자 알파벳·숫자, 대문자 및 특수 문자를 인코딩합니다.

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
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 설명 |
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

