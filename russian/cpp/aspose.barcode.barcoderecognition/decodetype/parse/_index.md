---
title: "method"
linktitle: "Parse"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Преобразует строковое представление SingleDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование или нет в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


Преобразует строковое представление [SingleDecodeType](../../singledecodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование или нет.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| parsingType | System::String | Строка, содержащая [SingleDecodeType](../../singledecodetype/) в формате "EAN8" или "EAN13" или "CodaBar"... для преобразования. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Фактический [SingleDecodeType](../../singledecodetype/) возвращается, когда преобразование завершилось успешно; в противном случае он возвращает неопределённый тип: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## См. также

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
