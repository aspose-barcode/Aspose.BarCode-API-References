---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Generador de codetext extendido para códigos de barras MaxiCode en el modo ExtendedCodetext de MaxiCodeEncodeMode. Utilice la propiedad TwoDDisplayText de BarcodeGenerator para establecer el texto visible al eliminar caracteres de gestión."
type: docs
weight: 54
url: /es/java/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Generador de codetexto extendido para códigos de barras MaxiCode en modo ExtendedCodetext de MaxiCodeEncodeMode. Use la propiedad TwoDDisplayText de BarcodeGenerator para establecer el texto visible eliminando caracteres de gestión. Este ejemplo muestra cómo usar MaxiCodeExtCodetextBuilder en modo extendido.

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Añade codetext con Identificador de Canal Extendido |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Añade codetext simple a los elementos de codetext extendido |
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
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
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

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Añade codetext simple a los elementos de codetext extendido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codetext | java.lang.String | Codetext en unicode para agregar como elemento de texto de código extendido |

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

