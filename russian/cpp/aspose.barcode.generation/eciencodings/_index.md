---
title: "enum"
linktitle: "Кодировки ECI"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать enum в C++."
type: docs
weight: 6600
url: /ru/cpp/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enum




```cpp
enum class ECIEncodings
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| ISO_8859_1 | 3 | ISO/IEC 8859-1 кодировка латинского алфавита № 1. ECI Id:"\000003" |
| ISO_8859_2 | 4 | ISO/IEC 8859-2 кодировка латинского алфавита № 2. ECI Id:"\000004" |
| ISO_8859_3 | 5 | ISO/IEC 8859-3 кодировка латинского алфавита № 3. ECI Id:"\000005" |
| ISO_8859_4 | 6 | ISO/IEC 8859-4 кодировка латинского алфавита № 4. ECI Id:"\000006" |
| ISO_8859_5 | 7 | ISO/IEC 8859-5 кодировка латинского/кириллического алфавита. ECI Id:"\000007" |
| ISO_8859_6 | 8 | ISO/IEC 8859-6 кодировка латинского/арабского алфавита. ECI Id:"\000008" |
| ISO_8859_7 | 9 | ISO/IEC 8859-7 кодировка латинского/греческого алфавита. ECI Id:"\000009" |
| ISO_8859_8 | 10 | ISO/IEC 8859-8 кодировка латинского/иврита. ECI Id:"\000010" |
| ISO_8859_9 | 11 | ISO/IEC 8859-9 кодировка латинского алфавита № 5. ECI Id:"\000011" |
| ISO_8859_10 | 12 | ISO/IEC 8859-10 латинский алфавит № 6 кодировка. ECI Id:"\000012" |
| ISO_8859_11 | 13 | ISO/IEC 8859-11 латинско‑тайский алфавит кодировка. ECI Id:"\000013" |
| ISO_8859_13 | 15 | ISO/IEC 8859-13 латинский алфавит № 7 (Балтийский регион) кодировка. ECI Id:"\000015" |
| ISO_8859_14 | 16 | ISO/IEC 8859-14 латинский алфавит № 8 (Кельтский) кодировка. ECI Id:"\000016" |
| ISO_8859_15 | 17 | ISO/IEC 8859-15 латинский алфавит № 9 кодировка. ECI Id:"\000017" |
| ISO_8859_16 | 18 | ISO/IEC 8859-16 латинский алфавит № 10 кодировка. ECI Id:"\000018" |
| Shift_JIS | 20 | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) кодировка. ECI Id:"\000020" |
| Win1250 | 21 | [Windows](../../aspose.barcode.windows/) 1250 Latin 2 (Центральная Европа) кодировка. ECI Id:"\000021" |
| Win1251 | 22 | [Windows](../../aspose.barcode.windows/) 1251 кодировка кириллицы. ECI Id:"\000022" |
| Win1252 | 23 | [Windows](../../aspose.barcode.windows/) 1252 Latin 1 кодировка. ECI Id:"\000023" |
| Win1256 | 24 | [Windows](../../aspose.barcode.windows/) 1256 арабская кодировка. ECI Id:"\000024" |
| UTF16BE | 25 | ISO/IEC 10646 UCS-2 (старший байт первым) кодировка. ECI Id:"\000025" |
| UTF8 | 26 | ISO/IEC 10646 UTF-8 кодировка. ECI Id:"\000026" |
| US_ASCII | 27 | ISO/IEC 646:1991 Международная справочная версия 7‑битного кодированного набора символов ISO кодировка. ECI Id:"\000027" |
| Big5 | 28 | Кодировка набора китайских символов Big 5 (Тайвань). ECI Id:"\000028" |
| GB2312 | 29 | Кодировка набора китайских символов GB2312. ECI Id:"\000029" |
| EUC_KR | 30 | Кодировка корейского набора символов. ECI Id:"\000030" |
| GBK | 31 | Кодировка GBK (расширение GB2312 для упрощённого китайского). ECI Id:"\000031" |
| GB18030 | 32 | Кодировка набора китайских символов GGB18030. ECI Id:"\000032" |
| UTF16LE | 33 | Кодировка ISO/IEC 10646 UTF-16LE. ECI Id:"\000033" |
| UTF32BE | 34 | Кодировка ISO/IEC 10646 UTF-32BE. ECI Id:"\000034" |
| UTF32LE | 35 | Кодировка ISO/IEC 10646 UTF-32LE. ECI Id:"\000035" |
| INVARIANT | 170 | ISO/IEC 646: 7-битный кодированный набор символов ISO - кодировка набора неизменных символов. ECI Id:"\000170" |
| BINARY | 899 | 8-битные двоичные данные. ECI Id:"\000899" |
| NONE | 0 | Нет расширенной интерпретации канала |

## Примечания


Идентификаторы расширенной интерпретации канала. Используется для передачи считывателю штрихкода сведений о используемых ссылках для кодирования данных в символе.

Этот пример показывает, как использовать кодировку ECI и сохранить изображение [BarCode](../../aspose.barcode/).
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
        generator.CodeText = "12345TEXT"
        generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding
        generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8
        generator.Save("test.png")
    End Using
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
