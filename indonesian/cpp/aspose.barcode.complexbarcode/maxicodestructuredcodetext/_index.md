---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext kelas"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext kelas. Kelas dasar untuk enkoding dan dekoding teks yang disematkan dalam kode MaxiCode untuk mode 2 dan 3 dalam C++."
type: docs
weight: 2200
url: /id/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode 2 dan 3.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [MaxiCodeStructuredCodetext](./) yang ditentukan. |
| [get_CountryCode](./get_countrycode/)() const | Mengidentifikasi kode negara 3 digit. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Mendapatkan enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Mendapatkan mode enkoding MaxiCode. Nilai default: Auto. |
| [get_PostalCode](./get_postalcode/)() const | Mengidentifikasi kode pos. Harus 9 digit dalam mode 2 atau 6 simbol alfanumerik dalam mode 3. |
| [get_SecondMessage](./get_secondmessage/)() const | Mengidentifikasi pesan kedua dari kode batang. |
| [get_ServiceCategory](./get_servicecategory/)() const | Mengidentifikasi kategori layanan 3 digit. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Mendapatkan tipe barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Menyusun codetext |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | Mendapatkan mode MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi instance dari codetext yang disusun. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | Mengidentifikasi kode negara 3 digit. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Mengatur enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Mengatur mode enkoding MaxiCode. Nilai default: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | Mengidentifikasi kode pos. Harus 9 digit dalam mode 2 atau 6 simbol alfanumerik dalam mode 3. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Mengidentifikasi pesan kedua dari kode batang. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | Mengidentifikasi kategori layanan 3 digit. |
## Catatan


Contoh ini menunjukkan cara mendekode teks kode MaxiCode mentah menjadi instance [MaxiCodeStructuredCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

## Lihat Juga

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
