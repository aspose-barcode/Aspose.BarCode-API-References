---
title: SecondaryAndAdditionalData
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Clase para almacenar datos secundarios y adicionales HIBC LIC.
type: docs
weight: 35
url: /es/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

Clase para almacenar datos secundarios y adicionales HIBC LIC.
## Constructors

| Constructor | Descripción |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de  SecondaryAndAdditionalData . |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Identifica la fecha de fabricación. |
| [getExpiryDate()](#getExpiryDate--) | Identifica la fecha de caducidad. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifica el formato de la fecha de caducidad. |
| [getLotNumber()](#getLotNumber--) | Identifica el número de lote o de partida. |
| [getQuantity()](#getQuantity--) | Identifica la cantidad, debe ser un valor entero de 0 a 500. |
| [getSerialNumber()](#getSerialNumber--) | Identifica el número de serie. |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | Instancia datos suplementarios secundarios y adicionales a partir de una cadena según la especificación HIBC LIC. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Identifica la fecha de fabricación. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Identifica la fecha de caducidad. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Identifica el formato de la fecha de caducidad. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifica el número de lote o de partida. |
| [setQuantity(int value)](#setQuantity-int-) | Identifica la cantidad, debe ser un valor entero de 0 a 500. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifica el número de serie. |
| [toString()](#toString--) | Convierte los datos a formato de cadena según la especificación HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de  SecondaryAndAdditionalData .

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor de  SecondaryAndAdditionalData  para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Valor predeterminado: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Identifica la fecha de caducidad. Se usará si ExpiryDateFormat no está establecido en None.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Identifica el formato de la fecha de caducidad.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Identifica el número de lote o de partida. El número de lote/partida debe ser una cadena alfanumérica con una longitud máxima de 18 símbolos.

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos de longitud.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


Instancia datos suplementarios secundarios y adicionales a partir de una cadena según la especificación HIBC LIC.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | Cadena formateada. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Valor predeterminado: DateTime.MinValue

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Identifica la fecha de caducidad. Se usará si ExpiryDateFormat no está establecido en None.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Identifica el formato de la fecha de caducidad.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Identifica el número de lote o de partida. El número de lote/partida debe ser una cadena alfanumérica con una longitud máxima de 18 símbolos.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos de longitud.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Convierte los datos a formato de cadena según la especificación HIBC LIC.

**Returns:**
java.lang.String - Cadena formateada.
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

