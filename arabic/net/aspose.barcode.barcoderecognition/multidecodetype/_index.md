---
title: "الفئة MultiDecodeType"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.BarCodeRecognition.MultiDecodeType فئة. نوع فك تشفير مركب"
type: docs
weight: 320
url: /ar/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

نوع فك تشفير مركب.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | يُنشئ مثيلًا جديدًا من الفئة `MultiDecodeType`. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | يُنشئ مثيلًا جديدًا من الفئة `MultiDecodeType`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | يرجع عددًا من الأنواع الفردية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | يضيف نوعًا آخر [`SingleDecodeType`](../singledecodetype/) إلى MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | تحقق مما إذا كان يحتوي هذا على جميع الأنواع من أنواع الباركود. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | هل يحتوي على أي من الأنواع |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة [`BaseDecodeType`](../basedecodetype/) المحددة. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة `MultiDecodeType` المحددة. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة `MultiDecodeType` المحددة. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | يرجع قيمة تشير إلى ما إذا كانت مجموعة أنواع فك التشفير هذه تحتوي فقط على القيمة المحددة [`SingleDecodeType`](../singledecodetype/). |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | يستثني [`SingleDecodeType`](../singledecodetype/) من MultiDecodeType ويُرجع مثيلًا جديدًا من MultiDecodeType. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | يعيد قيمة التجزئة (hash code) لهذه المثيلة. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | يمثل قائمة من الأنواع الفردية. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | طريقة مُعاد تعريفها تمثل MultiDecodeType كسلسلة نصية. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | يحوّل تمثيل السلسلة النصية لـ MultiDecodeType إلى مثيله. تُشير قيمة الإرجاع إلى ما إذا كانت عملية التحويل ناجحة أم فاشلة. |

## أمثلة

يعرض هذا المثال كيفية إنشاء أنواع MultiDecode مركبة تجمع بين SingleDecodeType وأنواع MultiDecode.

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### انظر أيضًا

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


