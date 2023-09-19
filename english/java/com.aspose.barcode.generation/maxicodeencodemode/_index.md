---
title: MaxiCodeEncodeMode
second_title: Aspose.BarCode for Java API Reference
description: Encoding mode for MaxiCode barcodes.
type: docs
weight: 90
url: /java/com.aspose.barcode.generation/maxicodeencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeEncodeMode extends Enum<MaxiCodeEncodeMode>
```

Encoding mode for MaxiCode barcodes.

```
//Auto mode
 String codetext = "\u72acRight\u72d7";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 {
     generator.getParameters().getBarcode().getMaxiCode().setECIEncoding(ECIEncodings.UTF8);
     generator.save("test.bmp");
 }

 //Bytes mode
 byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };

 //encode array to string
 StringBuilder strBld = new StringBuilder();
 for(byte bval : encodedArr)
     strBld.append((char) bval);
 String codetext = strBld.ToString();

 BarcodeGenerator generator1 = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.BYTES);
 generator.save("test.bmp");

 //Extended codetext mode
 //create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 // generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext);
 generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## Fields

| Field | Description |
| --- | --- |
| [AUTO](#AUTO) | Encode codetext with value set in the ECIEncoding property. |
| [BYTES](#BYTES) | Encode codetext as plain bytes. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) | Extended mode which supports multi ECI modes. |
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
public static final MaxiCodeEncodeMode AUTO
```


Encode codetext with value set in the ECIEncoding property.

### BYTES {#BYTES}
```
public static final MaxiCodeEncodeMode BYTES
```


Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final MaxiCodeEncodeMode EXTENDED_CODETEXT
```


Extended mode which supports multi ECI modes. It is better to use MaxiCodeExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset.

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
public static MaxiCodeEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode)
### values() {#values--}
```
public static MaxiCodeEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeEncodeMode[]
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

