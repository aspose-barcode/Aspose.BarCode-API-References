---
title: AIDescription
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.common/aidescription/
---
**Inheritance:**
java.lang.Object
```
public class AIDescription
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AIDescription(String ai, boolean aiWildCard, int length1, int length2, boolean fnc1Required)](#AIDescription-java.lang.String-boolean-int-int-boolean-) |  |
| [AIDescription(String ai, int length1, int length2, boolean fnc1Required)](#AIDescription-java.lang.String-int-int-boolean-) |  |
| [AIDescription(String ai, boolean aiWildCard, int length, boolean fnc1Required)](#AIDescription-java.lang.String-boolean-int-boolean-) |  |
| [AIDescription(String ai, int length, boolean fnc1Required)](#AIDescription-java.lang.String-int-boolean-) |  |
## Fields

| Field | Description |
| --- | --- |
| [AI](#AI) |  |
| [AIWildCard](#AIWildCard) |  |
| [FNC1Required](#FNC1Required) |  |
| [Length1](#Length1) |  |
| [Length2](#Length2) |  |
## Methods

| Method | Description |
| --- | --- |
| [checkAI(String ai)](#checkAI-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFixedCodeLength()](#getFixedCodeLength--) |  |
| [getFullAILength()](#getFullAILength--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [updateChecksum(GS1AiPair pair)](#updateChecksum-com.aspose.barcode.common.GS1AiPair-) |  |
| [validate(GS1AiPair pair, String[] msg)](#validate-com.aspose.barcode.common.GS1AiPair-java.lang.String---) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AIDescription(String ai, boolean aiWildCard, int length1, int length2, boolean fnc1Required) {#AIDescription-java.lang.String-boolean-int-int-boolean-}
```
public AIDescription(String ai, boolean aiWildCard, int length1, int length2, boolean fnc1Required)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ai | java.lang.String |  |
| aiWildCard | boolean |  |
| length1 | int |  |
| length2 | int |  |
| fnc1Required | boolean |  |

### AIDescription(String ai, int length1, int length2, boolean fnc1Required) {#AIDescription-java.lang.String-int-int-boolean-}
```
public AIDescription(String ai, int length1, int length2, boolean fnc1Required)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ai | java.lang.String |  |
| length1 | int |  |
| length2 | int |  |
| fnc1Required | boolean |  |

### AIDescription(String ai, boolean aiWildCard, int length, boolean fnc1Required) {#AIDescription-java.lang.String-boolean-int-boolean-}
```
public AIDescription(String ai, boolean aiWildCard, int length, boolean fnc1Required)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ai | java.lang.String |  |
| aiWildCard | boolean |  |
| length | int |  |
| fnc1Required | boolean |  |

### AIDescription(String ai, int length, boolean fnc1Required) {#AIDescription-java.lang.String-int-boolean-}
```
public AIDescription(String ai, int length, boolean fnc1Required)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ai | java.lang.String |  |
| length | int |  |
| fnc1Required | boolean |  |

### AI {#AI}
```
public String AI
```


### AIWildCard {#AIWildCard}
```
public boolean AIWildCard
```


### FNC1Required {#FNC1Required}
```
public boolean FNC1Required
```


### Length1 {#Length1}
```
public int Length1
```


### Length2 {#Length2}
```
public int Length2
```


### checkAI(String ai) {#checkAI-java.lang.String-}
```
public boolean checkAI(String ai)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ai | java.lang.String |  |

**Returns:**
boolean
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
### getFixedCodeLength() {#getFixedCodeLength--}
```
public boolean getFixedCodeLength()
```




**Returns:**
boolean
### getFullAILength() {#getFullAILength--}
```
public int getFullAILength()
```




**Returns:**
int
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
### updateChecksum(GS1AiPair pair) {#updateChecksum-com.aspose.barcode.common.GS1AiPair-}
```
public void updateChecksum(GS1AiPair pair)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pair | [GS1AiPair](../../com.aspose.barcode.common/gs1aipair) |  |

### validate(GS1AiPair pair, String[] msg) {#validate-com.aspose.barcode.common.GS1AiPair-java.lang.String---}
```
public boolean validate(GS1AiPair pair, String[] msg)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pair | [GS1AiPair](../../com.aspose.barcode.common/gs1aipair) |  |
| msg | java.lang.String[] |  |

**Returns:**
boolean
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

