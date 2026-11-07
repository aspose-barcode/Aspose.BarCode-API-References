---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext класс"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext класс. Класс для кодирования и декодирования текста, встроенного в код HIBC PAS, на C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


Класс для кодирования и декодирования текста, встроенного в код HIBC PAS.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Добавляет новую запись |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Добавляет новую запись |
| [Clear](./clear/)() | Очищает список записей |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [HIBCPASCodetext](./). |
| [get_BarcodeType](./get_barcodetype/)() const | Получает тип штрих‑кода. Текст HIBC PAS может быть закодирован с использованием типов кодирования HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS и HIBCQRPAS. Значение по умолчанию: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Определяет расположение данных. |
| [GetBarcodeType](./getbarcodetype/)() override | Получает тип штрихкода. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Создаёт текст кода |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [GetRecords](./getrecords/)() | Получает список записей |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Инициализирует экземпляр из построенного текста кода. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Устанавливает тип штрих‑кода. Текст HIBC PAS может быть закодирован с использованием типов кодирования HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS и HIBCQRPAS. Значение по умолчанию: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Определяет расположение данных. |
## Примечания


Этот пример показывает, как кодировать и декодировать HIBC PAS с помощью [HIBCPASCodetext](./).
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
            HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## См. также

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
