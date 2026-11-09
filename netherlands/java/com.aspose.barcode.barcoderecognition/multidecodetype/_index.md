---
title: "MultiDecodeType"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Samengestelde decodeertype."
type: docs
weight: 34
url: /nl/java/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

Samengestelde decodeertype.

Dit voorbeeld toont hoe samengestelde MultiDecode-types te maken die SingleDecodeType- en MultiDecode-types combineren.

```

```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Initialiseert een nieuw exemplaar van de [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) klasse. |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Initialiseert een nieuw exemplaar van de [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Voegt nog één [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) toe aan de MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Controleer of dit alle typen van barcodetypen bevat. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Bevat het een van de typen? |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) waarde. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Retourneert een waarde die aangeeft of deze collectie decode‑typen alleen de opgegeven [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) waarde bevat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) waarde. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Sluit [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) uit van de MultiDecodeType en retourneert een nieuwe MultiDecodeType‑instantie. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Stelt een lijst van enkele typen voor. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Retourneert een aantal enkele typen. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Overschreven methode die MultiDecodeType als een string weergeeft. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converteert de tekenreeksrepresentatie van een BaseDecodeType naar de bijbehorende instantie, nadat het concrete type is bepaald. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Converteert de tekenreeksrepresentatie van een MultiDecodeType naar de bijbehorende instantie. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


Initialiseert een nieuw exemplaar van de [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Array van enkele decode‑typen |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


Initialiseert een nieuw exemplaar van de [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array van multi‑ en enkele decode‑typen |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


Voegt nog één [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) toe aan de MultiDecodeType.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Een enkele DecodeType die aan de lijst moet worden toegevoegd |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Controleer of dit alle typen van barcodetypen bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Invoer enkele of meerdere barcode‑typen |

**Returns:**
boolean - Waarde is true als alle typen zijn opgenomen in
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Bevat het een van de typen?

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Decode‑typen |

**Returns:**
boolean - Waarde is true als een van de types is opgenomen.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | Een [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Retourneert een waarde die aangeeft of deze collectie decode‑typen alleen de opgegeven [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Een [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) waarde om te vergelijken met deze collectie decode‑typen. |

**Returns:**
boolean - **true** als deze collectie alleen het opgegeven decode‑type bevat; anders **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


Sluit [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) uit van de MultiDecodeType en retourneert een nieuwe MultiDecodeType‑instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Een enkele DecodeType die moet worden uitgesloten. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - New MultiDecodeType instance with excluded SingleDecodeType.
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


Stelt een lijst van enkele typen voor.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Lijst van enkele typen
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Retourneert een aantal enkele typen.

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


Overschreven methode die MultiDecodeType als een string weergeeft.

**Returns:**
java.lang.String - Een string die een MultiDecodeType‑instantie weergeeft als "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Converteert de tekenreeksrepresentatie van een BaseDecodeType naar zijn instantie, nadat het concrete type is bepaald. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string die een MultiDecodeType‑representatie bevat om te converteren. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

anders retourneert het een onbepaald type. of MultiDecodeType (\"None\").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Converteert de tekenreeksrepresentatie van een MultiDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string die een MultiDecodeType‑representatie bevat om te converteren. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

anders retourneert het een onbepaald type. of MultiDecodeType (\"None\").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string die een SingleDecodeType bevat in het formaat \"EAN8\" of \"EAN13\" of \"CodaBar\"... om te converteren. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

anders retourneert het een onbepaald type. of SingleDecodeType (-1, \"None\").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

