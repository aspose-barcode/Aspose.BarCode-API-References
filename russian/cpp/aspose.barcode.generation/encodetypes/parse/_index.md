---
title: "method"
linktitle: "Parse"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Преобразует строковое представление BaseEncodeType в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование, в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode.generation/encodetypes/parse/
---
## EncodeTypes::Parse method


Преобразует строковое представление [BaseEncodeType](../../baseencodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::Parse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| parsingType | System::String | Строка, содержащая представление [BaseEncodeType](../../baseencodetype/) для преобразования. |
| result | System::SharedPtr\<BaseEncodeType\>\& | Фактический [BaseEncodeType](../../baseencodetype/) возвращается, когда преобразование завершилось успешно; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Примечания



в противном случае возвращает null.

## См. также

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
