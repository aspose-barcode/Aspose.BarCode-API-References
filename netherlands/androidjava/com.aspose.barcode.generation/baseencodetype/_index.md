---
title: BaseEncodeType
second_title: Aspose.BarCode for Android via Java API-referentie
description: Basisklasse voor SymbologyEncodeType.
type: docs
weight: 16
url: /nl/androidjava/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

Basisklasse voor SymbologyEncodeType.
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BaseEncodeType‑waarde. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Haalt een classificatie van dit symbool op. |
| [getString()](#getString--) | Converteert de instantie van BaseEncodeType naar de equivalente tekenreeksrepresentatie. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Converteert de instantie van BaseEncodeType naar de equivalente tekenreeksrepresentatie. |
| [getTypeIndex()](#getTypeIndex--) | Haalt een index van het codeertype op |
| [getTypeName()](#getTypeName--) | Haalt een naam van het codeertype op |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Converteert de tekenreeksrepresentatie van de naam van een BaseEncodeType naar de bijbehorende instantie. |
| [toString()](#toString--) | Retourneert de naam van de opgegeven BaseEncodeType als een tekenreeks. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Converteert de tekenreeksrepresentatie van een BaseEncodeType naar de bijbehorende instantie. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Converteert de tekenreeksrepresentatie van een BaseEncodeType naar de bijbehorende instantie. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BaseEncodeType‑waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anders | java.lang.Object | Een BaseEncodeType‑waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


Haalt een classificatie van dit symbool op.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Converteert de instantie van BaseEncodeType naar de equivalente tekenreeksrepresentatie. Het tekenreeksformaat is: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - Een tekenreeks die de volledige waarde van het encodeertype weergeeft
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Converteert de instantie van BaseEncodeType naar de equivalente tekenreeksrepresentatie. Het tekenreeksformaat is: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | De BaseEncodeType‑instantie om te converteren |

**Returns:**
java.lang.String - Een tekenreeks die de volledige waarde van het opgegeven encodeertype weergeeft
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Haalt een index van het codeertype op

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Haalt een naam van het codeertype op

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


Converteert de tekenreeksrepresentatie van de naam van een BaseEncodeType naar de bijbehorende instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stringEncodeType | java.lang.String | Een tekenreeks die de naam van een BaseEncodeType bevat om te converteren. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Retourneert de naam van de opgegeven BaseEncodeType als een tekenreeks.

**Returns:**
java.lang.String - Een tekenreeks die de naam van het encodeertype weergeeft
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Converteert de tekenreeksrepresentatie van een BaseEncodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een tekenreeks in het formaat "Index:-1; Name:None" om te converteren. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Een daadwerkelijke SingleEncodeType wordt geretourneerd wanneer de conversie succesvol is voltooid; |

anders wordt null geretourneerd. |

**Returns:**
boolean -  **true**  als s succesvol is geconverteerd; anders,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Converteert de tekenreeksrepresentatie van een BaseEncodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een tekenreeks in het formaat "Index:-1; Name:None" om te converteren. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Een daadwerkelijke SingleEncodeType wordt geretourneerd wanneer de conversie succesvol is voltooid; |

anders wordt null geretourneerd. |

**Returns:**
boolean -  **true**  als s succesvol is geconverteerd; anders,  **false** .
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

