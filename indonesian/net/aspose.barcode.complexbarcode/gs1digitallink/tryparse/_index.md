---
title: "GS1DigitalLink.TryParse"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Metode GS1DigitalLink. Mencoba mengurai sebuah URI GS1 Digital Link yang tidak terkompresi dan mengembalikan kesalahan validasi terstruktur."
type: docs
weight: 190
url: /id/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

Mencoba memparsing URI GS1 Digital Link yang tidak terkompresi dan mengembalikan kesalahan validasi terstruktur.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | String | URI GS1 Digital Link yang akan diurai. |
| result | GS1DigitalLink& | Ketika metode ini mengembalikan true, berisi GS1 Digital Link yang telah diurai; jika tidak, null. |
| validationResult | GS1ValidationResult& | Berisi hasil validasi, atau null ketika *value* bernilai null. |

### Nilai Kembali

Benar ketika parsing berhasil; jika tidak, salah.

### Lihat Juga

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


