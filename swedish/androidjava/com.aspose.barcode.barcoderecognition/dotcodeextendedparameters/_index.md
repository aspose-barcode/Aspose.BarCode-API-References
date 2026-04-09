---
title: DotCodeExtendedParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Lagrar speciella data för DotCode igenkänd streckkod
type: docs
weight: 33
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Lagrar speciella data för DotCode igenkänd streckkod

Detta exempel visar hur man får råvärden för DotCode.

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");

 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)-värde. |
| [getClass()](#getClass--) |  |
| [getDotCodeIsReaderInitialization()](#getDotCodeIsReaderInitialization--) | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Hämtar ID för DotCode strukturerade tilläggsläge streckkod. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Hämtar antalet DotCode strukturerade tilläggsläge streckkoder. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Hämtar ID för DotCode strukturerade tilläggsläge streckkod. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Hämtar antalet DotCode strukturerade tilläggsläge streckkoder. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isEmpty()](#isEmpty--) | Testar om alla parametrar endast har standardvärden |
| [isReaderInitialization()](#isReaderInitialization--) | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Returnerar ett värde som indikerar om det första [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)-värdet är lika med det andra. |
| [op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Returnerar ett värde som indikerar om det första [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)-värdet är annorlunda än det andra. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)-värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett System.Object‑värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDotCodeIsReaderInitialization() {#getDotCodeIsReaderInitialization--}
```
public final boolean getDotCodeIsReaderInitialization()
```


Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är false.

**Returns:**
boolean
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Hämtar ID för DotCode strukturerade tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1.

Värde: ID för DotCode strukturerade tilläggsläge streckkod.

**Returns:**
int - ID för DotCode strukturerade tilläggsläge streckkod.
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Hämtar antalet DotCode strukturerade tilläggsläge streckkoder. Standardvärdet är -1. Antalet måste vara ett värde mellan 1 och 35.

Värde: Antalet DotCode strukturerade tilläggsläge streckkod.

**Returns:**
int - antalet DotCode strukturerade tilläggsläge streckkoder.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Hämtar ID för DotCode strukturerade tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1.

Värde: ID för DotCode strukturerade tilläggsläge streckkod.

**Returns:**
int - ID för DotCode strukturerade tilläggsläge streckkod.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Hämtar antalet DotCode strukturerade tilläggsläge streckkoder. Standardvärdet är -1. Antalet måste vara ett värde mellan 1 och 35.

Värde: Antalet DotCode strukturerade tilläggsläge streckkod.

**Returns:**
int - antalet DotCode strukturerade tilläggsläge streckkoder.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Testar om alla parametrar endast har standardvärden

Värde: Returnerar  **true**  om alla parametrar endast har standardvärden; annars,  **false** .

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är false.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Returnerar ett värde som indikerar om det första [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)-värdet är lika med det andra.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Ett första jämfört värde |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Ett andra jämfört värde |

**Returns:**
boolean -  **true**  om första har samma värde som andra; annars,  **false** .
### op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Returnerar ett värde som indikerar om det första [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)-värdet är annorlunda än det andra.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Ett första jämfört värde |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Ett andra jämfört värde |

**Returns:**
boolean -  **true**  om första har ett annat värde än andra; annars,  **false** .
### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - En sträng som representerar detta [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).
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

