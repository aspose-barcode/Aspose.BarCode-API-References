---
title: "طريقة"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. إنشاء صورة الباركود وفق الإعدادات الحالية في C++."
type: docs
weight: 800
url: /ar/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


توليد صورة الباركود وفق الإعدادات الحالية.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

صورة الباركود. راجع [Bitmap](../).
## ملاحظات



يعرض هذا المثال كيفية إنشاء وحفظ صورة باركود.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## انظر أيضًا

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
