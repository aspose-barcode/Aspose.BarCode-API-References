---
title: "BaseEncodeType"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: "Basisklasse voor SymbologyEncodeType."
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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven  BaseEncodeType  waarde. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Verkrijgt een classificatie van deze symbologie. |
| [getString()](#getString--) | Converteert de instantie van BaseEncodeType naar de equivalente stringrepresentatie. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Converteert de instantie van BaseEncodeType naar de equivalente stringrepresentatie. |
| [getTypeIndex()](#getTypeIndex--) | Verkrijgt een index van de codeertype. |
| [getTypeName()](#getTypeName--) | Verkrijgt een naam van de codeertype. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Converteert de stringrepresentatie van de naam van een BaseEncodeType naar de instantie. |
| [toString()](#toString--) | Retourneert de naam van de opgegeven BaseEncodeType als string. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Converteert de stringrepresentatie van een BaseEncodeType naar de instantie. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Converteert de stringrepresentatie van een BaseEncodeType naar de instantie. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven  BaseEncodeType  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anders | java.lang.Object | Een  BaseEncodeType  waarde om te vergelijken met deze instantie. |

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


Verkrijgt een classificatie van deze symbologie.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Converteert de instantie van BaseEncodeType naar de equivalente stringrepresentatie. Het stringformaat is: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - Een string die de volledige waarde van de codeertype weergeeft
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Converteert de instantie van BaseEncodeType naar de equivalente stringrepresentatie. Het stringformaat is: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | De BaseEncodeType‑instantie om te converteren |

**Returns:**
java.lang.String - Een string die de volledige waarde van de opgegeven codeertype weergeeft
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Verkrijgt een index van de codeertype.

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Verkrijgt een naam van de codeertype.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bit ondertekend geheel getal hashcode.
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


Converteert de stringrepresentatie van de naam van een BaseEncodeType naar de instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stringEncodeType | java.lang.String | Een string die de naam van een BaseEncodeType bevat om te converteren. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Retourneert de naam van de opgegeven BaseEncodeType als string.

**Returns:**
java.lang.String - Een string die de naam van de codeertype weergeeft
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Converteert de stringrepresentatie van een BaseEncodeType naar de instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string in het formaat "Index:-1; Name:None" om te converteren. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Een daadwerkelijke SingleEncodeType wordt geretourneerd wanneer de conversie succesvol is voltooid; |

anders retourneert het null. |

**Returns:**
boolean -  **true**  als s succesvol is geconverteerd; anders,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Converteert de stringrepresentatie van een BaseEncodeType naar de instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string in het formaat "Index:-1; Name:None" om te converteren. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Een daadwerkelijke SingleEncodeType wordt geretourneerd wanneer de conversie succesvol is voltooid; |

anders retourneert het null. |

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

