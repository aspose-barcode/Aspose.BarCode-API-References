---
title: "SingleDecodeType"
second_title: "Aspose.BarCode för Java API-referens"
description: "Enkel avkodningstyp."
type: docs
weight: 44
url: /sv/java/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

Enkel avkodningstyp. Se avkodningstyp för att få en instans.

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Returnerar ett värde som indikerar om den här instansen är inkluderad i den angivna listan. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om den här instansen är lika med ett specificerat [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)-värde. |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | Konverterar en instans av SingleDecodeType till dess motsvarande strängrepresentation, med följande format: "Index:-1; Name:None". |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Konverterar en instans av SingleDecodeType till dess motsvarande strängrepresentation, med följande format: "Index:-1; Name:None". |
| [getTypeIndex()](#getTypeIndex--) | Hämtar ett index för avkodningstypen |
| [getTypeName()](#getTypeName--) | Hämtar ett namn för avkodningstypen |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | Konverterar strängrepresentationen av namnet på en SingleDecodeType till dess instans. |
| [toString()](#toString--) | Åsidosatt metod som representerar SingleDecodeType som namnsträngen. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en BaseDecodeType till dess instans, efter att ha bestämt den konkreta typen. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en MultiDecodeType till dess instans. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en SingleDecodeType till dess instans. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


Returnerar ett värde som indikerar om den här instansen är inkluderad i den angivna listan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array av enkla och multipla avkodningstyper |

**Returns:**
boolean - Värdet är sant om någon typ är inkluderad i
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om den här instansen är lika med ett specificerat [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)-värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett System.Object‑värde att jämföra med detta objekt. |

**Returns:**
boolean - Sant om obj har samma värde som detta objekt; annars falskt.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getString() {#getString--}
```
public String getString()
```


Konverterar en instans av SingleDecodeType till dess motsvarande strängrepresentation, med följande format: "Index:-1; Name:None".

**Returns:**
java.lang.String - En sträng som representerar det fullständiga värdet av den enkla avkodningstypen
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


Konverterar en instans av SingleDecodeType till dess motsvarande strängrepresentation, med följande format: "Index:-1; Name:None".

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | SingleDecodeType-instansen att konvertera |

**Returns:**
java.lang.String - En sträng som representerar det fullständiga värdet av den givna enkla avkodningstypen
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Hämtar ett index för avkodningstypen

**Returns:**
short - Indexet för avkodningstypen
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Hämtar ett namn för avkodningstypen

**Returns:**
java.lang.String - Namnet på avkodningstypen
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




### parseSingleDecodeType(String stringDecodeType) {#parseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType parseSingleDecodeType(String stringDecodeType)
```


Konverterar strängrepresentationen av namnet på en SingleDecodeType till dess instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stringDecodeType | java.lang.String | En sträng som innehåller namnet på en SingleDecodeType att konvertera. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


Åsidosatt metod som representerar SingleDecodeType som namnsträngen.

**Returns:**
java.lang.String - En sträng som representerar namnet på den enkla avkodningstypen
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Konverterar strängrepresentationen av en BaseDecodeType till dess instans, efter att den konkreta typen har bestämts. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng som innehåller en MultiDecodeType-representation att konvertera. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

annars returneras en obestämd typ, eller MultiDecodeType (\"None\").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Konverterar strängrepresentationen av en MultiDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng som innehåller en MultiDecodeType-representation att konvertera. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

annars returneras en obestämd typ, eller MultiDecodeType (\"None\").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Konverterar strängrepresentationen av en SingleDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng som innehåller en SingleDecodeType i formatet \"EAN8\" eller \"EAN13\" eller \"CodaBar\"... att konvertera. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

annars returneras en obestämd typ, eller SingleDecodeType (-1, \"None\").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

