---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Elementos obligatorios (campos) de la tarjeta"
type: docs
weight: 590
url: /es/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

Elementos obligatorios (campos) de la tarjeta

```js
new MandatoryFields()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, porción de ciudad de la dirección del titular de la tarjeta, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, porción de código postal de la dirección del titular de la tarjeta en EE. UU. y Canadá. Si la porción final del código postal en |
| [getAddressState()](#getaddressstate) | DAJ, porción de estado de la dirección del titular de la tarjeta, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, País en el que se emite el DL/ID. EE. UU. = USA, Canadá = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, El número asignado o calculado por la autoridad emisora, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, Fecha en la que se emitió el documento, MMDDCCYY para EE. UU., CCYYMMDD para Canadá, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, El número debe identificar de forma única un documento específico emitido a ese cliente de entre otros que puedan haber sido emitidos i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, Códigos de endoso específicos de la jurisdicción, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, Color de los ojos del titular de la tarjeta. (códigos ANSI D-20). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, Apellido del titular de la tarjeta, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado |
| [getFirstName()](#getfirstname) | DAC, Nombre del titular de la tarjeta, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado |
| [getHeight()](#getheight) | DAU, Altura del titular de la tarjeta. Pulgadas (in): número de pulgadas seguido de " in" ej. 6'1'' = "073 in" Centímetros (cm): número |
| [getMiddleName()](#getmiddlename) | DAD, Segundo(s) nombre(s) del titular de la tarjeta. En caso de varios segundos nombres deberán separarse con una coma ",". , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, Códigos de restricciones específicos de la jurisdicción, DL, V12ANS |
| [getSex()](#getsex) | DBC, Género del titular de la tarjeta. 1 = masculino, 2 = femenino, 9 = no especificado, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, Código de clase / grupo de vehículo específico de la jurisdicción, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, porción de ciudad de la dirección del titular de la tarjeta, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, porción de código postal de la dirección del titular de la tarjeta en EE. UU. y Canadá. Si la porción final del código postal en |
| [setAddressState()](#setaddressstate) | DAJ, porción de estado de la dirección del titular de la tarjeta, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, País en el que se emite el DL/ID. EE. UU. = USA, Canadá = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, El número asignado o calculado por la autoridad emisora, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, Fecha en la que se emitió el documento, MMDDCCYY para EE. UU., CCYYMMDD para Canadá, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, El número debe identificar de forma única un documento específico emitido a ese cliente de entre otros que puedan haber sido emitidos i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, Códigos de endoso específicos de la jurisdicción, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, Color de los ojos del titular de la tarjeta. (códigos ANSI D-20). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, Apellido del titular de la tarjeta, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado |
| [setFirstName()](#setfirstname) | DAC, Nombre del titular de la tarjeta, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado |
| [setHeight()](#setheight) | DAU, Altura del titular de la tarjeta. Pulgadas (in): número de pulgadas seguido de " in" ej. 6'1'' = "073 in" Centímetros (cm): número |
| [setMiddleName()](#setmiddlename) | DAD, Segundo(s) nombre(s) del titular de la tarjeta. En caso de varios segundos nombres deberán separarse con una coma ",". , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, Códigos de restricciones específicos de la jurisdicción, DL, V12ANS |
| [setSex()](#setsex) | DBC, Género del titular de la tarjeta. 1 = masculino, 2 = femenino, 9 = no especificado, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, Código de clase / grupo de vehículo específico de la jurisdicción, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, porción de ciudad de la dirección del titular de la tarjeta, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, Porción del código postal de la dirección del titular de la tarjeta en EE. UU. y Canadá. Si la parte final del código postal en EE. UU. no se conoce, se usarán ceros para completar el conjunto final de números hasta 9 dígitos, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, porción de estado de la dirección del titular de la tarjeta, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, País en el que se emite el DL/ID. EE. UU. = USA, Canadá = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, El número asignado o calculado por la autoridad emisora, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, Fecha en la que se emitió el documento, MMDDCCYY para EE. UU., CCYYMMDD para Canadá, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, El número debe identificar de forma única un documento específico emitido a ese cliente entre otros que puedan haber sido emitidos en el pasado. Este número puede servir para múltiples propósitos de discriminación de documentos, número de información de auditoría y/o control de inventario, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, Códigos de endoso específicos de la jurisdicción, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, Color de los ojos del titular de la tarjeta. (códigos ANSI D-20). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, Apellido del titular de la tarjeta, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, Nombre del titular de la tarjeta, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, Altura del titular de la tarjeta. Pulgadas (in): número de pulgadas seguido de " in" ej. 6'1'' = "073 in" Centímetros (cm): número de centímetros seguido de " cm" ej. 181 centímetros = "181 cm" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, Segundo(s) nombre(s) del titular de la tarjeta. En caso de varios segundos nombres deberán separarse con una coma ",". , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, Códigos de restricciones específicos de la jurisdicción, DL, V12ANS

### getSex() {#getsex}

DBC, Género del titular de la tarjeta. 1 = masculino, 2 = femenino, 9 = no especificado, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, Código de clase / grupo de vehículo específico de la jurisdicción, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, porción de ciudad de la dirección del titular de la tarjeta, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, Porción del código postal de la dirección del titular de la tarjeta en EE. UU. y Canadá. Si la parte final del código postal en EE. UU. no se conoce, se usarán ceros para completar el conjunto final de números hasta 9 dígitos, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, porción de estado de la dirección del titular de la tarjeta, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, porción de calle de la dirección del titular de la tarjeta, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, País en el que se emite el DL/ID. EE. UU. = USA, Canadá = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, El número asignado o calculado por la autoridad emisora, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, Fecha en la que se emitió el documento, MMDDCCYY para EE. UU., CCYYMMDD para Canadá, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, El número debe identificar de forma única un documento específico emitido a ese cliente entre otros que puedan haber sido emitidos en el pasado. Este número puede servir para múltiples propósitos de discriminación de documentos, número de información de auditoría y/o control de inventario, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, Códigos de endoso específicos de la jurisdicción, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, Color de los ojos del titular de la tarjeta. (códigos ANSI D-20). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, Apellido del titular de la tarjeta, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, Nombre del titular de la tarjeta, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, Altura del titular de la tarjeta. Pulgadas (in): número de pulgadas seguido de " in" ej. 6'1'' = "073 in" Centímetros (cm): número de centímetros seguido de " cm" ej. 181 centímetros = "181 cm" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, Segundo(s) nombre(s) del titular de la tarjeta. En caso de varios segundos nombres deberán separarse con una coma ",". , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, Un código que indica si un campo ha sido truncado (T), no ha sido truncado (N), o se desconoce si está truncado (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, Códigos de restricciones específicos de la jurisdicción, DL, V12ANS

### setSex() {#setsex}

DBC, Género del titular de la tarjeta. 1 = masculino, 2 = femenino, 9 = no especificado, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, Código de clase / grupo de vehículo específico de la jurisdicción, DL, V6ANS
