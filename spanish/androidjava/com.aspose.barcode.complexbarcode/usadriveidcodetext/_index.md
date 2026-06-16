---
title: USADriveIdCodetext
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Clase para codificar y decodificar el texto incrustado en el código PDF417 de la Licencia de Conducir de EE. UU.
type: docs
weight: 38
url: /es/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

Clase para codificar y decodificar el texto incrustado en el código PDF417 de la Licencia de Conducir de EE. UU.
## Constructors

| Constructor | Descripción |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | Constructor predeterminado |
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | Número de versión AAMVA 00-99 |
| [getBarcodeType()](#getBarcodeType--) | Devuelve el tipo de código de barras de USA DL (Pdf417). |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construir codetext a partir de los datos de USA DL. |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | Este número identifica de forma única la jurisdicción emisora y puede obtenerse contactando a la Autoridad emisora ISO (AAMVA). |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | Campos específicos de la jurisdicción |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | Número de versión de la jurisdicción 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | Elementos obligatorios (campos) de la tarjeta. |
| [getNumberOfEntries()](#getNumberOfEntries--) | Número 00-99 de subarchivos |
| [getOptionalElements()](#getOptionalElements--) | Elementos opcionales (campos) de la tarjeta |
| [getSubfileDesignator()](#getSubfileDesignator--) | Contiene información sobre los siguientes subarchivos, tipos, desplazamientos y longitudes. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inicializar el objeto USA DL a partir del codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | Guarda en XML. |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | Número de versión AAMVA 00-99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | Este número identifica de forma única la jurisdicción emisora y puede obtenerse contactando a la Autoridad emisora ISO (AAMVA). |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | Campos específicos de la jurisdicción |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | Número de versión de la jurisdicción 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | Elementos obligatorios (campos) de la tarjeta. |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | Número 00-99 de subarchivos |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | Elementos opcionales (campos) de la tarjeta |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | Contiene información sobre los siguientes subarchivos, tipos, desplazamientos y longitudes. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


Constructor predeterminado

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
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


Número de versión AAMVA 00-99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Devuelve el tipo de código de barras de USA DL (Pdf417).

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


Construir codetext a partir de los datos de USA DL.

**Returns:**
java.lang.String - Codetext construido
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


Este número identifica de forma única la jurisdicción emisora y puede obtenerse contactando a la Autoridad emisora ISO (AAMVA). El IIN completo de 6 dígitos debe codificarse.

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


Campos específicos de la jurisdicción

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


Número de versión de la jurisdicción 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


Elementos obligatorios (campos) de la tarjeta.

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


Número 00-99 de subarchivos

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


Elementos opcionales (campos) de la tarjeta

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


Contiene información sobre los siguientes subarchivos, tipos, desplazamientos y longitudes. Importante: establezca solo el tipo, el desplazamiento y la longitud se establecerán automáticamente.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


Inicializar el objeto USA DL a partir del codetext.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Texto de código construido |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


Guarda en XML.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | Secuencia para guardar |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


Número de versión AAMVA 00-99

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


Este número identifica de forma única la jurisdicción emisora y puede obtenerse contactando a la Autoridad emisora ISO (AAMVA). El IIN completo de 6 dígitos debe codificarse.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


Campos específicos de la jurisdicción

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


Número de versión de la jurisdicción 00-99

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


Elementos obligatorios (campos) de la tarjeta.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


Número 00-99 de subarchivos

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


Elementos opcionales (campos) de la tarjeta

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


Contiene información sobre los siguientes subarchivos, tipos, desplazamientos y longitudes. Importante: establezca solo el tipo, el desplazamiento y la longitud se establecerán automáticamente.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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

