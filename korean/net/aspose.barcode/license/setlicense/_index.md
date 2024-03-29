---
title: SetLicense
second_title: .NET API 참조용 Aspose.BarCode
description: 라이브러리에 라이센스를 부여합니다.
type: docs
weight: 20
url: /ko/net/aspose.barcode/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

라이브러리에 라이센스를 부여합니다.

```csharp
public void SetLicense(string licenseName)
```

### 비고

다음 위치에서 라이센스를 찾으려고 시도합니다.

1. 명시적 경로.

2. Aspose 컴포넌트 어셈블리가 포함된 폴더.

3. 클라이언트의 호출 어셈블리가 포함된 폴더.

4. 항목(시작) 어셈블리가 포함된 폴더.

5. 클라이언트의 호출 어셈블리에 포함된 리소스.

**메모:**.NET Compact Framework에서는 다음 위치에서만 라이선스를 찾으려고 시도합니다.

1. 명시적 경로.

2. 클라이언트의 호출 어셈블리에 포함된 리소스.

### 예

이 예에서는 구성 요소가 포함된 폴더, 호출 어셈블리가 포함된 폴더, 항목 어셈블리의 폴더에서 라는 라이센스 파일을 찾은 다음 포함된 호출 어셈블리의 리소스. 포함된 리소스의 전체 또는 짧은 파일 이름 또는 이름일 수 있습니다.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### 또한보십시오

* class [License](../)
* 네임스페이스 [Aspose.BarCode](../../license/)
* 집회 [Aspose.BarCode](../../../)

---

## SetLicense(Stream) {#setlicense}

라이브러리에 라이센스를 부여합니다.

```csharp
public void SetLicense(Stream stream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 라이선스가 포함된 스트림입니다. |

### 비고

스트림에서 라이센스를 로드하려면 이 방법을 사용하십시오.

### 예

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### 또한보십시오

* class [License](../)
* 네임스페이스 [Aspose.BarCode](../../license/)
* 집회 [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
