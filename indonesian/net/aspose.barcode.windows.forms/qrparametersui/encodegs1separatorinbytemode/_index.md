---
title: "QrParametersUI.EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Properti QrParametersUI. Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk barcode QR dan RectMicroQR"
type: docs
weight: 30
url: /id/net/aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/
---
## QrParametersUI.EncodeGS1SeparatorInByteMode property

Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk kode batang QR dan RectMicroQR.

Jika false, pemisah GS1 dapat dienkode sebagai '%' dalam mode Alfanumerik menurut spesifikasi QR.

Jika true, pemisah grup GS1 dienkode dalam mode Byte sebagai karakter 0x1D, dan karakter '%' juga dienkode dalam mode Byte untuk mempertahankannya sebagai data.

Opsi ini dapat meningkatkan kompatibilitas dengan decoder yang mengharapkan pemisah grup GS1 pada tingkat byte dan mencegah karakter data '%' diinterpretasikan sebagai pemisah GS1.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Lihat Juga

* class [QrParametersUI](../)
* namespace [Aspose.BarCode.Windows.Forms](../../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../../)


