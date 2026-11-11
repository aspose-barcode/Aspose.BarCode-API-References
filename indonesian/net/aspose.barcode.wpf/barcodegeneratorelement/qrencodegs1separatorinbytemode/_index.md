---
title: "BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "BarcodeGeneratorElement property. Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk kode batang QR dan RectMicroQR"
type: docs
weight: 1290
url: /id/net/aspose.barcode.wpf/barcodegeneratorelement/qrencodegs1separatorinbytemode/
---
## BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode property

Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk kode batang QR dan RectMicroQR.

Jika false, pemisah GS1 dapat dienkode sebagai '%' dalam mode Alfanumerik menurut spesifikasi QR.

Jika true, pemisah grup GS1 dienkode dalam mode Byte sebagai karakter 0x1D, dan karakter '%' juga dienkode dalam mode Byte untuk mempertahankannya sebagai data.

Opsi ini dapat meningkatkan kompatibilitas dengan decoder yang mengharapkan pemisah grup GS1 pada tingkat byte dan mencegah karakter data '%' diinterpretasikan sebagai pemisah GS1.

```csharp
public bool QREncodeGS1SeparatorInByteMode { get; set; }
```

### Lihat Juga

* class [BarcodeGeneratorElement](../)
* namespace [Aspose.BarCode.WPF](../../../aspose.barcode.wpf/)
* assembly [Aspose.BarCode](../../../)


