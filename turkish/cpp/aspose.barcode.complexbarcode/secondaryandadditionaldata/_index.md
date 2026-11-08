---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData sınıfı. C++'da HIBC LIC ikincil ve ek verileri depolamak için sınıf."
type: docs
weight: 2600
url: /tr/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


HIBC LIC ikincil ve ek verileri depolamak için sınıf.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bu örneğin belirtilen [SecondaryAndAdditionalData](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Üretim tarihini tanımlar. Üretim tarihi, bu alan kullanılmayacaksa DateTime.MinValue olarak ayarlanabilir. Varsayılan değer: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Son kullanma tarihini tanımlar. ExpiryDateFormat None olarak ayarlanmamışsa kullanılacaktır. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Son kullanma tarihi biçimini tanımlar. |
| [get_LotNumber](./get_lotnumber/)() const | Lot veya batch numarasını tanımlar. Lot/batch numarası, en fazla 18 karakter uzunluğunda alfanümerik bir dize olmalıdır. |
| [get_Quantity](./get_quantity/)() const | Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. Bu alan kullanılmayacaksa miktar -1 olarak ayarlanabilir. Varsayılan değer: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | Seri numarasını tanımlar. Seri numarası, en fazla 18 karakter uzunluğunda alfanümerik bir dize olmalıdır. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [ParseFromString](./parsefromstring/)(System::String) | HIBC LIC spesifikasyonuna göre dize formatından ikincil ve ek tamamlayıcı verileri örnekler. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Üretim tarihini tanımlar. Üretim tarihi, bu alan kullanılmayacaksa DateTime.MinValue olarak ayarlanabilir. Varsayılan değer: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Son kullanma tarihini tanımlar. ExpiryDateFormat None olarak ayarlanmamışsa kullanılacaktır. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Son kullanma tarihi biçimini tanımlar. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Lot veya batch numarasını tanımlar. Lot/batch numarası, en fazla 18 karakter uzunluğunda alfanümerik bir dize olmalıdır. |
| [set_Quantity](./set_quantity/)(int32_t) | Miktarı tanımlar, 0 ile 500 arasında tam sayı olmalıdır. Bu alan kullanılmayacaksa miktar -1 olarak ayarlanabilir. Varsayılan değer: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Seri numarasını tanımlar. Seri numarası, en fazla 18 karakter uzunluğunda alfanümerik bir dize olmalıdır. |
| [ToString](./tostring/)() const override | Verileri HIBC LIC spesifikasyonuna göre dize formatına dönüştürür. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
