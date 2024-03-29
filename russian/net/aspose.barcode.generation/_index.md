---
title: Aspose.BarCode.Generation
second_title: Справочник по API Aspose.BarCode для .NET
description: Aspose.BarCode.Generation содержащие общие классы для реализации функций генерации штрих-кода.
type: docs
weight: 50
url: /ru/net/aspose.barcode.generation/
---
**Aspose.BarCode.Generation** содержащие общие классы для реализации функций генерации штрих-кода.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters) | Параметры штрих-кода Почты Австралии. |
| [AztecParameters](./aztecparameters) | Параметры ацтеков. |
| [BarcodeGenerator](./barcodegenerator) | BarcodeGenerator для генерации внутренних изображений штрих-кода. |
| [BarcodeParameters](./barcodeparameters) | Параметры генерации штрих-кода. |
| [BaseEncodeType](./baseencodetype) | Базовый класс для SymbologyEncodeType. |
| [BaseGenerationParameters](./basegenerationparameters) | Параметры генерации изображения штрих-кода. |
| [BorderParameters](./borderparameters) | Параметры границы изображения штрих-кода |
| [CaptionParameters](./captionparameters) | Параметры подписи. |
| [CodabarParameters](./codabarparameters) | Параметры Codabar. |
| [CodablockParameters](./codablockparameters) | Параметры блока кода. |
| [Code16KParameters](./code16kparameters) | Параметры Code16K. |
| [CodetextParameters](./codetextparameters) | Параметры кодового текста. |
| [CouponParameters](./couponparameters) | Параметры купона. Используется для UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters) | Параметры панели данных. |
| [DataMatrixParameters](./datamatrixparameters) | Параметры DataMatrix. |
| [DotCodeParameters](./dotcodeparameters) | Параметры DotCode. |
| [EncodeTypes](./encodetypes) | Указывает тип кодируемого штрих-кода. |
| [ExtCodetextBuilder](./extcodetextbuilder) | Вспомогательный класс для автоматической генерации кодового текста в режиме расширенного кодового текста |
| [FontUnit](./fontunit) | Определяет определенный формат для текста, включая начертание шрифта, размер и атрибуты стиля. , где размер в свойстве Unit value. |
| [GS1CompositeBarParameters](./gs1compositebarparameters) | Параметры составного стержня GS1. |
| [ITFParameters](./itfparameters) | Параметры ITF. |
| [MaxiCodeParameters](./maxicodeparameters) | Параметры MaxiCode. |
| [Padding](./padding) | Параметры заполнения. |
| [PatchCodeParameters](./patchcodeparameters) | параметры PatchCode. |
| [Pdf417Parameters](./pdf417parameters) | параметры PDF417. Содержит параметры PDF417, MacroPDF417 и MicroPDF417. MacroPDF417 требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. MicroPDF417 в режиме структурированного добавления (аналогично режиму MacroPDF417) требует двух полей: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. |
| [PostalParameters](./postalparameters) | Почтовые параметры. Используется для Postnet, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder) | Расширенный генератор кодового текста для 2D штрих-кодов QR для режима ExtendedCodetext режима QrEncodeMode |
| [QrParameters](./qrparameters) | QR-параметры. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters) | Параметры структурированного добавления QR. |
| [SupplementParameters](./supplementparameters) | Дополнительные параметры. Используется для Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SymbologyEncodeType](./symbologyencodetype) | Тип кодирования символов. См. EncodeTypes, чтобы получить instance. |
| [Unit](./unit) | Указывает значение размера в разных единицах (пиксели, дюймы и т. д.). |
## перечисление

| перечисление | Описание |
| --- | --- |
| [AutoSizeMode](./autosizemode) | Определяет различные типы режимов автоматического изменения размера. |
| [AztecSymbolMode](./aztecsymbolmode) | Определяет режим символа Aztec. |
| [BarcodeClassifications](./barcodeclassifications) | Классификация символов |
| [BarCodeImageFormat](./barcodeimageformat) | Определяет формат файла изображения. |
| [BorderDashStyle](./borderdashstyle) | Определяет стиль пунктирных линий границы. |
| [CodabarChecksumMode](./codabarchecksummode) | Определяет алгоритм контрольной суммы для Codabar |
| [CodabarSymbol](./codabarsymbol) | Указывает начальный или конечный символ спецификации штрих-кода Codabar. |
| [Code128Emulation](./code128emulation) | Кодовые слова функций для эмуляции Code 128. Применяется только для MicroPDF417. Игнорируется для штрих-кодов PDF417 и MacroPDF417. |
| [CodeLocation](./codelocation) | Расположение кодового текста |
| [DataMatrixEccType](./datamatrixecctype) | Укажите тип ECC для кодирования. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Режим кодирования кодировщика DataMatrix, по умолчанию Auto |
| [ECIEncodings](./eciencodings) | Расширенные идентификаторы интерпретации канала. Он используется, чтобы сообщить считывателю штрих-кода подробности об используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки набора символов. В настоящее время он используется только для штрих-кода QR 2D. |
| [EnableChecksum](./enablechecksum) | Включить контрольную сумму при генерации одномерных штрих-кодов. |
| [FontMode](./fontmode) | Режим размера шрифта. |
| [ITF14BorderType](./itf14bordertype) | Тип границы штрих-кода ITF14 |
| [MacroCharacter](./macrocharacter) | Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. 05 Символ макроса преобразуется в "[)&gt;\u001E05\u001D" как заголовок декодированных данных и "\u001E\u0004" как конец декодированных данных. 06 Преобразование макроса преобразуется в "[)&gt;\u001E06\u001D" как заголовок декодированных данных и "\u001E\u0004" как конец декодированных данных. |
| [PatchFormat](./patchformat) | Формат кода исправления. Выберите PatchOnly, чтобы сгенерировать один PatchCode. Используйте формат страницы для создания страницы исправлений с кодами исправлений как borders |
| [Pdf417CompactionMode](./pdf417compactionmode) | Режим уплотнения штрих-кода Pdf417 |
| [Pdf417ErrorLevel](./pdf417errorlevel) | Уровень исправления ошибок штрих-кода pdf417, от уровня 0 до уровня 9, уровень 0 означает отсутствие исправления ошибок, уровень 9 означает лучшее исправление ошибок |
| [QREncodeMode](./qrencodemode) | Режим кодирования штрих-кодов QR. Рекомендуется использовать Auto с CodeTextEncoding = Encoding.UTF8 для латинских символов или цифр и Utf8BOM для символов Unicode. |
| [QREncodeType](./qrencodetype) | Режим выбора QR / MicroQR. Выберите ForceQR для стандартных символов QR, Auto для MicroQR. ForceMicroQR используется для строгой генерации символов MicroQR, если это возможно. |
| [QRErrorLevel](./qrerrorlevel) | Уровень исправления ошибок Рида-Соломона. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. |
| [QRVersion](./qrversion) | Версия QR-кода. От версии 1 до версии 40 для QR-кода и от M1 до M4 для MicroQr. |
| [TextAlignment](./textalignment) | Выравнивание текста. |
| [TwoDComponentType](./twodcomponenttype) | Тип 2D-компонента |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
