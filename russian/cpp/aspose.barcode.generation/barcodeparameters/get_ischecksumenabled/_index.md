---
title: "method"
linktitle: "get_IsChecksumEnabled"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать метод get_IsChecksumEnabled класса Aspose::BarCode::Generation::BarcodeParameters в C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.barcode.generation/barcodeparameters/get_ischecksumenabled/
---
## BarcodeParameters::get_IsChecksumEnabled method




```cpp
EnableChecksum Aspose::BarCode::Generation::BarcodeParameters::get_IsChecksumEnabled() const
```

## Примечания


Включить контрольную сумму при генерации 1D штрихкодов.

По умолчанию считается Yes для символогии, которая должна содержать контрольную сумму, и No там, где контрольная сумма только возможна.

Контрольная сумма возможна: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Контрольная сумма всегда используется: остальные типы символогии
## См. также

* Enum [EnableChecksum](../../enablechecksum/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
