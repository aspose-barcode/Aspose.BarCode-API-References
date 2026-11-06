---
title: "طريقة"
linktitle: "set_RotationAngle"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. زاوية دوران صورة BarCode، تُقاس بالدرجة، مثال: RotationAngle = 0 أو RotationAngle = 360 يعني لا دوران. إذا لم تكن RotationAngle مساوية لـ 90 أو 180 أو 270 أو 0، قد تزيد صعوبة قراءة الصورة بواسطة الماسح. القيمة الافتراضية: 0 في C++."
type: docs
weight: 800
url: /ar/cpp/aspose.barcode.generation/basegenerationparameters/set_rotationangle/
---
## BaseGenerationParameters::set_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
void Aspose::BarCode::Generation::BaseGenerationParameters::set_RotationAngle(float value)
```

## ملاحظات


هذا المثال يوضح كيفية إنشاء وحفظ صورة [BarCode](../../../aspose.barcode/).
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## انظر أيضًا

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
