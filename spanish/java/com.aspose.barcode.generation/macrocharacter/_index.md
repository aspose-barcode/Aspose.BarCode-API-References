---
title: "MacroCharacter"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Los valores de Macro Characters 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales."
type: docs
weight: 92
url: /es/java/com.aspose.barcode.generation/macrocharacter/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MacroCharacter extends Enum<MacroCharacter>
```

Los valores de los Caracteres Macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. El carácter Macro 05 se traduce a "[)>05" como encabezado de datos decodificados y "" como pie de datos decodificados. El carácter Macro 06 se traduce a "[)>06" como encabezado de datos decodificados y "" como pie de datos decodificados.

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
## Campos

| Campo | Descripción |
| --- | --- |
| [MACRO_05](#MACRO-05) | El carácter Macro 05 se agrega a los datos del código de barras en la primera posición. |
| [MACRO_06](#MACRO-06) | El carácter Macro 06 se agrega a los datos del código de barras en la primera posición. |
| [NONE](#NONE) | Ninguno de los Caracteres Macro se agrega a los datos del código de barras |
## Métodos

| Método | Descripción |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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


El carácter Macro 05 se agrega a los datos del código de barras en la primera posición. El carácter Identificador de Datos GS1 ISO 15434 se traduce a "[)>05" como encabezado de datos decodificados y "" como pie de datos decodificados.

### MACRO_06 {#MACRO-06}
```
public static final MacroCharacter MACRO_06
```


El carácter Macro 06 se agrega a los datos del código de barras en la primera posición. El carácter Identificador de Datos ASC MH10 ISO 15434 se traduce a "[)>06" como encabezado de datos decodificados y "" como pie de datos decodificados.

### NONE {#NONE}
```
public static final MacroCharacter NONE
```


Ninguno de los Caracteres Macro se agrega a los datos del código de barras

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static MacroCharacter fromValue(int value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

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
public final native void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

