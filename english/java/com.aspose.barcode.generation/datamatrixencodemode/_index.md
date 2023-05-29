---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode for Java API Reference
description: DataMatrix encoders encoding mode default to AUTO
type: docs
weight: 68
url: /java/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

DataMatrix encoder's encoding mode, default to AUTO

This sample shows how to do codetext in Extended Mode: com.aspose.barcode.generation.BarcodeGenerator generator = new com.aspose.barcode.generation.BarcodeGenerator(EncodeTypes.DATA\_MATRIX); generator.setCodeText("\\\\ansix12:ANSIX12TEXT\\\\ascii:backslash must be \\\\\\\\ doubled\\\\edifact:EdifactEncodedText"); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED\_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.png");
## Fields

| Field | Description |
| --- | --- |
| [ANSIX12](#ANSIX12) | Uses ANSI X12 encoding. |
| [ASCII](#ASCII) | Encodes one alphanumeric or two numeric characters per byte |
| [AUTO](#AUTO) | Automatically pick up the best encode mode for datamatrix encoding |
| [C40](#C40) | Uses C40 encoding. |
| [CUSTOM](#CUSTOM) | Encode with the encoding specified in BarCodeBuilder.CodeTextEncoding |
| [EDIFACT](#EDIFACT) | Uses EDIFACT encoding. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) | ```
ExtendedCodetext mode allows to manually switch encodation schemes in codetext.
``` |
| [FULL](#FULL) | Encode 8 bit values |
| [TEXT](#TEXT) | UUses TEXT encoding. |
## Methods

| Method | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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


Automatically pick up the best encode mode for datamatrix encoding

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters

### CUSTOM {#CUSTOM}
```
public static final DataMatrixEncodeMode CUSTOM
```


Encode with the encoding specified in BarCodeBuilder.CodeTextEncoding

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


```
ExtendedCodetext mode allows to manually switch encodation schemes in codetext.
 Format : "\Encodation_scheme_name:text\Encodation_scheme_name:text".
 Allowed encodation schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
 Extended codetext example: "\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText"
All backslashes (\) must be doubled in text.
```

### FULL {#FULL}
```
public static final DataMatrixEncodeMode FULL
```


Encode 8 bit values

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


UUses TEXT encoding. Encodes Lower-case alphanumeric, Upper case and special characters

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
public final native void wait(long arg0)
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

