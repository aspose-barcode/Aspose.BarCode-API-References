---
title: "GS1Codetext.TryParse"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Metode GS1Codetext. Mencoba mengurai string elemen GS1 dalam kurung dalam bentuk AIvalueAIvalue dan mengembalikan kesalahan validasi terstruktur. Literal  di dalam nilai harus ditulis sebagai  tidak ada urutan pelolosan lain yang didukung dan  tidak memerlukan pelolosan."
type: docs
weight: 140
url: /id/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Mencoba mengurai string elemen GS1 dalam tanda kurung dengan format (AI)nilai(AI)nilai dan mengembalikan kesalahan validasi terstruktur. Tanda kurung buka literal '(' di dalam nilai harus ditulis sebagai \(; tidak ada urutan pelarian lain yang didukung, dan ')' tidak memerlukan pelarian.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | String | String elemen GS1 dalam kurung untuk diurai. |
| result | GS1Codetext& | Ketika metode ini mengembalikan true, berisi kode teks GS1 yang diurai; jika tidak, null. |
| validationResult | GS1ValidationResult& | Berisi hasil validasi, atau null ketika *value* bernilai null. |

### Nilai Kembali

Benar ketika parsing berhasil; jika tidak, salah.

### Lihat Juga

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


