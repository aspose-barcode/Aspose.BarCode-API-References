---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Преобразует строковое представление SingleDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование или нет в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Преобразует строковое представление [SingleDecodeType](../../singledecodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование или нет.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| parsingType | System::String | Строка, содержащая [SingleDecodeType](../../singledecodetype/) в формате "EAN8" или "EAN13" или "CodaBar"... для преобразования. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Фактический [SingleDecodeType](../../singledecodetype/) возвращается, когда преобразование завершилось успешно; в противном случае возвращается неопределённый тип: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## См. также

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Преобразует строковое представление [MultiDecodeType](../../multidecodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование или нет.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| parsingType | System::String | Строка, содержащая представление [MultiDecodeType](../../multidecodetype/) для преобразования. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Фактический [MultiDecodeType](../../multidecodetype/) возвращается, когда преобразование завершилось успешно; в противном случае возвращается неопределённый тип: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## См. также

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Преобразует строковое представление [BaseDecodeType](../) в его экземпляр, определив конкретный тип. Возвращаемое значение указывает, удалось ли выполнить преобразование или нет.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| parsingType | System::String | Строка, содержащая представление [MultiDecodeType](../../multidecodetype/) для преобразования. |
| result | System::SharedPtr\<BaseDecodeType\>\& | Фактический [MultiDecodeType](../../multidecodetype/) возвращается, когда преобразование завершилось успешно; в противном случае возвращается неопределённый тип: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## См. также

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
