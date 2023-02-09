---
title: TryParse
second_title: Aspose.BarCode untuk .NET API Referensi
description: Mengonversi representasi string dari SingleDecodeType ke instancenya. Nilai yang dikembalikan menunjukkan apakah konversi berhasil atau gagal.
type: docs
weight: 920
url: /id/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

Mengonversi representasi string dari SingleDecodeType ke instance-nya. Nilai yang dikembalikan menunjukkan apakah konversi berhasil atau gagal.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| parsingType | String | String dalam format "Index:-1; Name:None" untuk dikonversi. |
| result | SingleDecodeType& | Pengembalian SingleDecodeType yang sebenarnya, ketika konversi telah berhasil diselesaikan; |

### Nilai Pengembalian

**BENAR** jika s berhasil dikonversi; jika tidak, **PALSU**.

### Lihat juga

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../decodetype/)
* perakitan [Aspose.BarCode](../../../)

---

## TryParse(string, out MultyDecodeType) {#tryparse}

Mengonversi representasi string dari MultyDecodeType ke instance-nya. Nilai yang dikembalikan menunjukkan apakah konversi berhasil atau gagal.

```csharp
public static bool TryParse(string parsingType, out MultyDecodeType result)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| parsingType | String | String dalam format "AllSupportedTypes" atau "EAN8,EAN13,CodaBar" untuk dikonversi. |
| result | MultyDecodeType& | MultyDecodeType aktual dikembalikan, ketika konversi berhasil diselesaikan; |

### Nilai Pengembalian

**BENAR** jika s berhasil dikonversi; jika tidak, **PALSU**.

### Lihat juga

* class [MultyDecodeType](../../multydecodetype/)
* class [DecodeType](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../decodetype/)
* perakitan [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->