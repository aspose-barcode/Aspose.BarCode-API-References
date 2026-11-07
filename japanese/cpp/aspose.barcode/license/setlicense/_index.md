---
title: "メソッド"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ でライブラリにライセンスを適用します。"
type: docs
weight: 200
url: /ja/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


ライブラリにライセンスを付与します。

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| licenseName | System::String | 完全なファイル名または短いファイル名、あるいは埋め込みリソースの名前にすることができます。 |
## 備考


次の場所でライセンスを検索します:

1. 明示的なパス。

2. **Aspose** コンポーネント アセンブリを含むフォルダー。

3. クライアントの呼び出しアセンブリを含むフォルダー。

4. エントリ (スタートアップ) アセンブリを含むフォルダー。

5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明示的なパス。

2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
@endverbatim
```


## 関連項目

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


ライブラリにライセンスを付与します。

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | ライセンスを含むストリーム。 |
## 備考



このメソッドを使用して、ストリームからライセンスをロードします。


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## 関連項目

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
