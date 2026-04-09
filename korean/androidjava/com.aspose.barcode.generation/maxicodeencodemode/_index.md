---
title: MaxiCodeEncodeMode
second_title: Aspose.BarCode for Android via Java API Reference
description: MaxiCode 바코드용 인코딩 모드.
type: docs
weight: 95
url: /ko/androidjava/com.aspose.barcode.generation/maxicodeencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeEncodeMode extends Enum<MaxiCodeEncodeMode>
```

MaxiCode 바코드용 인코딩 모드.

```
//Auto mode
 String codetext = "\u72acRight\u72d7";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 {
     generator.getParameters().getBarcode().getMaxiCode().setECIEncoding(ECIEncodings.UTF8);
     generator.save("test.bmp");
 }

 //Bytes mode
 byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE);
 generator.setCodetext(encodedArr);
 generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.BINARY);
 generator.save("test.bmp");

 //Extended codetext mode
 //create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 // generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext);
 generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | Auto 모드에서는 CodeText가 최대 데이터 압축도로 인코딩됩니다. |
| [BINARY](#BINARY) | Binary 모드에서는 CodeText가 최대 데이터 압축도로 인코딩됩니다. |
| [BYTES](#BYTES) | 코드텍스트를 일반 바이트로 인코딩합니다. |
| [ECI](#ECI) | ECI 모드에서는 전체 메시지가 ECIEncoding에서 지정한 인코딩으로 다시 인코딩되며, ECI 식별자가 삽입됩니다. |
| [EXTENDED](#EXTENDED) |  |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
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
### AUTO {#AUTO}
```
public static final MaxiCodeEncodeMode AUTO
```


Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 ECIEncoding에서 지정한 인코딩으로 다시 인코딩되며, ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다.

### BINARY {#BINARY}
```
public static final MaxiCodeEncodeMode BINARY
```


Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다.

### BYTES {#BYTES}
```
public static final MaxiCodeEncodeMode BYTES
```


코드텍스트를 일반 바이트로 인코딩합니다. Unicode 문자를 감지하면 해당 문자는 두 바이트로 인코딩되며, 낮은 바이트가 먼저 기록됩니다.

### ECI {#ECI}
```
public static final MaxiCodeEncodeMode ECI
```


ECI 모드에서는 전체 메시지가 ECIEncoding에서 지정한 인코딩으로 다시 인코딩되며, ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있음을 유의하십시오.

### EXTENDED {#EXTENDED}
```
public static final MaxiCodeEncodeMode EXTENDED
```


다중 ECI 모드를 지원하는 확장 모드입니다.

확장 코드텍스트 생성을 위해 MaxiCodeExtCodetextBuilder를 사용하는 것이 좋습니다.

표시 텍스트를 설정하려면 Display2DText 속성을 사용하여 관리 문자를 제거합니다.

ECI 식별자는 단일 슬래시와 6자리 식별자 "\\000026" - UTF8 ECI 식별자로 설정됩니다.

ECI 식별자 이후의 모든 유니코드 문자는 자동으로 올바른 문자 코드셋으로 인코딩됩니다.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final MaxiCodeEncodeMode EXTENDED_CODETEXT
```


다중 ECI 모드를 지원하는 확장 모드입니다.

확장 코드텍스트 생성을 위해 MaxiCodeExtCodetextBuilder를 사용하는 것이 좋습니다.

표시 텍스트를 설정하려면 Display2DText 속성을 사용하여 관리 문자를 제거합니다.

ECI 식별자는 단일 슬래시와 6자리 식별자 "\\000026" - UTF8 ECI 식별자로 설정됩니다.

ECI 식별자 이후의 모든 유니코드 문자는 자동으로 올바른 문자 코드셋으로 인코딩됩니다.

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
public static MaxiCodeEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode)
### values() {#values--}
```
public static MaxiCodeEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeEncodeMode[]
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

