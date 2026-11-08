---
title: "metot"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "metodu. Kütüphaneyi C++'ta lisanslar."
type: docs
weight: 200
url: /tr/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Kütüphaneyi lisanslar.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseName | System::String | Tam veya kısa bir dosya adı ya da gömülü kaynağın adı olabilir. |
## Açıklamalar


Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

2. **Aspose** bileşen derlemesini içeren klasör.

3. İstemcinin çağıran derlemesini içeren klasör.

4. Giriş (başlangıç) derlemesini içeren klasör.

5. İstemcinin çağıran derlemesindeki gömülü kaynak.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Açık yol.

2. İstemcinin çağıran derlemesindeki gömülü kaynak.

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
@endverbatim
```


## Ayrıca Bakınız

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Kütüphaneyi lisanslar.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Lisansı içeren bir akış. |
## Açıklamalar



Bu metodu bir akıştan lisans yüklemek için kullanın.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## Ayrıca Bakınız

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
