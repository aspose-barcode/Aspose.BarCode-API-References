---
title: MacroCharacter
second_title: Aspose.BarCode for Android via Java API-referentie
description: Macro‑tekens 05 en 06-waarden worden gebruikt om compactere codering te verkrijgen in speciale modi.
type: docs
weight: 94
url: /nl/androidjava/com.aspose.barcode.generation/macrocharacter/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MacroCharacter extends Enum<MacroCharacter>
```

Macro‑tekens 05 en 06 worden gebruikt om compactere codering te verkrijgen in speciale modi. Macro‑teken 05 wordt vertaald naar "[)>05" als gedecodeerde gegevensheader en "" als gedecodeerde gegevenstrailer. Macro‑teken 06 wordt vertaald naar "[)>06" als gedecodeerde gegevensheader en "" als gedecodeerde gegevenstrailer.

```
hese samples show how to encode Macro Characters in MicroPdf417 and DataMatrix
 

 //to generate autoidentified GS1 message like this "(10)123ABC(10)123ABC" in ISO 15434 format you need:
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "10123ABC10123ABC");
 generator.getParameters().getBarcode().getDataMatrix().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS1DataMatrix);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println("BarCode CodeText: " + result.getCodeText());

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println(result.getCodeText());
```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [MACRO_05](#MACRO-05) | Macro‑teken 05 wordt toegevoegd aan de barcode‑gegevens op de eerste positie. |
| [MACRO_06](#MACRO-06) | 06 Macro‑karakter is toegevoegd aan de barcode‑gegevens op de eerste positie. |
| [NONE](#NONE) | Er worden geen Macro‑karakters toegevoegd aan de barcode‑gegevens. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MACRO_05 {#MACRO-05}
```
public static final MacroCharacter MACRO_05
```


05 Macro‑karakter is toegevoegd aan de barcode‑gegevens op de eerste positie. GS1‑gegevensidentificatie ISO 15434‑karakter wordt vertaald naar "[)>05" als gedecodeerde gegevensheader en "" als gedecodeerde gegevenstrailer.

### MACRO_06 {#MACRO-06}
```
public static final MacroCharacter MACRO_06
```


06 Macro‑karakter is toegevoegd aan de barcode‑gegevens op de eerste positie. ASC MH10‑gegevensidentificatie ISO 15434‑karakter wordt vertaald naar "[)>06" als gedecodeerde gegevensheader en "" als gedecodeerde gegevenstrailer.

### NONE {#NONE}
```
public static final MacroCharacter NONE
```


Er worden geen Macro‑karakters toegevoegd aan de barcode‑gegevens.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static MacroCharacter fromValue(int value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MacroCharacter valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### values() {#values--}
```
public static MacroCharacter[] values()
```




**Returns:**
com.aspose.barcode.generation.MacroCharacter[]
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

