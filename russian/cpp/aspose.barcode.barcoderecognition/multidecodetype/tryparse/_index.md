---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode для C++ справочник API"
description: " method. Преобразует строковое представление MultiDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование или нет в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


Преобразует строковое представление [MultiDecodeType](../) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование или нет.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| parsingType | System::String | Строка в формате либо \"AllSupportedTypes\", либо \"EAN8,EAN13,CodaBar\" для преобразования. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Фактический [MultiDecodeType](../) возвращается, когда преобразование завершилось успешно; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Примечания



в противном случае возвращается неопределённый тип.

или [MultiDecodeType](../) ("None").

## См. также

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
