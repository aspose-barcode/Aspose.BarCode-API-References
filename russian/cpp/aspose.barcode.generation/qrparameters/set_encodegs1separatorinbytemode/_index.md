---
title: "method"
linktitle: "set_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать метод set_EncodeGS1SeparatorInByteMode класса Aspose::BarCode::Generation::QrParameters в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.barcode.generation/qrparameters/set_encodegs1separatorinbytemode/
---
## QrParameters::set_EncodeGS1SeparatorInByteMode method




```cpp
void Aspose::BarCode::Generation::QrParameters::set_EncodeGS1SeparatorInByteMode(bool value)
```

## Примечания


Устанавливает значение, указывающее, следует ли кодировать специальные символы GS1 в байтовом режиме для штрихкодов QR и RectMicroQR.

Если false, разделители GS1 могут быть закодированы как '' в альфа-числовом режиме согласно спецификации QR.

Если true, групповые разделители GS1 кодируются в байтовом режиме как символ 0x1D, а символы '' также кодируются в байтовом режиме для сохранения их как данных.

Эта опция может улучшить совместимость с декодерами, ожидающими байтовые групповые разделители GS1, и предотвращает интерпретацию символов данных '' как разделителей GS1.
## См. также

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
