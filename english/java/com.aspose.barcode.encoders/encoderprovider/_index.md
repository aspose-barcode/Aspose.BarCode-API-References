---
title: EncoderProvider
second_title: Aspose.BarCode for Java API Reference
description: Utility tools for symbology related applications
type: docs
weight: 12
url: /java/com.aspose.barcode.encoders/encoderprovider/
---
**Inheritance:**
java.lang.Object
```
public class EncoderProvider
```

Utility tools for symbology related applications
## Constructors

| Constructor | Description |
| --- | --- |
| [EncoderProvider()](#EncoderProvider--) |  |
## Fields

| Field | Description |
| --- | --- |
| [CHARSET_ALPHANUMERIC](#CHARSET-ALPHANUMERIC) |  |
| [CHARSET_NUMERIC](#CHARSET-NUMERIC) |  |
| [LefthandEven](#LefthandEven) |  |
| [LefthandOdd](#LefthandOdd) |  |
| [Parity5](#Parity5) |  |
| [uebCenterGuards](#uebCenterGuards) |  |
| [uebSeparator](#uebSeparator) |  |
| [uebStartGuards](#uebStartGuards) |  |
| [upc_code_c](#upc-code-c) |  |
## Methods

| Method | Description |
| --- | --- |
| [UPC25SUPP(String str)](#UPC25SUPP-java.lang.String-) |  |
| [UPC2SUPP(String str)](#UPC2SUPP-java.lang.String-) |  |
| [UPC5SUPP(String str)](#UPC5SUPP-java.lang.String-) |  |
| [codeTobinary(String str)](#codeTobinary-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filterCodeText(String str, int maxCharIntValue)](#filterCodeText-java.lang.String-int-) |  |
| [filterCodeText(String str, String charset)](#filterCodeText-java.lang.String-java.lang.String-) |  |
| [filterCodeText(String str, String charset, int length)](#filterCodeText-java.lang.String-java.lang.String-int-) |  |
| [filterCodeText(String str, String charset, int length, boolean paddingLeft)](#filterCodeText-java.lang.String-java.lang.String-int-boolean-) |  |
| [getClass()](#getClass--) |  |
| [getUPCCheck(String str)](#getUPCCheck-java.lang.String-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EncoderProvider() {#EncoderProvider--}
```
public EncoderProvider()
```


### CHARSET_ALPHANUMERIC {#CHARSET-ALPHANUMERIC}
```
public static String CHARSET_ALPHANUMERIC
```


### CHARSET_NUMERIC {#CHARSET-NUMERIC}
```
public static String CHARSET_NUMERIC
```


### LefthandEven {#LefthandEven}
```
public static String[] LefthandEven
```


### LefthandOdd {#LefthandOdd}
```
public static String[] LefthandOdd
```


### Parity5 {#Parity5}
```
public static String[] Parity5
```


### uebCenterGuards {#uebCenterGuards}
```
public static String uebCenterGuards
```


### uebSeparator {#uebSeparator}
```
public static String uebSeparator
```


### uebStartGuards {#uebStartGuards}
```
public static String uebStartGuards
```


### upc_code_c {#upc-code-c}
```
public static String[] upc_code_c
```


### UPC25SUPP(String str) {#UPC25SUPP-java.lang.String-}
```
public static String UPC25SUPP(String str)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
java.lang.String
### UPC2SUPP(String str) {#UPC2SUPP-java.lang.String-}
```
public static String UPC2SUPP(String str)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
java.lang.String
### UPC5SUPP(String str) {#UPC5SUPP-java.lang.String-}
```
public static String UPC5SUPP(String str)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
java.lang.String
### codeTobinary(String str) {#codeTobinary-java.lang.String-}
```
public static String codeTobinary(String str)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
java.lang.String
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### filterCodeText(String str, int maxCharIntValue) {#filterCodeText-java.lang.String-int-}
```
public static String filterCodeText(String str, int maxCharIntValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |
| maxCharIntValue | int |  |

**Returns:**
java.lang.String
### filterCodeText(String str, String charset) {#filterCodeText-java.lang.String-java.lang.String-}
```
public static String filterCodeText(String str, String charset)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |
| charset | java.lang.String |  |

**Returns:**
java.lang.String
### filterCodeText(String str, String charset, int length) {#filterCodeText-java.lang.String-java.lang.String-int-}
```
public static String filterCodeText(String str, String charset, int length)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |
| charset | java.lang.String |  |
| length | int |  |

**Returns:**
java.lang.String
### filterCodeText(String str, String charset, int length, boolean paddingLeft) {#filterCodeText-java.lang.String-java.lang.String-int-boolean-}
```
public static String filterCodeText(String str, String charset, int length, boolean paddingLeft)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |
| charset | java.lang.String |  |
| length | int |  |
| paddingLeft | boolean |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getUPCCheck(String str) {#getUPCCheck-java.lang.String-}
```
public static char getUPCCheck(String str)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
char
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

