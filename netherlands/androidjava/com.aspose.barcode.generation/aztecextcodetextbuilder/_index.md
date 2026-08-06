---
title: AztecExtCodetextBuilder
second_title: Aspose.BarCode for Android via Java API-referentie
description: 
type: docs
weight: 11
url: /nl/androidjava/com.aspose.barcode.generation/aztecextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class AztecExtCodetextBuilder extends ExtCodetextBuilder
```

Uitgebreide codetextgenerator voor Aztec-barcode voor de ExtendedCodetext-modus van AztecEncodeMode

Gebruik de TwoDDisplayText‑eigenschap van BarcodeGenerator om zichtbare tekst in te stellen door beheer‑tekens te verwijderen.

--------------------

> ```
> This sample shows how to use AztecExtCodetextBuilder in Extended Mode.
>  
>  //create codetext
>  AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
>  generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>  generator.save("test.bmp");
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AztecExtCodetextBuilder()](#AztecExtCodetextBuilder--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Voegt codetext toe met Extended Channel Identifier |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Voegt platte codetekst toe aan de uitgebreide codetekstitems |
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
### AztecExtCodetextBuilder() {#AztecExtCodetextBuilder--}
```
public AztecExtCodetextBuilder()
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

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Voegt platte codetekst toe aan de uitgebreide codetekstitems

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codetekst | java.lang.String | Codetekst in Unicode om toe te voegen als uitgebreid codetekstitem |

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

