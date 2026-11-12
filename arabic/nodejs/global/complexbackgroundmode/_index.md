---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركود الملون في الصور الملونة."
type: docs
weight: 160
url: /ar/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركود الملون في الصور الملونة. يوضح هذا المثال كيفية استخدام وضع ComplexBackground let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## القيم

| اسم | الوصف |
| --- | --- |
| C_TABLE | استخدم C_TABLE لتفسير معلومات العميل. يسمح بـ A..Z، a..z، 1..9، المسافة و # sing. |
| N_TABLE | استخدم N_TABLE لتفسير معلومات العميل. يسمح بالأرقام. |
| OTHER | لا تقم بتفسير معلومات العميل. يسمح بالرمز 0 أو 1 أو 2 أو 3 فقط. |
