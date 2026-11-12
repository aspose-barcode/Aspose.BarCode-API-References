---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "تمكين التحقق من صحة المجموع الاختباري أثناء التعرف على الباركود أحادي الأبعاد."
type: docs
weight: 100
url: /ar/nodejs/global/checksumvalidation/
---

## ChecksumValidation

تمكين التحقق من صحة المجموع الاختباري أثناء التعرف على الباركود أحادي الأبعاد. يُعامل الوضع الافتراضي على أنه نعم للأنماط التي يجب أن تحتوي على المجموع الاختباري، ولا عندما يكون المجموع الاختباري ممكنًا فقط. لا يُستخدم المجموع الاختباري أبداً: Codabar. المجموع الاختباري ممكن في: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. المجموع الاختباري يُستخدم دائمًا في باقي الأنماط. يوضح هذا المثال تأثير ChecksumValidation على جودة التعرف والنتائج \code generator = BarcodeGenerator(EncodeTypes.EAN_13, \"1234567890128\") generator.save(\"test.png\", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader(\"test.png\", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print(\"BarCode CodeText: \" + result.getCodeText()) print(\"BarCode Value: \" + result.getExtended().getOneD().getValue()) print(\"BarCode Checksum: \" + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader(\"test.png\", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print(\"BarCode CodeText: \" + result.getCodeText()) print(\"BarCode Value: \" + result.getExtended().getOneD().getValue()) print(\"BarCode Checksum: \" + result.getExtended().getOneD().getCheckSum()) \endcode

## القيم

| اسم | الوصف |
| --- | --- |
| MOD_10 | يحدد خوارزمية Mod 10 لـ Codabar. |
| MOD_16 | يحدد خوارزمية Mod 16 لـ Codabar (موصى به AIIM). |
