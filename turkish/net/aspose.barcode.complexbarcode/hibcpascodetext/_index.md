---
title: "Sınıf HIBCPASCodetext"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.HIBCPASCodetext sınıfı. HIBC PAS koduna gömülü metni kodlamak ve kodunu çözmek için sınıf."
type: docs
weight: 600
url: /tr/net/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class

HIBC PAS kodunda gömülü metni kodlamak ve çözmek için sınıf.

```csharp
public class HIBCPASCodetext : IComplexCodetext
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [HIBCPASCodetext](hibcpascodetext/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/barcodetype/) { get; set; } | Barkod tipini alır veya ayarlar. HIBC PAS kodmetni, HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS ve HIBCQRPAS kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39PAS. |
| [DataLocation](../../aspose.barcode.complexbarcode/hibcpascodetext/datalocation/) { get; set; } | Veri konumunu belirler. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord_1)(HIBCPASRecord) | Yeni kayıt ekler |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord)(HIBCPASDataType, string) | Yeni kayıt ekler |
| [Clear](../../aspose.barcode.complexbarcode/hibcpascodetext/clear/)() | Kayıt listesini temizler |
| override [Equals](../../aspose.barcode.complexbarcode/hibcpascodetext/equals/)(object) | Bu örneğin belirtilen `HIBCPASCodetext` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/getbarcodetype/)() | Barkod tipini alır. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcpascodetext/getconstructedcodetext/)() | Kod metnini oluşturur |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcpascodetext/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| [GetRecords](../../aspose.barcode.complexbarcode/hibcpascodetext/getrecords/)() | Kayıt listesini alır |
| [InitFromString](../../aspose.barcode.complexbarcode/hibcpascodetext/initfromstring/)(string) | Oluşturulmuş kod metninden örneği başlatır. |

## Örnekler

Bu örnek, HIBCPASCodetext kullanarak HIBC PAS nasıl kodlanır ve kodu çözülür gösterir.

```csharp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText; 
		HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
		Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

### Ayrıca Bakınız

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


