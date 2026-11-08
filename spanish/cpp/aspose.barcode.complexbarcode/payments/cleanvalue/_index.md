---
title: "método"
linktitle: "CleanValue"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Limpia un valor de cadena para hacerlo viable según los Swiss Payment Standards 2018 en C++."
type: docs
weight: 100
url: /es/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Limpia un valor de cadena para que sea viable para los estándares de pago suizos 2018.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | System::String | El valor de cadena a limpiar. |
| result | Payments::CleaningResult\& | El resultado que se llenará con la cadena limpiada y la bandera. |
## Observaciones


Los caracteres no compatibles(según Swiss Payment Standards 2018, ch. 2.4.1 y apéndice D) se reemplazan por espacios(espacios en blanco no compatibles) o puntos (todos los demás caracteres no compatibles). Los espacios en blanco iniciales y finales se eliminan.

Si se detectan caracteres más allá de 0xff, la cadena se normaliza primero de modo que las letras con diéresis o acentos expresadas con dos puntos de código se fusionen en un solo punto de código(si es posible), algunos de los cuales podrían volverse válidos.

Si la cadena resultante es todo espacio en blanco, **null** es devuelto.

## Ver también

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
