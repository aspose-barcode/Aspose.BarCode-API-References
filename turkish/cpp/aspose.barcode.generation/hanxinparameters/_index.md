---
title: "Aspose::BarCode::Generation::HanXinParameters sınıfı"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::HanXinParameters sınıfı. C++'de Han Xin parametreleri."
type: docs
weight: 2900
url: /tr/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Han Xin parametreleri.

```cpp
class HanXinParameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya detayları bildirmek için kullanılır. Mevcut uygulama tüm bilinen karakter kümesi kodlamalarını içerir. |
| [get_EncodeMode](./get_encodemode/)() const | HanXin kodlama modu. Varsayılan değer: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Han Xin barkodu için Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: L1, L2, L3, L4. bkz. ErrorLevel. |
| [get_Version](./get_version/)() const | HanXin Kodu sürümü. Han Xin kodu için Version01'den Version84'e kadar. Varsayılan değer [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya detayları bildirmek için kullanılır. Mevcut uygulama tüm bilinen karakter kümesi kodlamalarını içerir. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | HanXin kodlama modu. Varsayılan değer: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Han Xin barkodu için Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: L1, L2, L3, L4. bkz. ErrorLevel. |
| [set_Version](./set_version/)(HanXinVersion) | HanXin Kodu sürümü. Han Xin kodu için Version01'den Version84'e kadar. Varsayılan değer [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Bu [HanXinParameters](./) nesnesinin insan tarafından okunabilir dize temsili döndürür. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
