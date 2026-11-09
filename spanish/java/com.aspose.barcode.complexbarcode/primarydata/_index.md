---
title: "PrimaryData"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Clase para almacenar los datos primarios de HIBC LIC."
type: docs
weight: 33
url: /es/java/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Clase para almacenar los datos primarios de HIBC LIC.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor de PrimaryData especificado. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifica la fecha del código de identificación del etiquetador. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifica el número de producto o catálogo. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifica el ID de unidad de medida. |
| [hashCode()](#hashCode--) | Devuelve el código hash de esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Instancia datos primarios a partir de una cadena según la especificación HIBC LIC. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifica la fecha del código de identificación del etiquetador. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifica el número de producto o catálogo. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifica el ID de unidad de medida. |
| [toString()](#toString--) | Convierte los datos al formato de cadena según la especificación HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor de PrimaryData especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor de PrimaryData para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


Identifica la fecha del código de identificación del etiquetador. El código de identificación del etiquetador debe ser una cadena alfanumérica de 4 símbolos, con el primer carácter siempre alfabético.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Identifica el número de producto o catálogo. El número de producto o catálogo debe ser una cadena alfanumérica de hasta 18 símbolos de longitud.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Identifica el ID de unidad de medida. El ID de unidad de medida debe ser un valor entero de 0 a 9.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash de esta instancia.

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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


Instancia datos primarios a partir de una cadena según la especificación HIBC LIC.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Cadena formateada. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Identifica la fecha del código de identificación del etiquetador. El código de identificación del etiquetador debe ser una cadena alfanumérica de 4 símbolos, con el primer carácter siempre alfabético.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Identifica el número de producto o catálogo. El número de producto o catálogo debe ser una cadena alfanumérica de hasta 18 símbolos de longitud.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Identifica el ID de unidad de medida. El ID de unidad de medida debe ser un valor entero de 0 a 9.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### toString() {#toString--}
```
public String toString()
```


Convierte los datos al formato de cadena según la especificación HIBC LIC.

**Returns:**
java.lang.String - Cadena formateada.
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

