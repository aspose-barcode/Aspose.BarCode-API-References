---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class. Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - Nulo o Prueba "1" - 1C (Minorista) "2" - 2C (Minorista) "3" - 3C (Minorista) "4" - Premium (Correo de Publicación Minorista) (para posible uso futuro) "5" - Diferido (Minorista) "6" - Aéreo (Minorista) (para posible uso futuro) "7" - Superficie (Minorista) (para posible uso futuro) "8" - Premium (Acceso a Red) "9" - Estándar (Acceso a Red) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | El PC y el DP deben cumplir con un formato PAF. Cadena de nueve caracteres que indica internacional "XY11     " (note los 5 espacios finales) o un patrón de caracteres que indica un código de clasificación doméstico. Un código de clasificación doméstico consta de un código postal externo, un código postal interno y un sufijo de punto de entrega. |
| [get_Format](./get_format/)() const | "0" – Nulo o Prueba "1" – Carta "2" – Carta Grande |
| [get_ItemID](./get_itemid/)() const | El valor máximo es 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | Los valores máximos son 99 para el código de barras C y 999999 para el código de barras L. |
| [get_VersionID](./get_versionid/)() const | Actualmente "1" – Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro) |
| [GetBarcodeType](./getbarcodetype/)() override | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construye el texto de código a partir de los datos de Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Inicializa los datos de Mailmark a partir del texto de código construido. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Inicializa una nueva instancia de la clase [MailmarkCodetext](./). |
| [set_Class](./set_class/)(System::String) | "0" - Nulo o Prueba "1" - 1C (Minorista) "2" - 2C (Minorista) "3" - 3C (Minorista) "4" - Premium (Correo de Publicación Minorista) (para posible uso futuro) "5" - Diferido (Minorista) "6" - Aéreo (Minorista) (para posible uso futuro) "7" - Superficie (Minorista) (para posible uso futuro) "8" - Premium (Acceso a Red) "9" - Estándar (Acceso a Red) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | El PC y el DP deben cumplir con un formato PAF. Cadena de nueve caracteres que indica internacional "XY11     " (note los 5 espacios finales) o un patrón de caracteres que indica un código de clasificación doméstico. Un código de clasificación doméstico consta de un código postal externo, un código postal interno y un sufijo de punto de entrega. |
| [set_Format](./set_format/)(int32_t) | "0" – Nulo o Prueba "1" – Carta "2" – Carta Grande |
| [set_ItemID](./set_itemid/)(int32_t) | El valor máximo es 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Los valores máximos son 99 para el código de barras C y 999999 para el código de barras L. |
| [set_VersionID](./set_versionid/)(int32_t) | Actualmente "1" – Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro) |
## Ver también

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
