---
title: BaseEncodeType
second_title: Aspose.BarCode for Android via Java API-referens
description: Basklass för SymbologyEncodeType.
type: docs
weight: 16
url: /sv/androidjava/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

Basklass för SymbologyEncodeType.
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet  BaseEncodeType  värde. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Hämtar en klassificering av denna symbol. |
| [getString()](#getString--) | Konverterar instansen av BaseEncodeType till dess motsvarande strängrepresentation. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Konverterar instansen av BaseEncodeType till dess motsvarande strängrepresentation. |
| [getTypeIndex()](#getTypeIndex--) | Hämtar ett index för kodningstypen |
| [getTypeName()](#getTypeName--) | Hämtar ett namn för kodningstypen |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Konverterar strängrepresentationen av namnet på en BaseEncodeType till dess instans. |
| [toString()](#toString--) | Returnerar namnet på den angivna BaseEncodeType som en sträng. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Konverterar strängrepresentationen av en BaseEncodeType till dess instans. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Konverterar strängrepresentationen av en BaseEncodeType till dess instans. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Returnerar ett värde som indikerar om denna instans är lika med ett angivet  BaseEncodeType  värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| annat | java.lang.Object | Ett  BaseEncodeType  värde att jämföra med denna instans. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
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


Hämtar en klassificering av denna symbol.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Konverterar instansen av BaseEncodeType till dess motsvarande strängrepresentation. Strängformatet är: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - En sträng som representerar det kompletta värdet av kodningstypen
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Konverterar instansen av BaseEncodeType till dess motsvarande strängrepresentation. Strängformatet är: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | BaseEncodeType-instansen att konvertera |

**Returns:**
java.lang.String - En sträng som representerar det kompletta värdet av den givna kodningstypen
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Hämtar ett index för kodningstypen

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Hämtar ett namn för kodningstypen

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
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


Konverterar strängrepresentationen av namnet på en BaseEncodeType till dess instans.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| stringEncodeType | java.lang.String | En sträng som innehåller namnet på en BaseEncodeType att konvertera. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Returnerar namnet på den angivna BaseEncodeType som en sträng.

**Returns:**
java.lang.String - En sträng som representerar namnet på kodningstypen
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Konverterar strängrepresentationen av en BaseEncodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng i formatet "Index:-1; Name:None" att konvertera. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | En faktisk SingleEncodeType returneras när konverteringen har slutförts framgångsrikt; |

annars returneras null. |

**Returns:**
boolean -  **true**  om s konverterades framgångsrikt; annars,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Konverterar strängrepresentationen av en BaseEncodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng i formatet "Index:-1; Name:None" att konvertera. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | En faktisk SingleEncodeType returneras när konverteringen har slutförts framgångsrikt; |

annars returneras null. |

**Returns:**
boolean -  **true**  om s konverterades framgångsrikt; annars,  **false** .
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

