---
title: DecodeType
second_title: Справочник по API Aspose.BarCode для .NET
description: Укажите тип считываемого штрих-кода.
type: docs
weight: 190
url: /ru/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Укажите тип считываемого штрих-кода.

```csharp
public static class DecodeType
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | Получает массив, представляющий AllSupportedTypes |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | Извлекает массив имен типов декодирования. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | Определяет, является ли указанный[`BaseDecodeType`](../basedecodetype) содержит любой одномерный штрих-код symbology |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | Определяет, является ли указанный[`BaseDecodeType`](../basedecodetype) содержит любой двумерный штрих-код symbology |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | Определяет, является ли указанный[`BaseDecodeType`](../basedecodetype) содержит любые почтовые штрих-коды symbology |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | Преобразует строковое представление SingleDecodeType в его экземпляр. Возвращаемое значение указывает, успешно ли выполнено преобразование. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | Указать наборы сканов по barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse)(string, out MultyDecodeType) | Преобразует строковое представление MultyDecodeType в его экземпляр. Возвращаемое значение указывает, успешно ли выполнено преобразование. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse_1)(string, out SingleDecodeType) | Преобразует строковое представление SingleDecodeType в его экземпляр. Возвращаемое значение указывает, успешно ли выполнено преобразование. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes) | Указывает, что данные будут проверяться со всеми доступными символами |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel) | Указывает, что данные должны быть декодированы с **Внутренний штрих-код электронной посылки Почты Австралии** спецификация штрих-кода |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost) | Указывает, что данные должны быть декодированы с **Почта Австралии** спецификация штрих-кода |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec) | Указывает, что данные должны быть декодированы с **ацтек** спецификация штрих-кода |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar) | Указывает, что данные должны быть декодированы с **КОДАБАР** спецификация штрих-кода |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf) | Указывает, что данные должны быть декодированы с **КодаблокF** спецификация штрих-кода |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11) | Указывает, что данные должны быть декодированы с **КОД 11** спецификация штрих-кода |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128) | Указывает, что данные должны быть декодированы с **КОД 128** спецификация штрих-кода |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k) | Указывает, что данные должны быть декодированы с **SCode16K** спецификация штрих-кода |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32) | Указывает, что данные должны быть декодированы с **Код32** пустая спецификация |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended) | Указывает, что данные должны быть декодированы с **Расширенный КОД 39** спецификация штрих-кода |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard) | Указывает, что данные должны быть декодированы с **Стандартный КОД 39** спецификация штрих-кода |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended) | Указывает, что данные должны быть декодированы с **Расширенный КОД 93** спецификация штрих-кода |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard) | Указывает, что данные должны быть декодированы с **Стандартный КОД 93** спецификация штрих-кода |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417) | Указывает, что данные должны быть декодированы с **КомпактныйPDF417** (Pdf417Truncated) спецификация штрих-кода |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded) | Указывает, что данные должны быть декодированы с **Расширенная панель данных GS1** спецификация штрих-кода |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked) | Указывает, что данные должны быть декодированы с **Расширенная панель данных GS1 с накоплением** спецификация штрих-кода |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited) | Указывает, что данные должны быть декодированы с **Панель данных GS1 ограничена** спецификация штрих-кода |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional) | Указывает, что данные должны быть декодированы с **Всенаправленная панель данных GS1** спецификация штрих-кода |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked) | Указывает, что данные должны быть декодированы с **Панель данных GS1 сложена** спецификация штрих-кода |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional) | Указывает, что данные должны быть декодированы с **GS1 Databar многоплоскостной многонаправленный** спецификация штрих-кода |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated) | Указывает, что данные должны быть декодированы с **Панель данных GS1 усечена** спецификация штрих-кода |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5) | Указывает, что данные должны быть декодированы с **ДатаЛоджик 2 из 5** пустая спецификация |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix) | Указывает, что данные должны быть декодированы с **DataMatrix** символика штрих-кода |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode) | Указывает, что данные должны быть декодированы с **Идентификационный код DeutschePost** спецификация штрих-кода |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode) | Указывает, что данные должны быть декодированы с **Лейт-код DeutschePost** спецификация штрих-кода |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode) | Указывает, что данные должны быть декодированы с **Точечный код** пустая спецификация |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix) | Указывает, что данные должны быть декодированы с **Точечный код** пустая спецификация |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13) | Указывает, что данные должны быть декодированы с **EAN-13** спецификация штрих-кода |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14) | Указывает, что данные должны быть декодированы с **EAN14** спецификация штрих-кода |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8) | Указывает, что данные должны быть декодированы с **EAN-8** спецификация штрих-кода |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128) | Указывает, что данные должны быть декодированы с **КОД GS1 128** спецификация штрих-кода |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix) | Указывает, что данные должны быть декодированы с **GS1DataMatrix** символика штрих-кода |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr) | Указывает, что данные должны быть декодированы с **GS1 QR** спецификация штрих-кода |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5) | Указывает, что данные должны быть декодированы с **ИАТА 2 из 5** Спецификация штрих-кода. IATA (Международная ассоциация воздушного транспорта) использует этот штрих-код для управления воздушными грузами. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5) | Указывает, что данные должны быть декодированы с **ПРОМЕЖУТОЧНЫЙ 2 из 5** спецификация штрих-кода |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn) | Указывает, что данные должны быть декодированы с **ISBN** спецификация штрих-кода |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn) | Указывает, что данные должны быть декодированы с **ISMN** спецификация штрих-кода |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn) | Указывает, что данные должны быть декодированы с **ISSN** спецификация штрих-кода |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25) | Указывает, что данные должны быть декодированы с **Почта Италии 25** спецификация штрих-кода |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14) | Указывает, что данные должны быть декодированы с **ITF14** спецификация штрих-кода |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6) | Указывает, что данные должны быть декодированы с **ITF6** спецификация штрих-кода |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417) | Указывает, что данные должны быть декодированы с **макросPDf417** спецификация штрих-кода |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark) | Указывает, что данные должны быть декодированы с **Почтовый знак Королевской почты** Спецификация штрих-кода. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5) | Указывает, что данные должны быть декодированы с **Матрица 2 из 5** спецификация штрих-кода |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode) | Указывает, что данные должны быть декодированы с **МаксиКод** спецификация штрих-кода |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b) | Указывает, что данные должны быть декодированы с **МКР Э-13Б** пустая спецификация |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417) | Указывает, что данные должны быть декодированы с **MicroPDF417** спецификация штрих-кода |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr) | Указывает, что данные должны быть декодированы с **МикроQR-код** спецификация штрих-кода |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes) | Указывает, что данные будут проверяться с наиболее часто используемыми символами |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi) | Указывает, что данные должны быть декодированы с **MSI Плесси** спецификация штрих-кода |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none) | Не указан тип декодирования. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode) | Указывает, что данные должны быть декодированы с помощью USPS **OneCode** спецификация штрих-кода |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc) | Указывает, что данные должны быть декодированы с **OPC** спецификация штрих-кода |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode) | Указывает, что данные должны быть декодированы с **Код исправления** Спецификация штрих-кода. Символика штрих-кода используется для автоматического сканирования |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417) | Указывает, что данные должны быть декодированы с **PDF417** символика штрих-кода |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode) | Указывает, что данные должны быть декодированы с **Фармакод** штрих-код. Эта символика также известна как фармацевтический двоичный код . |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet) | Указывает, что данные должны быть декодированы с **планета** спецификация штрих-кода |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes) | Указывает, что данные будут проверяться со всеми **1.5D Почтовый** символы штрих-кода, такие как **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet) | Указывает, что данные должны быть декодированы с **Постнет** спецификация штрих-кода |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn) | Указывает, что данные должны быть декодированы с **ПЗН**Спецификация штрих-кода. Этот символ также известен как Pharma Zentral Nummer . |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr) | Указывает, что данные должны быть декодированы с **QR код** спецификация штрих-кода |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc) | Указывает, что данные должны быть декодированы с **RM4SCC** Спецификация штрих-кода. RM4SCC (код клиента Royal Mail с 4 штатами) используется для автоматизированного процесса сортировки почты в Великобритании. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14) | Указывает, что данные должны быть декодированы с **SCC14** спецификация штрих-кода |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18) | Указывает, что данные должны быть декодированы с **SSCC18** спецификация штрих-кода |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5) | Указывает, что данные должны быть декодированы с **Стандарт 2 из 5** спецификация штрих-кода |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement) | Указывает, что данные должны быть декодированы с **Дополнение (EAN2, EAN5)** спецификация штрих-кода |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel) | Указывает, что данные должны быть декодированы с **Штрих-код почтовой посылки Швейцарии** спецификация штрих-кода |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d) | Указывает, что данные будут проверяться со всеми **1D** символы штрих-кода |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d) | Указывает, что данные будут проверяться со всеми **2D** символы штрих-кода |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca) | Указывает, что данные должны быть декодированы с **СКП-А** спецификация штрих-кода |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce) | Указывает, что данные должны быть декодированы с **СКП-Э** спецификация штрих-кода |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin) | Указывает, что данные должны быть декодированы с **ВИН** (идентификационный номер транспортного средства) спецификация штрих-кода |

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
