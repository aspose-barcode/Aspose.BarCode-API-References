---
title: DotCodeExtCodetextBuilder
second_title: Aspose.BarCode for Android via Java API-referentie
description: 
type: docs
weight: 35
url: /nl/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Uitgebreide codetekstgenerator voor 2D DotCode barcodes voor de ExtendedCodetext-modus van DotCodeEncodeMode.

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  	   generator.save("test.bmp");
>  }
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Voegt codetext toe met Extended Channel Identifier |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Voegt FNC1-formaatidentificatie toe aan de uitgebreide codetekstitems. |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Voegt FNC3-lezerinitialisatie toe aan de uitgebreide codetekstitems. |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Voegt FNC3-symboolscheidingsteken toe aan de uitgebreide codetekstitems. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Voegt platte codetekst toe aan de uitgebreide codetekstitems |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Voegt gestructureerde toevoegingsmodus toe aan de uitgebreide codetekstitems. |
| [clear()](#clear--) | Leegt uitgebreide codetekstitems |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genereert uitgebreide codetekst vanuit de uitgebreide codetekstlijst. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Controleert de noodzaak om het vorige item te beschermen met "\\000000" |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Voegt codetext toe met Extended Channel Identifier

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ECIEncoding | int | Uitgebreide kanaalidentificatie |
| codetekst | java.lang.String | Codetekst in Unicode om toe te voegen als uitgebreid codetekstitem met Uitgebreide kanaalidentificatie |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public void addFNC1FormatIdentifier()
```


Voegt FNC1-formaatidentificatie toe aan de uitgebreide codetekstitems.

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public void addFNC3ReaderInitialization()
```


Voegt FNC3-lezerinitialisatie toe aan de uitgebreide codetekstitems.

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public void addFNC3SymbolSeparator()
```


Voegt FNC3-symboolscheidingsteken toe aan de uitgebreide codetekstitems.

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Voegt platte codetekst toe aan de uitgebreide codetekstitems

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codetekst | java.lang.String | Codetekst in Unicode om toe te voegen als uitgebreid codetekstitem |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Voegt gestructureerde toevoegingsmodus toe aan de uitgebreide codetekstitems.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| barcodeId | int | ID van barcode |
| barcodesCount | int | Aantal barcodes |

### clear() {#clear--}
```
public void clear()
```


Leegt uitgebreide codetekstitems

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


Genereert uitgebreide codetekst vanuit de uitgebreide codetekstlijst.

**Returns:**
java.lang.String - Uitgebreide codetekst als string
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


Controleert de noodzaak om het vorige item te beschermen met "\\000000"

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Index | int | Index in m\_List |

**Returns:**
boolean - Noodzaak om te beschermen
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

