---
title: DotCodeExtCodetextBuilder
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: 
type: docs
weight: 35
url: /es/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Generador de codetexto extendido para códigos de barras 2D DotCode en el modo ExtendedCodetext de DotCodeEncodeMode.

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

| Constructor | Descripción |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Adds codetext with Extended Channel Identifier |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Agrega el identificador de formato FNC1 a los elementos de codetexto extendido. |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Agrega la inicialización del lector FNC3 a los elementos de codetexto extendido. |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Agrega el separador de símbolo FNC3 a los elementos de codetexto extendido. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Agrega texto de código simple a los elementos de texto de código extendido |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Agrega el modo de anexado estructurado a los elementos de codetexto extendido. |
| [clear()](#clear--) | Elimina los elementos de texto de código extendido |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genera texto de código extendido a partir de la lista de texto de código extendido. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Comprueba la necesidad de proteger el elemento anterior con "\\000000" |
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


Adds codetext with Extended Channel Identifier

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| Codificación ECI | int | Identificador de Canal Extendido |
| texto de código | java.lang.String | Texto de código en Unicode para agregar como elemento de texto de código extendido con Identificador de Canal Extendido |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public void addFNC1FormatIdentifier()
```


Agrega el identificador de formato FNC1 a los elementos de codetexto extendido.

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public void addFNC3ReaderInitialization()
```


Agrega la inicialización del lector FNC3 a los elementos de codetexto extendido.

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public void addFNC3SymbolSeparator()
```


Agrega el separador de símbolo FNC3 a los elementos de codetexto extendido.

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Agrega texto de código simple a los elementos de texto de código extendido

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| texto de código | java.lang.String | Texto de código en Unicode para agregar como elemento de texto de código extendido |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Agrega el modo de anexado estructurado a los elementos de codetexto extendido.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| barcodeId | int | ID del código de barras |
| barcodesCount | int | Cantidad de códigos de barras |

### clear() {#clear--}
```
public void clear()
```


Elimina los elementos de texto de código extendido

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
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


Genera texto de código extendido a partir de la lista de texto de código extendido.

**Returns:**
java.lang.String - Texto de código extendido como cadena
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


Comprueba la necesidad de proteger el elemento anterior con "\\000000"

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| Índice | int | Índice en m\_List |

**Returns:**
boolean - Necesidad de proteger
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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

