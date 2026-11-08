---
title: "clase Aspose::BarCode::Generation::BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "clase Aspose::BarCode::Generation::BarcodeParameters. Parámetros de generación de códigos de barras en C++."
type: docs
weight: 500
url: /es/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Parámetros de generación de códigos de barras.

```cpp
class BarcodeParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | Parámetros de código de barras AustralianPost. |
| [get_Aztec](./get_aztec/)() const | Parámetros Aztec. |
| [get_BarColor](./get_barcolor/)() const | Color de las barras. Valor predeterminado: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | Altura de las barras de códigos de barras 1D en valor [Unit](../unit/). Ignorada si la propiedad [BaseGenerationParameters::AutoSizeMode](../) está establecida en [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Obtiene o establece el valor de reducción de las barras que se usa para compensar la difusión de tinta al imprimir. Valor predeterminado: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Mostrar siempre el dígito de suma de verificación en el texto legible para humanos de los códigos de barras Code128 y GS1Code128. |
| [get_Codabar](./get_codabar/)() const | Parámetros de Codabar. |
| [get_Codablock](./get_codablock/)() const | Parámetros de Codablock. |
| [get_Code128](./get_code128/)() const | Parámetros de Code128. |
| [get_Code16K](./get_code16k/)() const | Parámetros de Code16K. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Parámetros de Codetext. |
| [get_Coupon](./get_coupon/)() const | Parámetros de cupón. Usado para UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | Parámetros de Databar. |
| [get_DataMatrix](./get_datamatrix/)() const | Parámetros de DataMatrix. |
| [get_DotCode](./get_dotcode/)() const | Parámetros de DotCode. |
| [get_FilledBars](./get_filledbars/)() const | Obtiene un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. Valor predeterminado: true. |
| [get_GS1](./get_gs1/)() const | Parámetros de GS1. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | Parámetros de GS1 Composite Bar. |
| [get_HanXin](./get_hanxin/)() const | Parámetros de HanXin. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | Parámetros de ITF. |
| [get_MaxiCode](./get_maxicode/)() const | Parámetros de MaxiCode. |
| [get_Padding](./get_padding/)() const | Rellenos del código de barras. Valor predeterminado: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | Parámetros de PatchCode. |
| [get_Pdf417](./get_pdf417/)() const | Parámetros de PDF417. |
| [get_Postal](./get_postal/)() const | Parámetros postales. Usado para Postnet, Planet. |
| [get_QR](./get_qr/)() const | Parámetros de QR, MicroQR y RectMicroQR. |
| [get_Supplement](./get_supplement/)() const | Parámetros suplementarios. Usado para Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Solo para códigos de barras 1D. Si el codetext es incorrecto y el valor se establece en true, se lanzará una excepción. De lo contrario, el codetext se corregirá para cumplir con la especificación del código de barras. La excepción siempre se lanzará para: la simbología Databar si el codetext es incorrecto. La excepción nunca se lanzará para: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbología Code128 si el codetext es incorrecto. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las barras estrechas. Utilizado para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [get_XDimension](./get_xdimension/)() const | La x-dimensión es el ancho más pequeño de la unidad de barras o espacios de [BarCode](../../aspose.barcode/). Incrementar esto aumentará el ancho total de la imagen del código de barras. Se ignora si la propiedad [BaseGenerationParameters::AutoSizeMode](../) está configurada a [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Color de las barras. Valor predeterminado: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | Altura de las barras de códigos de barras 1D en valor [Unit](../unit/). Ignorada si la propiedad [BaseGenerationParameters::AutoSizeMode](../) está establecida en [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Obtiene o establece el valor de reducción de las barras que se usa para compensar la difusión de tinta al imprimir. Valor predeterminado: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Mostrar siempre el dígito de suma de verificación en el texto legible para humanos de los códigos de barras Code128 y GS1Code128. |
| [set_FilledBars](./set_filledbars/)(bool) | Establece un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. Valor predeterminado: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | Parámetros de GS1 Composite Bar. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Solo para códigos de barras 1D. Si el codetext es incorrecto y el valor se establece en true, se lanzará una excepción. De lo contrario, el codetext se corregirá para cumplir con la especificación del código de barras. La excepción siempre se lanzará para: la simbología Databar si el codetext es incorrecto. La excepción nunca se lanzará para: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbología Code128 si el codetext es incorrecto. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las barras estrechas. Utilizado para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | La x-dimensión es el ancho más pequeño de la unidad de barras o espacios de [BarCode](../../aspose.barcode/). Incrementar esto aumentará el ancho total de la imagen del código de barras. Se ignora si la propiedad [BaseGenerationParameters::AutoSizeMode](../) está configurada a [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
