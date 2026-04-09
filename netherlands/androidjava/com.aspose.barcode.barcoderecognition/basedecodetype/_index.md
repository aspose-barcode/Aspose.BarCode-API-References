---
title: BaseDecodeType
second_title: Aspose.BarCode for Android via Java API-referentie
description: Basisklasse voor MultiDecodeType en SingleDecodeType.
type: docs
weight: 23
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Basisklasse voor MultiDecodeType en SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | Beschrijving |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Bepaalt of een van de opgegeven decodeertypes is opgenomen in |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) waarde. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) waarde. |
| [equals(Object other)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) waarde. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converteert de tekenreeksrepresentatie van een BaseDecodeType naar de bijbehorende instantie, nadat het concrete type is bepaald. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Converteert de tekenreeksrepresentatie van een MultiDecodeType naar de bijbehorende instantie. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Bepaalt of een van de opgegeven decodeertypes is opgenomen in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Types om te verifiëren. |

**Returns:**
boolean - Waarde is true als een van de types is opgenomen.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anders | com.aspose.barcode.barcoderecognition.MultiDecodeType | Een java.lang.Object-waarde om te vergelijken met deze instantie. |

**Returns:**
boolean - True als obj dezelfde waarde heeft als deze instantie; anders, false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Een java.lang.Object-waarde om te vergelijken met deze instantie. |

**Returns:**
boolean - True als obj dezelfde waarde heeft als deze instantie; anders, false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anders | java.lang.Object | Een java.lang.Object-waarde om te vergelijken met deze instantie. |

**Returns:**
boolean - True als obj dezelfde waarde heeft als deze instantie; anders, false.
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


Converteert de tekenreeksrepresentatie van een BaseDecodeType naar zijn instantie, nadat het concrete type is bepaald. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string die een MultiDecodeType-representatie bevat om te converteren. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

anders retourneert het een onbepaald type. of MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Converteert de tekenreeksrepresentatie van een MultiDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string die een MultiDecodeType-representatie bevat om te converteren. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Een daadwerkelijke MultiDecodeType wordt geretourneerd wanneer de conversie succesvol is voltooid;

anders retourneert het een onbepaald type. of MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string die een SingleDecodeType bevat in het formaat "EAN8" of "EAN13" of "CodaBar"... om te converteren. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

anders retourneert het een onbepaald type. of SingleDecodeType (-1, "None").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

