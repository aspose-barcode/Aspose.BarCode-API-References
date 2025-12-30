---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode for Android via Java API Reference
description: DataMatrix encoders encoding mode default to Auto
type: docs
weight: 83
url: /androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

DataMatrix encoder's encoding mode, default to Auto

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
>  generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,DataMatrixEncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Fields

| Field | Description |
| --- | --- |
| [ANSIX12](#ANSIX12) | Uses ANSI X12 encoding. |
| [ASCII](#ASCII) | Encodes one alphanumeric or two numeric characters per byte |
| [AUTO](#AUTO) | In Auto mode, the CodeText is encoded with maximum data compactness. |
| [BASE_256](#BASE-256) | Encode 8 bit values |
| [BINARY](#BINARY) | In Binary mode, the CodeText is encoded with maximum data compactness. |
| [BYTES](#BYTES) | Encode 8 bit values |
| [C40](#C40) | Uses C40 encoding. |
| [ECI](#ECI) | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. |
| [EDIFACT](#EDIFACT) | Uses EDIFACT encoding. |
| [EXTENDED](#EXTENDED) | ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Uses Text encoding. |
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
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


Uses ANSI X12 encoding.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Encodes one alphanumeric or two numeric characters per byte

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Encode 8 bit values

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown.

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


Encode 8 bit values

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext. It is better to use DataMatrixExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. Encodation schemes are set in the next format : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Allowed encodation schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. All backslashes (\\) must be doubled in text.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext.

It is better to use DataMatrixExtCodetextBuilder for extended codetext generation.

Use Display2DText property to set visible text to removing managing characters.

ECI identifiers are set as single slash and six digits identifier "\\000026" - UTF8 ECI identifier

All unicode characters after ECI identifier are automatically encoded into correct character codeset.

Encodation schemes are set in the next format : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text".

Allowed encodation schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.

All backslashes (\\) must be doubled in text.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters

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
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
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

