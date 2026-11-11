---
title: "Sınıf USADriveIdCodetext"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext sınıfı. USA Sürücü Belgesi PDF417 koduna gömülü metni kodlamak ve kodunu çözmek için sınıf."
type: docs
weight: 810
url: /tr/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

ABD Sürücü Belgesi PDF417 kodunda gömülü metni kodlamak ve çözmek için sınıf.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | AAMVA Sürüm Numarası 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Bu sayı, veren yargı bölgesini benzersiz şekilde tanımlar ve ISO Yayın Yetkilisi (AAMVA) ile iletişime geçilerek elde edilebilir. Tam 6 haneli IIN kodlanmalıdır. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Yargı Bölgesi Özel Alanları |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Yargı Bölgesi Sürüm Numarası 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Kartın zorunlu öğeleri (alanları) |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Alt dosyaların 00-99 numarası |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Kartın isteğe bağlı öğeleri (alanları) |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Aşağıdaki alt dosyalar, tipler, ofsetler ve uzunluklar hakkında bilgi içerir. Önemli: sadece tip ayarlandığında, ofset ve uzunluk otomatik olarak ayarlanacaktır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | USA DL (Pdf417) barkod tipini döndürür |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | USA DL verilerinden kod metni oluşturur |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Kod metninden USA DL nesnesini başlatır |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | XML'ye kaydeder |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Kartın zorunlu öğeleri (alanları) |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Kartın isteğe bağlı öğeleri (alanları) |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | USA DL alt dosya özellikleri, ofset ve uzunluk otomatik olarak ayarlanır. |

### Ayrıca Bakınız

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


