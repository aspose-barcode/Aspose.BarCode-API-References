---
title: "DataMatrixEncodeMode.EXTENDED"
linktitle: "EXTENDED"
articleTitle: "EXTENDED"
second_title: "Aspose.BarCode for Python via Java"
description: "ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext. It is better to use DataMatrixExtCodetextBuilder for extended "
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/datamatrixencodemode/extended/
---

## DataMatrixEncodeMode.EXTENDED

**Type:** `int`


**Value:** `13`


ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext. It is better to use DataMatrixExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. Encodation schemes are set in the next format : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Allowed encodation schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. All backslashes () must be doubled in text.

