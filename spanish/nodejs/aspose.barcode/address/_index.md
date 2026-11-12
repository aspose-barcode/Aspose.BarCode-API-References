---
title: "Dirección"
linktitle: "Dirección"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Dirección del acreedor o deudor."
type: docs
weight: 10
url: /es/nodejs/aspose.barcode/address/
---

## Address class

Dirección del acreedor o deudor. Puede establecer la calle, el número de casa, el código postal y la localidad (tipo dirección estructurada) o la línea de dirección 1 y 2 (tipo elementos de dirección combinados). El tipo se establece automáticamente una vez que cualquiera de estos campos se completa. Antes de establecer los campos, el tipo de dirección es indeterminado. Si se establecen campos de ambos tipos, el tipo de dirección pasa a ser conflictivo. El nombre y el código de país deben estar siempre establecidos a menos que todos los campos estén vacíos.

```js
new Address()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [clear()](#clear) | Borra todos los campos y establece el tipo a AddressType.UNDETERMINED. |
| [equals(obj)](#equals) | Determina si el objeto especificado es igual al objeto actual. |
| [getAddressLine1()](#getaddressline1) | Obtiene la línea de dirección 1. La línea de dirección 1 contiene el nombre de la calle, el número de casa o el apartado de correos. Establecer este campo define la dir |
| [getAddressLine2()](#getaddressline2) | Obtiene la línea de dirección 2. La línea de dirección 2 contiene el código postal y la localidad. Establecer este campo define el tipo de dirección a Addre |
| [getCountryCode()](#getcountrycode) | Obtiene el código de país ISO de dos letras. El código de país es obligatorio a menos que toda la dirección contenga valores nulos o vacíos |
| [getHouseNo()](#gethouseno) | Obtiene el número de casa. Establecer este campo define el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressTyp |
| [getName()](#getname) | Obtiene el nombre, ya sea el nombre y apellido de una persona física o el nombre de la empresa de una entidad jurídica. |
| [getPostalCode()](#getpostalcode) | Obtiene el código postal. Establecer este campo define el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType |
| [getStreet()](#getstreet) | Obtiene la calle. La calle debe especificarse sin número de casa. Establecer este campo define el tipo de dirección a AddressT |
| [getTown()](#gettown) | Obtiene la localidad o ciudad. Establecer este campo define el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressTyp |
| [getType()](#gettype) | Obtiene el tipo de dirección. El tipo de dirección se establece automáticamente al establecer la calle / número de casa o la línea de dirección 1 a |
| [hashCode()](#hashcode) | Obtiene el código hash de esta instancia. |
| [setAddressLine1(value:)](#setaddressline1) | Establece la línea de dirección 1. La línea de dirección 1 contiene el nombre de la calle, el número de casa o el apartado de correos. Establecer este campo define la dir |
| [setAddressLine2(value:)](#setaddressline2) | Establece la línea de dirección 2. La línea de dirección 2 contiene el código postal y la ciudad. Establecer este campo establece el tipo de dirección a Addre |
| [setCountryCode(value)](#setcountrycode) | Establece el código de país ISO de dos letras. El código de país es obligatorio a menos que toda la dirección contenga valores nulos o vacíos val |
| [setHouseNo(value:)](#sethouseno) | Establece el número de casa. Establecer este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressTyp |
| [setName(value:)](#setname) | Establece el nombre, ya sea el nombre y apellido de una persona natural o el nombre de la empresa de una persona jurídica. |
| [setPostalCode(value)](#setpostalcode) | Establece el código postal. Establecer este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType |
| [setStreet(value:)](#setstreet) | Establece la calle. La calle debe especificarse sin número de casa. Establecer este campo establece el tipo de dirección a AddressT |
| [setTown(value)](#settown) | Establece la localidad o ciudad. Establecer este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressTyp |

### clear() {#clear}

Borra todos los campos y establece el tipo a AddressType.UNDETERMINED.

### equals(obj) {#equals}

Determina si el objeto especificado es igual al objeto actual.

| Parámetro | Descripción |
| --- | --- |
| obj | El objeto a comparar con el objeto actual. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

Obtiene la línea de dirección 1. La línea de dirección 1 contiene el nombre de la calle, número de casa o apartado postal. Establecer este campo establece el tipo de dirección a AddressType.COMBINED_ELEMENTS a menos que ya sea AddressType.STRUCTURED, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones de elementos combinados y es opcional.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

Obtiene la línea de dirección 2. La línea de dirección 2 contiene el código postal y la ciudad. Establecer este campo establece el tipo de dirección a AddressType.COMBINED_ELEMENTS a menos que ya sea AddressType.STRUCTURED, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones de elementos combinados. Para este tipo, es obligatorio.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

Obtiene el código de país ISO de dos letras. El código de país es obligatorio a menos que toda la dirección contenga valores nulos o vacíos.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

Obtiene el número de casa. Establecer este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType.COMBINED_ELEMENTS, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones estructuradas y es opcional.

**Returns:** The house number.

### getName() {#getname}

Obtiene el nombre, ya sea el nombre y apellido de una persona física o el nombre de la empresa de una entidad jurídica.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

Obtiene el código postal. Establecer este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType.COMBINED_ELEMENTS, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

**Returns:** The postal code.

### getStreet() {#getstreet}

Obtiene la calle. La calle debe especificarse sin número de casa. Establecer este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType.COMBINED_ELEMENTS, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones estructuradas y es opcional.

**Returns:** The street.

### getTown() {#gettown}

Obtiene la localidad o ciudad. Establecer este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType.COMBINED_ELEMENTS, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

**Returns:** The town or city.

### getType() {#gettype}

Obtiene el tipo de dirección. El tipo de dirección se establece automáticamente al configurar la calle / número de casa o la línea de dirección 1 y 2. Antes de configurar los campos, el tipo de dirección es Undetermined. Si se configuran campos de ambos tipos, el tipo de dirección se vuelve Conflicting.

**Returns:** The address type.

### hashCode() {#hashcode}

Obtiene el código hash de esta instancia.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

Establece la línea de dirección 1. La línea de dirección 1 contiene el nombre de la calle, número de casa o apartado postal. Establecer este campo establece el tipo de dirección a AddressType.COMBINED_ELEMENTS a menos que ya sea AddressType.STRUCTURED, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones de elementos combinados y es opcional.

| Parámetro | Descripción |
| --- | --- |
| valor: | La línea de dirección 1. |

### setAddressLine2(value:) {#setaddressline2}

Establece la línea de dirección 2. La línea de dirección 2 contiene el código postal y la ciudad. Establecer este campo establece el tipo de dirección a AddressType.COMBINED_ELEMENTS a menos que ya sea AddressType.STRUCTURED, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones de elementos combinados. Para este tipo, es obligatorio.

| Parámetro | Descripción |
| --- | --- |
| valor: | La línea de dirección 2. |

### setCountryCode(value) {#setcountrycode}

Establece el código de país ISO de dos letras. El código de país es obligatorio a menos que toda la dirección contenga valores nulos o vacíos.

| Parámetro | Descripción |
| --- | --- |
| valor | El código de país ISO. |

### setHouseNo(value:) {#sethouseno}

Establece el número de casa. Configurar este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType.COMBINED_ELEMENTS, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones estructuradas y es opcional.

| Parámetro | Descripción |
| --- | --- |
| valor: | El número de casa. |

### setName(value:) {#setname}

Establece el nombre, ya sea el nombre y apellido de una persona natural o el nombre de la empresa de una persona jurídica.

| Parámetro | Descripción |
| --- | --- |
| valor: | El nombre. |

### setPostalCode(value) {#setpostalcode}

Establece el código postal. Configurar este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType.COMBINED_ELEMENTS, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

| Parámetro | Descripción |
| --- | --- |
| valor | El código postal. |

### setStreet(value:) {#setstreet}

Establece la calle. La calle debe especificarse sin número de casa. Configurar este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType.COMBINED_ELEMENTS, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones estructuradas y es opcional.

| Parámetro | Descripción |
| --- | --- |
| valor: | La calle. |

### setTown(value) {#settown}

Establece la localidad o ciudad. Configurar este campo establece el tipo de dirección a AddressType.STRUCTURED a menos que ya sea AddressType.COMBINED_ELEMENTS, en cuyo caso se convierte en AddressType.CONFLICTING. Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.

| Parámetro | Descripción |
| --- | --- |
| valor | La localidad o ciudad. |
