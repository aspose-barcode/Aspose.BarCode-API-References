---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Utökad kodtextgenerator för MaxiCode-streckkoder för ExtendedCodetext‑läge i MaxiCodeEncodeMode. Använd egenskapen TwoDDisplayText i BarcodeGenerator för att ange synlig text genom att ta bort hanterande tecken."
type: docs
weight: 54
url: /sv/androidjava/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Utökad kodtextgenerator för MaxiCode-streckkoder för ExtendedCodetext-läget i MaxiCodeEncodeMode. Använd TwoDDisplayText-egenskapen i BarcodeGenerator för att ange synlig text genom att ta bort styrtecken. Detta exempel visar hur man använder MaxiCodeExtCodetextBuilder i Extended-läget.

```
//create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Lägger till kodtext med Extended Channel Identifier |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| [clear()](#clear--) | Rensar utökade kodtextobjekt |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genererar utökad kodtext från den utökade kodtextlistan. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Lägger till kodtext med Extended Channel Identifier

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ECIEncoding | int | Utökad kanalidentifierare |
| kodtext | java.lang.String | Kodtext i Unicode för att lägga till som utökad kodtextpost med Utökad kanalidentifierare |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Lägger till vanlig kodtext till de utökade kodtextobjekten

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kodtext | java.lang.String | Kodtext i Unicode för att lägga till som utökad kodtextpost |

### clear() {#clear--}
```
public void clear()
```


Rensar utökade kodtextobjekt

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Genererar utökad kodtext från den utökade kodtextlistan.

**Returns:**
java.lang.String - Utökad kodtext som sträng
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

