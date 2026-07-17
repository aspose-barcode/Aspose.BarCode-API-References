---
title: QrExtCodetextBuilder
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 63
url: /java/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of EncodeMode

Use TwoDDisplayText property of BarcodeGenerator to set visible text to removing managing characters.

This sample shows how to use FNC1 first position in Extended Mode.

```

 [C#]
 //create codetext
 QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
 TextBuilder.AddFNC1FirstPosition();
 TextBuilder.AddPlainCodetext("000%89%%0");
 TextBuilder.AddFNC1GroupSeparator();
 TextBuilder.AddPlainCodetext("12345<FNC1>");
 //generate codetext
 String codetext = TextBuilder.GetExtendedCodetext();
 //generate
 using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
 {
     generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
     generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
 	generator.CodeText = codetext;
     generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
 	generator.Save("test.bmp");
 }
 
```

This sample shows how to use FNC1 second position in Extended Mode.

```

 [C#]
 //create codetext
 QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
 TextBuilder.AddFNC1SecondPosition("12");
 TextBuilder.AddPlainCodetext("TRUE3456");
 //generate codetext
 String codetext = TextBuilder.GetExtendedCodetext();
 //generate
 using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
 {
     generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
     generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
 	generator.CodeText = codetext;
     generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
 	generator.Save("test.bmp");
 }
 
```

This sample shows how to use multi ECI mode in Extended Mode.

```

 [C#]
 //create codetext
 QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
 TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
 TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
 TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
 TextBuilder.AddPlainCodetext(@"t\e\\st");
 TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
 TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");
 //generate codetext
 String codetext = TextBuilder.GetExtendedCodetext();
 //generate
 using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
 {
     generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
     generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
 	generator.CodeText = codetext;
     generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
 	generator.Save("test.bmp");
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | Adds codetext with the specified QR compaction mode to the extended codetext items. |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Adds codetext with Extended Channel Identifier |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Sets FNC1 in first position. |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Adds Group Separator (GS - '\\\\u001D') to the extended codetext items |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Sets FNC1 in second position. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Adds plain codetext to the extended codetext items |
| [clear()](#clear--) | Clears extended codetext items |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Generates Extended codetext from the extended codetext list. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext) {#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-}
```
public final void addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)
```


Adds codetext with the specified QR compaction mode to the extended codetext items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | QR compaction mode for the codetext. |
| codetext | java.lang.String | Codetext in Unicode to add as an extended codetext item. |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Adds codetext with Extended Channel Identifier

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Codetext in unicode to add as extended codetext item with Extended Channel Identifier |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


Sets FNC1 in first position. If another FNC1 mode was set before, it is replaced.

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


Adds Group Separator (GS - '\\\\u001D') to the extended codetext items

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


Sets FNC1 in second position. If another FNC1 mode was set before, it is replaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String | Value of the FNC1 in the second position. The value must be a single letter from a-z or A-Z, or a two-digit number from 00 to 99. |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Adds plain codetext to the extended codetext items

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in unicode to add as extended codetext item |

### clear() {#clear--}
```
public void clear()
```


Clears extended codetext items

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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Generates Extended codetext from the extended codetext list.

**Returns:**
java.lang.String - Extended codetext as string
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

