---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType класс"
linktitle: "DecodeType"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType класс. Указывает тип штрихкода для чтения в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Укажите тип штрих‑кода для чтения.

```cpp
class DecodeType
```

## Methods

| Method | Описание |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | Получает массив, представляющий AllSupportedTypes |
| static [GetNames](./getnames/)() | Получает массив имен типов декодирования. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Определяет, содержит ли указанный [BaseDecodeType](../basedecodetype/) какая‑либо 1D символьная система штрихкода |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Определяет, содержит ли указанный [BaseDecodeType](../basedecodetype/) какая‑либо 2D символьная система штрихкода |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Определяет, содержит ли указанный [BaseDecodeType](../basedecodetype/) какая‑либо почтовая символьная система штрихкода |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Преобразует строковое представление [SingleDecodeType](../singledecodetype/) в его экземпляр. Возвращаемое значение указывает, успешно ли выполнено преобразование или нет. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Укажите наборы сканирования по barcodeTypes |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Преобразует строковое представление [SingleDecodeType](../singledecodetype/) в его экземпляр. Возвращаемое значение указывает, успешно ли выполнено преобразование или нет. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Преобразует строковое представление [MultiDecodeType](../multidecodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование или нет. |
## Поля

| Поле | Описание |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Указывает, что данные будут проверяться со всеми доступными символьными системами |
| static [AustralianPosteParcel](./australianposteparcel/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Australian Post Domestic eParcel Barcode** |
| static [AustraliaPost](./australiapost/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Australia Post** |
| static [Aztec](./aztec/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Aztec** |
| static [Codabar](./codabar/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **CODABAR** |
| static [CodablockF](./codablockf/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **CodablockF** |
| static [Code11](./code11/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **CODE 11** |
| static [Code128](./code128/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **CODE 128** |
| static [Code16K](./code16k/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **SCode16K** |
| static [Code32](./code32/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Code32** |
| static [Code39](./code39/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Code 39** с базовым набором символов: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Code 39** с полным набором символов ASCII: ISO/IEC 16388 |
| static [Code93](./code93/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **CODE 93** |
| static [CompactPdf417](./compactpdf417/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **CompactPdf417** (Pdf417Truncated) |
| static [DatabarExpanded](./databarexpanded/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **GS1 Databar expanded** |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **GS1 Databar expanded stacked** |
| static [DatabarLimited](./databarlimited/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **GS1 Databar limited** |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **GS1 Databar omni-directional** |
| static [DatabarStacked](./databarstacked/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **GS1 Databar stacked** |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **GS1 Databar stacked omni-directional** |
| static [DatabarTruncated](./databartruncated/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **GS1 Databar truncated** |
| static [DataLogic2of5](./datalogic2of5/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **DataLogic 2 of 5** |
| static [DataMatrix](./datamatrix/) | Указывает, что данные должны быть декодированы с символикой штрихкода **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **DeutschePost Ident code** |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **DeutschePost Leit code** |
| static [DotCode](./dotcode/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **DotCode** |
| static [DutchKIX](./dutchkix/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **DotCode** |
| static [EAN13](./ean13/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **EAN-13** |
| static [EAN14](./ean14/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **EAN14** |
| static [EAN8](./ean8/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **EAN-8** |
| static [GS1Aztec](./gs1aztec/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **GS1 Aztec** |
| static [GS1Code128](./gs1code128/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **GS1 CODE 128** |
| static [GS1CompositeBar](./gs1compositebar/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **GS1 Composite Bar** |
| static [GS1DataMatrix](./gs1datamatrix/) | Указывает, что данные должны быть декодированы с символикой штрихкода **GS1DataMatrix** |
| static [GS1DotCode](./gs1dotcode/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **GS1 DotCode** |
| static [GS1HanXin](./gs1hanxin/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **GS1 Han Xin Code** |
| static [GS1MicroPdf417](./gs1micropdf417/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **MicroPdf417** |
| static [GS1QR](./gs1qr/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [HanXin](./hanxin/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **Han Xin Code** |
| static [HIBCAztecLIC](./hibcazteclic/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **HIBC LIC Aztec** |
| static [HIBCAztecPAS](./hibcaztecpas/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **HIBC PAS Aztec** |
| static [HIBCCode128LIC](./hibccode128lic/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **HIBC LIC Code128** |
| static [HIBCCode128PAS](./hibccode128pas/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **HIBC PAS Code128** |
| static [HIBCCode39LIC](./hibccode39lic/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **HIBC LIC Code39** |
| static [HIBCCode39PAS](./hibccode39pas/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **HIBC PAS Code39** |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** |
| static [HIBCQRLIC](./hibcqrlic/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [HIBCQRPAS](./hibcqrpas/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [IATA2of5](./iata2of5/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **IATA 2 of 5**. IATA (International Air Transport Association) использует этот штрихкод для управления воздушными грузами. |
| static [Interleaved2of5](./interleaved2of5/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ISBN** |
| static [ISMN](./ismn/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ISMN** |
| static [ISSN](./issn/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ISSN** |
| static [ItalianPost25](./italianpost25/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Italian Post 25** |
| static [ITF14](./itf14/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ITF14** |
| static [ITF6](./itf6/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ITF6** |
| static [JapanPost](./japanpost/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Japan Post** |
| static [MacroPdf417](./macropdf417/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MacroPdf417** |
| static [Mailmark](./mailmark/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Royal Mail Mailmark**. |
| static [Matrix2of5](./matrix2of5/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Matrix 2 of 5** |
| static [MaxiCode](./maxicode/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MaxiCode** |
| static [MicrE13B](./micre13b/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MICR E-13B** |
| static [MicroPdf417](./micropdf417/) | Указывает, что данные должны быть декодированы со спецификацией штрихкода **MicroPdf417** |
| static [MicroQR](./microqr/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MicroQR Code** |
| static [MostCommonTypes](./mostcommontypes/) | Указывает, что данные будут проверяться с использованием наиболее часто используемых символогий |
| static [MSI](./msi/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MSI Plessey** |
| static [None](./none/) | Неуказанный тип декодирования. |
| static [OneCode](./onecode/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода USPS **OneCode** |
| static [OPC](./opc/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **OPC** |
| static [PatchCode](./patchcode/) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Patch code**. Симвология штрихкода используется для автоматического сканирования |
| static [Pdf417](./pdf417/) | Указывает, что данные должны быть декодированы с использованием символогии штрихкода **Pdf417** |
| static [Pharmacode](./pharmacode/) | Указывает, что данные должны быть декодированы с использованием штрихкода **Pharmacode**. Эта симвология также известна как Pharmaceutical Binary Code |
| static [Planet](./planet/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Planet** |
| static [PostalTypes](./postaltypes/) | Указывает, что данные будут проверяться со всеми символьными системами штрихкода **1.5D Postal**, такими как **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Postnet** |
| static [PZN](./pzn/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **PZN**. Эта символьная система также известна как Pharma Zentral Nummer. Поддерживаются PZN7 и PZN8. |
| static [QR](./qr/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** |
| static [RectMicroQR](./rectmicroqr/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) используется в процессе автоматической сортировки почты в Великобритании. |
| static [SCC14](./scc14/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **SCC14** |
| static [SSCC18](./sscc18/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **SSCC18** |
| static [Standard2of5](./standard2of5/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Standard 2 of 5** |
| static [Supplement](./supplement/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Supplement(EAN2, EAN5)** |
| static [SwissPostParcel](./swisspostparcel/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **Swiss Post Parcel Barcode** |
| static [Types1D](./types1d/) | Указывает, что данные будут проверяться со всеми символьными системами штрихкода **1D** |
| static [Types2D](./types2d/) | Указывает, что данные будут проверяться со всеми символьными системами штрихкода **2D** |
| static [UPCA](./upca/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **UPC-A** |
| static [UPCE](./upce/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **UPC-E** |
| static [VIN](./vin/) | Указывает, что данные должны быть декодированы согласно спецификации штрихкода **VIN** (Vehicle Identification Number) |
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
