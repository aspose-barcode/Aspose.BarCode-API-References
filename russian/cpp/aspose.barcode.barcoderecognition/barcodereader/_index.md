---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader class"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader class. BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрихкодов, после чего может выполнить операцию ReadBarCodes для обнаружения штрихкодов в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Methods

| Method | Описание |
| --- | --- |
| [Abort](./abort/)() | Функция запрашивает завершение текущего сеанса распознавания из другого потока. Abort — метод, который нельзя заблокировать, и он возвращает управление сразу после вызова. Этот метод следует использовать, когда процесс распознавания слишком длительный. |
| [BarCodeReader](./barcodereader/)() | Инициализирует новый экземпляр класса [BarCodeReader](./) со значениями по умолчанию. Требуется установить изображение (SetBitmapImage()) перед вызовом метода [ReadBarCodes()](./readbarcodes/). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Инициализирует новый экземпляр класса [BarCodeReader](./) из изображения. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String) | Инициализирует новый экземпляр класса [BarCodeReader](./) из файла. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Инициализирует новый экземпляр класса [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | Инициализирует новый экземпляр класса [BarCodeReader](./) из кадра яркости. |
| [Dispose](./dispose/)() override | Освободить ресурс |
| [ExportToXml](./exporttoxml/)(System::String) | Экспортирует свойства [BarCode](../../aspose.barcode/) в указанный XML‑файл |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Экспортирует свойства [BarCode](../../aspose.barcode/) в указанный XML‑поток |
| [get_BarCodeReadType](./get_barcodereadtype/)() | Получает тип декодирования штрихкода, используемый для распознавания. Должен быть установлен перед вызовом [ReadBarCodes](./readbarcodes/). |
| [get_BarcodeSettings](./get_barcodesettings/)() | Основные параметры декодирования [BarCode](../../aspose.barcode/). Содержит параметры, влияющие на распознанные данные. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Получает массив распознанных [BarCodeResult](../barcoderesult/) |
| [get_FoundCount](./get_foundcount/)() | Получает количество распознанных штрихкодов |
| static [get_ProcessorSettings](./get_processorsettings/)() | Получает настройки использования ядер процессора. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) позволяет вручную настраивать качество распознавания и скорость. Вы можете быстро установить [QualitySettings](../qualitysettings/) с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, либо вручную настроить отдельные параметры. Значение по умолчанию для [QualitySettings](../qualitysettings/) — NormalQuality. |
| [get_Timeout](./get_timeout/)() | Получает тайм-аут процесса распознавания в миллисекундах. |
| static [ImportFromXml](./importfromxml/)(System::String) | Импортирует свойства [BarCode](../../aspose.barcode/) из указанного XML‑файла и применяет их к текущему экземпляру [BarCodeReader](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Импортирует свойства [BarCode](../../aspose.barcode/) из указанного XML‑потока и применяет их к текущему экземпляру [BarCodeReader](./). |
| [ReadBarCodes](./readbarcodes/)() | Считывает [BarCodeResult](../barcoderesult/) из изображения. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Устанавливает тип декодирования штрихкода, используемый для распознавания. Должен быть установлен до вызова [ReadBarCodes](./readbarcodes/). |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) позволяет вручную настраивать качество распознавания и скорость. Вы можете быстро установить [QualitySettings](../qualitysettings/) с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, либо вручную настроить отдельные параметры. Значение по умолчанию для [QualitySettings](../qualitysettings/) — NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | Устанавливает тайм-аут процесса распознавания в миллисекундах. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Устанавливает растровое изображение для распознавания. Должен вызываться до метода [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Устанавливает растровое изображение и области для распознавания. Должен вызываться до метода [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Устанавливает растровое изображение и область для распознавания. Должен вызываться до метода [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Устанавливает файл изображения для распознавания. Должен вызываться до метода [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Устанавливает поток изображения для распознавания. Должен вызываться до метода [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | Устанавливает кадр яркости и область для распознавания. Должен вызываться до метода [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Устанавливает кадр яркости и области для распознавания. Должен вызываться до метода [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | Устанавливает кадр яркости для распознавания. Должен вызываться до метода [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Устанавливает массив типов [SingleDecodeType](../singledecodetype/) для распознавания. Должен вызываться до метода [ReadBarCodes()](./readbarcodes/). |
## Примечания


Этот пример показывает, как обнаружить штрихкоды Code39 и Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
