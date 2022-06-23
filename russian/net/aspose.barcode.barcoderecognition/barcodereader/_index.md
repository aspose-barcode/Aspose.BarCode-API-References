---
title: BarCodeReader
second_title: Справочник по API Aspose.BarCode для .NET
description: BarCodeReader инкапсулирует изображение которое может содержать один или несколько штрих-кодов затем может выполнять операцию ReadBarCodes для обнаружения штрих-кодов.
type: docs
weight: 60
url: /ru/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрих-кодов, затем может выполнять операцию ReadBarCodes для обнаружения штрих-кодов.

```csharp
public class BarCodeReader : Component
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BarCodeReader](barcodereader#constructor)() | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader)со значениями по умолчанию. Требуется установить изображение (SetBitmapImage()) перед вызовом метода ReadBarCodes(). |
| [BarCodeReader](barcodereader#constructor_1)(Bitmap) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader)из изображения. |
| [BarCodeReader](barcodereader#constructor_8)(Stream) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_11)(string) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader)из файла. |
| [BarCodeReader](barcodereader#constructor_2)(Bitmap, BaseDecodeType) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_3)(Bitmap, params BaseDecodeType[]) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_9)(Stream, BaseDecodeType) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_10)(Stream, params BaseDecodeType[]) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_12)(string, BaseDecodeType) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_13)(string, params BaseDecodeType[]) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |
| [BarCodeReader](barcodereader#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Инициализирует новый экземпляр класса[`BarCodeReader`](../barcodereader). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings) { get; } | Основные параметры декодирования штрих-кода. Содержит параметры, влияющие на распознаваемые данные. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes) { get; } | Распознается[`BarCodeResult`](../barcoderesult)s array |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount) { get; } | Получает количество распознанных штрих-кодов |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings) { get; set; } | QualitySettings позволяет настроить качество и скорость распознавания вручную. Вы можете быстро настроить QualitySettings с помощью встроенных пресетов:HighPerformance, NormalQuality, HighQuality, MaxBarCodes или вручную настроить отдельные параметры. Значением QualitySettings по умолчанию является NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout) { get; set; } | Получает или задает время ожидания процесса распознавания в миллисекундах. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings) { get; } | Получает настройки использования ядер процессора. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml)(Stream) | Импортирует свойства BarCode из указанного xml-потока и применяет их к текущему экземпляру BarCodeReader. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml_1)(string) | Импортирует свойства BarCode из указанного xml-файла и применяет их к текущему экземпляру BarCodeReader. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort)() | Функция запрашивает завершение текущего сеанса распознавания из другого потока. Abort является неблокируемым методом и возвращает управление сразу после вызова. Метод следует использовать, когда процесс распознавания слишком длительный. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml)(Stream) | Экспортирует свойства BarCode в указанный xml-поток |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml_1)(string) | Экспортирует свойства BarCode в указанный xml-файл |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes)() | Читает[`BarCodeResult`](../barcoderesult)s из образа. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage)(Bitmap) | Устанавливает растровое изображение для распознавания. Должен вызываться перед методом ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_3)(Stream) | Устанавливает поток изображений для распознавания. Должен вызываться перед методом ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_4)(string) | Устанавливает файл изображения для распознавания. Должен вызываться перед методом ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_1)(Bitmap, Rectangle) | Задает растровое изображение и область для распознавания. Должен вызываться перед методом ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_2)(Bitmap, Rectangle[]) | Задает растровое изображение и области для распознавания. Должен вызываться перед методом ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype)(BaseDecodeType) | Устанавливает тип декодирования для распознавания. Должен вызываться перед методом ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype_1)(params SingleDecodeType[]) | Наборы[`SingleDecodeType`](../singledecodetype)массив типов для распознавания. Должен вызываться перед методом ReadBarCodes(). |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Смотрите также

* пространство имен [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
