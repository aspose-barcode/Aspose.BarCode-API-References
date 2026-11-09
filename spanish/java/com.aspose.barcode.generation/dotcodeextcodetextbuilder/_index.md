---
title: "DotCodeExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: 
type: docs
weight: 33
url: /es/java/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Generador de texto codificado extendido para códigos de barras 2D DotCode en el modo ExtendedCodetext de DotCodeEncodeMode

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
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Añade codetext con Identificador de Canal Extendido |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Agrega el identificador de formato FNC1 a los elementos de texto codificado extendido |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Agrega la inicialización del lector FNC3 a los elementos de texto codificado extendido |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Agrega el separador de símbolo FNC3 a los elementos de texto codificado extendido |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Añade codetext simple a los elementos de codetext extendido |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Agrega el modo de anexado estructurado a los elementos de texto codificado extendido |
| [clear()](#clear--) | Borra los elementos de codetext extendido |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genera codetext extendido a partir de la lista de codetext extendido. |
| [hashCode()](#hashCode--) |  |
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
public final void addECICodetext(int ECIEncoding, String codetext)
```


Añade codetext con Identificador de Canal Extendido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ECIEncoding | int | Identificador de Canal Extendido |
| codetext | java.lang.String | Codetext en unicode para añadir como elemento de codetext extendido con Identificador de Canal Extendido |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


Agrega el identificador de formato FNC1 a los elementos de texto codificado extendido

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


Agrega la inicialización del lector FNC3 a los elementos de texto codificado extendido

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


Agrega el separador de símbolo FNC3 a los elementos de texto codificado extendido

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Añade codetext simple a los elementos de codetext extendido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codetext | java.lang.String | Codetext en unicode para agregar como elemento de texto de código extendido |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Agrega el modo de anexado estructurado a los elementos de texto codificado extendido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| barcodeId | int | ID del código de barras |
| barcodesCount | int | Cantidad de códigos de barras |

### clear() {#clear--}
```
public void clear()
```


Borra los elementos de codetext extendido

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Genera codetext extendido a partir de la lista de codetext extendido.

**Returns:**
java.lang.String - Texto de código extendido como cadena
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

