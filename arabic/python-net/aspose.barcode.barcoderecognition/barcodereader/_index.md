---
title: "BarCodeReader"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader يضم صورة قد تحتوي على باركود واحد أو عدة باركودات، ثم يمكنه تنفيذ عملية ReadBarCodes لاكتشاف الباركودات.

يعرض نوع BarCodeReader الأعضاء التالية:
## المنشئات
| الاسم | الوصف |
| :- | :- |
| BarCodeReader() | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) بالقيم الافتراضية.<br/>            يتطلب تعيين الصورة (SetBitmapImage()) قبل استدعاء طريقة ReadBarCodes(). |
| BarCodeReader(image) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(image, decode_types) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(image, type) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(image, area, decode_types) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(image, area, type) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(image, areas, decode_types) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(image, areas, type) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(filename) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(filename, decode_types) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(filename, type) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(stream) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(stream, type) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(stream, decode_types) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(frame, areas, type) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(frame, areas, decode_types) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(frame, area, type) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(frame, area, decode_types) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(frame, type) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(frame, decode_types) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
| BarCodeReader(frame) | ينشئ مثيلًا جديدًا من فئة BarCodeReader |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| processor_settings | يحصل على إعدادات استخدام نوى المعالج. |
| timeout | يحصل أو يضبط مهلة عملية التعرف بالمللي ثانية. |
| found_bar_codes | يحصل على مصفوفة [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) المعترف بها |
| found_count | يحصل على عدد الباركودات المعترف بها |
| quality_settings | QualitySettings يسمح بتكوين جودة وسرعة التعرف يدويًا.<br/>            يمكنك إعداد QualitySettings بسرعة باستخدام الإعدادات المضمنة: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes أو يمكنك تكوين الخيارات بشكل منفصل يدويًا.<br/>            القيمة الافتراضية لـ QualitySettings هي NormalQuality. |
| barcode_settings | معلمات فك تشفير BarCode الرئيسية. تحتوي على معلمات تؤثر على البيانات المعترف بها. |
| bar_code_read_type | يحصل أو يضبط نوع فك تشفير الباركود المستخدم للتعرف.<br/>            يجب ضبطه قبل استدعاء [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## الطرق
| الاسم | الوصف |
| :- | :- |
| set_bar_code_image(value) | يضبط صورة البت ماب للتعرف. <br/>            يجب استدعاؤه قبل طريقة ReadBarCodes(). |
| set_bar_code_image(value, areas) | يضبط صورة البت ماب والمناطق للتعرف. <br/>            يجب استدعاؤه قبل طريقة ReadBarCodes(). |
| set_bar_code_image(value, area) | يضبط صورة البت ماب والمناطق للتعرف. <br/>            يجب استدعاؤه قبل طريقة ReadBarCodes(). |
| set_bar_code_image(filename) | يضبط ملف الصورة للتعرف. <br/>            يجب استدعاؤه قبل طريقة ReadBarCodes(). |
| set_bar_code_image(stream) | يضبط تدفق الصورة للتعرف. <br/>            يجب استدعاؤه قبل طريقة ReadBarCodes(). |
| set_bar_code_image(frame, area) | يضبط إطار الإضاءة والمنطقة للتعرف. يجب استدعاؤه قبل طريقة [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame, areas) | يضبط إطار الإضاءة والمناطق للتعرف. يجب استدعاؤه قبل طريقة [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame) | يضبط إطار الإضاءة والمنطقة للتعرف. يجب استدعاؤه قبل طريقة [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| export_to_xml(xml_file) | يصدّر خصائص BarCode إلى ملف XML المحدد |
| export_to_xml(xml_stream) | يصدّر خصائص BarCode إلى تدفق XML المحدد |
| import_from_xml(xml_file) | يستورد خصائص BarCode من ملف XML المحدد ويطبقها على نسخة BarCodeReader الحالية. |
| import_from_xml(xml_stream) | يستورد خصائص BarCode من تدفق XML المحدد ويطبقها على نسخة BarCodeReader الحالية. |
| abort() | تطلب الدالة إنهاء جلسة التعرف الحالية من خيط آخر. Abort هي طريقة لا يمكن إيقافها وتعيد التحكم مباشرة بعد الاستدعاء. <br/>            يجب استخدام الطريقة عندما تكون عملية التعرف طويلة جدًا. |
| read_bar_codes() | يقرأ [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s من الصورة. |
| set_bar_code_read_type(barcode_types) | يضبط مصفوفة نوع [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) للتعرف. <br/>            يجب استدعاؤه قبل طريقة ReadBarCodes(). |

### انظر أيضًا

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

