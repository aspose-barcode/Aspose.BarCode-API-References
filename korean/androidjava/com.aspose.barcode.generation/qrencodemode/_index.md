---
title: QREncodeMode
second_title: Aspose.BarCode for Android via Java API Reference
description: QR 바코드의 인코딩 모드.
type: docs
weight: 102
url: /ko/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

QR 바코드의 인코딩 모드.

--------------------

> ```
> Example how to use ECI encoding
>  
>      BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>      generator.setCodeText("12345TEXT");
>      generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
>      generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.png");
> ```

--------------------

> ```
> Example how to use FNC1 first position in Extended Mode
>   
>       QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>       textBuilder.addPlainCodetext("000%89%%0");
>       textBuilder.addFNC1GroupSeparator();
>       textBuilder.addPlainCodetext("12345<FNC1>");
>       //generate barcode
>       BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>       generator.setCodeText(textBuilder.getExtended());
>       generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>       generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>       generator.save("d:/test.png");
>  
>       *
>  This sample shows how to use FNC1 second position in Extended Mode.
>  
> 
>     //create codetext
>     QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>     textBuilder.addFNC1SecondPosition("12");
>     textBuilder.addPlainCodetext("TRUE3456");
>     //generate barcode
>     BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>     generator.setCodeText(textBuilder.getExtended());
>     generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>     generator.save("d:/test.png");
>     
> 
>     This sample shows how to use multi ECI mode in Extended Mode.
>     
> 
>    //create codetext
>    QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>    textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>    textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
>    textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
>    textBuilder.addPlainCodetext("t\e\\st");
>    //generate barcode
>    BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>    generator.setCodeText(textBuilder.getExtended());
>    generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>    generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>    generator.save("d:/test.png");
> ```
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | Auto 모드에서는 CodeText가 최대 데이터 압축도로 인코딩됩니다. |
| [BINARY](#BINARY) | Binary 모드에서는 CodeText가 최대 데이터 압축도로 인코딩됩니다. |
| [BYTES](#BYTES) | 코드텍스트를 일반 바이트로 인코딩합니다. |
| [ECI](#ECI) | ECI 모드에서는 전체 메시지가 ECIEncoding에서 지정한 인코딩으로 다시 인코딩되며, ECI 식별자가 삽입됩니다. |
| [ECI_ENCODING](#ECI-ENCODING) | Encode codetext with value set in the ECIEncoding property. |
| [EXTENDED](#EXTENDED) | Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. It is better to use QrExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. Encoding Principles: All symbols "\\" must be doubled "\\\\" in the codetext. FNC1 in first position is set in codetext as as "<FNC1>" FNC1 in second position is set in codetext as as "<FNC1(value)>". |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) | Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. It is better to use QrExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. Encoding Principles: All symbols "\\" must be doubled "\\\\" in the codetext. FNC1 in first position is set in codetext as as "<FNC1>" FNC1 in second position is set in codetext as as "<FNC1(value)>". |
| [UTF_16_BEBOM](#UTF-16-BEBOM) | Encode codetext with UTF8 encoding with first ByteOfMark character. |
| [UTF_8_BOM](#UTF-8-BOM) | Encode codetext with UTF8 encoding with first ByteOfMark character. |
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
public static final QREncodeMode AUTO
```


In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are encoded in kanji mode if possible, or they are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다.

### BYTES {#BYTES}
```
public static final QREncodeMode BYTES
```


코드텍스트를 일반 바이트로 인코딩합니다. Unicode 문자를 감지하면 해당 문자는 두 바이트로 인코딩되며, 낮은 바이트가 먼저 기록됩니다.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. This mode is not supported by MicroQR barcodes.

### ECI_ENCODING {#ECI-ENCODING}
```
public static final QREncodeMode ECI_ENCODING
```


Encode codetext with value set in the ECIEncoding property. It can be problems with some old (pre 2006) barcode scanners. This mode is not supported by MicroQR barcodes.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. It is better to use QrExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. Encoding Principles: All symbols "\\" must be doubled "\\\\" in the codetext. FNC1 in first position is set in codetext as as "<FNC1>" FNC1 in second position is set in codetext as as "<FNC1(value)>". The value must be single symbols (a-z, A-Z) or digits from 0 to 99. Group Separator for FNC1 modes is set as 0x1D character '\\\\u001D'  If you need to insert "<FNC1>" string into barcode write it as "<\\FNC1>"  ECI identifiers are set as single slash and six digits identifier "\\000026" - UTF8 ECI identifier To disable current ECI mode and convert to default JIS8 mode zero mode ECI indetifier is set. "\\000000" All unicode characters after ECI identifier are automatically encoded into correct character codeset. This mode is not supported by MicroQR barcodes.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final QREncodeMode EXTENDED_CODETEXT
```


Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. It is better to use QrExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. Encoding Principles: All symbols "\\" must be doubled "\\\\" in the codetext. FNC1 in first position is set in codetext as as "<FNC1>" FNC1 in second position is set in codetext as as "<FNC1(value)>". The value must be single symbols (a-z, A-Z) or digits from 0 to 99. Group Separator for FNC1 modes is set as 0x1D character '\\\\u001D'  If you need to insert "<FNC1>" string into barcode write it as "<\\FNC1>"  ECI identifiers are set as single slash and six digits identifier "\\000026" - UTF8 ECI identifier To disable current ECI mode and convert to default JIS8 mode zero mode ECI indetifier is set. "\\000000" All unicode characters after ECI identifier are automatically encoded into correct character codeset. This mode is not supported by MicroQR barcodes.

### UTF_16_BEBOM {#UTF-16-BEBOM}
```
public static final QREncodeMode UTF_16_BEBOM
```


Encode codetext with UTF8 encoding with first ByteOfMark character. It can be problems with some barcode scanners.

### UTF_8_BOM {#UTF-8-BOM}
```
public static final QREncodeMode UTF_8_BOM
```


Encode codetext with UTF8 encoding with first ByteOfMark character.

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
public static QREncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

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

