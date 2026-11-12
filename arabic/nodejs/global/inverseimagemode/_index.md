---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة)."
type: docs
weight: 370
url: /ar/nodejs/global/inverseimagemode/
---

## InverseImageMode

الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركود في الصور ذات الألوان المعكوسة (الإضاءة). يوضح هذا المثال كيفية استخدام وضع InverseImage let reader = new BarCodeReader(\"test.png\", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText()); }

## القيم

| اسم | الوصف |
| --- | --- |
| NONE | لا حدود تحيط بالباركود |
| FRAME | FRAME تحيط بالباركود |
| BAR | شريطان أفقيان يحيطان بالباركود |
| FRAME_OUT | FRAME تحيط بالباركود |
| BAR_OUT | شريطان أفقيان يحيطان بالباركود |
