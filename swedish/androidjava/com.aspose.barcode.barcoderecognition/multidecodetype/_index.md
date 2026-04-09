---
title: MultiDecodeType
second_title: Aspose.BarCode for Android via Java API-referens
description: Sammansatt avkodningstyp.
type: docs
weight: 37
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

Sammansatt avkodningstyp.

Detta exempel visar hur man skapar sammansatta MultiDecode-typer som kombinerar SingleDecodeType och MultiDecode-typer.

```

```
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Initierar en ny instans av klassen MultiDecodeType. |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Initierar en ny instans av klassen MultiDecodeType. |
## Methods

| Method | Beskrivning |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Lägger till ytterligare en [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) till MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Kontrollera om detta innehåller alla typer från streckkodstyper. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Innehåller någon av typerna |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet MultiDecodeType value. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Returnerar ett värde som indikerar om denna samling av avkodningstyper endast innehåller det angivna [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)-värdet. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet MultiDecodeType value. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Exkluderar [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) från MultiDecodeType och returnerar en ny MultiDecodeType‑instans. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Representerar en lista med enkla typer. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Returnerar antalet enkla typer. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Åsidosatt metod som representerar MultiDecodeType som en sträng. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en BaseDecodeType till dess instans, efter att ha bestämt den konkreta typen. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en MultiDecodeType till dess instans. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en SingleDecodeType till dess instans. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


Initierar en ny instans av klassen MultiDecodeType.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Array av enkla avkodningstyper |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


Initierar en ny instans av klassen MultiDecodeType.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array av multi- och enkla avkodningstyper |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


Lägger till ytterligare en [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) till MultiDecodeType.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | En Single DecodeType att lägga till i listan |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Kontrollera om detta innehåller alla typer från streckkodstyper.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Ange enkla eller multi streckkodstyper |

**Returns:**
boolean – Värdet är sant om alla typer är inkluderade i
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Innehåller någon av typerna

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Avkodningstyper |

**Returns:**
boolean - Värdet är true om någon typ är inkluderad i
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Returnerar ett värde som indikerar om denna instans är lika med ett angivet MultiDecodeType value.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| annat | com.aspose.barcode.barcoderecognition.MultiDecodeType | Ett MultiDecodeType‑värde att jämföra med denna instans. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Returnerar ett värde som indikerar om denna samling av avkodningstyper endast innehåller det angivna [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)-värdet.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ett [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)-värde att jämföra med denna samling av avkodningstyper. |

**Returns:**
boolean -  **true**  om denna samling endast innehåller den angivna avkodningstypen; annars,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om denna instans är lika med ett angivet MultiDecodeType value.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett System.Object‑värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


Exkluderar [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) från MultiDecodeType och returnerar en ny MultiDecodeType‑instans.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | En enskild DecodeType att uteslutas. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Ny MultiDecodeType-instans med utesluten SingleDecodeType.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


Representerar en lista med enkla typer.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Lista över enskilda typer
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Returnerar antalet enkla typer.

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


Åsidosatt metod som representerar MultiDecodeType som en sträng.

**Returns:**
java.lang.String - En sträng som representerar MultiDecodeType-instans som "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
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

