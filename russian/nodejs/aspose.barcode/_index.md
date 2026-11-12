---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Пространство имён aspose.barcode предоставляет классы и перечисления для создания, настройки и декодирования широкого спектра типов штрихкодов в Node.js через Java."
type: docs
weight: 10
url: /ru/nodejs/aspose.barcode/
---
Используйте эти типы для настройки параметров генерации штрихкодов, таких как форматирование адресов, региональные спецификации и расширенные параметры для Aztec и других симболологий. Пространство имён включает вспомогательные средства для построения расширённых текстов кода и обработки специализированных почтовых стандартов.

## Классы

| Класс | Описание |
| --- | --- |
| [Address](./address/) | Адрес кредитора или должника. Вы можете задать улицу, номер дома, почтовый индекс и город (тип структурированный адрес) o |
| [AlternativeScheme](./alternativescheme/) | Инструкции альтернативной схемы оплаты |
| [AustraliaPostSettings](./australiapostsettings/) | Параметры декодирования AustraliaPost. Содержит параметры, влияющие на распознанные данные симболологии AustraliaPost |
| [AustralianPostParameters](./australianpostparameters/) | Параметры штрихкода AustralianPost. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Генератор расширённого текста кода для штрихкодов Aztec в режиме ExtendedCodetext свойства AztecEncodeMode. Используйте свойство TwoDDisplayText. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Сохраняет специальные данные распознанного штрихкода Aztec. Этот пример показывает, как получить необработанные значения Aztec, let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Параметры Aztec. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Сохраняет расширенные параметры распознанного штрихкода |
| [BarCodeReader](./barcodereader/) | BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрихкодов, после чего может выполнять операцию ReadBarCodes operatio |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Представляет регион распознанного штрихкода и угол штрихкода |
| [BarCodeResult](./barcoderesult/) | Сохраняет данные распознанного штрихкода, такие как тип SingleDecodeType, `string` codetext, BarCodeRegionParameters region и другие p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator для генерации изображений штрихкодов на сервере. поддерживаемые симболологии: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Параметры генерации штрих‑кода. |
| [BarcodeSettings](./barcodesettings/) | Основные параметры декодирования BarCode. Содержит параметры, влияющие на распознанные данные. |
| [BaseGenerationParameters](./basegenerationparameters/) | Параметры генерации изображения штрих‑кода. |
| [BorderParameters](./borderparameters/) | Параметры границы изображения штрих‑кода |
| [CMYKColor](./cmykcolor/) | Класс для цвета CMYK. Нулевой экземпляр означает, что CMYK не используется, а применяется цвет по умолчанию RGB. |
| [CaptionParameters](./captionparameters/) | Параметры подписи. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Сохраняет дополнительную информацию Codabar распознанного штрих‑кода |
| [CodabarParameters](./codabarparameters/) | Параметры Codabar. |
| [CodablockParameters](./codablockparameters/) | Параметры Codablock. |
| [Code128DataPortion](./code128dataportion/) | Содержит данные подтипа для штрих‑кода типа Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Сохраняет специальные данные распознанного штрих‑кода Code128. Представляет регион распознанного штрих‑кода и угол штрих‑кода. |
| [Code128Parameters](./code128parameters/) | Параметры Code128. |
| [Code16KParameters](./code16kparameters/) | Параметры Code16K. |
| [CodetextParameters](./codetextparameters/) | Параметры Codetext. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator для генерации изображений сложных штрих‑кодов бекэнда (например, SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader декодирует codetext в указанный тип сложного штрих‑кода. |
| [CouponParameters](./couponparameters/) | Параметры купона. Используется для UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Сохраняет дополнительную информацию DataBar распознанного штрих‑кода |
| [DataBarParameters](./databarparameters/) | Параметры Databar. |
| [DataElement](./dataelement/) | Представляет специфическое для юрисдикции поле данных, используемое в документах, например ElementID = "ZVA" со значением Value = "01". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Генератор расширенного codetext для 2D штрих‑кодов DataMatrix в режиме ExtendedCodetext режима DataMatrixEncodeMode //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Сохраняет специальные данные распознанного штрих‑кода DataMatrix. Этот пример показывает, как получить необработанные значения DataMatrix, let generator = |
| [DataMatrixParameters](./datamatrixparameters/) | Параметры DataMatrix. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Генератор расширенного codetext для 2D штрих‑кодов DotCode в режиме ExtendedCodetext режима DotCodeEncodeMode |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Сохраняет специальные данные распознанного штрих‑кода DotCode. Этот пример показывает, как получить необработанные значения DotCode |
| [DotCodeParameters](./dotcodeparameters/) | Параметры DotCode. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Вспомогательный класс для автоматической генерации кодового текста в режиме Extended Codetext Mode |
| [FontUnit](./fontunit/) | Определяет определённый формат текста, включая шрифт, размер и атрибуты стиля, где размер задаётся в свойстве Unit value. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Сохраняет специальные данные распознанного штрихкода `GS1 Composite Bar ` |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | Параметры GS1 Composite bar. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные и вторичные данные. Этот пример |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Базовый класс для кодирования и декодирования текста, встроенного в код HIBC LIC. Этот пример показывает, как декодировать необработанный HIBC LI |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные данные. Этот пример показывает, как |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит вторичные данные. |
| [HIBCPASCodetext](./hibcpascodetext/) | Класс для кодирования и декодирования текста, встроенного в код HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord/) | Класс для хранения записи HIBC PAS. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Генератор расширенного кодового текста для Han Xin Code в расширенном режиме HanXinEncodeMode //Extended codetext mode //create cod |
| [HanXinParameters](./hanxinparameters/) | Параметры Han Xin. |
| [HslaColor](./hslacolor/) | Класс для представления цвета HSLA (Hue, Saturation, Lightness, Alpha) |
| [IComplexCodetext](./icomplexcodetext/) | Интерфейс для сложного кодового текста, используемого с ComplexBarcodeGenerator. |
| [ITFParameters](./itfparameters/) | Параметры ITF. |
| [ImageParameters](./imageparameters/) | Параметры изображения. |
| [License](./license/) | Предоставляет методы для лицензирования компонента. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Класс для кодирования и декодирования текста, встроенного в код Royal Mail 2D Mailmark. |
| [MailmarkCodetext](./mailmarkcodetext/) | Класс для кодирования и декодирования текста, встроенного в 4-state код Royal Mailmark. |
| [MandatoryFields](./mandatoryfields/) | Обязательные элементы (поля) карты |
| [MaxiCodeCodetext](./maxicodecodetext/) | Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode. Этот пример показывает, как декодировать необработанный MaxiCod |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режима 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режима 3. Этот пример показывает, как кодировать и |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Генератор расширенного кодового текста для штрихкодов MaxiCode в режиме ExtendedCodetext режима MaxiCodeEncodeMode Use TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Сохраняет дополнительную информацию MaxiCode распознанного штрихкода |
| [MaxiCodeParameters](./maxicodeparameters/) | Параметры MaxiCode. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Класс для кодирования и декодирования текста MaxiCode для режимов 4, 5 и 6. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Класс для кодирования и декодирования текста MaxiCode для режимов 4, 5 и 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Класс для кодирования и декодирования стандартного второго сообщения для штрихкода MaxiCode. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | Класс для кодирования и декодирования стандартного второго сообщения для штрихкода MaxiCode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode, для режимов 2 и 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Класс для кодирования и декодирования структурированного второго сообщения для штрихкода MaxiCode. |
| [OneDExtendedParameters](./onedextendedparameters/) | Сохраняет специальные данные 1D распознанного штрихкода, такие как отдельный текст и контрольная сумма. |
| [OptionalFields](./optionalfields/) | Опциональные элементы (поля) карты. |
| [Padding](./padding/) | Параметры заполнения. |
| [PatchCodeParameters](./patchcodeparameters/) | Параметры PatchCode. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Сохраняет метаданные MacroPdf417 распознанного штрихкода. |
| [Pdf417Parameters](./pdf417parameters/) | Параметры PDF417. Содержит параметры PDF417, MacroPDF417, MicroPDF417 и GS1MicroPdf417. MacroPDF417 требует два поля. |
| [PdfParameters](./pdfparameters/) | Обёртка параметров PDF. Ожидает экземпляр базового `mwObject`, предоставляющего соответствующие методы получения/установки. |
| [PostalParameters](./postalparameters/) | Почтовые параметры. Используется для Postnet, Planet. |
| [PrimaryData](./primarydata/) | Класс для хранения первичных данных HIBC LIC. |
| [QRExtendedParameters](./qrextendedparameters/) | Сохраняет информацию о Structured Append QR распознанного штрихкода. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Генератор расширенного текста для 2D QR штрихкодов в режиме ExtendedCodetext режима QREncodeMode. Используйте свойство Display2DText класса B. |
| [QrParameters](./qrparameters/) | Параметры QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | Параметры структурированного добавления QR. |
| [Quadrangle](./quadrangle/) | Сохраняет набор из четырёх точек, представляющих регион в виде четырёхугольника. |
| [QualitySettings](./qualitysettings/) | QualitySettings позволяет вручную настраивать качество и скорость распознавания. Вы можете быстро настроить QualitySettings с помощью em. |
| [RecognitionAbortedException](./recognitionabortedexception/) | Представляет исключение прерывания распознавания, которое выбрасывается при превышении тайм‑аута во время распознавания с BarCodeReader. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Класс для хранения вторичных и дополнительных данных HIBC LIC. |
| [SubfileProperties](./subfileproperties/) | Свойства подфайла USA DL, смещение и длина устанавливаются автоматически. |
| [SupplementParameters](./supplementparameters/) | Дополнительные параметры. Используется для Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | Параметры SVG. |
| [SwissQRBill](./swissqrbill/) | Данные счета SwissQR |
| [SwissQRCodetext](./swissqrcodetext/) | Класс для кодирования и декодирования текста, встроенного в код SwissQR. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Класс для кодирования и декодирования текста, встроенного в код PDF417 водительского удостоверения США. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Класс для полей, специфичных для юрисдикции, в водительском удостоверении США |
| [Unit](./unit/) | Указывает значение размера в разных единицах (пиксели, дюймы и т.д.). |
