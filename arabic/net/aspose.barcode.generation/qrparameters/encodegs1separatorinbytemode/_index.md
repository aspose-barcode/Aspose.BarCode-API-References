---
title: "QrParameters.EncodeGS1SeparatorInByteMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "خاصية QrParameters. يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت للباركودات QR وRectMicroQR"
type: docs
weight: 30
url: /ar/net/aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/
---
## QrParameters.EncodeGS1SeparatorInByteMode property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت للباركودات QR و RectMicroQR.

إذا كان خاطئًا، قد يتم ترميز فواصل GS1 كـ '%' في وضع أبجدي رقمي وفقًا لمواصفات QR.

إذا كان صحيحًا، يتم ترميز فواصل مجموعة GS1 في وضع البايت كحرف 0x1D، كما يتم ترميز الأحرف '%' أيضًا في وضع البايت للحفاظ عليها كبيانات.

قد يحسن هذا الخيار التوافق مع أجهزة فك الترميز التي تتوقع فواصل مجموعة GS1 على مستوى البايت ويمنع تفسير أحرف البيانات '%' كفواصل GS1.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### انظر أيضًا

* class [QrParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


