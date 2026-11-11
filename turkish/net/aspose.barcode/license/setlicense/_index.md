---
title: "License.SetLicense"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "License yöntemi. Kütüphaneyi lisanslar"
type: docs
weight: 20
url: /tr/net/aspose.barcode/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Kütüphaneyi lisanslar.

```csharp
public void SetLicense(string licenseName)
```

## Açıklamalar

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

2. Aspose bileşen derlemesini içeren klasör.

3. İstemcinin çağıran derlemesini içeren klasör.

4. Giriş (başlangıç) derlemesini içeren klasör.

5. İstemcinin çağıran derlemesindeki gömülü kaynak.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Açık yol.

2. İstemcinin çağıran derlemesindeki gömülü kaynak.

## Örnekler

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Tam veya kısa dosya adı ya da gömülü kaynağın adı olabilir.

### Ayrıca Bakınız

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)

---

## SetLicense(Stream) {#setlicense}

Kütüphaneyi lisanslar.

```csharp
public void SetLicense(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Akış | Lisansı içeren bir akış. |

## Açıklamalar

Bir akıştan lisans yüklemek için bu yöntemi kullanın.

## Örnekler

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Ayrıca Bakınız

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)


