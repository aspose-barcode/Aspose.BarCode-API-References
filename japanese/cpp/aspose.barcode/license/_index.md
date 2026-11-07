---
title: "Aspose::BarCode::License クラス"
linktitle: "ライセンス"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::License クラス。C++ でコンポーネントにライセンスを付与するためのメソッドを提供します。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode/license/
---
## License class


コンポーネントのライセンス付与のためのメソッドを提供します。

```cpp
class License : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [License](./license/)() | このクラスの新しいインスタンスを初期化します。 |
| [SetLicense](./setlicense/)(System::String) | ライブラリにライセンスを付与します。 |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | ライブラリにライセンスを付与します。 |
## 備考


この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
@endverbatim
```

## 関連項目

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
