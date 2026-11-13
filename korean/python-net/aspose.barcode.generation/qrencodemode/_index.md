---
title: "QREncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Reference"
description: 
type: docs
url: /ko/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

QR 바코드의 인코딩 모드.

## Members
| 멤버 이름 | 설명 |
| :- | :- |
| AUTO | 자동 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. <br/>            가능한 경우 유니코드 문자는 한자 모드로 인코딩되며, 그렇지 않으면 ECIEncoding에서 지정한 인코딩으로 ECI 식별자를 삽입하여 다시 인코딩됩니다.<br/>            선택한 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. |
| EXTENDED |  |
| BINARY | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. <br/>            Unicode 문자가 발견되면 예외가 발생합니다. |
| ECI | ECI 모드에서는 전체 메시지가 ECIEncoding에서 지정한 인코딩으로 ECI 식별자를 삽입하여 다시 인코딩됩니다.<br/>            선택한 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다.<br/>            일부 오래된 (2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있습니다.<br/>            이 모드는 MicroQR 바코드에서 지원되지 않습니다. |

### 또 보기

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

