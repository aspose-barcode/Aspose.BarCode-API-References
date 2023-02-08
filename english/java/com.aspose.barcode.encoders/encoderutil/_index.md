---
title: EncoderUtil
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.encoders/encoderutil/
---
**Inheritance:**
java.lang.Object
```
public class EncoderUtil
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EncoderUtil()](#EncoderUtil--) |  |
## Fields

| Field | Description |
| --- | --- |
| [EMPTYSTRING](#EMPTYSTRING) |  |
## Methods

| Method | Description |
| --- | --- |
| [applyEscapeCodes(String barcodeText)](#applyEscapeCodes-java.lang.String-) | This function parses "\\" characters |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOnlyDigits(String value)](#getOnlyDigits-java.lang.String-) |  |
| [getOnlyDigits(String value, char[] exclusion)](#getOnlyDigits-java.lang.String-char---) |  |
| [hashCode()](#hashCode--) |  |
| [isAllDigits(char[] chars)](#isAllDigits-char---) | Check if all input chars are digits |
| [isAllDigits(String code)](#isAllDigits-java.lang.String-) |  |
| [isAllLetters(String code)](#isAllLetters-java.lang.String-) |  |
| [isAllLetters(String code, boolean onlyUpperCase)](#isAllLetters-java.lang.String-boolean-) |  |
| [isAlphaNum(String value, boolean onlyDigitsLetters)](#isAlphaNum-java.lang.String-boolean-) |  |
| [isDigit(char ch)](#isDigit-char-) |  |
| [isLetter(char ch)](#isLetter-char-) |  |
| [isLetter(char ch, boolean UpperCaseOrLowerCase)](#isLetter-char-boolean-) |  |
| [isNullOrEmpty(String value)](#isNullOrEmpty-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toBinaryString(long param, int len)](#toBinaryString-long-int-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EncoderUtil() {#EncoderUtil--}
```
public EncoderUtil()
```


### EMPTYSTRING {#EMPTYSTRING}
```
public static final String EMPTYSTRING
```


### applyEscapeCodes(String barcodeText) {#applyEscapeCodes-java.lang.String-}
```
public static String applyEscapeCodes(String barcodeText)
```


This function parses "\\" characters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeText | java.lang.String | barcode text |

**Returns:**
java.lang.String - parse text
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
### getOnlyDigits(String value) {#getOnlyDigits-java.lang.String-}
```
public static String getOnlyDigits(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

**Returns:**
java.lang.String
### getOnlyDigits(String value, char[] exclusion) {#getOnlyDigits-java.lang.String-char---}
```
public static String getOnlyDigits(String value, char[] exclusion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
| exclusion | char[] |  |

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAllDigits(char[] chars) {#isAllDigits-char---}
```
public static boolean isAllDigits(char[] chars)
```


Check if all input chars are digits

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chars | char[] | Input chars |

**Returns:**
boolean - True if all input chars are digits
### isAllDigits(String code) {#isAllDigits-java.lang.String-}
```
public static boolean isAllDigits(String code)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| code | java.lang.String |  |

**Returns:**
boolean
### isAllLetters(String code) {#isAllLetters-java.lang.String-}
```
public static boolean isAllLetters(String code)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| code | java.lang.String |  |

**Returns:**
boolean
### isAllLetters(String code, boolean onlyUpperCase) {#isAllLetters-java.lang.String-boolean-}
```
public static boolean isAllLetters(String code, boolean onlyUpperCase)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| code | java.lang.String |  |
| onlyUpperCase | boolean |  |

**Returns:**
boolean
### isAlphaNum(String value, boolean onlyDigitsLetters) {#isAlphaNum-java.lang.String-boolean-}
```
public static boolean isAlphaNum(String value, boolean onlyDigitsLetters)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
| onlyDigitsLetters | boolean |  |

**Returns:**
boolean
### isDigit(char ch) {#isDigit-char-}
```
public static boolean isDigit(char ch)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ch | char |  |

**Returns:**
boolean
### isLetter(char ch) {#isLetter-char-}
```
public static boolean isLetter(char ch)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ch | char |  |

**Returns:**
boolean
### isLetter(char ch, boolean UpperCaseOrLowerCase) {#isLetter-char-boolean-}
```
public static boolean isLetter(char ch, boolean UpperCaseOrLowerCase)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ch | char |  |
| UpperCaseOrLowerCase | boolean |  |

**Returns:**
boolean
### isNullOrEmpty(String value) {#isNullOrEmpty-java.lang.String-}
```
public static boolean isNullOrEmpty(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toBinaryString(long param, int len) {#toBinaryString-long-int-}
```
public static char[] toBinaryString(long param, int len)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| param | long |  |
| len | int |  |

**Returns:**
char[]
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

