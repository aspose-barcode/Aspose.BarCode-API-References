---
title: MaxiCodeStructuredCodetext
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Clase base para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2 y 3.
type: docs
weight: 32
url: /es/androidjava/com.aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public abstract class MaxiCodeStructuredCodetext extends MaxiCodeCodetext
```

Clase base para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2 y 3. Este ejemplo muestra cómo decodificar el codetexto bruto de MaxiCode a una instancia de MaxiCodeStructuredCodetext.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for (BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
      {
          MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
      }
  }
```
## Constructors

| Constructor | Descripción |
| --- | --- |
| [MaxiCodeStructuredCodetext()](#MaxiCodeStructuredCodetext--) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de MaxiCodeStructuredCodetext. |
| [getBarcodeType()](#getBarcodeType--) | Obtiene el tipo de código de barras. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construye codetext |
| [getCountryCode()](#getCountryCode--) | Identifica el código de país de 3 dígitos. |
| [getECIEncoding()](#getECIEncoding--) | Obtiene la codificación ECI. |
| [getEncodeMode()](#getEncodeMode--) | Obtiene un modo de codificación MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Obtiene un modo de codificación MaxiCode. |
| [getMode()](#getMode--) | Obtiene el modo MaxiCode. |
| [getPostalCode()](#getPostalCode--) | Identifica el código postal. |
| [getSecondMessage()](#getSecondMessage--) | Identifica el segundo mensaje del código de barras. |
| [getServiceCategory()](#getServiceCategory--) | Identifica la categoría de servicio de 3 dígitos. |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inicializa la instancia a partir del codetext construido. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | Identifica el código de país de 3 dígitos. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Establece la codificación ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Establece un modo de codificación MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Establece un modo de codificación MaxiCode. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Identifica el código postal. |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Identifica el segundo mensaje del código de barras. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | Identifica la categoría de servicio de 3 dígitos. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStructuredCodetext() {#MaxiCodeStructuredCodetext--}
```
public MaxiCodeStructuredCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de MaxiCodeStructuredCodetext.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor de MaxiCodeStructuredCodetext para comparar con esta instancia |

**Returns:**
boolean - **true** si obj tiene el mismo valor que esta instancia; de lo contrario, **false**
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


Construye codetext

**Returns:**
java.lang.String - Codetext construido
### getCountryCode() {#getCountryCode--}
```
public int getCountryCode()
```


Identifica el código de país de 3 dígitos.

**Returns:**
int
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
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Obtiene un modo de codificación MaxiCode. Valor predeterminado: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract int getMode()
```


Obtiene el modo MaxiCode.

**Returns:**
int - modo MaxiCode
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o 6 símbolos alfanuméricos en el modo 3.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public MaxiCodeSecondMessage getSecondMessage()
```


Identifica el segundo mensaje del código de barras.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public int getServiceCategory()
```


Identifica la categoría de servicio de 3 dígitos.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Inicializa la instancia a partir del codetext construido.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Codetext construido. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCountryCode(int value) {#setCountryCode-int-}
```
public void setCountryCode(int value)
```


Identifica el código de país de 3 dígitos.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int | Codificación ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Establece un modo de codificación MaxiCode. Valor predeterminado: Auto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | un modo de codificación MaxiCode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Establece un modo de codificación MaxiCode. Valor predeterminado: Auto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | un modo de codificación MaxiCode. |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o 6 símbolos alfanuméricos en el modo 3.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public void setSecondMessage(MaxiCodeSecondMessage value)
```


Identifica el segundo mensaje del código de barras.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public void setServiceCategory(int value)
```


Identifica la categoría de servicio de 3 dígitos.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

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

