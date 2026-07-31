---
title: "MaxiCodeEncodeMode Enum"
linktitle: "MaxiCodeEncodeMode"
articleTitle: "MaxiCodeEncodeMode"
second_title: "Aspose.BarCode for Python via Java"
description: "Encoding mode for MaxiCode barcodes. codetext = \"犬Right狗\" generator = BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext) generator.parameters.barcode.maxi_code.e"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation.maxi_code_encode_mode/maxicodeencodemode/
---

## MaxiCodeEncodeMode enum

**Module:** `aspose_barcode.generation.maxi_code_encode_mode`


Encoding mode for MaxiCode barcodes. codetext = "犬Right狗" generator = BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext) generator.parameters.barcode.maxi_code.eci_encoding = ECIEncodings.UTF8 generator.save(image_path_to_save5, BarCodeImageFormat.BMP) encoded_arr = [0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9] str_bld = "" for bval in encoded_arr: str_bld += str(bval) codetext = str_bld generator = BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext) generator.parameters.barcode.maxi_code.encode_mode = MaxiCodeEncodeMode.BYTES generator.save(image_path_to_save5, BarCodeImageFormat.BMP) text_builder = MaxiCodeExtCodetextBuilder() text_builder.add_eci_codetext(ECIEncodings.Win1251, "Will") text_builder.add_eci_codetext(ECIEncodings.UTF8, "犬Right狗") text_builder.add_eci_codetext(ECIEncodings.UTF16BE, "犬Power狗") text_builder.add_plain_codetext("Plain text") codetext = text_builder.extended_codetext generator = BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext) generator.parameters.barcode.maxi_code.encode_mode = MaxiCodeEncodeMode.EXTENDED_CODETEXT generator.parameters.barcode.code_text_parameters.two_d_display_text = "My Text" generator.save(image_path_to_save5, BarCodeImageFormat.BMP)


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [AUTO](./auto/) | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| [BINARY](./binary/) | `4` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| [BYTES](./bytes/) | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| [EXTENDED](./extended/) | `3` | Extended mode which supports multi ECI modes. It is better to use MaxiCodeExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
| [EXTENDED_CODETEXT](./extended_codetext/) | `2` | Extended mode which supports multi ECI modes. It is better to use MaxiCodeExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
