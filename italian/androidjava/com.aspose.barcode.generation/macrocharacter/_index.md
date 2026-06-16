---
title: MacroCharacter
second_title: Aspose.BarCode per Android via Java API Reference
description: I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali.
type: docs
weight: 94
url: /it/androidjava/com.aspose.barcode.generation/macrocharacter/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MacroCharacter extends Enum<MacroCharacter>
```

I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Il Macro character 05 è tradotto in "[)>05" come intestazione dei dati decodificati e "" come trailer dei dati decodificati. Il Macro character 06 è tradotto in "[)>06" come intestazione dei dati decodificati e "" come trailer dei dati decodificati.

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
## Campi

| Campo | Descrizione |
| --- | --- |
| [MACRO_05](#MACRO-05) | Il Macro character 05 è aggiunto ai dati del codice a barre nella prima posizione. |
| [MACRO_06](#MACRO-06) | 06 Macro craracter è aggiunto ai dati del codice a barre nella prima posizione. |
| [NONE](#NONE) | Nessun carattere macro è aggiunto ai dati del codice a barre |
## Methods

| Method | Descrizione |
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


05 Macro craracter è aggiunto ai dati del codice a barre nella prima posizione. GS1 Data Identifier ISO 15434 Character è tradotto in "[)>05" come intestazione dei dati decodificati e "" come trailer dei dati decodificati.

### MACRO_06 {#MACRO-06}
```
public static final MacroCharacter MACRO_06
```


06 Macro craracter è aggiunto ai dati del codice a barre nella prima posizione. ASC MH10 Data Identifier ISO 15434 Character è tradotto in "[)>06" come intestazione dei dati decodificati e "" come trailer dei dati decodificati.

### NONE {#NONE}
```
public static final MacroCharacter NONE
```


Nessun carattere macro è aggiunto ai dati del codice a barre

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static MacroCharacter fromValue(int value)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

