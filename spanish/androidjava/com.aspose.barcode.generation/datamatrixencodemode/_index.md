---
title: "DataMatrixEncodeMode"
second_title: "Referencia de API de Aspose.BarCode para Android mediante Java"
description: "El modo de codificación de los codificadores DataMatrix es Auto por defecto"
type: docs
weight: 82
url: /es/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

Modo de codificación del codificador DataMatrix, por defecto Auto

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Campos

| Campo | Descripción |
| --- | --- |
| [ANSIX12](#ANSIX12) | Utiliza codificación ANSI X12. |
| [ASCII](#ASCII) | Codifica un carácter alfanumérico o dos caracteres numéricos por byte |
| [AUTO](#AUTO) | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. |
| [BASE_256](#BASE-256) | Codificar valores de 8 bits |
| [BINARY](#BINARY) | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. |
| [C40](#C40) | Utiliza codificación C40. |
| [ECI](#ECI) | En modo ECI, todo el mensaje se vuelve a codificar con la codificación especificada por ECIEncoding mediante la inserción de un identificador ECI. |
| [EDIFACT](#EDIFACT) | Utiliza codificación EDIFACT. |
| [EXTENDED](#EXTENDED) | El modo ExtendedCodetext permite cambiar manualmente los esquemas de codificación y las codificaciones ECI en el texto de código. |
| [TEXT](#TEXT) | Utiliza codificación de texto. |
## Métodos

| Método | Descripción |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


Utiliza codificación ANSI X12.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Codifica un carácter alfanumérico o dos caracteres numéricos por byte

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se vuelven a codificar con la codificación especificada por ECIEncoding mediante la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Codificar valores de 8 bits

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción.

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Utiliza codificación C40. Codifica alfanuméricos en mayúsculas, minúsculas y caracteres especiales.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


En modo ECI, todo el mensaje se vuelve a codificar con la codificación especificada por ECIEncoding mediante la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no ser compatibles con este modo.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Utiliza codificación EDIFACT. Usa seis bits por carácter, codifica dígitos, letras mayúsculas y muchos signos de puntuación, pero no admite letras minúsculas.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


El modo ExtendedCodetext permite cambiar manualmente los esquemas de codificación y las codificaciones ECI en el texto de código. Es mejor usar DataMatrixExtCodetextBuilder para la generación de texto de código extendido. Use la propiedad Display2DText para establecer el texto visible al eliminar los caracteres de gestión. Los identificadores ECI se establecen como una barra diagonal única y un identificador de seis dígitos \"\\000026\" - identificador ECI UTF8. Todos los caracteres Unicode después del identificador ECI se codifican automáticamente en el conjunto de códigos de caracteres correcto. Los esquemas de codificación se establecen en el siguiente formato: \"\\Encodation\\_scheme\\_name:text\\Encodation\\_scheme\\_name:text\". Los esquemas de codificación permitidos son: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Todas las barras invertidas (\\) deben duplicarse en el texto.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Utiliza codificación de texto. Codifica alfanuméricos en minúsculas, mayúsculas y caracteres especiales.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static DataMatrixEncodeMode fromValue(int value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

