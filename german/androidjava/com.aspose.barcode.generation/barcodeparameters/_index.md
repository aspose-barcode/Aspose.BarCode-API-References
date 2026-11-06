---
title: "BarcodeParameters"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Parameter zur Barcode-Erzeugung."
type: docs
weight: 14
url: /de/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Parameter zur Barcode-Erzeugung.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost-Barcode-Parameter. |
| [getAztec()](#getAztec--) | Aztec-Parameter. |
| [getBarColor()](#getBarColor--) | Farbe der Balken. |
| [getBarHeight()](#getBarHeight--) | Höhe der Balken von 1D‑Barcodes im [Unit](../../com.aspose.barcode.generation/unit)-Wert. |
| [getBarWidthReduction()](#getBarWidthReduction--) | Ermittelt den Reduktionswert der Balken, der zum Ausgleich der Tintenausbreitung beim Drucken verwendet wird. |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Zeigt die Prüfziffer im menschenlesbaren Text für Code128‑ und GS1Code128‑Barcodes immer an. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar-Parameter. |
| [getCodablock()](#getCodablock--) | Codablock-Parameter. |
| [getCode128()](#getCode128--) | Code128-Parameter. |
| [getCode16K()](#getCode16K--) | Code16K-Parameter. |
| [getCodeTextParameters()](#getCodeTextParameters--) | Codetext-Parameter. |
| [getCoupon()](#getCoupon--) | Gutschein-Parameter. |
| [getDataBar()](#getDataBar--) | Databar-Parameter. |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix-Parameter. |
| [getDotCode()](#getDotCode--) | DotCode-Parameter. |
| [getFilledBars()](#getFilledBars--) | Ermittelt einen Wert, der angibt, ob die Balken gefüllt sind. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | Parameter für GS1 Composite Bar. |
| [getHanXin()](#getHanXin--) | Parameter für HanXin. |
| [getITF()](#getITF--) | ITF-Parameter. |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode-Parameter. |
| [getPadding()](#getPadding--) | Abstände des Barcodes. |
| [getPatchCode()](#getPatchCode--) | PatchCode-Parameter. |
| [getPdf417()](#getPdf417--) | PDF417-Parameter. |
| [getPostal()](#getPostal--) | Post‑Parameter. |
| [getQR()](#getQR--) | Parameter für QR, MicroQR und RectMicroQR. |
| [getSupplement()](#getSupplement--) | Ergänzungs‑Parameter. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Nur für 1D‑Barcodes. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Verhältnis von breiten zu schmalen Balken. |
| [getXDimension()](#getXDimension--) | Die x‑Dimension ist die kleinste Breite der Einheit von Barcode‑Balken oder -Lücken. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Farbe der Balken. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Höhe der Balken von 1D‑Barcodes im [Unit](../../com.aspose.barcode.generation/unit)-Wert. |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Legt den Reduktionswert der Balken fest, der zum Ausgleich der Tintenausbreitung beim Drucken verwendet wird. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Zeigt die Prüfziffer im menschenlesbaren Text für Code128‑ und GS1Code128‑Barcodes immer an. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Legt einen Wert fest, der angibt, ob die Balken gefüllt sind. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | Parameter für GS1 Composite Bar. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Nur für 1D‑Barcodes. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Verhältnis von breiten zu schmalen Balken. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | Die x‑Dimension ist die kleinste Breite der Einheit von Barcode‑Balken oder -Lücken. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


AustralianPost-Barcode-Parameter.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Aztec-Parameter.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


Farbe der Balken. Standardwert: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Höhe der Balken von 1D‑Barcodes im [Unit](../../com.aspose.barcode.generation/unit)-Wert. Ignoriert, wenn die Eigenschaft BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Ermittelt den Reduktionswert der Balken, der zum Ausgleich der Tintenausbreitung beim Drucken verwendet wird. Standardwert: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Zeigt die Prüfziffer im menschenlesbaren Text für Code128‑ und GS1Code128‑Barcodes immer an.

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


Codabar-Parameter.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Codablock-Parameter.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Code128-Parameter.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Code16K-Parameter.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Codetext-Parameter.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


Coupon‑Parameter. Verwendet für UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databar-Parameter.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix-Parameter.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode-Parameter.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Ermittelt einen Wert, der angibt, ob die Balken gefüllt sind. Nur für 1D‑Barcodes. Standardwert: true.

**Returns:**
boolean – ein Wert, der angibt, ob die Balken gefüllt sind.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


Parameter für GS1 Composite Bar.

Dieses Beispiel zeigt, wie ein GS1 Composite Bar‑Bild erstellt und gespeichert wird. Beachten Sie, dass 1D‑Codetext und 2D‑Codetext durch das Symbol '|' getrennt sind.

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


Parameter für HanXin.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


ITF-Parameter.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


MaxiCode-Parameter.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Barcode-Abstände. Standardwert: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


PatchCode-Parameter.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417-Parameter.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Post-Parameter. Verwendet für Postnet, Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


Parameter für QR, MicroQR und RectMicroQR.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Zusätzliche Parameter. Verwendet für Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Nur für 1D-Barcodes. Wenn der Codetext inkorrekt ist und der Wert auf true gesetzt wird, wird eine Ausnahme ausgelöst. Andernfalls wird der Codetext korrigiert, um der Spezifikation des Barcodes zu entsprechen. Eine Ausnahme wird immer ausgelöst für: Databar-Symbologie, wenn der Codetext inkorrekt ist. Eine Ausnahme wird niemals ausgelöst für: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-Symbologie, wenn der Codetext inkorrekt ist.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind 3‑mal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


Die x-Dimension ist die kleinste Breite der Einheit von Barcode‑Balken oder -Lücken. Eine Erhöhung davon vergrößert die gesamte Barcode‑Bildbreite. Ignoriert, wenn die Eigenschaft BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

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


Prüfsumme während der Erzeugung von 1D-Barcodes aktivieren.

Standard wird als Ja behandelt für Symbologien, die eine Prüfsumme enthalten müssen, und als Nein, wo eine Prüfsumme nur optional ist.

Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar.

Prüfsumme wird immer verwendet: übrige Symbologien.

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


Farbe der Balken. Standardwert: Color.Black.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Höhe der Balken von 1D‑Barcodes im [Unit](../../com.aspose.barcode.generation/unit)-Wert. Ignoriert, wenn die Eigenschaft BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Legt den Reduktionswert für Balken fest, der zum Ausgleich der Tintenausbreitung beim Drucken verwendet wird. Standardwert: 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | Reduktionswert für Balken, der zum Ausgleich der Tintenausbreitung beim Drucken verwendet wird. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Zeigt die Prüfziffer im menschenlesbaren Text für Code128‑ und GS1Code128‑Barcodes immer an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Prüfsumme während der Erzeugung von 1D-Barcodes aktivieren.

Standard wird als Ja behandelt für Symbologien, die eine Prüfsumme enthalten müssen, und als Nein, wo eine Prüfsumme nur optional ist.

Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar.

Prüfsumme wird immer verwendet: übrige Symbologien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Legt einen Wert fest, der angibt, ob Balken gefüllt sind. Nur für 1D-Barcodes. Standardwert: true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob Balken gefüllt sind. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


Parameter für GS1 Composite Bar.

Dieses Beispiel zeigt, wie ein GS1 Composite Bar‑Bild erstellt und gespeichert wird. Beachten Sie, dass 1D‑Codetext und 2D‑Codetext durch das Symbol '|' getrennt sind.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Nur für 1D-Barcodes. Wenn der Codetext inkorrekt ist und der Wert auf true gesetzt wird, wird eine Ausnahme ausgelöst. Andernfalls wird der Codetext korrigiert, um der Spezifikation des Barcodes zu entsprechen. Eine Ausnahme wird immer ausgelöst für: Databar-Symbologie, wenn der Codetext inkorrekt ist. Eine Ausnahme wird niemals ausgelöst für: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-Symbologie, wenn der Codetext inkorrekt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind 3‑mal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


Die x-Dimension ist die kleinste Breite der Einheit von Barcode‑Balken oder -Lücken. Eine Erhöhung davon vergrößert die gesamte Barcode‑Bildbreite. Ignoriert, wenn die Eigenschaft BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

