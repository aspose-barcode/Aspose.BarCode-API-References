---
title: Address
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Dirección del acreedor o deudor.
type: docs
weight: 10
url: /es/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Dirección del acreedor o deudor.

You can either set street, house number, postal code and town (type  *structured address* ) or address line 1 and 2 (type  *combined address elements* ). The type is automatically set once any of these fields is set. Before setting the fields, the address type is  *undetermined* . If fields of both types are set, the address type becomes  *conflicting* . Name and country code must always be set unless all fields are empty.
## Constructors

| Constructor | Descripción |
| --- | --- |
| [Address()](#Address--) | Creates instance of Address |
## Methods

| Method | Descripción |
| --- | --- |
| [clear()](#clear--) | Borra todos los campos y establece el tipo a  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el objeto especificado es igual al objeto actual. |
| [getAddressLine1()](#getAddressLine1--) | Obtiene la línea de dirección 1. |
| [getAddressLine2()](#getAddressLine2--) | Obtiene la línea de dirección 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Obtiene el código de país ISO de dos letras. |
| [getHouseNo()](#getHouseNo--) | Obtiene el número de casa. |
| [getName()](#getName--) | Obtiene el nombre, ya sea el nombre y apellido de una persona física o el nombre de la empresa de una persona jurídica. |
| [getPostalCode()](#getPostalCode--) | Obtiene el código postal. |
| [getStreet()](#getStreet--) | Obtiene la calle. |
| [getTown()](#getTown--) | Obtiene la ciudad o pueblo. |
| [getType()](#getType--) | Obtiene el tipo de dirección. |
| [hashCode()](#hashCode--) | Obtiene el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Establece la línea de dirección 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Establece la línea de dirección 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Establece el código de país ISO de dos letras. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Establece el número de casa. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre, ya sea el nombre y apellido de una persona física o el nombre de la empresa de una persona jurídica. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Establece el código postal. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Establece la calle. |
| [setTown(String value)](#setTown-java.lang.String-) | Establece la ciudad o pueblo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Creates instance of Address

### clear() {#clear--}
```
public void clear()
```


Borra todos los campos y establece el tipo a  AddressType.Undetermined .

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
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Obtiene la línea de dirección 1.

Línea de dirección 1 contiene el nombre de la calle, número de casa o apartado postal.

Establecer este campo establece el tipo de dirección a  AddressType.CombinedElements  a menos que ya sea  AddressType.Structured , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones de elementos combinados y es opcional.

Valor: La línea de dirección 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Obtiene la línea de dirección 2.

Línea de dirección 2 contiene el código postal y la ciudad.

Establecer este campo establece el tipo de dirección a  AddressType.CombinedElements  a menos que ya sea  AddressType.Structured , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones de elementos combinados. Para este tipo, es obligatorio.

Valor: La línea de dirección 2.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


Obtiene el código de país ISO de dos letras.

El código de país es obligatorio a menos que toda la dirección contenga  null  o valores emtpy.

Valor: El código de país ISO.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Obtiene el número de casa.

Establecer este campo asigna el tipo de dirección a  AddressType.Structured  a menos que ya sea  AddressType.CombinedElements , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones estructuradas y es opcional.

Valor: El número de casa.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre, ya sea el nombre y apellido de una persona física o el nombre de la empresa de una persona jurídica.

Valor: El nombre.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Obtiene el código postal.

Establecer este campo asigna el tipo de dirección a  AddressType.Structured  a menos que ya sea  AddressType.CombinedElements , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

Valor: El código postal.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Obtiene la calle.

La calle debe especificarse sin número de casa.

Establecer este campo asigna el tipo de dirección a  AddressType.Structured  a menos que ya sea  AddressType.CombinedElements , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones estructuradas y es opcional.

Valor: La calle.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Obtiene la ciudad o pueblo.

Establecer este campo asigna el tipo de dirección a  AddressType.Structured  a menos que ya sea  AddressType.CombinedElements , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

Valor: La localidad o ciudad.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Obtiene el tipo de dirección.

El tipo de dirección se establece automáticamente al configurar la calle / número de casa o la línea de dirección 1 y 2. Antes de configurar los campos, el tipo de dirección es  *Undetermined* . Si se configuran campos de ambos tipos, el tipo de dirección se vuelve  *Conflicting* .

Valor: El tipo de dirección.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
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




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


Establece la línea de dirección 1.

Línea de dirección 1 contiene el nombre de la calle, número de casa o apartado postal.

Establecer este campo establece el tipo de dirección a  AddressType.CombinedElements  a menos que ya sea  AddressType.Structured , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones de elementos combinados y es opcional.

Valor: La línea de dirección 1.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Establece la línea de dirección 2.

Línea de dirección 2 contiene el código postal y la ciudad.

Establecer este campo establece el tipo de dirección a  AddressType.CombinedElements  a menos que ya sea  AddressType.Structured , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones de elementos combinados. Para este tipo, es obligatorio.

Valor: La línea de dirección 2.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Establece el código de país ISO de dos letras.

El código de país es obligatorio a menos que toda la dirección contenga  null  o valores emtpy.

Valor: El código de país ISO.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Establece el número de casa.

Establecer este campo asigna el tipo de dirección a  AddressType.Structured  a menos que ya sea  AddressType.CombinedElements , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones estructuradas y es opcional.

Valor: El número de casa.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre, ya sea el nombre y apellido de una persona física o el nombre de la empresa de una persona jurídica.

Valor: El nombre.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Establece el código postal.

Establecer este campo asigna el tipo de dirección a  AddressType.Structured  a menos que ya sea  AddressType.CombinedElements , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

Valor: El código postal.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Establece la calle.

La calle debe especificarse sin número de casa.

Establecer este campo asigna el tipo de dirección a  AddressType.Structured  a menos que ya sea  AddressType.CombinedElements , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones estructuradas y es opcional.

Valor: La calle.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Establece la ciudad o pueblo.

Establecer este campo asigna el tipo de dirección a  AddressType.Structured  a menos que ya sea  AddressType.CombinedElements , en cuyo caso se convierte en  AddressType.Conflicting .

Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

Valor: La localidad o ciudad.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

