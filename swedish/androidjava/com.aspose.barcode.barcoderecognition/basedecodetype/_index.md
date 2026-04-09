---
title: BaseDecodeType
second_title: Aspose.BarCode for Android via Java API-referens
description: Basklass för MultiDecodeType och SingleDecodeType.
type: docs
weight: 23
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Basklass för MultiDecodeType och SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | Beskrivning |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Bestämmer om någon av de angivna avkodningstyperna är inkluderad i |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Returnerar ett värde som indikerar om den här instansen är lika med ett angivet [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-värde. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Returnerar ett värde som indikerar om den här instansen är lika med ett angivet [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-värde. |
| [equals(Object other)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om den här instansen är lika med ett angivet [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-värde. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en BaseDecodeType till dess instans, efter att ha bestämt den konkreta typen. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en MultiDecodeType till dess instans. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en SingleDecodeType till dess instans. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Bestämmer om någon av de angivna avkodningstyperna är inkluderad i

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Typer att verifiera. |

**Returns:**
boolean - Värdet är sant om någon typ är inkluderad i.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Returnerar ett värde som indikerar om den här instansen är lika med ett angivet [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| annat | com.aspose.barcode.barcoderecognition.MultiDecodeType | Ett java.lang.Object-värde att jämföra med denna instans. |

**Returns:**
boolean - True om obj har samma värde som den här instansen; annars false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Returnerar ett värde som indikerar om den här instansen är lika med ett angivet [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ett java.lang.Object-värde att jämföra med denna instans. |

**Returns:**
boolean - True om obj har samma värde som den här instansen; annars false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Returnerar ett värde som indikerar om den här instansen är lika med ett angivet [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| annat | java.lang.Object | Ett java.lang.Object-värde att jämföra med denna instans. |

**Returns:**
boolean - True om obj har samma värde som den här instansen; annars false.
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Konverterar strängrepresentationen av en BaseDecodeType till dess instans, efter att ha bestämt den konkreta typen. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng som innehåller en MultiDecodeType-representation att konvertera. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

annars returneras en obestämd typ. eller MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Konverterar strängrepresentationen av en MultiDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng som innehåller en MultiDecodeType-representation att konvertera. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - En faktisk MultiDecodeType returneras när konverteringen har slutförts framgångsrikt;

annars returneras en obestämd typ. eller MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Konverterar strängrepresentationen av en SingleDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng som innehåller en SingleDecodeType i formatet "EAN8" eller "EAN13" eller "CodaBar"... för att konvertera. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

annars returneras en obestämd typ. eller SingleDecodeType (-1, "None").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

