---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Reference"
description: 
type: docs
url: /ko/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Han Xin Code 인코딩 모드. ASCII/중국어 문자와 함께 Auto를 사용하거나 유니코드 문자는 Unicode를 사용하는 것이 권장됩니다.

## Members
| 멤버 이름 | 설명 |
| :- | :- |
| AUTO | Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. <br/>            유니코드 문자는 HanXin 바코드 사양에 따라 GB18030 인코딩을 사용하여 인코딩됩니다. |
| BINARY | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. <br/>            Unicode 문자가 발견되면 예외가 발생합니다. |
| ECI | ECI 모드에서는 전체 메시지가 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다.<br/>            선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다.<br/>            일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있다는 점에 유의하십시오. |
| UNICODE | Unicode 모드는 Han Xin 코드에서 UTF8 인코딩/문자 집합을 참조하여 모든 텍스트 데이터를 표현하는 방법을 설계합니다. |
| URI | URI 모드는 Han Xin 코드에서 표현되는 데이터가 통합 자원 식별자(URI)임을 나타냅니다.<br/>            RFC 3986을 참조합니다. |
| EXTENDED | Extended 모드는 내부 모드의 조합을 허용합니다: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            코드텍스트는 접두사와 이중 백슬래시를 사용하여 수동으로 구성할 수 있습니다. 예: @\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\" 또는 HanXinExtCodetextBuilder를 사용합니다.<br/>            코드텍스트에 ECI 조각이 포함된 경우, 해당 ECI 조각 이후에는 다음 모드만 코드텍스트에 사용할 수 있습니다:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### 또 보기

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

