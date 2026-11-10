---
title: "الفئة HIBCPASCodetext"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.ComplexBarcode.HIBCPASCodetext. فئة لتشفير وفك تشفير النص المضمن في رمز HIBC PAS"
type: docs
weight: 600
url: /ar/net/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز HIBC PAS.

```csharp
public class HIBCPASCodetext : IComplexCodetext
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HIBCPASCodetext](hibcpascodetext/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/barcodetype/) { get; set; } | يحصل أو يعيّن نوع الباركود. يمكن تشفير نص HIBC PAS باستخدام أنواع الترميز HIBCCode39PAS، HIBCCode128PAS، HIBCAztec:PAS، HIBCDataMatrixPAS و HIBCQRPAS. القيمة الافتراضية: HIBCCode39PAS. |
| [DataLocation](../../aspose.barcode.complexbarcode/hibcpascodetext/datalocation/) { get; set; } | يحدد موقع البيانات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord_1)(HIBCPASRecord) | يضيف سجلًا جديدًا |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord)(HIBCPASDataType, string) | يضيف سجلًا جديدًا |
| [Clear](../../aspose.barcode.complexbarcode/hibcpascodetext/clear/)() | يمسح قائمة السجلات |
| override [Equals](../../aspose.barcode.complexbarcode/hibcpascodetext/equals/)(object) | يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة `HIBCPASCodetext` المحددة. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/getbarcodetype/)() | يحصل على نوع الباركود. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcpascodetext/getconstructedcodetext/)() | يبني نص الرمز |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcpascodetext/gethashcode/)() | يعيد قيمة التجزئة (hash code) لهذه المثيلة. |
| [GetRecords](../../aspose.barcode.complexbarcode/hibcpascodetext/getrecords/)() | يحصل على قائمة السجلات |
| [InitFromString](../../aspose.barcode.complexbarcode/hibcpascodetext/initfromstring/)(string) | يُهيئ المثيلة من نص الرمز المُنشأ. |

## أمثلة

يوضح هذا المثال كيفية تشفير وفك تشفير HIBC PAS باستخدام HIBCPASCodetext.

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

### انظر أيضًا

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


