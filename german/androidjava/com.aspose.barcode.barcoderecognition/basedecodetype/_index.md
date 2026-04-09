---
title: BaseDecodeType
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Basisklasse für MultiDecodeType und SingleDecodeType.
type: docs
weight: 23
url: /de/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Basisklasse für MultiDecodeType und SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | Beschreibung |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Bestimmt, ob einer der angegebenen Dekodierungstypen enthalten ist. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) Wert entspricht. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) Wert entspricht. |
| [equals(Object other)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) Wert entspricht. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines BaseDecodeType in seine Instanz, nachdem der konkrete Typ ermittelt wurde. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Bestimmt, ob einer der angegebenen Dekodierungstypen enthalten ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Zu überprüfende Typen. |

**Returns:**
boolean - Der Wert ist true, wenn irgendein Typ enthalten ist.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| andere | com.aspose.barcode.barcoderecognition.MultiDecodeType | Ein java.lang.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean – True, wenn obj denselben Wert wie diese Instanz hat; andernfalls false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ein java.lang.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean – True, wenn obj denselben Wert wie diese Instanz hat; andernfalls false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| andere | java.lang.Object | Ein java.lang.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean – True, wenn obj denselben Wert wie diese Instanz hat; andernfalls false.
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


Konvertiert die String-Darstellung eines BaseDecodeType in seine Instanz, nachdem der konkrete Typ ermittelt wurde. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Ein String, der eine MultiDecodeType-Darstellung zum Konvertieren enthält. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

Andernfalls gibt es einen unbestimmten Typ zurück, oder MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Konvertiert die String-Darstellung eines MultiDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Ein String, der eine MultiDecodeType-Darstellung zum Konvertieren enthält. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Ein tatsächlicher MultiDecodeType wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde;

Andernfalls gibt es einen unbestimmten Typ zurück, oder MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Konvertiert die String-Darstellung eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Ein String, der einen SingleDecodeType im Format "EAN8" oder "EAN13" oder "CodaBar"... zum Konvertieren enthält. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

Andernfalls gibt es einen unbestimmten Typ zurück, oder SingleDecodeType (-1, "None").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

