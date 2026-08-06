---
title: SwissQRBill
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Datos de factura SwissQR.
type: docs
weight: 36
url: /es/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

Datos de factura SwissQR.
## Methods

| Method | Descripción |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el objeto especificado es igual al objeto actual. |
| [getAccount()](#getAccount--) | Gets the creditor's account number. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Obtiene o establece los esquemas de pago alternativos. |
| [getAmount()](#getAmount--) | Obtiene el importe del pago. |
| [getBillInformation()](#getBillInformation--) | Obtiene la información estructurada adicional de la factura. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Obtiene la dirección del acreedor. |
| [getCurrency()](#getCurrency--) | Obtiene la moneda del pago. |
| [getDebtor()](#getDebtor--) | Obtiene la dirección del deudor. |
| [getReference()](#getReference--) | Obtiene la referencia de pago del acreedor. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Obtiene el mensaje no estructurado adicional. |
| [getVersion()](#getVersion--) | Obtiene la versión del estándar de factura SwissQR. |
| [hashCode()](#hashCode--) | Obtiene el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Establece el número de cuenta del acreedor. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Obtiene o establece los esquemas de pago alternativos. |
| [setAmount(double value)](#setAmount-double-) | Establece el importe del pago. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Establece la información estructurada adicional de la factura. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Establece la dirección del acreedor. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Establece la moneda del pago. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Establece la dirección del deudor. |
| [setReference(String value)](#setReference-java.lang.String-) | Establece la referencia de pago del acreedor. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Establece el mensaje no estructurado adicional. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Establece la versión del estándar de factura SwissQR. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum.

Se elimina el espacio en blanco de la referencia

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| rawReference | java.lang.String | La referencia cruda. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el objeto especificado es igual al objeto actual.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto para comparar con el objeto actual. |

**Returns:**
boolean -  true  si el objeto especificado es igual al objeto actual; de lo contrario,  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


Gets the creditor's account number.

Los números de cuenta deben ser IBAN válidos de un banco de Suiza o Liechtenstein. Se permiten espacios en el número de cuenta.

Valor: El número de cuenta del acreedor.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Obtiene o establece los esquemas de pago alternativos.

Se permite un máximo de dos esquemas con parámetros.

Valor: Los esquemas de pago alternativos.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Obtiene el importe del pago.

Los valores válidos están entre 0.01 y 999,999,999.99.

Valor: El importe del pago.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Obtiene la información estructurada adicional de la factura.

Valor: La información estructurada de la factura.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


Obtiene la dirección del acreedor.

Valor: La dirección del acreedor.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Obtiene la moneda del pago.

Los valores válidos son "CHF" y "EUR".

Valor: La moneda del pago.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Obtiene la dirección del deudor.

El deudor es opcional. Si se omite, tanto establecer este campo a  null  como establecer una dirección con todos los valores  null  o vacíos es aceptable.

Valor: La dirección del deudor.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Obtiene la referencia de pago del acreedor.

La referencia es obligatoria para los IBAN SwissQR, es decir, los IBAN en el rango CHxx30000xxxxxx hasta CHxx31999xxxxx.

Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente al formulario de referencia ISR) o una referencia de acreedor válida según ISO 11649 ("RFxxxx"). Ambas pueden contener espacios para el formato.

Valor: La referencia de pago del acreedor.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Obtiene el mensaje no estructurado adicional.

Valor: El mensaje no estructurado.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Obtiene la versión del estándar de factura SwissQR.

Valor: La versión del estándar de factura SwissQR.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash para esta instancia.

**Returns:**
int - Un código hash para el objeto actual.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


Establece el número de cuenta del acreedor.

Los números de cuenta deben ser IBAN válidos de un banco de Suiza o Liechtenstein. Se permiten espacios en el número de cuenta.

Valor: El número de cuenta del acreedor.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Obtiene o establece los esquemas de pago alternativos.

Se permite un máximo de dos esquemas con parámetros.

Valor: Los esquemas de pago alternativos.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Establece el importe del pago.

Los valores válidos están entre 0.01 y 999,999,999.99.

Valor: El importe del pago.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Establece la información estructurada adicional de la factura.

Valor: La información estructurada de la factura.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Establece la dirección del acreedor.

Valor: La dirección del acreedor.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Establece la moneda del pago.

Los valores válidos son "CHF" y "EUR".

Valor: La moneda del pago.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Establece la dirección del deudor.

El deudor es opcional. Si se omite, tanto establecer este campo a  null  como establecer una dirección con todos los valores  null  o vacíos es aceptable.

Valor: La dirección del deudor.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Establece la referencia de pago del acreedor.

La referencia es obligatoria para los IBAN SwissQR, es decir, los IBAN en el rango CHxx30000xxxxxx hasta CHxx31999xxxxx.

Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente al formulario de referencia ISR) o una referencia de acreedor válida según ISO 11649 ("RFxxxx"). Ambas pueden contener espacios para el formato.

Valor: La referencia de pago del acreedor.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Establece el mensaje no estructurado adicional.

Valor: El mensaje no estructurado.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Establece la versión del estándar de factura SwissQR.

Valor: La versión del estándar de factura SwissQR.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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

