---
title: MultiDecodeType
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Composite‑Dekodierungstyp.
type: docs
weight: 37
url: /de/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

Composite‑Dekodierungstyp.

Dieses Beispiel zeigt, wie zusammengesetzte MultiDecode-Typen erstellt werden, die SingleDecodeType- und MultiDecode-Typen kombinieren.

```

```
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Initialisiert eine neue Instanz der Klasse MultiDecodeType. |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Initialisiert eine neue Instanz der Klasse MultiDecodeType. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Fügt einen weiteren [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) zum MultiDecodeType hinzu. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Prüfen, ob dies alle Typen aus den Barcode-Typen enthält. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Enthält irgendeinen Typ |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen MultiDecodeType-Wert entspricht. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Gibt einen Wert zurück, der angibt, ob diese Sammlung von Decodierungstypen nur den angegebenen [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)-Wert enthält. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen MultiDecodeType-Wert entspricht. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Schließt [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) vom MultiDecodeType aus und gibt eine neue MultiDecodeType-Instanz zurück. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Stellt eine Liste einzelner Typen dar. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Gibt die Anzahl einzelner Typen zurück. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Überschriebene Methode, die MultiDecodeType als Zeichenkette darstellt. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines BaseDecodeType in seine Instanz, nachdem der konkrete Typ ermittelt wurde. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


Initialisiert eine neue Instanz der Klasse MultiDecodeType.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Array einzelner Decodierungstypen |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


Initialisiert eine neue Instanz der Klasse MultiDecodeType.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array von Multi- und Einzel-Decodierungstypen |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


Fügt einen weiteren [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) zum MultiDecodeType hinzu.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ein Single DecodeType, der zur Liste hinzugefügt werden soll |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Prüfen, ob dies alle Typen aus den Barcode-Typen enthält.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Eingabe einzelner oder mehrerer Barcode-Typen |

**Returns:**
boolean – Der Wert ist true, wenn alle Typen enthalten sind.
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Enthält irgendeinen Typ

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Decodierungstypen |

**Returns:**
boolean – Der Wert ist true, wenn irgendein Typ eingeschlossen ist.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen MultiDecodeType-Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| andere | com.aspose.barcode.barcoderecognition.MultiDecodeType | Ein MultiDecodeType-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Gibt einen Wert zurück, der angibt, ob diese Sammlung von Decodierungstypen nur den angegebenen [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)-Wert enthält.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ein [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)-Wert zum Vergleich mit dieser Sammlung von Decodierungstypen. |

**Returns:**
boolean -  **true**  wenn diese Sammlung nur den angegebenen Decodetyp enthält; andernfalls **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen MultiDecodeType-Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


Schließt [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) vom MultiDecodeType aus und gibt eine neue MultiDecodeType-Instanz zurück.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ein einzelner DecodeType, der ausgeschlossen werden soll. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Neue MultiDecodeType-Instanz mit ausgeschlossenen SingleDecodeType.
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


Stellt eine Liste einzelner Typen dar.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Liste einzelner Typen
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Gibt die Anzahl einzelner Typen zurück.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
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


Überschriebene Methode, die MultiDecodeType als Zeichenkette darstellt.

**Returns:**
java.lang.String - Ein String, der eine MultiDecodeType-Instanz darstellt, z. B. \"singleDecodeType1, singleDecodeType2, ...\"

 **"AllSupportedTypes"**  returns when all types are included.
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

