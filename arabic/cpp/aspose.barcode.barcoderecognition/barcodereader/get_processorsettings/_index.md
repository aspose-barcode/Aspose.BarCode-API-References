---
title: "طريقة"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "طريقة. يحصل على إعدادات استخدام نوى المعالج في C++."
type: docs
weight: 100
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


يحصل على إعدادات استخدام نوى المعالج.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## ملاحظات


هذا المثال يوضح كيفية استخدام ProcessorSettings لإضافة أقصى أداء متعدد الخيوط
```cpp
[C#]
//هذا يسمح باستخدام جميع الأنوية لاستدعاء واحد لـ BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//هذا يسمح باستخدام عدد الأنوية الحالي
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## انظر أيضًا

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
