---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill clase"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill clase. Datos de factura SwissQR en C++."
type: docs
weight: 2700
url: /es/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


Datos de factura SwissQR

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Crea y establece una referencia de acreedor ISO11649 a partir de una cadena cruda añadiendo el prefijo "RF" a la cadena y el checksum módulo 97. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determina si el objeto especificado es igual al objeto actual. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Determina si la factura especificada es igual a la factura actual. |
| [get_Account](./get_account/)() const | Obtiene el número de cuenta del acreedor. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Obtiene o establece los esquemas de pago alternativos. |
| [get_Amount](./get_amount/)() const | Obtiene el importe del pago. |
| [get_BillInformation](./get_billinformation/)() const | Obtiene la información estructurada adicional de la factura. |
| [get_Creditor](./get_creditor/)() const | Obtiene la dirección del acreedor. |
| [get_Currency](./get_currency/)() const | Obtiene la moneda del pago. |
| [get_Debtor](./get_debtor/)() const | Obtiene la dirección del deudor. |
| [get_Reference](./get_reference/)() const | Obtiene la referencia de pago del acreedor. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Obtiene el mensaje no estructurado adicional. |
| [get_Version](./get_version/)() const | Obtiene la versión del estándar de factura SwissQR. |
| [GetHashCode](./gethashcode/)() const override | Obtiene el código hash de esta instancia. |
| [set_Account](./set_account/)(System::String) | Establece el número de cuenta del acreedor. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Obtiene o establece los esquemas de pago alternativos. |
| [set_Amount](./set_amount/)(System::Decimal) | Establece el importe del pago. |
| [set_BillInformation](./set_billinformation/)(System::String) | Establece la información estructurada adicional de la factura. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Establece la dirección del acreedor. |
| [set_Currency](./set_currency/)(System::String) | Establece la moneda del pago. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Establece la dirección del deudor. |
| [set_Reference](./set_reference/)(System::String) | Establece la referencia de pago del acreedor. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Establece el mensaje adicional no estructurado. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | Establece la versión del estándar de factura SwissQR. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | Versión del estándar de factura SwissQR |
## Ver también

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
