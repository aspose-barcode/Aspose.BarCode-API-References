---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext kelas"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext kelas. Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mail 2D Mailmark di C++."
type: docs
weight: 1400
url: /id/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mail 2D Mailmark.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Class](./get_class/)() const | Mengidentifikasi kelas dari item. |
| [get_CustomerContent](./get_customercontent/)() const | Ruang opsional untuk digunakan oleh pelanggan. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Mode enkode barcode Datamatrix. Nilai default: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | Tipe 2D Mailmark menentukan ukuran barcode Data Matrix. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Berisi Kode Pos dari [Address](../address/) Pengiriman dengan DPS. Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut: Area (1 atau 2 karakter) Distrik (1 atau 2 karakter) Sektor (1 karakter) Unit (2 karakter) DPS (2 karakter). Kode Pos dan DPS harus mematuhi format PAF® yang valid. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Mengidentifikasi muatan barcode Royal Mail Mailmark untuk setiap tipe produk. |
| [get_ItemID](./get_itemid/)() const | Mengidentifikasi item unik dalam ID Rantai Pasokan. Setiap barcode Mailmark harus membawa ID sehingga dapat diidentifikasi secara unik setidaknya selama 90 hari. Nilai maksimum: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Berisi Kode Pos Pengembalian ke Pengirim tetapi tanpa DPS. PC (tanpa DPS) harus mematuhi format PAF®. |
| [get_RTSFlag](./get_rtsflag/)() const | Bendera yang menunjukkan tingkat layanan Pengembalian ke Pengirim yang diminta. |
| [get_SupplyChainID](./get_supplychainid/)() const | Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. Nilai maksimum: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter. |
| [get_VersionID](./get_versionid/)() const | Mengidentifikasi versi barcode yang relevan untuk setiap ID Tipe Informasi. |
| [GetBarcodeType](./getbarcodetype/)() override | Mendapatkan tipe barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Bangun kode teks dari data Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi data Mailmark dari kode teks yang dibangun. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Konstruktor. Membuat instance default dari kelas [Mailmark2DCodetext](./). |
| [set_Class](./set_class/)(System::String) | Mengidentifikasi kelas dari item. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Ruang opsional untuk digunakan oleh pelanggan. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Mode enkode barcode Datamatrix. Nilai default: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | Tipe 2D Mailmark menentukan ukuran barcode Data Matrix. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Berisi Kode Pos dari [Address](../address/) Pengiriman dengan DPS. Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut: Area (1 atau 2 karakter) Distrik (1 atau 2 karakter) Sektor (1 karakter) Unit (2 karakter) DPS (2 karakter). Kode Pos dan DPS harus mematuhi format PAF® yang valid. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Mengidentifikasi muatan barcode Royal Mail Mailmark untuk setiap tipe produk. |
| [set_ItemID](./set_itemid/)(int32_t) | Mengidentifikasi item unik dalam ID Rantai Pasokan. Setiap barcode Mailmark harus membawa ID sehingga dapat diidentifikasi secara unik setidaknya selama 90 hari. Nilai maksimum: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Berisi Kode Pos Pengembalian ke Pengirim tetapi tanpa DPS. PC (tanpa DPS) harus mematuhi format PAF®. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | Bendera yang menunjukkan tingkat layanan Pengembalian ke Pengirim yang diminta. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. Nilai maksimum: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter. |
| [set_VersionID](./set_versionid/)(System::String) | Mengidentifikasi versi barcode yang relevan untuk setiap ID Tipe Informasi. |
## Lihat Juga

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
