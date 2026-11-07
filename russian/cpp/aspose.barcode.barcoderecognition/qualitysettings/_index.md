---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings class"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings class. QualitySettings позволяет вручную настраивать качество и скорость распознавания. Вы можете быстро установить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxQuality, либо вручную настроить отдельные параметры. Значение по умолчанию для QualitySettings в C++ — NormalQuality."
type: docs
weight: 3100
url: /ru/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Позволяет движку распознавать штрихкоды с некорректной контрольной суммой или неверными значениями. Режим может использоваться для распознавания повреждённых штрихкодов с ошибочным текстом. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. Элемент штрихкода более низкого качества требует более сложных методов, что замедляет распознавание. |
| [get_ComplexBackground](./get_complexbackground/)() const | Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| [get_Deconvolution](./get_deconvolution/)() const | Режим деконволюции (восстановления изображений), определяющий уровень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, искажённое (свёрнутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология. |
| static [get_HighPerformance](./get_highperformance/)() | Предустановка качества распознавания HighPerformance. Штрихкоды высокого качества хорошо распознаются в этом режиме. |
| static [get_HighQuality](./get_highquality/)() | Предустановка качества распознавания HighQuality. Эта предустановка разработана для штрихкодов низкого качества. Позволяет обнаруживать сильно повреждённые штрихкоды. |
| [get_InverseImage](./get_inverseimage/)() const | Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркостью). |
| static [get_MaxQuality](./get_maxquality/)() | Предустановка качества распознавания MaxQuality. Эта предустановка разработана для распознавания всех возможных штрихкодов, даже некорректных штрихкодов. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension. |
| static [get_NormalQuality](./get_normalquality/)() | Предустановка качества распознавания NormalQuality. Подходит для большинства штрихкодов. |
| [get_XDimension](./get_xdimension/)() const | Режим [Recognition](../../aspose.barcode.barcoderecognition.recognition/) задаёт размер (от 1 до бесконечности) минимального элемента штрихкода: ячейки матрицы или полосы. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Позволяет движку распознавать штрихкоды с некорректной контрольной суммой или неверными значениями. Режим может использоваться для распознавания повреждённых штрихкодов с ошибочным текстом. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. Элемент штрихкода более низкого качества требует более сложных методов, что замедляет распознавание. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Режим деконволюции (восстановления изображений), определяющий уровень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, искажённое (свёрнутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (яркостью). |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | Минимальный размер XDimension в пикселях, используемый с UseMinimalXDimension. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | Режим [Recognition](../../aspose.barcode.barcoderecognition.recognition/) задаёт размер (от 1 до бесконечности) минимального элемента штрихкода: ячейки матрицы или полосы. |
## Примечания


Этот пример показывает, как использовать [QualitySettings](./) с [BarCodeReader](../barcodereader/)
```cpp
[C#]
//установить режим распознавания HighPerformance
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//установить режим распознавания HighQuality
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//установить режим распознавания HighPerformance для небольших штрихкодов
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//установить режим распознавания HighPerformance для низкокачественных штрихкодов
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
