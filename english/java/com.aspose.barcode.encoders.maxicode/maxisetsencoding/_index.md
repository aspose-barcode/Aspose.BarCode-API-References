---
title: MaxiSetsEncoding
second_title: Aspose.BarCode for Java API Reference
description: Functions for encoding codesets logic
type: docs
weight: 12
url: /java/com.aspose.barcode.encoders.maxicode/maxisetsencoding/
---
**Inheritance:**
java.lang.Object
```
public class MaxiSetsEncoding
```

Functions for encoding codesets logic
## Constructors

| Constructor | Description |
| --- | --- |
| [MaxiSetsEncoding()](#MaxiSetsEncoding--) |  |
## Fields

| Field | Description |
| --- | --- |
| [LatchAfromCDE](#LatchAfromCDE) | Latch A from sets C, D or E |
## Methods

| Method | Description |
| --- | --- |
| [encodeCodeSetA(String text, List<Integer> codeWords, int[] index)](#encodeCodeSetA-java.lang.String-java.util.List-java.lang.Integer--int---) | Encode a part of input text from index with codeset A and return next codeset and index. |
| [encodeCodeSetB(String text, List<Integer> codeWords, int[] index)](#encodeCodeSetB-java.lang.String-java.util.List-java.lang.Integer--int---) | Encode a part of input text from index with codeset B and return next codeset and index. |
| [encodeCodeSetCDorE(String text, int codeSet, List<Integer> codeWords, int[] index, int[] nextCodeSet)](#encodeCodeSetCDorE-java.lang.String-int-java.util.List-java.lang.Integer--int---int---) | Encode a part of input text from index with codeset C, D or E and return next codeset and index. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCodesetA(String text)](#isCodesetA-java.lang.String-) | Is all chars from text belong to codeset A |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiSetsEncoding() {#MaxiSetsEncoding--}
```
public MaxiSetsEncoding()
```


### LatchAfromCDE {#LatchAfromCDE}
```
public static final byte LatchAfromCDE
```


Latch A from sets C, D or E

### encodeCodeSetA(String text, List<Integer> codeWords, int[] index) {#encodeCodeSetA-java.lang.String-java.util.List-java.lang.Integer--int---}
```
public static int encodeCodeSetA(String text, List<Integer> codeWords, int[] index)
```


Encode a part of input text from index with codeset A and return next codeset and index. Put result to codewords

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Input text |
| codeWords | java.util.List<java.lang.Integer> | Codewords |
| index | int[] | An index |

**Returns:**
int - Next codeset
### encodeCodeSetB(String text, List<Integer> codeWords, int[] index) {#encodeCodeSetB-java.lang.String-java.util.List-java.lang.Integer--int---}
```
public static int encodeCodeSetB(String text, List<Integer> codeWords, int[] index)
```


Encode a part of input text from index with codeset B and return next codeset and index. Put result to codewords

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Input text |
| codeWords | java.util.List<java.lang.Integer> | Codewords |
| index | int[] | An index |

**Returns:**
int - Next codeset
### encodeCodeSetCDorE(String text, int codeSet, List<Integer> codeWords, int[] index, int[] nextCodeSet) {#encodeCodeSetCDorE-java.lang.String-int-java.util.List-java.lang.Integer--int---int---}
```
public static boolean encodeCodeSetCDorE(String text, int codeSet, List<Integer> codeWords, int[] index, int[] nextCodeSet)
```


Encode a part of input text from index with codeset C, D or E and return next codeset and index. Put result to codewords

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Input text |
| codeSet | int | Input codeset |
| codeWords | java.util.List<java.lang.Integer> | Codewords |
| index | int[] | An index |
| nextCodeSet | int[] | Next codeset |

**Returns:**
boolean - Is encoded
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCodesetA(String text) {#isCodesetA-java.lang.String-}
```
public static boolean isCodesetA(String text)
```


Is all chars from text belong to codeset A

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | A text |

**Returns:**
boolean - Is char belongs to codeset A
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

