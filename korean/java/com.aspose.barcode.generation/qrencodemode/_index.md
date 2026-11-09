---
title: "QREncodeMode"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "QR 바코드의 인코딩 모드."
type: docs
weight: 100
url: /ko/java/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

QR 바코드의 인코딩 모드. 이 샘플은 확장 데이터 형식으로 QR 바코드를 인코딩하고 저장하는 방법을 보여줍니다.

```
{@code
 //This sample shows how to use ECI encoding and save a BarCode image.
 
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText("12345TEXT");
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
 generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
 generator.save("test.png");
 
 //This sample shows how to use FNC1 first position in Extended Mode.
 Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes.
 It is better to use QrExtCodetextBuilder for extended codetext generation.
 Use Display2DText property to set visible text by removing managing characters.
 Encoding Principles:
 All symbols "\" must be doubled "\\" in the codetext.
 FNC1 in first position is set in codetext as "<FNC1>".
 FNC1 in second position is set in codetext as "<FNC1(value)>". The value must be a single character from a-z or A-Z, or a two-digit number from 00 to 99.
 Group Separator for FNC1 modes is set as 0x1D character ''.
 If you need to insert "<FNC1>" string into barcode write it as "<\FNC1>".
 ECI identifiers are set as single slash and six digits identifier, for example "\000026" for UTF8 ECI identifier.
 The default ECI mode is ISO/IEC 8859-1 ECI identifier "\000003". It does not need to be encoded at the beginning of the codetext.
 To switch from another ECI mode to the default ECI mode, use "\000003".
 All unicode characters after ECI identifier are automatically encoded into correct character codeset.
 QR compaction mode selectors are set as single slash and mode name: "\auto", "\num", "\alnum", "\byte", "\kanji".
 "\auto" sets automatic compaction mode, "\num" sets Numeric mode, "\alnum" sets AlphaNumeric mode, "\byte" sets Bytes mode, and "\kanji" sets Kanji mode.
 The default compaction mode is "\auto".
 Compaction mode selectors define the encoding mode for the following data until the next compaction mode selector or ECI identifier is found.
 If the data cannot be encoded in the selected compaction mode, an ArgumentException is thrown.
 This mode is not supported by MicroQR barcodes.
 
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");
 
 //This sample shows how to use FNC1 second position in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");
 
 //This sample shows how to use multi ECI mode in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
 textBuilder.addPlainCodetext"t\e\\st");
 textBuilder.addAlphaNumericCodetext("ASPOSE2001");
 textBuilder.addNumericCodetext(@"20012026");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.getExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text";
 generator.save("test.png");
```
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | 자동 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. |
| [BINARY](#BINARY) | 바이너리 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. |
| [ECI](#ECI) | ECI 모드에서는 전체 메시지가 ECIEncoding에서 지정한 인코딩으로 다시 인코딩되며 ECI 식별자가 삽입됩니다. |
| [EXTENDED](#EXTENDED) | FNC1 첫 번째 위치, FNC1 두 번째 위치 및 다중 ECI 모드를 지원하는 확장 채널 모드. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
### AUTO {#AUTO}
```
public static final QREncodeMode AUTO
```


Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 가능한 경우 kanji 모드로 인코딩되며, 그렇지 않으면 ECIEncoding에서 지정한 인코딩으로 ECI 식별자를 삽입하여 다시 인코딩됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자를 발견하면 예외가 발생합니다.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


ECI 모드에서는 전체 메시지가 ECIEncoding에서 지정한 인코딩으로 ECI 식별자를 삽입하여 다시 인코딩됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자를 발견하면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있습니다. 이 모드는 MicroQR 바코드에서 지원되지 않습니다.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


FNC1 첫 번째 위치, FNC1 두 번째 위치 및 다중 ECI 모드를 지원하는 확장 채널 모드입니다. 확장 코덱스트 생성에는 QrExtCodetextBuilder를 사용하는 것이 좋습니다. 관리 문자를 제거하여 표시 텍스트를 설정하려면 Display2DText 속성을 사용하십시오. 인코딩 원칙: 모든 기호 "\\\\"는 코덱스트에서 "\\\\\\\\"로 두 배로 해야 합니다. 첫 번째 위치의 FNC1은 코덱스트에서 "<FNC1>"로 설정됩니다. 두 번째 위치의 FNC1은 코덱스트에서 "<FNC1(value)>"로 설정됩니다. 값은 a‑z 또는 A‑Z의 단일 문자이거나 00부터 99까지의 두 자리 숫자여야 합니다. FNC1 모드의 그룹 구분자는 0x1D 문자 '\\u001d'로 설정됩니다. 바코드에 "<FNC1>" 문자열을 삽입해야 하면 "<\\\\FNC1>"로 작성하십시오. ECI 식별자는 단일 슬래시와 6자리 식별자로 설정되며, 예를 들어 UTF8 ECI 식별자는 "\\\\000026"입니다. 기본 ECI 모드는 ISO/IEC 8859-1 ECI 식별자 "\\\\000003"이며, 코덱스트 시작 부분에 인코딩할 필요가 없습니다. 다른 ECI 모드에서 기본 ECI 모드로 전환하려면 "\\\\000003"을 사용하십시오. ECI 식별자 뒤의 모든 유니코드 문자는 자동으로 올바른 문자 집합으로 인코딩됩니다. QR 압축 모드 선택자는 단일 슬래시와 모드 이름으로 설정됩니다: "\\\\auto", "\\\\num", "\\\\alnum", "\\\\byte", "\\\\kanji". "\\\\auto"는 자동 압축 모드를, "\\\\num"은 숫자 모드를, "\\\\alnum"은 알파벳-숫자 모드를, "\\\\byte"는 바이트 모드를, "\\\\kanji"는 한자 모드를 설정합니다. 기본 압축 모드는 "\\\\auto"입니다. 압축 모드 선택자는 다음 압축 모드 선택자나 ECI 식별자가 나타날 때까지 이후 데이터의 인코딩 모드를 정의합니다. 데이터가 선택된 압축 모드에서 인코딩될 수 없으면 ArgumentException이 발생합니다. 이 모드는 MicroQR 바코드에서 지원되지 않습니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QREncodeMode fromValue(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
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
public static QREncodeMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### values() {#values--}
```
public static QREncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.QREncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

