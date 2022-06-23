---
title: QualitySettings
second_title: Справочник по API Aspose.BarCode для .NET
description: QualitySettings позволяет настроить качество и скорость распознавания вручную. Вы можете быстро настроить QualitySettings с помощью встроенных пресетовHighPerformance NormalQuality HighQuality MaxBarCodes или вручную настроить отдельные параметры. Значением QualitySettings по умолчанию является NormalQuality.
type: docs
weight: 250
url: /ru/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings позволяет настроить качество и скорость распознавания вручную. Вы можете быстро настроить QualitySettings с помощью встроенных пресетов:HighPerformance, NormalQuality, HighQuality, MaxBarCodes или вручную настроить отдельные параметры. Значением QualitySettings по умолчанию является NormalQuality.

```csharp
public sealed class QualitySettings
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance) { get; } | Предустановка качества распознавания HighPerformance. В этом режиме хорошо распознаются штрих-коды высокого качества. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality) { get; } | Предустановка качества распознавания HighQuality. Этот пресет разработан для штрих-кодов низкого качества. Позволяет обнаруживать диагональные и сильно поврежденные штрих-коды. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection) { get; } | Предустановка качества распознавания HighQualityDetection. То же, что и NormalQuality, но с высоким качеством[`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes) { get; } | Предустановка качества распознавания MaxBarCodes. Этот пресет разработан для распознавания всех возможных штрих-кодов, даже неправильных штрих-кодов. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection) { get; } | Предустановка качества распознавания MaxQualityDetection. То же, что и NormalQuality, но с наивысшим качеством[`DetectorSettings`](./detectorsettings). Позволяет обнаруживать диагональные и поврежденные штрих-коды. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality) { get; } | Стандарт качества распознавания NormalQuality. Подходит для большинства штрих-кодов |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground) { get; set; } | Позволяет движку распознавать цветные штрих-коды на цветном фоне как дополнительное сканирование. Крайне медленный режим. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes) { get; set; } | Позволяет движку Datamatrix распознавать пунктирные промышленные штрих-коды Datamatrix. Медленный режим, который помогает только для пунктирных штрих-кодов, состоящих из точек. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage) { get; set; } | Позволяет движку распознавать уменьшенное изображение как дополнительное сканирование. Размер для уменьшения выбирается внутренними алгоритмами движка. Режим помогает распознавать штрих-коды, которые зашумлены и размыты, но захвачены с высоким разрешением. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap) { get; set; } | Позволяет движку использовать промежутки между сканами для увеличения скорости распознавания. Режим может вызвать проблемы с распознаванием штрих-кодов небольшой высоты. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes) { get; set; } | Позволяет движку распознавать штрих-коды с неверной контрольной суммой или неправильными значениями. Режим можно использовать для распознавания поврежденных штрих-кодов с неправильным текстом. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage) { get; set; } | Позволяет движку распознавать инверсное цветное изображение как дополнительный скан. Режим можно использовать, когда штрих-код белый на черном фоне. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing) { get; set; } | Позволяет движку включить срединное сглаживание в качестве дополнительного сканирования. Режим помогает распознавать зашумленные штрих-коды. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving) { get; set; } | Позволяет движку для почтовых штрих-кодов распознавать слегка зашумленные изображения. Режим помогает распознавать слегка поврежденные почтовые штрих-коды. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector) { get; set; } | Позволяет движку для 1D штрих-кодов быстро распознавать высококачественные штрих-коды, которые заполняют почти все изображение. Режим помогает быстро распознавать сгенерированные штрих-коды из Интернета. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration) { get; set; } | Позволяет движку для одномерных штрих-кодов распознавать штрих-коды с одиночными стертыми/склеенными штрихами в шаблоне. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration) { get; set; } | Позволяет движку для QR/MicroQR распознавать поврежденные штрих-коды MicroQR. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage) { get; set; } | Позволяет движку распознавать обычное изображение без каких-либо реставраций в качестве основного скана. Режим распознавания изображения как есть. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering) { get; set; } | Позволяет движку распознавать штрих-коды с шумом соли и бумаги. Режим может удалить небольшой шум с белыми и черными точками. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving) { get; set; } | Позволяет движку распознавать изображение без мелких белых пятен как дополнительный скан. Режим помогает распознавать зашумленное изображение, а также медианную сглаживающую фильтрацию. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants) { get; set; } | Позволяет движку распознавать одномерные штрих-коды с контрольной суммой, проверяя больше вариантов распознавания. Значение по умолчанию:Ложь. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings) { get; set; } | Настройки детектора штрих-кода. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly) { get; set; } | Позволяет движку для одномерных штрих-кодов быстро распознавать средний фрагмент изображения и возвращать результат без использования трудоемких алгоритмов. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize) { get; set; } | Размер окна для медианного сглаживания. Типичные значения — 3 или 4. Значение по умолчанию — 3. Должен быть установлен параметр AllowMedianSmoothing. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes) { get; set; } | Позволяет движку распознавать крошечные штрих-коды на больших изображениях. Игнорируется, если[`AllowIncorrectBarcodes`](./allowincorrectbarcodes)имеет значение True. Значение по умолчанию:Ложь. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector) { get; set; } | Переключение на старый детектор штрих-кода. |

### Примеры

В этом примере показано, как использовать настройки качества с BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    //установить режим высокой производительности
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    //режим нормального качества установлен по умолчанию
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    // установить режим высокого качества с низкой скоростью распознавания 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // установить режим максимального количества штрих-кодов, который пытается найти все возможные штрих-коды, даже неправильные. Самый медленный режим распознавания
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    //установить режим высокой производительности
   reader.QualitySettings = QualitySettings.HighPerformance;
    //устанавливаем отдельные options
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    //режим по умолчанию — NormalQuality
    //устанавливаем отдельные options
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'установить режим высокой производительности
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'режим нормального качества установлен по умолчанию
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    //установить режим высокого качества с низкой скоростью распознавания
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    //установить режим максимального количества штрих-кодов, который пытается найти все возможные штрих-коды, даже неправильные. Самый медленный режим распознавания
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   //установить режим высокой производительности
   reader.QualitySettings = QualitySettings.HighPerformance
   //установить отдельные параметры
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   //режим по умолчанию — NormalQuality
   //установить отдельные параметры
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Смотрите также

* пространство имен [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
