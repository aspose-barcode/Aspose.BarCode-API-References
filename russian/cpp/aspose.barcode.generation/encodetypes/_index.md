---
title: "Aspose::BarCode::Generation::EncodeTypes класс"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::EncodeTypes класс. Указывает тип штрих‑кода для кодирования в C++."
type: docs
weight: 2300
url: /ru/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


Указывает тип штрихкода для кодирования.

```cpp
class EncodeTypes
```

## Methods

| Method | Описание |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | Указывает, что данные будут проверяться со всеми доступными символьными системами. |
| static [GetNames](./getnames/)() | Получает массив имён типов кодирования. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Преобразует строковое представление [BaseEncodeType](../baseencodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Преобразует строковое представление [BaseEncodeType](../baseencodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование. |
## Поля

| Поле | Описание |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **Australian Post Domestic eParcel Barcode** |
| static [AustraliaPost](./australiapost/) | Представляет клиентский [BarCode](../../aspose.barcode/) Australia Post |
| static [Aztec](./aztec/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **Aztec** |
| static [Codabar](./codabar/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **CODABAR** |
| static [CodablockF](./codablockf/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **Codablock-F**. |
| static [Code11](./code11/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **CODE 11** |
| static [Code128](./code128/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **CODE 128** |
| static [Code16K](./code16k/) | Представляет штрихкод Code 16K. |
| static [Code32](./code32/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **Code32** |
| static [Code39](./code39/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **Code 39** с базовым набором символов: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **Code 39** с полным набором ASCII‑символов: ISO/IEC 16388 |
| static [Code93](./code93/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **CODE 93** |
| static [DatabarExpanded](./databarexpanded/) | Представляет расширенный штрихкод GS1 Databar. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Представляет расширенный штабелируемый штрихкод GS1 Databar. |
| static [DatabarLimited](./databarlimited/) | Представляет ограниченный штрихкод GS1 Databar. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **GS1 Databar omni-directional**. |
| static [DatabarStacked](./databarstacked/) | Представляет штабелируемый штрихкод GS1 Databar. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Представляет штабелируемый омни‑направленный штрихкод GS1 Databar. |
| static [DatabarTruncated](./databartruncated/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **GS1 Databar truncated**. |
| static [DataLogic2of5](./datalogic2of5/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **DataLogic 2 of 5** |
| static [DataMatrix](./datamatrix/) | 2‑мерная символьная система штрихкода DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Представляет штрихкод Deutsch Post, эта символьная система также известна как Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Представляет штрихкод Deutsch Post Leitcode, также известный как German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| static [DotCode](./dotcode/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **DotCode** |
| static [DutchKIX](./dutchkix/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **Dutch KIX** |
| static [EAN13](./ean13/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **EAN-13** |
| static [EAN14](./ean14/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **EAN14** |
| static [EAN8](./ean8/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **EAN-8** |
| static [GS1Aztec](./gs1aztec/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **GS1 Aztec**. Текст кода должен содержать скобки для AI. |
| static [GS1CodablockF](./gs1codablockf/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **GS1 Codablock-F**. Текст кода должен содержать скобки для AI. |
| static [GS1Code128](./gs1code128/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **GS1 Code 128**. Текст кода должен содержать скобки для AI. |
| static [GS1CompositeBar](./gs1compositebar/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **GS1 Composite Bar**. Текст кода должен содержать скобки для AI. 1D‑текст кода и 2D‑текст кода должны быть разделены символом '/' |
| static [GS1DataMatrix](./gs1datamatrix/) | 2D‑символика штрихкода DataMatrix с форматом строки GS1 |
| static [GS1DotCode](./gs1dotcode/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **GS1 DotCode**. Текст кода должен содержать скобки для AI. |
| static [GS1HanXin](./gs1hanxin/) | 2D‑символика штрихкода HanXin с форматом строки GS1 |
| static [GS1MicroPdf417](./gs1micropdf417/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **GS1MicroPdf417** |
| static [GS1QR](./gs1qr/) | 2D‑символика штрихкода QR с форматом строки GS1 |
| static [HanXin](./hanxin/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **Han Xin** |
| static [HIBCAztecLIC](./hibcazteclic/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC LIC Aztec**. |
| static [HIBCAztecPAS](./hibcaztecpas/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC PAS Aztec**. |
| static [HIBCCode128LIC](./hibccode128lic/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC LIC Code128**. |
| static [HIBCCode128PAS](./hibccode128pas/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC PAS Code128**. |
| static [HIBCCode39LIC](./hibccode39lic/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC LIC Code39**. |
| static [HIBCCode39PAS](./hibccode39pas/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC PAS Code39**. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC LIC DataMatrix**. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC PAS DataMatrix**. |
| static [HIBCQRLIC](./hibcqrlic/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC LIC QR**. |
| static [HIBCQRPAS](./hibcqrpas/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **HIBC PAS QR**. |
| static [IATA2of5](./iata2of5/) | Представляет штрихкод IATA 2 of 5. IATA (International Air Transport Association) использует этот штрихкод для управления воздушными грузами. |
| static [Interleaved2of5](./interleaved2of5/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **ISBN** |
| static [ISMN](./ismn/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **ISMN** |
| static [ISSN](./issn/) | Указывает, что данные должны быть закодированы согласно спецификации штрихкода **ISSN** |
| static [ItalianPost25](./italianpost25/) | Представляет штрих‑код Italian Post 25. |
| static [ITF14](./itf14/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **ITF14** |
| static [ITF6](./itf6/) | Представляет штрих‑код ITF-6. |
| static [JapanPost](./japanpost/) | Представляет Japan Post [BarCode](../../aspose.barcode/) |
| static [MacroPdf417](./macropdf417/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **MacroPdf417** |
| static [Mailmark](./mailmark/) | Представляет штрих‑код Royal Mail Mailmark. |
| static [Matrix2of5](./matrix2of5/) | Представляет Matrix 2 of 5 [BarCode](../../aspose.barcode/) |
| static [MaxiCode](./maxicode/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **MaxiCode** |
| static [MicroPdf417](./micropdf417/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **MicroPdf417** |
| static [MicroQR](./microqr/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **MicroQR Code** |
| static [MSI](./msi/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **MSI Plessey** |
| static [None](./none/) | Неуказанный тип кодирования. |
| static [OneCode](./onecode/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода USPS **OneCode** |
| static [OPC](./opc/) | Представляет штрих‑код OPC (Optical Product Code), также известный как VCA Barcode, VCA OPC, Vision Council of America OPC Barcode. |
| static [PatchCode](./patchcode/) | Представляет штрих‑код Patch code |
| static [Pdf417](./pdf417/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **Pdf417** |
| static [Pharmacode](./pharmacode/) | Представляет штрих‑код Pharmacode. |
| static [Planet](./planet/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **Planet** |
| static [Postnet](./postnet/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **Postnet** |
| static [PZN](./pzn/) | Представляет штрих‑код PZN. Эта символьная система также известна как Pharmacy central number, Pharmazentralnummer. Поддерживаются PZN7 и PZN8. PZN7 генерируется из 6 или менее цифр, например "123456". PZN8 генерируется из 7 или более цифр, например "1234567". Предоставленная последняя контрольная цифра игнорируется и генерируется движком штрих‑кода. |
| static [QR](./qr/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **QR Code** |
| static [RectMicroQR](./rectmicroqr/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | Представляет штрих‑код RM4SCC. RM4SCC (Royal Mail 4-state Customer Code) используется в процессе автоматической сортировки почты в Великобритании. |
| static [SCC14](./scc14/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **SCC14** |
| static [SingaporePost](./singaporepost/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **Singapore Post Barcode** |
| static [SSCC18](./sscc18/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **SSCC18** |
| static [Standard2of5](./standard2of5/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **Standard 2 of 5** |
| static [SwissPostParcel](./swisspostparcel/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **Swiss Post Parcel Barcode**. Поддерживаемые типы: Внутренняя почта, Международная почта, Дополнительные услуги (новое) |
| static [UPCA](./upca/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **UPC-A** |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **UPC coupon with GS1-128 Extended Code**. Пример входной строки: BarcodeGenerator.Codetext = "514141100906(8102)03", где часть UPCA равна "514141100906", часть GS1Code128 — (8102)03. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **UPC coupon with GS1 DataBar addition**. Пример входной строки: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", где часть UPCA равна "514141100906", часть Databar — "(8110)106141416543213500110000310123196000". Чтобы изменить подпись, используйте Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | Указывает, что данные должны быть закодированы согласно спецификации штрих‑кода **UPC-E** |
| static [VIN](./vin/) | Представляет штрих‑код VIN (Vehicle Identification Number). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
