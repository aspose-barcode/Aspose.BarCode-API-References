---
title: "BarcodeParameters"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "바코드 생성 매개변수."
type: docs
weight: 14
url: /ko/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

바코드 생성 매개변수.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost 바코드 매개변수. |
| [getAztec()](#getAztec--) | Aztec 매개변수. |
| [getBarColor()](#getBarColor--) | 바 색상. |
| [getBarHeight()](#getBarHeight--) | 1D 바코드 바의 높이를 [Unit](../../com.aspose.barcode.generation/unit) 값으로 지정합니다. |
| [getBarWidthReduction()](#getBarWidthReduction--) | 인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 가져옵니다. |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar 매개변수. |
| [getCodablock()](#getCodablock--) | Codablock 매개변수. |
| [getCode128()](#getCode128--) | Code128 매개변수. |
| [getCode16K()](#getCode16K--) | Code16K 매개변수. |
| [getCodeTextParameters()](#getCodeTextParameters--) | 코드텍스트 매개변수. |
| [getCoupon()](#getCoupon--) | 쿠폰 매개변수. |
| [getDataBar()](#getDataBar--) | Databar 매개변수. |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix 매개변수. |
| [getDotCode()](#getDotCode--) | DotCode 매개변수. |
| [getFilledBars()](#getFilledBars--) | 바가 채워졌는지 여부를 나타내는 값을 가져옵니다. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 복합 바 매개변수. |
| [getHanXin()](#getHanXin--) | HanXin 매개변수. |
| [getITF()](#getITF--) | ITF 매개변수. |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode 매개변수. |
| [getPadding()](#getPadding--) | 바코드 패딩. |
| [getPatchCode()](#getPatchCode--) | PatchCode 매개변수. |
| [getPdf417()](#getPdf417--) | PDF417 매개변수. |
| [getPostal()](#getPostal--) | 우편 매개변수. |
| [getQR()](#getQR--) | QR, MicroQR 및 RectMicroQR 매개변수. |
| [getSupplement()](#getSupplement--) | 보충 매개변수. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | 1D 바코드 전용. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | 넓은 바와 좁은 바의 비율. |
| [getXDimension()](#getXDimension--) | x-차원은 바코드 바 또는 공백 단위의 가장 작은 너비입니다. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | 바 색상. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | 1D 바코드 바의 높이를 [Unit](../../com.aspose.barcode.generation/unit) 값으로 지정합니다. |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | 인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 설정합니다. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | 바가 채워졌는지 여부를 나타내는 값을 설정합니다. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 복합 바 매개변수. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | 1D 바코드 전용. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | 넓은 바와 좁은 바의 비율. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-차원은 바코드 바 또는 공백 단위의 가장 작은 너비입니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


AustralianPost 바코드 매개변수.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Aztec 매개변수.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


바 색상. 기본값: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


1D 바코드 바의 높이 [Unit](../../com.aspose.barcode.generation/unit) 값. BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 가져옵니다. 기본값: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다.

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


Codabar 매개변수.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Codablock 매개변수.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Code128 매개변수.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Code16K 매개변수.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


코드텍스트 매개변수.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


쿠폰 매개변수. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon에 사용됩니다.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databar 매개변수.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix 매개변수.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode 매개변수.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


바가 채워졌는지 여부를 나타내는 값을 가져옵니다. 1D 바코드에만 적용됩니다. 기본값: true.

**Returns:**
boolean - 바가 채워졌는지 여부를 나타내는 값.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 복합 바 매개변수.

이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D 코드텍스트와 2D 코드텍스트는 '|' 기호로 구분된다는 점에 유의하세요.

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Returns:**
[GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters)
### getHanXin() {#getHanXin--}
```
public final HanXinParameters getHanXin()
```


HanXin 매개변수.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


ITF 매개변수.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


MaxiCode 매개변수.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


바코드 패딩. 기본값: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


PatchCode 매개변수.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417 매개변수.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


우편 파라미터입니다. Postnet, Planet에 사용됩니다.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


QR, MicroQR 및 RectMicroQR 매개변수.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


보조 매개변수. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN에 사용됩니다.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


1D 바코드에만 적용됩니다. 코드텍스트가 올바르지 않고 값이 true로 설정된 경우 예외가 발생합니다. 그렇지 않으면 코드텍스트가 바코드 사양에 맞게 수정됩니다. 예외가 항상 발생하는 경우: 코드텍스트가 올바르지 않은 경우 Databar 심볼로지. 예외가 발생하지 않는 경우: 코드텍스트가 올바르지 않은 경우 AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 심볼로지.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


넓은 바와 좁은 바의 비율. 기본값: 3, 즉 넓은 바는 좁은 바보다 3배 넓습니다. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII에 사용됩니다.

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-차원은 BarCode 바 또는 공백 단위의 최소 너비입니다. 이를 증가시키면 전체 바코드 이미지 너비가 증가합니다. BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


1D 바코드 생성 시 체크섬을 활성화합니다.

체크섬이 반드시 포함되어야 하는 심볼로지는 기본값이 Yes로, 체크섬이 선택적인 경우 No로 처리됩니다.

체크섬이 가능한 경우: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

체크섬이 항상 사용되는 경우: 나머지 심볼로지

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


바 색상. 기본값: Color.Black.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


1D 바코드 바의 높이 [Unit](../../com.aspose.barcode.generation/unit) 값. BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 설정합니다. 기본값: 0

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | 인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


1D 바코드 생성 시 체크섬을 활성화합니다.

체크섬이 반드시 포함되어야 하는 심볼로지는 기본값이 Yes로, 체크섬이 선택적인 경우 No로 처리됩니다.

체크섬이 가능한 경우: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

체크섬이 항상 사용되는 경우: 나머지 심볼로지

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


바가 채워졌는지 여부를 나타내는 값을 설정합니다. 1D 바코드에만 적용됩니다. 기본값: true.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 바가 채워졌는지 여부를 나타내는 값. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 복합 바 매개변수.

이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D 코드텍스트와 2D 코드텍스트는 '|' 기호로 구분된다는 점에 유의하세요.

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


1D 바코드에만 적용됩니다. 코드텍스트가 올바르지 않고 값이 true로 설정된 경우 예외가 발생합니다. 그렇지 않으면 코드텍스트가 바코드 사양에 맞게 수정됩니다. 예외가 항상 발생하는 경우: 코드텍스트가 올바르지 않은 경우 Databar 심볼로지. 예외가 발생하지 않는 경우: 코드텍스트가 올바르지 않은 경우 AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 심볼로지.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


넓은 바와 좁은 바의 비율. 기본값: 3, 즉 넓은 바는 좁은 바보다 3배 넓습니다. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII에 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-차원은 BarCode 바 또는 공백 단위의 최소 너비입니다. 이를 증가시키면 전체 바코드 이미지 너비가 증가합니다. BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

