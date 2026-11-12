---
title: "QREncodeType"
linktitle: "QREncodeType"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Modo selector QR / MicroQR."
type: docs
weight: 490
url: /es/nodejs/global/qrencodetype/
---

## QREncodeType

Modo selector QR / MicroQR. Seleccione FORCE_QR para símbolos QR estándar, AUTO para MicroQR. FORCE_MICRO_QR se utiliza para la generación de símbolos MicroQR de forma estricta si es posible.

## Valores

| Nombre | Descripción |
| --- | --- |
| AUTO | El modo inicia la negociación de versión de código de barras desde MicroQR V1 |
| FORCE_QR | El modo inicia la negociación de versión de código de barras desde QR V1 |
| FORCE_MICRO_QR | El modo inicia la negociación de versión del código de barras desde MicroQR V1 hasta V4. Si los datos no pueden codificarse en MicroQR, se lanza una excepción. |
