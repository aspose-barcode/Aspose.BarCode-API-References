---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext クラス"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext クラス。 C++ で USA 運転免許証 PDF417 コードに埋め込まれたテキストをエンコードおよびデコードするクラスです。"
type: docs
weight: 2900
url: /ja/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


USA 運転 [License](../../aspose.barcode/license/) PDF417 コードに埋め込まれたテキストをエンコードおよびデコードするクラスです。

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | AAMVA バージョン番号 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | この番号は発行管轄を一意に識別し、ISO 発行機関 (AAMVA) に問い合わせることで取得できます。6 桁の完全な IIN をエンコードする必要があります。 |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | 管轄固有フィールド |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | 管轄バージョン番号 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | カードの必須要素（フィールド） |
| [get_NumberOfEntries](./get_numberofentries/)() const | サブファイルの番号 00-99 |
| [get_OptionalElements](./get_optionalelements/)() const | カードの任意要素（フィールド） |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | 以下のサブファイル、タイプ、オフセット、長さに関する情報を含みます。重要: タイプのみを設定すると、オフセットと長さは自動的に設定されます。 |
| [GetBarcodeType](./getbarcodetype/)() override | USA DL（Pdf417）のバーコードタイプを返します |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | USA DL データからコードテキストを構築します |
| [InitFromString](./initfromstring/)(System::String) override | コードテキストから USA DL オブジェクトを初期化します |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | XML に保存 |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | AAMVA バージョン番号 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | この番号は発行管轄を一意に識別し、ISO 発行機関 (AAMVA) に問い合わせることで取得できます。6 桁の完全な IIN をエンコードする必要があります。 |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | 管轄固有フィールド |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | 管轄バージョン番号 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | カードの必須要素（フィールド） |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | サブファイルの番号 00-99 |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | カードの任意要素（フィールド） |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | 以下のサブファイル、タイプ、オフセット、長さに関する情報を含みます。重要: タイプのみを設定すると、オフセットと長さは自動的に設定されます。 |
| [USADriveIdCodetext](./usadriveidcodetext/)() | デフォルトコンストラクタ |
## 関連項目

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
