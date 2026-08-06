---
title: Mailmark2DCodetext
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark.
type: docs
weight: 23
url: /es/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark.
## Constructors

| Constructor | Descripción |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Crea una instancia predeterminada de la clase Mailmark2DCodetext. |
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Obtiene el tipo de código de barras. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construye el texto codificado a partir de los datos Mailmark. |
| [getCustomerContent()](#getCustomerContent--) | Espacio opcional para uso del cliente. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Modo de codificación del código de barras Datamatrix. |
| [getDataMatrixType()](#getDataMatrixType--) | El tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. |
| [getItemID()](#getItemID--) | Identifica el elemento único dentro del ID de la cadena de suministro. |
| [getRTSFlag()](#getRTSFlag--) | Indicador que muestra qué nivel de servicio de Devolución al Remitente se está solicitando. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Contiene el código postal de Devolución al Remitente pero sin DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifica el grupo único de clientes involucrados en el envío. |
| [getUPUCountryID()](#getUPUCountryID--) | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
| [getVersionID()](#getVersionID--) | Identifica la versión del código de barras según cada ID de tipo de información. |
| [getclass()](#getclass--) | Identifica la clase del artículo. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inicializa los datos Mailmark a partir del texto codificado construido. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Espacio opcional para uso del cliente. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Modo de codificación del código de barras Datamatrix. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | El tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. |
| [setItemID(int value)](#setItemID-int-) | Identifica el elemento único dentro del ID de la cadena de suministro. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Indicador que muestra qué nivel de servicio de Devolución al Remitente se está solicitando. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Contiene el código postal de Devolución al Remitente pero sin DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifica el grupo único de clientes involucrados en el envío. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Identifica la versión del código de barras según cada ID de tipo de información. |
| [setclass(String value)](#setclass-java.lang.String-) | Identifica la clase del artículo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Crea una instancia predeterminada de la clase Mailmark2DCodetext.

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
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construye el texto codificado a partir de los datos Mailmark.

**Returns:**
java.lang.String - Codetext construido
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Espacio opcional para uso del cliente. Longitud máxima por tipo: Tipo 7: 6 caracteres Tipo 9: 45 caracteres Tipo 29: 25 caracteres

**Returns:**
java.lang.String - Contenido del cliente
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Modo de codificación del código de barras Datamatrix. Valor predeterminado: DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


El tipo 2D Mailmark define el tamaño del código de barras Data Matrix.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres. Área (1 o 2 caracteres) Distrito (1 o 2 caracteres) Sector (1 carácter) Unidad (2 caracteres) DPS (2 caracteres). El código postal y el DPS deben cumplir con un formato PAF® válido.

**Returns:**
java.lang.String - el código postal de la dirección de entrega con DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. Valores válidos: '0' - Doméstico clasificado y no clasificado 'A' - Envío en línea 'B' - Franqueo 'C' - Consolidación

**Returns:**
java.lang.String - ID de tipo de información
### getItemID() {#getItemID--}
```
public int getItemID()
```


Identifica el artículo único dentro del ID de la cadena de suministro. Cada código de barras Mailmark debe llevar un ID para poder ser identificado de forma única durante al menos 90 días. Valor máximo: 99999999.

**Returns:**
int - artículo dentro del ID de la cadena de suministro
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Indicador que muestra qué nivel de servicio de Devolución al Remitente se está solicitando.

**Returns:**
java.lang.String - Indicador RTS
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Contiene el código postal de Devolución al Remitente pero sin DPS. El CP (sin DPS) debe cumplir con un formato PAF®.

**Returns:**
java.lang.String - Código postal de Devolución al Remitente pero sin DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999.

**Returns:**
int - ID de cadena de suministro
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Identifica el ID de país UPU. Longitud máxima: 4 caracteres.

**Returns:**
java.lang.String - ID de país
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Identifica la versión del código de barras según cada ID de tipo de información. Valores válidos: Actualmente '1'. '0' y del '2' al '9' y de la 'A' a la 'Z' reservados para uso futuro potencial.

**Returns:**
java.lang.String - ID de versión
### getclass() {#getclass--}
```
public String getclass()
```


Identifica la clase del artículo. Valores válidos: '1' - 1C (Minorista) '2' - 2C (Minorista) '3' - Económica (Minorista) '5' - Diferida (Minorista) '8' - Premium (Acceso a red) '9' - Estándar (Acceso a red)

**Returns:**
java.lang.String - clase del artículo
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




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


Espacio opcional para uso del cliente. Longitud máxima por tipo: Tipo 7: 6 caracteres Tipo 9: 45 caracteres Tipo 29: 25 caracteres

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.C40.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Modo de codificación del código de barras Datamatrix. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


El tipo 2D Mailmark define el tamaño del código de barras Data Matrix.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres. Área (1 o 2 caracteres) Distrito (1 o 2 caracteres) Sector (1 carácter) Unidad (2 caracteres) DPS (2 caracteres). El código postal y el DPS deben cumplir con un formato PAF® válido.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. Valores válidos: '0' - Doméstico clasificado y no clasificado 'A' - Envío en línea 'B' - Franqueo 'C' - Consolidación

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Identifica el artículo único dentro del ID de la cadena de suministro. Cada código de barras Mailmark debe llevar un ID para poder ser identificado de forma única durante al menos 90 días. Valor máximo: 99999999.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Indicador que muestra qué nivel de servicio de Devolución al Remitente se está solicitando.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Contiene el código postal de Devolución al Remitente pero sin DPS. El CP (sin DPS) debe cumplir con un formato PAF®.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Identifica el ID de país UPU. Longitud máxima: 4 caracteres.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Identifica la versión del código de barras según cada ID de tipo de información. Valores válidos: Actualmente '1'. '0' y del '2' al '9' y de la 'A' a la 'Z' reservados para uso futuro potencial.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Identifica la clase del artículo. Valores válidos: '1' - 1C (Minorista) '2' - 2C (Minorista) '3' - Económica (Minorista) '5' - Diferida (Minorista) '8' - Premium (Acceso a red) '9' - Estándar (Acceso a red)

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String | class of the item |

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

