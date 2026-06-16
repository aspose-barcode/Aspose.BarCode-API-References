---
title: MailmarkCodetext
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados.
type: docs
weight: 24
url: /es/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados.
## Constructors

| Constructor | Descripción |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Inicializa una nueva instancia de la clase  MailmarkCodetext . |
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Obtiene el tipo de código de barras. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Nulo o Prueba "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (para uso futuro potencial) "5" - Diferido (Retail) "6" - Aire (Retail) (para uso futuro potencial) "7" - Superficie (Retail) (para uso futuro potencial) "8" - Premium (Acceso a Red) "9" - Estándar (Acceso a Red) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construye el texto codificado a partir de los datos Mailmark. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | El PC y DP deben cumplir con un formato PAF. |
| [getFormat()](#getFormat--) | "0" \\u2013 Nulo o Prueba "1" \\u2013 Carta "2" \\u2013 Carta grande |
| [getItemID()](#getItemID--) | El valor máximo es 99999999. |
| [getSupplychainID()](#getSupplychainID--) | Los valores máximos son 99 para el código de barras C y 999999 para el código de barras L. |
| [getVersionID()](#getVersionID--) | Actualmente "1" \\u2013 Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inicializa los datos Mailmark a partir del texto codificado construido. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Nulo o Prueba "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (para uso futuro potencial) "5" - Diferido (Retail) "6" - Aire (Retail) (para uso futuro potencial) "7" - Superficie (Retail) (para uso futuro potencial) "8" - Premium (Acceso a Red) "9" - Estándar (Acceso a Red) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | El PC y DP deben cumplir con un formato PAF. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Nulo o Prueba "1" \\u2013 Carta "2" \\u2013 Carta grande |
| [setItemID(int value)](#setItemID-int-) | El valor máximo es 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Los valores máximos son 99 para el código de barras C y 999999 para el código de barras L. |
| [setVersionID(int value)](#setVersionID-int-) | Actualmente "1" \\u2013 Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Inicializa una nueva instancia de la clase  MailmarkCodetext .

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
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
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Nulo o Prueba "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (para uso futuro potencial) "5" - Diferido (Retail) "6" - Aire (Retail) (para uso futuro potencial) "7" - Superficie (Retail) (para uso futuro potencial) "8" - Premium (Acceso a Red) "9" - Estándar (Acceso a Red)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construye el texto codificado a partir de los datos Mailmark.

**Returns:**
java.lang.String - Codetext construido
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


El PC y DP deben cumplir con un formato PAF. Cadena de nueve caracteres que indica el internacional "XY11 " (nota los 5 espacios finales) o un patrón de caracteres que indica un código de clasificación doméstico. Un código de clasificación doméstico consta de un código postal externo, un código postal interno y un sufijo de punto de entrega.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Nulo o Prueba "1" \\u2013 Carta "2" \\u2013 Carta grande

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


El valor máximo es 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Los valores máximos son 99 para el código de barras C y 999999 para el código de barras L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


Actualmente "1" \\u2013 Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Inicializa los datos Mailmark a partir del texto codificado construido.

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




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Nulo o Prueba "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (para uso futuro potencial) "5" - Diferido (Retail) "6" - Aire (Retail) (para uso futuro potencial) "7" - Superficie (Retail) (para uso futuro potencial) "8" - Premium (Acceso a Red) "9" - Estándar (Acceso a Red)

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


El PC y DP deben cumplir con un formato PAF. Cadena de nueve caracteres que indica el internacional "XY11 " (nota los 5 espacios finales) o un patrón de caracteres que indica un código de clasificación doméstico. Un código de clasificación doméstico consta de un código postal externo, un código postal interno y un sufijo de punto de entrega.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Nulo o Prueba "1" \\u2013 Carta "2" \\u2013 Carta grande

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


El valor máximo es 99999999.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Los valores máximos son 99 para el código de barras C y 999999 para el código de barras L.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


Actualmente "1" \\u2013 Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro)

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

