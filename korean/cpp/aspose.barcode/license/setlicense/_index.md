---
title: "메서드"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. 라이브러리에 라이선스를 적용합니다 C++에서."
type: docs
weight: 200
url: /ko/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


라이브러리에 라이선스를 적용합니다.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| licenseName | System::String | 전체 파일 이름이거나 짧은 파일 이름, 혹은 포함된 리소스의 이름일 수 있습니다. |
## 비고


다음 위치에서 라이선스를 찾으려고 시도합니다:

1. 명시적 경로.

2. **Aspose** 구성 요소 어셈블리를 포함하는 폴더.

3. 클라이언트의 호출 어셈블리를 포함하는 폴더.

4. 엔트리(시작) 어셈블리를 포함하는 폴더.

5. 클라이언트의 호출 어셈블리에 포함된 임베디드 리소스.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 명시적 경로.

2. 클라이언트의 호출 어셈블리에 포함된 임베디드 리소스.

이 예제에서는 구성 요소가 포함된 폴더, 호출 어셈블리가 포함된 폴더, 진입 어셈블리 폴더, 그리고 호출 어셈블리의 임베디드 리소스에서 MyLicense.lic 라는 라이선스 파일을 찾으려고 시도합니다.
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


## 또 보기

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


라이브러리에 라이선스를 적용합니다.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 라이선스를 포함하는 스트림. |
## 비고



이 메서드를 사용하여 스트림에서 라이선스를 로드합니다.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## 또 보기

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
