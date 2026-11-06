---
title: "طريقة"
linktitle: "TryParse"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " method. يحول تمثيل السلسلة لنوع SingleDecodeType إلى مثيله. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فشل في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


يحول تمثيل السلسلة لنوع [SingleDecodeType](../../singledecodetype/) إلى مثيله. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فشل.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | System::String | سلسلة تحتوي على [SingleDecodeType](../../singledecodetype/) بالتنسيق مثل "EAN8" أو "EAN13" أو "CodaBar"... للتحويل. |
| result | System::SharedPtr\<SingleDecodeType\>\& | يتم إرجاع [SingleDecodeType](../../singledecodetype/) فعليًا عندما يكتمل التحويل بنجاح؛ وإلا فإنه يُرجع النوع غير المحدد: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## انظر أيضًا

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


يحول تمثيل السلسلة لنوع [MultiDecodeType](../../multidecodetype/) إلى مثيله. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فشل.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | System::String | سلسلة تحتوي على تمثيل [MultiDecodeType](../../multidecodetype/) للتحويل. |
| result | System::SharedPtr\<MultiDecodeType\>\& | يتم إرجاع [MultiDecodeType](../../multidecodetype/) فعليًا عندما يكتمل التحويل بنجاح؛ وإلا فإنه يُرجع النوع غير المحدد: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## انظر أيضًا

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


يحول تمثيل السلسلة لنوع [BaseDecodeType](../) إلى مثيله، بعد تحديد النوع المحدد. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فشل.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | System::String | سلسلة تحتوي على تمثيل [MultiDecodeType](../../multidecodetype/) للتحويل. |
| result | System::SharedPtr\<BaseDecodeType\>\& | يتم إرجاع [MultiDecodeType](../../multidecodetype/) فعليًا عندما يكتمل التحويل بنجاح؛ وإلا فإنه يُرجع النوع غير المحدد: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## انظر أيضًا

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
