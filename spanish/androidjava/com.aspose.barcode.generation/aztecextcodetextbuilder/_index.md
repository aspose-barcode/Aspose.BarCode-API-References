---
title: "AztecExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Android mediante Java"
description: 
type: docs
weight: 11
url: /es/androidjava/com.aspose.barcode.generation/aztecextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class AztecExtCodetextBuilder extends ExtCodetextBuilder
```

Generador de texto de código extendido para códigos de barras Aztec para el modo ExtendedCodetext de AztecEncodeMode.

Utilice la propiedad TwoDDisplayText de BarcodeGenerator para establecer el texto visible al eliminar los caracteres de gestión.

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AztecExtCodetextBuilder()](#AztecExtCodetextBuilder--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Agrega codetext con Extended Channel Identifier |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Agrega texto de código simple a los elementos de texto de código extendido |
| [clear()](#clear--) | Elimina los elementos de texto de código extendido |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genera texto de código extendido a partir de la lista de texto de código extendido. |
| [hashCode()](#hashCode--) |  |
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
public final void addECICodetext(int ECIEncoding, String codetext)
```


Agrega codetext con Extended Channel Identifier

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| Codificación ECI | int | Identificador de Canal Extendido |
| texto de código | java.lang.String | Texto de código en Unicode para agregar como elemento de texto de código extendido con Identificador de Canal Extendido |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Agrega texto de código simple a los elementos de texto de código extendido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto de código | java.lang.String | Texto de código en Unicode para agregar como elemento de texto de código extendido |

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


Genera texto de código extendido a partir de la lista de texto de código extendido.

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

