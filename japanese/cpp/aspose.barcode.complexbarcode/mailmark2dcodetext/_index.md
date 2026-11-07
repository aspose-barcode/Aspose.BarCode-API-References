---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext クラス"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext クラス。C++ における Royal Mail 2D Mailmark コードに埋め込まれたテキストのエンコードとデコードのためのクラスです。"
type: docs
weight: 1400
url: /ja/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Royal Mail 2D Mailmarkコードに埋め込まれたテキストをエンコードおよびデコードするクラスです。

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Class](./get_class/)() const | アイテムのクラスを識別します。 |
| [get_CustomerContent](./get_customercontent/)() const | 顧客が使用するための任意のスペースです。 |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | DataMatrix バーコードのエンコードモード。デフォルト値: EncodeMode.C40。 |
| [get_DataMatrixType](./get_datamatrixtype/)() const | 2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。 |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | 配達先 [Address](../address/) の郵便番号と DPS を含みます。国内の場合、郵便番号/DP は以下の文字数で構成されます。エリア (1 または 2 文字)、地区 (1 または 2 文字)、セクター (1 文字)、ユニット (2 文字)、DPS (2 文字)。郵便番号と DPS は有効な PAF® 形式に準拠している必要があります。 |
| [get_InformationTypeID](./get_informationtypeid/)() const | 各製品タイプに対する Royal Mail Mailmark バーコードのペイロードを識別します。 |
| [get_ItemID](./get_itemid/)() const | サプライチェーン ID 内のユニークなアイテムを識別します。すべての Mailmark バーコードは少なくとも 90 日間ユニークに識別できるよう ID を保持する必要があります。最大値: 99999999。 |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Return to Sender の郵便番号を含みますが DPS は含みません。DPS のない PC は PAF® 形式に準拠している必要があります。 |
| [get_RTSFlag](./get_rtsflag/)() const | 要求されている Return to Sender サービスのレベルを示すフラグです。 |
| [get_SupplyChainID](./get_supplychainid/)() const | メール送信に関与するユニークな顧客グループを識別します。最大値: 9999999。 |
| [get_UPUCountryID](./get_upucountryid/)() const | UPU カントリー ID を識別します。最大長さ: 4 文字。 |
| [get_VersionID](./get_versionid/)() const | 各情報タイプ ID に関連するバーコードバージョンを識別します。 |
| [GetBarcodeType](./getbarcodetype/)() override | バーコードの種類を取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Mailmark データからコードテキストを構築します。 |
| [InitFromString](./initfromstring/)(System::String) override | 構築されたコードテキストから Mailmark データを初期化します。 |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | コンストラクタ。[Mailmark2DCodetext](./) クラスのデフォルトインスタンスを作成します。 |
| [set_Class](./set_class/)(System::String) | アイテムのクラスを識別します。 |
| [set_CustomerContent](./set_customercontent/)(System::String) | 顧客が使用するための任意のスペースです。 |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | DataMatrix バーコードのエンコードモード。デフォルト値: EncodeMode.C40。 |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | 2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。 |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | 配達先 [Address](../address/) の郵便番号と DPS を含みます。国内の場合、郵便番号/DP は以下の文字数で構成されます。エリア (1 または 2 文字)、地区 (1 または 2 文字)、セクター (1 文字)、ユニット (2 文字)、DPS (2 文字)。郵便番号と DPS は有効な PAF® 形式に準拠している必要があります。 |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | 各製品タイプに対する Royal Mail Mailmark バーコードのペイロードを識別します。 |
| [set_ItemID](./set_itemid/)(int32_t) | サプライチェーン ID 内のユニークなアイテムを識別します。すべての Mailmark バーコードは少なくとも 90 日間ユニークに識別できるよう ID を保持する必要があります。最大値: 99999999。 |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Return to Sender の郵便番号を含みますが DPS は含みません。DPS のない PC は PAF® 形式に準拠している必要があります。 |
| [set_RTSFlag](./set_rtsflag/)(System::String) | 要求されている Return to Sender サービスのレベルを示すフラグです。 |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | メール送信に関与するユニークな顧客グループを識別します。最大値: 9999999。 |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | UPU カントリー ID を識別します。最大長さ: 4 文字。 |
| [set_VersionID](./set_versionid/)(System::String) | 各情報タイプ ID に関連するバーコードバージョンを識別します。 |
## 関連項目

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
