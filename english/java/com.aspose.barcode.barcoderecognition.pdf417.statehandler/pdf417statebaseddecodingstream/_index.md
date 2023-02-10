---
title: Pdf417StateBasedDecodingStream
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 18
url: /java/com.aspose.barcode.barcoderecognition.pdf417.statehandler/pdf417statebaseddecodingstream/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417StateBasedDecodingStream
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Pdf417StateBasedDecodingStream()](#Pdf417StateBasedDecodingStream--) |  |
## Fields

| Field | Description |
| --- | --- |
| [c_Alpha_CharSet_Latch_AL](#c-Alpha-CharSet-Latch-AL) |  |
| [c_Alpha_CharSet_Shift_AS](#c-Alpha-CharSet-Shift-AS) |  |
| [c_ECI925_Latch](#c-ECI925-Latch) |  |
| [c_ECI926_Latch](#c-ECI926-Latch) |  |
| [c_ECI927_Latch](#c-ECI927-Latch) |  |
| [c_LowerCase_CharSet_Latch_LL](#c-LowerCase-CharSet-Latch-LL) |  |
| [c_Macro_Separator](#c-Macro-Separator) |  |
| [c_Macro_Start](#c-Macro-Start) |  |
| [c_Macro_Terminator](#c-Macro-Terminator) |  |
| [c_Mixed_CharSet_Latch_ML](#c-Mixed-CharSet-Latch-ML) |  |
| [c_Punctuation_CharSet_Latch_PL](#c-Punctuation-CharSet-Latch-PL) |  |
| [c_Punctuation_CharSet_Shift_PS](#c-Punctuation-CharSet-Shift-PS) |  |
| [c_Text_Latch](#c-Text-Latch) |  |
| [c_Text_To_Byte6_Latch](#c-Text-To-Byte6-Latch) |  |
| [c_Text_To_Byte_Latch](#c-Text-To-Byte-Latch) |  |
| [c_Text_To_Byte_Shift](#c-Text-To-Byte-Shift) |  |
| [c_Text_To_Numeric_Latch](#c-Text-To-Numeric-Latch) |  |
| [s_Text_Encoding_CharSet](#s-Text-Encoding-CharSet) |  |
## Methods

| Method | Description |
| --- | --- |
| [decode(List<Integer> v)](#decode-java.util.List-java.lang.Integer--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMacroPdf417FieldId()](#getMacroPdf417FieldId--) |  |
| [getMacroPdf417OptionalFields()](#getMacroPdf417OptionalFields--) |  |
| [getMacroPdf417SegmentIndex()](#getMacroPdf417SegmentIndex--) |  |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readEciId(int[] array, int[] offset, int[] count)](#readEciId-int---int---int---) |  |
| [setMacroPdf417OptionalFields(MacroPdf417OptionalFields value)](#setMacroPdf417OptionalFields-com.aspose.barcode.barcoderecognition.pdf417.statehandler.MacroPdf417OptionalFields-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pdf417StateBasedDecodingStream() {#Pdf417StateBasedDecodingStream--}
```
public Pdf417StateBasedDecodingStream()
```


### c_Alpha_CharSet_Latch_AL {#c-Alpha-CharSet-Latch-AL}
```
public static final char c_Alpha_CharSet_Latch_AL
```


### c_Alpha_CharSet_Shift_AS {#c-Alpha-CharSet-Shift-AS}
```
public static final char c_Alpha_CharSet_Shift_AS
```


### c_ECI925_Latch {#c-ECI925-Latch}
```
public static final int c_ECI925_Latch
```


### c_ECI926_Latch {#c-ECI926-Latch}
```
public static final int c_ECI926_Latch
```


### c_ECI927_Latch {#c-ECI927-Latch}
```
public static final int c_ECI927_Latch
```


### c_LowerCase_CharSet_Latch_LL {#c-LowerCase-CharSet-Latch-LL}
```
public static final char c_LowerCase_CharSet_Latch_LL
```


### c_Macro_Separator {#c-Macro-Separator}
```
public static final int c_Macro_Separator
```


### c_Macro_Start {#c-Macro-Start}
```
public static final int c_Macro_Start
```


### c_Macro_Terminator {#c-Macro-Terminator}
```
public static final int c_Macro_Terminator
```


### c_Mixed_CharSet_Latch_ML {#c-Mixed-CharSet-Latch-ML}
```
public static final char c_Mixed_CharSet_Latch_ML
```


### c_Punctuation_CharSet_Latch_PL {#c-Punctuation-CharSet-Latch-PL}
```
public static final char c_Punctuation_CharSet_Latch_PL
```


### c_Punctuation_CharSet_Shift_PS {#c-Punctuation-CharSet-Shift-PS}
```
public static final char c_Punctuation_CharSet_Shift_PS
```


### c_Text_Latch {#c-Text-Latch}
```
public static final int c_Text_Latch
```


### c_Text_To_Byte6_Latch {#c-Text-To-Byte6-Latch}
```
public static final int c_Text_To_Byte6_Latch
```


### c_Text_To_Byte_Latch {#c-Text-To-Byte-Latch}
```
public static final int c_Text_To_Byte_Latch
```


### c_Text_To_Byte_Shift {#c-Text-To-Byte-Shift}
```
public static final int c_Text_To_Byte_Shift
```


### c_Text_To_Numeric_Latch {#c-Text-To-Numeric-Latch}
```
public static final int c_Text_To_Numeric_Latch
```


### s_Text_Encoding_CharSet {#s-Text-Encoding-CharSet}
```
public static char[][] s_Text_Encoding_CharSet
```


### decode(List<Integer> v) {#decode-java.util.List-java.lang.Integer--}
```
public String decode(List<Integer> v)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| v | java.util.List<java.lang.Integer> |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417FieldId() {#getMacroPdf417FieldId--}
```
public String getMacroPdf417FieldId()
```




**Returns:**
java.lang.String
### getMacroPdf417OptionalFields() {#getMacroPdf417OptionalFields--}
```
public MacroPdf417OptionalFields getMacroPdf417OptionalFields()
```




**Returns:**
[MacroPdf417OptionalFields](../../com.aspose.barcode.barcoderecognition.pdf417.statehandler/macropdf417optionalfields)
### getMacroPdf417SegmentIndex() {#getMacroPdf417SegmentIndex--}
```
public int getMacroPdf417SegmentIndex()
```




**Returns:**
int
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```




**Returns:**
boolean
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




### readEciId(int[] array, int[] offset, int[] count) {#readEciId-int---int---int---}
```
public static int readEciId(int[] array, int[] offset, int[] count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | int[] |  |
| offset | int[] |  |
| count | int[] |  |

**Returns:**
int
### setMacroPdf417OptionalFields(MacroPdf417OptionalFields value) {#setMacroPdf417OptionalFields-com.aspose.barcode.barcoderecognition.pdf417.statehandler.MacroPdf417OptionalFields-}
```
public void setMacroPdf417OptionalFields(MacroPdf417OptionalFields value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MacroPdf417OptionalFields](../../com.aspose.barcode.barcoderecognition.pdf417.statehandler/macropdf417optionalfields) |  |

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

