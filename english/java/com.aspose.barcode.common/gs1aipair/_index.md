---
title: GS1AiPair
second_title: Aspose.BarCode for Java API Reference
description: The class represents a pair of AI and text strings.
type: docs
weight: 13
url: /java/com.aspose.barcode.common/gs1aipair/
---
**Inheritance:**
java.lang.Object
```
public class GS1AiPair
```

The class represents a pair of AI and text strings.
## Constructors

| Constructor | Description |
| --- | --- |
| [GS1AiPair(String ai, String value)](#GS1AiPair-java.lang.String-java.lang.String-) | Initializes a new instance of the  GS1AiPair  class by AI number and text to encode |
## Methods

| Method | Description |
| --- | --- |
| [addParentheses(String codetext)](#addParentheses-java.lang.String-) | Adds parentheses to GS1 codetext. |
| [combinePairs(System.Collections.Generic.List<GS1AiPair> pairs)](#combinePairs-com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.common.GS1AiPair--) | Combine pairs in a single line (without parenthesis) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [find(System.Collections.Generic.IGenericEnumerable<GS1AiPair> list, String ai)](#find-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.barcode.common.GS1AiPair--java.lang.String-) | Gets a pair by AI string |
| [getAi()](#getAi--) | Gets the AI type |
| [getAiDescription()](#getAiDescription--) | Gets the AI description |
| [getClass()](#getClass--) |  |
| [getFirst()](#getFirst--) | Gets an AI |
| [getSecond()](#getSecond--) | Gets a text |
| [getValue()](#getValue--) | Gets the text after AI |
| [hashCode()](#hashCode--) |  |
| [isAiBetween(int fromDigit, int toDigit)](#isAiBetween-int-int-) | Checks Ai for entry in the interval |
| [isValueBetween(int fromDigit, int toDigit)](#isValueBetween-int-int-) | Checks Value for entry in the interval |
| [isValueDate(String format)](#isValueDate-java.lang.String-) | Checks if a Value string is a date in the specified format |
| [isValueDigitsOnly()](#isValueDigitsOnly--) | Indicates wether the Value string is contained only digits |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAi(String value)](#setAi-java.lang.String-) | Sets the AI type |
| [setAiDescription(AIDescription value)](#setAiDescription-com.aspose.barcode.common.AIDescription-) | Sets the AI description |
| [setValue(String value)](#setValue-java.lang.String-) | Sets the text after AI |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GS1AiPair(String ai, String value) {#GS1AiPair-java.lang.String-java.lang.String-}
```
public GS1AiPair(String ai, String value)
```


Initializes a new instance of the  GS1AiPair  class by AI number and text to encode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ai | java.lang.String | AI type |
| value | java.lang.String | Text after AI |

### addParentheses(String codetext) {#addParentheses-java.lang.String-}
```
public static String addParentheses(String codetext)
```


Adds parentheses to GS1 codetext.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String | input codetext |

**Returns:**
java.lang.String - codetext with parenteses
### combinePairs(System.Collections.Generic.List<GS1AiPair> pairs) {#combinePairs-com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.common.GS1AiPair--}
```
public static String combinePairs(System.Collections.Generic.List<GS1AiPair> pairs)
```


Combine pairs in a single line (without parenthesis)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pairs | com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.common.GS1AiPair> | List of GS1AiPair-s |

**Returns:**
java.lang.String - a string
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
### find(System.Collections.Generic.IGenericEnumerable<GS1AiPair> list, String ai) {#find-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.barcode.common.GS1AiPair--java.lang.String-}
```
public static GS1AiPair find(System.Collections.Generic.IGenericEnumerable<GS1AiPair> list, String ai)
```


Gets a pair by AI string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| list | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.barcode.common.GS1AiPair> | List of GS1AiPair-s |
| ai | java.lang.String | AI of the pair |

**Returns:**
[GS1AiPair](../../com.aspose.barcode.common/gs1aipair) - pair with given AI if it exists. Else null
### getAi() {#getAi--}
```
public String getAi()
```


Gets the AI type

**Returns:**
java.lang.String
### getAiDescription() {#getAiDescription--}
```
public AIDescription getAiDescription()
```


Gets the AI description

**Returns:**
[AIDescription](../../com.aspose.barcode.common/aidescription)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFirst() {#getFirst--}
```
public String getFirst()
```


Gets an AI

**Returns:**
java.lang.String
### getSecond() {#getSecond--}
```
public String getSecond()
```


Gets a text

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public String getValue()
```


Gets the text after AI

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAiBetween(int fromDigit, int toDigit) {#isAiBetween-int-int-}
```
public boolean isAiBetween(int fromDigit, int toDigit)
```


Checks Ai for entry in the interval

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fromDigit | int | A start interval |
| toDigit | int | A end interval |

**Returns:**
boolean - True if includeded
### isValueBetween(int fromDigit, int toDigit) {#isValueBetween-int-int-}
```
public boolean isValueBetween(int fromDigit, int toDigit)
```


Checks Value for entry in the interval

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fromDigit | int | A start interval |
| toDigit | int | A end interval |

**Returns:**
boolean - True if includeded
### isValueDate(String format) {#isValueDate-java.lang.String-}
```
public boolean isValueDate(String format)
```


Checks if a Value string is a date in the specified format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | date format |

**Returns:**
boolean - True if string is a date
### isValueDigitsOnly() {#isValueDigitsOnly--}
```
public boolean isValueDigitsOnly()
```


Indicates wether the Value string is contained only digits

**Returns:**
boolean - True is value contains only didgits
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAi(String value) {#setAi-java.lang.String-}
```
public void setAi(String value)
```


Sets the AI type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setAiDescription(AIDescription value) {#setAiDescription-com.aspose.barcode.common.AIDescription-}
```
public void setAiDescription(AIDescription value)
```


Sets the AI description

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AIDescription](../../com.aspose.barcode.common/aidescription) |  |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets the text after AI

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

