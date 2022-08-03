---
title: DecodeType
second_title: Aspose.BarCode for .NET API Referansı
description: Okunacak barkod türünü belirtin.
type: docs
weight: 190
url: /tr/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Okunacak barkod türünü belirtin.

```csharp
public static class DecodeType
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | AllSupportedTypes 'yi temsil eden bir dizi alır |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | Kod çözme türlerinin adlarının bir dizisini alır. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | Belirtilen[`BaseDecodeType`](../basedecodetype) herhangi bir 1D barkod sembology içerir |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | Belirtilen[`BaseDecodeType`](../basedecodetype) herhangi bir 2D barkod sembology içerir |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | Belirtilen[`BaseDecodeType`](../basedecodetype) herhangi bir Posta barkodu sembology içerir |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönüş değeri, dönüşümün başarılı veya başarısız olduğunu gösterir. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | BarcodeTypes ile tarama setlerini belirtin |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse)(string, out MultyDecodeType) | Bir MultyDecodeType'ın dize temsilini örneğine dönüştürür. Dönüş değeri, dönüştürmenin başarılı veya başarısız olduğunu gösterir. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse_1)(string, out SingleDecodeType) | SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönüş değeri, dönüşümün başarılı veya başarısız olduğunu gösterir. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes) | Verilerin mevcut tüm sembolojilerle kontrol edileceğini belirtir |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Avustralya Postası Yurtiçi eParsel Barkodu** barkod özelliği |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Avustralya Postası** barkod belirtimi |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Aztek** barkod belirtimi |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **KODABAR** barkod özelliği |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **CodablockF** barkod belirtimi |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **KOD 11** barkod özelliği |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **KOD 128** barkod özelliği |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **SCCode16K** barkod belirtimi |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Code32** boş belirtim |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Genişletilmiş KOD 39** barkod özelliği |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Standart KOD 39** barkod özelliği |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Genişletilmiş KOD 93** barkod özelliği |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Standart KOD 93** barkod özelliği |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **KompaktPdf417** (Pdf417Truncated) barkod belirtimi |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1 Veri Çubuğu genişletildi** barkod belirtimi |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1 Veri Çubuğu genişletilmiş yığılmış** barkod belirtimi |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1 Veri Çubuğu sınırlı** barkod belirtimi |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1 Databar çok yönlü** barkod belirtimi |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1 Veri Çubuğu yığılmış** barkod belirtimi |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1 Databar yığılmış çok yönlü** barkod belirtimi |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1 Veri Çubuğu kesildi** barkod belirtimi |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **DataLogic 2/5** boş belirtim |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Veri matrisi** barkod sembolü |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **DeutschePost Kimlik kodu** barkod özelliği |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **DeutschePost Leit kodu** barkod özelliği |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **nokta kodu** boş belirtim |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **nokta kodu** boş belirtim |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **EAN-13** barkod özelliği |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **EAN14** barkod belirtimi |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **EAN-8** barkod özelliği |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1 KODU 128** barkod özelliği |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1VeriMatrisi** barkod sembolü |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **GS1 QR** barkod belirtimi |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **IATA 2/5** barkod özellikleri. IATA (Uluslararası Hava Taşımacılığı Birliği), hava kargo yönetimi için bu barkodu kullanır. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **ARALIKLI 2/5** barkod özelliği |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **ISBN'si** barkod özelliği |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **ISMN** barkod özelliği |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **ISSN** barkod özelliği |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **İtalyan Postası 25** barkod özelliği |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **ITF14** barkod belirtimi |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **ITF6** barkod özelliği |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **MakroPdf417** barkod belirtimi |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Kraliyet Posta Posta İşareti** barkod belirtimi. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Matris 2/5** barkod özelliği |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **MaksiKod** barkod belirtimi |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **MICR E-13B** boş belirtim |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **MikroPdf417** barkod belirtimi |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **MikroQR Kodu** barkod belirtimi |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes) | Verilerin en sık kullanılan sembolojilerle kontrol edileceğini belirtir |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **MSI Plessey** barkod özelliği |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none) | Belirtilmemiş kod çözme türü. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode) | Verilerin USPS ile kodunun çözülmesi gerektiğini belirtir **Tek Kod** barkod belirtimi |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **OPC** barkod özelliği |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Yama kodu** barkod özellikleri. Otomatik tarama için barkod sembolojisi kullanılır |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **PDF417** barkod sembolü |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **farmakod** barkod. Bu semboloji, Farmasötik İkili Kod olarak da bilinir |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Gezegen** barkod belirtimi |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes) | Verilerin tümü ile kontrol edileceğini belirtir. **1.5D Posta** gibi barkod sembolojileri **Gezegen, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **posta ağı** barkod özelliği |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **PZN**barkod özellikleri. Bu semboloji, Pharma Zentral Nummer olarak da bilinir. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **QR kod** barkod belirtimi |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **RM4SCC** barkod özellikleri. RM4SCC (Royal Mail 4-state Müşteri Kodu), Birleşik Krallık'ta otomatik posta sıralama işlemi için kullanılır. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **SCC14** barkod belirtimi |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **SSCC18** barkod belirtimi |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Standart 2/5** barkod özelliği |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **Ek(EAN2, EAN5)** barkod özelliği |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **İsviçre Posta Koli Barkodu** barkod belirtimi |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d) | Verilerin tümü ile kontrol edileceğini belirtir. **1B** barkod sembolojileri |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d) | Verilerin tümü ile kontrol edileceğini belirtir. **2B** barkod sembolojileri |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **UPC-A** barkod özelliği |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **UPC-E** barkod özelliği |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin) | Verilerin kodunun şununla çözülmesi gerektiğini belirtir. **şasi numarası** (Araç Kimlik Numarası) barkod özelliği |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ayrıca bakınız

* ad alanı [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
