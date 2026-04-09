---
title: BarcodeParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Параметры генерации штрихкода.
type: docs
weight: 14
url: /ru/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Параметры генерации штрихкода.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | Параметры штрихкода AustralianPost. |
| [getAztec()](#getAztec--) | Параметры Aztec. |
| [getBarColor()](#getBarColor--) | Цвет полос. |
| [getBarHeight()](#getBarHeight--) | Высота полос 1D штрихкодов в значении [Unit](../../com.aspose.barcode.generation/unit). |
| [getBarWidthReduction()](#getBarWidthReduction--) | Получить значение уменьшения полос, используемое для компенсации растекания чернил при печати. |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Всегда отображать контрольную цифру в читаемом тексте для штрихкодов Code128 и GS1Code128. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Параметры Codabar. |
| [getCodablock()](#getCodablock--) | Параметры Codablock. |
| [getCode128()](#getCode128--) | Параметры Code128. |
| [getCode16K()](#getCode16K--) | Параметры Code16K. |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | Параметры Codetext. |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | Параметры купона. |
| [getDataBar()](#getDataBar--) | Параметры Databar. |
| [getDataMatrix()](#getDataMatrix--) | Параметры DataMatrix. |
| [getDotCode()](#getDotCode--) | Параметры DotCode. |
| [getEnableEscape()](#getEnableEscape--) | Указывает, объясняет ли символ "\\" как символ экранирования в свойстве CodeText. |
| [getFilledBars()](#getFilledBars--) | Получает значение, указывающее, заполнены ли штрихи. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | Параметры GS1 Composite Bar. |
| [getHanXin()](#getHanXin--) | Параметры HanXin. |
| [getITF()](#getITF--) | Параметры ITF. |
| [getMaxiCode()](#getMaxiCode--) | Параметры MaxiCode. |
| [getPadding()](#getPadding--) | Отступы штрихкода. |
| [getPatchCode()](#getPatchCode--) | Параметры PatchCode. |
| [getPdf417()](#getPdf417--) | Параметры PDF417. |
| [getPostal()](#getPostal--) | Почтовые параметры. |
| [getQR()](#getQR--) | Параметры QR, MicroQR и RectMicroQR. |
| [getSupplement()](#getSupplement--) | Параметры дополнения. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Только для 1D штрихкодов. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Соотношение широких штрихов к узким. |
| [getXDimension()](#getXDimension--) | x-размер — это минимальная ширина единицы штрихов или пробелов штрихкода. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Цвет полос. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Высота полос 1D штрихкодов в значении [Unit](../../com.aspose.barcode.generation/unit). |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Устанавливает значение уменьшения штрихов, используемое для компенсации растекания чернил при печати. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Всегда отображать контрольную цифру в читаемом тексте для штрихкодов Code128 и GS1Code128. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setCodeText(String value)](#setCodeText-java.lang.String-) |  |
| [setEnableEscape(boolean value)](#setEnableEscape-boolean-) | Указывает, объясняет ли символ "\\" как символ экранирования в свойстве CodeText. |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Устанавливает значение, указывающее, заполнены ли штрихи. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | Параметры GS1 Composite Bar. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Только для 1D штрихкодов. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Соотношение широких штрихов к узким. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-размер — это минимальная ширина единицы штрихов или пробелов штрихкода. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```




**Returns:**
float
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


Параметры штрихкода AustralianPost.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Параметры Aztec.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


Цвет штрихов. Значение по умолчанию: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Высота штрихов 1D штрихкодов в значении [Unit](../../com.aspose.barcode.generation/unit). Игнорируется, если свойство BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\\#setAutoSizeMode)) установлено в AutoSizeMode.Nearest или AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Получить значение уменьшения штрихов, используемое для компенсации растекания чернил при печати. Значение по умолчанию: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Всегда отображать контрольную цифру в читаемом тексте для штрихкодов Code128 и GS1Code128.

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodabar() {#getCodabar--}
```
public final CodabarParameters getCodabar()
```


Параметры Codabar.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Параметры Codablock.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Параметры Code128.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Параметры Code16K.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeText() {#getCodeText--}
```
public final String getCodeText()
```




**Returns:**
java.lang.String
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Параметры Codetext.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getComplexBarcode() {#getComplexBarcode--}
```
public final ComplexBarcode getComplexBarcode()
```




**Returns:**
[ComplexBarcode](../../com.aspose.barcode.generation/complexbarcode)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


Параметры купона. Используется для UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Параметры Databar.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


Параметры DataMatrix.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


Параметры DotCode.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getEnableEscape() {#getEnableEscape--}
```
public final boolean getEnableEscape()
```


Указывает, объясняет ли символ "\\" как символ экранирования в свойстве CodeText. Используется только для Pdf417, DataMatrix, Code128. Если EnableEscape равно true, "\\" будет интерпретироваться как специальный символ экранирования. В противном случае "\\" будет рассматриваться как обычный символ.

Aspose.BarCode поддерживает ввод десятичного ASCII кода и мнемоники для символов управления ASCII. Например, \\013 и \\\\CR обозначают CR.

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Получает значение, указывающее, заполнены ли штрихи. Только для 1D штрихкодов. Значение по умолчанию: true.

**Returns:**
boolean — значение, указывающее, заполнены ли штрихи.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


Параметры GS1 Composite Bar.

Этот пример показывает, как создать и сохранить изображение GS1 Composite Bar. Обратите внимание, что 1D и 2D тексты кода разделены символом '|'

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
```

**Returns:**
[GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters)
### getHanXin() {#getHanXin--}
```
public final HanXinParameters getHanXin()
```


Параметры HanXin.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


Параметры ITF.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


Параметры MaxiCode.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Отступы штрихкода. Значение по умолчанию: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


Параметры PatchCode.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


Параметры PDF417.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Почтовые параметры. Используется для Postnet, Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


Параметры QR, MicroQR и RectMicroQR.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Дополнительные параметры. Используется для Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Только для 1D штрихкодов. Если текст кода неверен и значение установлено в true — будет выброшено исключение. В противном случае текст кода будет скорректирован в соответствии со спецификацией штрихкода. Исключение всегда будет выброшено для: символьной системы Databar, если текст кода неверен. Исключение никогда не будет выброшено для: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128, если текст кода неверен.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Соотношение широких штрихов к узким. Значение по умолчанию: 3, то есть широкие штрихи в 3 раза шире узких. Используется для ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-dimension — это наименьшая ширина единицы штрихов или пробелов штрих‑кода. Увеличение этого параметра увеличит общую ширину изображения штрих‑кода. Игнорируется, если свойство BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) установлено в AutoSizeMode.Nearest или AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


Включить контрольную сумму при генерации 1D‑штрих‑кодов.

По умолчанию считается «Да» для символьных наборов, где контрольная сумма обязательна, и «Нет», где она возможна только.

Контрольная сумма возможна: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Контрольная сумма всегда используется: остальные символьные наборы

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarColor(int value) {#setBarColor-int-}
```
public final void setBarColor(int value)
```


Цвет штрихов. Значение по умолчанию: Color.Black.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Высота штрихов 1D штрихкодов в значении [Unit](../../com.aspose.barcode.generation/unit). Игнорируется, если свойство BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\\#setAutoSizeMode)) установлено в AutoSizeMode.Nearest или AutoSizeMode.Interpolation.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Устанавливает значение уменьшения штрихов, используемое для компенсации растекания чернил при печати. Значение по умолчанию: 0

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | Значение уменьшения штрихов, используемое для компенсации растекания чернил при печати. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Всегда отображать контрольную цифру в читаемом тексте для штрихкодов Code128 и GS1Code128.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Включить контрольную сумму при генерации 1D‑штрих‑кодов.

По умолчанию считается «Да» для символьных наборов, где контрольная сумма обязательна, и «Нет», где она возможна только.

Контрольная сумма возможна: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Контрольная сумма всегда используется: остальные символьные наборы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


Указывает, объясняет ли символ "\\" как символ экранирования в свойстве CodeText. Используется только для Pdf417, DataMatrix, Code128. Если EnableEscape равно true, "\\" будет интерпретироваться как специальный символ экранирования. В противном случае "\\" будет рассматриваться как обычный символ.

Aspose.BarCode поддерживает ввод десятичного ASCII кода и мнемоники для символов управления ASCII. Например, \\013 и \\\\CR обозначают CR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Устанавливает значение, указывающее, заполнены ли штрихи. Только для 1D‑штрих‑кодов. Значение по умолчанию: true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, заполнены ли штрихи. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


Параметры GS1 Composite Bar.

Этот пример показывает, как создать и сохранить изображение GS1 Composite Bar. Обратите внимание, что 1D и 2D тексты кода разделены символом '|'

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Только для 1D штрихкодов. Если текст кода неверен и значение установлено в true — будет выброшено исключение. В противном случае текст кода будет скорректирован в соответствии со спецификацией штрихкода. Исключение всегда будет выброшено для: символьной системы Databar, если текст кода неверен. Исключение никогда не будет выброшено для: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128, если текст кода неверен.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Соотношение широких штрихов к узким. Значение по умолчанию: 3, то есть широкие штрихи в 3 раза шире узких. Используется для ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-dimension — это наименьшая ширина единицы штрихов или пробелов штрих‑кода. Увеличение этого параметра увеличит общую ширину изображения штрих‑кода. Игнорируется, если свойство BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) установлено в AutoSizeMode.Nearest или AutoSizeMode.Interpolation.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

