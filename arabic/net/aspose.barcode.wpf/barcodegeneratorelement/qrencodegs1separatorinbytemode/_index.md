---
title: "BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "BarcodeGeneratorElement خاصية. يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت للباركودات QR و RectMicroQR"
type: docs
weight: 1290
url: /ar/net/aspose.barcode.wpf/barcodegeneratorelement/qrencodegs1separatorinbytemode/
---
## BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت للباركودات QR و RectMicroQR.

إذا كان خاطئًا، قد يتم ترميز فواصل GS1 كـ '%' في وضع أبجدي رقمي وفقًا لمواصفات QR.

إذا كان صحيحًا، يتم ترميز فواصل مجموعة GS1 في وضع البايت كحرف 0x1D، كما يتم ترميز الأحرف '%' أيضًا في وضع البايت للحفاظ عليها كبيانات.

قد يحسن هذا الخيار التوافق مع أجهزة فك الترميز التي تتوقع فواصل مجموعة GS1 على مستوى البايت ويمنع تفسير أحرف البيانات '%' كفواصل GS1.

```csharp
public bool QREncodeGS1SeparatorInByteMode { get; set; }
```

### انظر أيضًا

* class [BarcodeGeneratorElement](../)
* namespace [Aspose.BarCode.WPF](../../../aspose.barcode.wpf/)
* assembly [Aspose.BarCode](../../../)


