---
title: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: 
type: docs
weight: 32
url: /nl/androidjava/com.aspose.barcode.generation/datamatrixextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DataMatrixExtCodetextBuilder extends ExtCodetextBuilder
```

Uitgebreide codetextgenerator voor 2D DataMatrix-streepjescodes voor de ExtendedCodetext-modus van EncodeMode.

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.BYTES, "World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DataMatrixExtCodetextBuilder()](#DataMatrixExtCodetextBuilder--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)](#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Voegt codetekst toe met gedefinieerde coderingsmodus aan de uitgebreide codetekstitems |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Voegt codetext toe met Extended Channel Identifier |
| [addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)](#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Voegt codetekst toe met Uitgebreide Kanaalidentificatie met gedefinieerde coderingsmodus |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Voegt platte codetext toe aan de uitgebreide codetext‑items |
| [clear()](#clear--) | Verwijdert uitgebreide codetext‑items |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genereert Extended codetext uit de uitgebreide codetext‑lijst. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataMatrixExtCodetextBuilder() {#DataMatrixExtCodetextBuilder--}
```
public DataMatrixExtCodetextBuilder()
```


### addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext) {#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)
```


Voegt codetekst toe met gedefinieerde coderingsmodus aan de uitgebreide codetekstitems

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Coderingsmoduswaarde |
| codetext | java.lang.String | Codetext in Unicode om toe te voegen als uitgebreid codetext‑item |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Voegt codetext toe met Extended Channel Identifier

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Codetext in Unicode om toe te voegen als uitgebreid codetext‑item met Extended Channel Identifier |

### addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext) {#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)
```


Voegt codetekst toe met Uitgebreide Kanaalidentificatie met gedefinieerde coderingsmodus

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Coderingsmoduswaarde |
| codetext | java.lang.String | Codetekst in Unicode om toe te voegen als uitgebreid codetekstitem met Uitgebreide Kanaalidentificatie met gedefinieerde coderingsmodus |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Voegt platte codetext toe aan de uitgebreide codetext‑items

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in Unicode om toe te voegen als uitgebreid codetext‑item |

### clear() {#clear--}
```
public void clear()
```


Verwijdert uitgebreide codetext‑items

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Genereert Extended codetext uit de uitgebreide codetext‑lijst.

**Returns:**
java.lang.String - Uitgebreide codetekst als string.
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

