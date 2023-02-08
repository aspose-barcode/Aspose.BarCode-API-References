---
title: GS1StandardValidator
second_title: Aspose.BarCode for Java API Reference
description: The class contains functions for validating a code text and getting raw string.
type: docs
weight: 15
url: /java/com.aspose.barcode.common/gs1standardvalidator/
---
**Inheritance:**
java.lang.Object
```
public class GS1StandardValidator
```

The class contains functions for validating a code text and getting raw string.
## Constructors

| Constructor | Description |
| --- | --- |
| [GS1StandardValidator()](#GS1StandardValidator--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAiPairs(String codeGs1, String exceptionMessage)](#getAiPairs-java.lang.String-java.lang.String-) | Get AI pairs for input gs1 string |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseGs1Standard(String codeGs1, char fnc1, String[] code, System.Collections.Generic.List<GS1AiPair>[] aiPairs, String[] msg)](#parseGs1Standard-java.lang.String-char-java.lang.String---com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.common.GS1AiPair----java.lang.String---) | Parses gs1 format and adds fnc1 symbol if needed |
| [rawCodeString(String codeGs1, char fnc1, System.Collections.Generic.List<GS1AiPair>[] pairs, String exceptionMessage)](#rawCodeString-java.lang.String-char-com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.common.GS1AiPair----java.lang.String-) | Removes "(" ,")", validates gs1 format and adds fnc1 symbol if needed |
| [rawCodeString(String codeGs1, char fnc1, String exceptionMessage)](#rawCodeString-java.lang.String-char-java.lang.String-) | Removes "(", ")", validates gs1 format and adds fnc1 symbol if needed |
| [rawCodeStringWithUpdatedCodeText(String codeGs1, char fnc1, String exceptionMessage)](#rawCodeStringWithUpdatedCodeText-java.lang.String-char-java.lang.String-) | Removes "(", ")", validates gs1 format and adds fnc1 symbol if needed. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GS1StandardValidator() {#GS1StandardValidator--}
```
public GS1StandardValidator()
```


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
### getAiPairs(String codeGs1, String exceptionMessage) {#getAiPairs-java.lang.String-java.lang.String-}
```
public static System.Collections.Generic.List<GS1AiPair> getAiPairs(String codeGs1, String exceptionMessage)
```


Get AI pairs for input gs1 string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeGs1 | java.lang.String | Gs1 string |
| exceptionMessage | java.lang.String | Exception message |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - List of AI pairs
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseGs1Standard(String codeGs1, char fnc1, String[] code, System.Collections.Generic.List<GS1AiPair>[] aiPairs, String[] msg) {#parseGs1Standard-java.lang.String-char-java.lang.String---com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.common.GS1AiPair----java.lang.String---}
```
public static boolean parseGs1Standard(String codeGs1, char fnc1, String[] code, System.Collections.Generic.List<GS1AiPair>[] aiPairs, String[] msg)
```


Parses gs1 format and adds fnc1 symbol if needed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeGs1 | java.lang.String | Text to parse |
| fnc1 | char | FNC1 symbol |
| code | java.lang.String[] | raw code string. "(" ,")" were removed |
| aiPairs | com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.common.GS1AiPair>[] | pairs of AI and text |
| msg | java.lang.String[] |  |

**Returns:**
boolean - True if parsed
### rawCodeString(String codeGs1, char fnc1, System.Collections.Generic.List<GS1AiPair>[] pairs, String exceptionMessage) {#rawCodeString-java.lang.String-char-com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.common.GS1AiPair----java.lang.String-}
```
public static String rawCodeString(String codeGs1, char fnc1, System.Collections.Generic.List<GS1AiPair>[] pairs, String exceptionMessage)
```


Removes "(" ,")", validates gs1 format and adds fnc1 symbol if needed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeGs1 | java.lang.String | Text to validate |
| fnc1 | char | FNC1 symbol |
| pairs | com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.common.GS1AiPair>[] | pairs of AI and text |
| exceptionMessage | java.lang.String | Exception message if text is invalid |

**Returns:**
java.lang.String - a raw code string
### rawCodeString(String codeGs1, char fnc1, String exceptionMessage) {#rawCodeString-java.lang.String-char-java.lang.String-}
```
public static String rawCodeString(String codeGs1, char fnc1, String exceptionMessage)
```


Removes "(", ")", validates gs1 format and adds fnc1 symbol if needed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeGs1 | java.lang.String | Text to validate |
| fnc1 | char | FNC1 symbol |
| exceptionMessage | java.lang.String | Exception message if text is invalid |

**Returns:**
java.lang.String - a raw code string"
### rawCodeStringWithUpdatedCodeText(String codeGs1, char fnc1, String exceptionMessage) {#rawCodeStringWithUpdatedCodeText-java.lang.String-char-java.lang.String-}
```
public static RawWithUpdatedCodeText rawCodeStringWithUpdatedCodeText(String codeGs1, char fnc1, String exceptionMessage)
```


Removes "(", ")", validates gs1 format and adds fnc1 symbol if needed. Returns updated code text with correct checksum.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeGs1 | java.lang.String | Text to validate |
| fnc1 | char | FNC1 symbol |
| exceptionMessage | java.lang.String | Exception message if text is invalid |

**Returns:**
[RawWithUpdatedCodeText](../../com.aspose.barcode.common/rawwithupdatedcodetext) - Object with a raw code string and updated code text with correct checksum"
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

