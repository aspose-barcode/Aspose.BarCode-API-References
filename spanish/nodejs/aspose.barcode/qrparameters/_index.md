---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Parámetros QR."
type: docs
weight: 830
url: /es/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

Parámetros QR.

```js
new QrParameters()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Relación altura/ancho del módulo de código de barras 2D. |
| [getECIEncoding()](#geteciencoding) | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para códigos QR y RectMicroQR |
| [getEncodeMode()](#getencodemode) | Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Nivel de corrección de errores Reed-Solomon para códigos QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | Versión del código MicroQR. Desde la versión M1 hasta la versión M4. Valor predeterminado: MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para |
| [getQrEncodeMode()](#getqrencodemode) | Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | Modo selector QR / MicroQR. Seleccione ForceQR para símbolos QR estándar, Auto para MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Nivel de corrección de errores Reed-Solomon para códigos QR. De bajo a alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. ver QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Versión del código QR. Desde Version1 hasta Version40 para códigos QR y desde M1 hasta M4 para MicroQr. Valor predeterminado: QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. Valor predeterminado: RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | Parámetros de QR structured append. |
| [getVersion()](#getversion) | Versión del código QR. Desde Version1 hasta Version40. Valor predeterminado: QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Relación altura/ancho del módulo de código de barras 2D. |
| [setECIEncoding()](#seteciencoding) | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para códigos QR y RectMicroQR |
| [setEncodeMode()](#setencodemode) | Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Nivel de corrección de errores Reed-Solomon para códigos QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | Versión del código MicroQR. Desde la versión M1 hasta la versión M4. Valor predeterminado: MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | Modo selector QR / MicroQR. Seleccione ForceQR para símbolos QR estándar, Auto para MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Nivel de corrección de errores Reed-Solomon para códigos QR. De bajo a alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. ver QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Versión del código QR. Desde Version1 hasta Version40 para códigos QR y desde M1 hasta M4 para MicroQr. Valor predeterminado: QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. Valor predeterminado: RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | Parámetros de QR structured append. |
| [setVersion()](#setversion) | Versión del código QR. Desde Version1 hasta Version40. Valor predeterminado: QRVersion.Auto. |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este QrParameters. |

### getAspectRatio() {#getaspectratio}

Relación altura/ancho del módulo de código de barras 2D.

### getECIEncoding() {#geteciencoding}

Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. No compatible con MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para códigos QR y RectMicroQR. Si es false, los separadores GS1 pueden codificarse como '%' en modo alfanumérico según la especificación QR. Si es true, los separadores de grupo GS1 se codifican en modo Byte como el carácter 0x1D, y los caracteres '%' también se codifican en modo Byte para preservarlos como datos. Esta opción puede mejorar la compatibilidad con decodificadores que esperan separadores de grupo GS1 a nivel de byte y evita que los caracteres de datos '%' se interpreten como separadores GS1.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Nivel de corrección de errores Reed-Solomon para códigos QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. Ver QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Versión del código MicroQR. Desde la versión M1 hasta la versión M4. Valor predeterminado: MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual consiste en todas las codificaciones de conjuntos de caracteres bien conocidas.

### getQrEncodeMode() {#getqrencodemode}

Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

Modo selector QR / MicroQR. Seleccione ForceQR para símbolos QR estándar, Auto para MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Nivel de corrección de errores Reed-Solomon para códigos QR. De bajo a alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. ver QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Versión del código QR. Desde Version1 hasta Version40 para códigos QR y desde M1 hasta M4 para MicroQr. Valor predeterminado: QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. Valor predeterminado: RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

Parámetros de QR structured append.

### getVersion() {#getversion}

Versión del código QR. Desde Version1 hasta Version40. Valor predeterminado: QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Relación altura/ancho del módulo de código de barras 2D.

### setECIEncoding() {#seteciencoding}

Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. No compatible con MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Obtiene o establece un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para códigos QR y RectMicroQR. Si es false, los separadores GS1 pueden codificarse como '%' en modo alfanumérico según la especificación QR. Si es true, los separadores de grupo GS1 se codifican en modo Byte como el carácter 0x1D, y los caracteres '%' también se codifican en modo Byte para preservarlos como datos. Esta opción puede mejorar la compatibilidad con decodificadores que esperan separadores de grupo GS1 a nivel de byte y evita que los caracteres de datos '%' se interpreten como separadores GS1.

| Parámetro | Descripción |
| --- | --- |
| valor | un valor que indica si los caracteres especiales GS1 deben codificarse en modo Byte para códigos QR y RectMicroQR. |

### setEncodeMode() {#setencodemode}

Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Nivel de corrección de errores Reed-Solomon para códigos QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. Ver QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Versión del código MicroQR. Desde la versión M1 hasta la versión M4. Valor predeterminado: MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual consiste en todas las codificaciones de conjuntos de caracteres bien conocidas.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

Tipo de simbología QR del modo de codificación de BarCode. Valor predeterminado: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

Modo selector QR / MicroQR. Seleccione ForceQR para símbolos QR estándar, Auto para MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Nivel de corrección de errores Reed-Solomon para códigos QR. De bajo a alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. ver QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Versión del código QR. Desde Version1 hasta Version40 para códigos QR y desde M1 hasta M4 para MicroQr. Valor predeterminado: QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Versión del código RectMicroQR. Desde la versión R7x59 hasta la versión R17x139. Valor predeterminado: RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

Parámetros de QR structured append.

### setVersion() {#setversion}

Versión del código QR. Desde Version1 hasta Version40. Valor predeterminado: QRVersion.Auto.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este QrParameters.

**Returns:** A string that represents this QrParameters.
