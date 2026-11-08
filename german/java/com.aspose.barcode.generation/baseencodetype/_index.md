---
title: "BaseEncodeType"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Basisklasse für SymbologyEncodeType."
type: docs
weight: 16
url: /de/java/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

Basisklasse für SymbologyEncodeType.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BaseEncodeType‑Wert entspricht. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Ermittelt die Klassifizierung dieses Symbols. |
| [getString()](#getString--) | Konvertiert die Instanz von BaseEncodeType in ihre äquivalente Zeichenkettenrepräsentation. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Konvertiert die Instanz von BaseEncodeType in ihre äquivalente Zeichenkettenrepräsentation. |
| [getTypeIndex()](#getTypeIndex--) | Ermittelt einen Index des Kodierungstyps |
| [getTypeName()](#getTypeName--) | Ermittelt einen Namen des Kodierungstyps |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation des Namens eines BaseEncodeType in seine Instanz. |
| [toString()](#toString--) | Gibt den Namen des angegebenen BaseEncodeType als Zeichenkette zurück. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Konvertiert die Zeichenkettenrepräsentation eines BaseEncodeType in seine Instanz. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Konvertiert die Zeichenkettenrepräsentation eines BaseEncodeType in seine Instanz. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BaseEncodeType‑Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | java.lang.Object | Ein BaseEncodeType‑Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolesch -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false** .
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


Ermittelt die Klassifizierung dieses Symbols.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Konvertiert die Instanz von BaseEncodeType in ihre entsprechende Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - Eine Zeichenkette, die den vollständigen Wert des Codierungstyps darstellt
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Konvertiert die Instanz von BaseEncodeType in ihre entsprechende Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:-1; Name:None".

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Die BaseEncodeType-Instanz, die konvertiert werden soll |

**Returns:**
java.lang.String - Eine Zeichenkette, die den vollständigen Wert des angegebenen Codierungstyps darstellt
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Ermittelt einen Index des Kodierungstyps

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Ermittelt einen Namen des Kodierungstyps

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Ganzzahl-Hashcode.
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


Konvertiert die Zeichenkettenrepräsentation des Namens eines BaseEncodeType in seine Instanz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stringEncodeType | java.lang.String | Eine Zeichenkette, die den Namen eines BaseEncodeType enthält, der konvertiert werden soll. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Gibt den Namen des angegebenen BaseEncodeType als Zeichenkette zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die den Namen des Codierungstyps darstellt
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Konvertiert die Zeichenkettenrepräsentation eines BaseEncodeType in seine Instanz. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Eine Zeichenkette im Format "Index:-1; Name:None" zum Konvertieren. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Ein tatsächlicher SingleEncodeType wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; |

andernfalls wird null zurückgegeben. |

**Returns:**
boolean -  **true**  wenn s erfolgreich konvertiert wurde; andernfalls **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Konvertiert die Zeichenkettenrepräsentation eines BaseEncodeType in seine Instanz. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Eine Zeichenkette im Format "Index:-1; Name:None" zum Konvertieren. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Ein tatsächlicher SingleEncodeType wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; |

andernfalls wird null zurückgegeben. |

**Returns:**
boolean -  **true**  wenn s erfolgreich konvertiert wurde; andernfalls **false** .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

