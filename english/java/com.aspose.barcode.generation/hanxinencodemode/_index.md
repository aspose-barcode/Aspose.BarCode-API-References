---
title: HanXinEncodeMode
second_title: Aspose.BarCode for Java API Reference
description: Han Xin Code encoding mode.
type: docs
weight: 78
url: /java/com.aspose.barcode.generation/hanxinencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinEncodeMode extends Enum<HanXinEncodeMode>
```

Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode characters.

--------------------

> ```
> // Auto mode
>   String codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.save("test.bmp");
> 
>   // Bytes mode
>   byte[] encodedArr = new byte[] {(byte) 0xFF, (byte) 0xFE, (byte) 0xFD, (byte) 0xFC, (byte) 0xFB, (byte) 0xFA, (byte) 0xF9};
> 
>   //encode array to string
>   StringBuilder strBld = new StringBuilder();
>   for (byte bval : encodedArr)
>       strBld.append((char) bval);
>   String codetext = strBld.toString();
> 
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.BYTES);
>   generator.save("test.bmp");
> 
>   // ECI mode
>   String codetext = "\u0391\u0392\u0393\u0394\u0395";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.ECI);
>   generator.getParameters().getBarcode().getHanXin().setHanXinECIEncoding(ECIEncodings.ISO_8859_7);
>   generator.save("test.bmp");
> 
>   // URI mode
>   String codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.URI);
>   generator.save("test.bmp");
> 
>   // Extended mode - TBD
> ```
## Fields

| Field | Description |
| --- | --- |
| [AUTO](#AUTO) | Sequence of Numeric, Text, ECI, Binary Bytes and 4 GB18030 modes changing automatically. |
| [BINARY](#BINARY) | Binary byte mode encodes binary data in any form and encodes them in their binary byte. |
| [ECI](#ECI) | Extended Channel Interpretation (ECI) mode |
| [EXTENDED](#EXTENDED) | Extended mode will allow more flexible combinations of other modes, this mode is currently not implemented. |
| [UNICODE](#UNICODE) | Unicode mode designs a way to represent any text data reference to UTF8 encoding/charset in Han Xin Code. |
| [URI](#URI) | URI mode indicates the data represented in Han Xin Code is Uniform Resource Identifier (URI) reference to RFC 3986. |
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
### AUTO {#AUTO}
```
public static final HanXinEncodeMode AUTO
```


Sequence of Numeric, Text, ECI, Binary Bytes and 4 GB18030 modes changing automatically.

### BINARY {#BINARY}
```
public static final HanXinEncodeMode BINARY
```


Binary byte mode encodes binary data in any form and encodes them in their binary byte. Every byte in Binary Byte mode is represented by 8 bits.

### ECI {#ECI}
```
public static final HanXinEncodeMode ECI
```


Extended Channel Interpretation (ECI) mode

### EXTENDED {#EXTENDED}
```
public static final HanXinEncodeMode EXTENDED
```


Extended mode will allow more flexible combinations of other modes, this mode is currently not implemented.

### UNICODE {#UNICODE}
```
public static final HanXinEncodeMode UNICODE
```


Unicode mode designs a way to represent any text data reference to UTF8 encoding/charset in Han Xin Code.

### URI {#URI}
```
public static final HanXinEncodeMode URI
```


URI mode indicates the data represented in Han Xin Code is Uniform Resource Identifier (URI) reference to RFC 3986.

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
public static HanXinEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### values() {#values--}
```
public static HanXinEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinEncodeMode[]
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

