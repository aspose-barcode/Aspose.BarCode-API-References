---
title: "MaxiCodeStandardCodetext"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Clase para codificar y decodificar el codetext MaxiCode para los modos 4, 5 y 6."
type: docs
weight: 29
url: /es/java/com.aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public class MaxiCodeStandardCodetext extends MaxiCodeCodetext
```

Clase para codificar y decodificar el texto del código MaxiCode para los modos 4, 5 y 6.

```
//Mode 4
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 5
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_5);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 6
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_6);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MaxiCodeStandardCodetext()](#MaxiCodeStandardCodetext--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor MaxiCodeStandardCodetext especificado. |
| [getBarcodeType()](#getBarcodeType--) | Obtiene el tipo de código de barras. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construye el texto del código. |
| [getECIEncoding()](#getECIEncoding--) | Obtiene la codificación ECI. |
| [getEncodeMode()](#getEncodeMode--) | Obtiene un modo de codificación MaxiCode. |
| [getMessage()](#getMessage--) | Obtiene el mensaje. |
| [getMode()](#getMode--) | Obtiene el modo MaxiCode. |
| [hashCode()](#hashCode--) | Devuelve el código hash de esta instancia. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inicializa la instancia a partir del texto del código construido. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Establece la codificación ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Establece un modo de codificación MaxiCode. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Establece el mensaje. |
| [setMode(MaxiCodeMode mode)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | Establece el modo MaxiCode. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStandardCodetext() {#MaxiCodeStandardCodetext--}
```
public MaxiCodeStandardCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor MaxiCodeStandardCodetext especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor MaxiCodeStandardCodetext para comparar con esta instancia. |

**Returns:**
boolean - si obj tiene el mismo valor que esta instancia; de lo contrario, **false**.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Obtiene el tipo de código de barras.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construye el texto del código.

**Returns:**
java.lang.String - Texto de código construido
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Obtiene la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1

**Returns:**
int - codificación ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Obtiene un modo de codificación MaxiCode. Valor predeterminado: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMessage() {#getMessage--}
```
public String getMessage()
```


Obtiene el mensaje.

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public MaxiCodeMode getMode()
```


Obtiene el modo MaxiCode.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash de esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Inicializa la instancia a partir del texto del código construido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Texto de código construido. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Codificación ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Establece un modo de codificación MaxiCode. Valor predeterminado: Auto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | un modo de codificación MaxiCode. |

### setMessage(String value) {#setMessage-java.lang.String-}
```
public void setMessage(String value)
```


Establece el mensaje.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setMode(MaxiCodeMode mode) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public void setMode(MaxiCodeMode mode)
```


Establece el modo MaxiCode. El codetext estándar solo puede usarse con los modos 4, 5 y 6.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) |  |

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

