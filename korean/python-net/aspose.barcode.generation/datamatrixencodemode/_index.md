---
title: "DataMatrixEncodeMode"
second_title: "Aspose.Sildes for Python via .NET API Reference"
description: 
type: docs
url: /ko/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

DataMatrix 인코더의 인코딩 모드, 기본값은 Auto

## Members
| 멤버 이름 | 설명 |
| :- | :- |
| AUTO | Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. <br/>            Unicode 문자는 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다.<br/>            선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. |
| ASCII | 바이트당 하나의 영숫자 문자 또는 두 개의 숫자를 인코딩합니다. |
| C40 | C40 인코딩을 사용합니다. 대문자 영숫자, 소문자 및 특수 문자를 인코딩합니다. |
| TEXT | Text 인코딩을 사용합니다. 소문자 영숫자, 대문자 및 특수 문자를 인코딩합니다. |
| EDIFACT | EDIFACT 인코딩을 사용합니다. 문자당 6비트를 사용하며, 숫자, 대문자 및 다양한 구두점을 인코딩하지만 소문자는 지원하지 않습니다. |
| ANSIX12 | ANSI X12 인코딩을 사용합니다. |
| EXTENDED |  |
| BASE256 | 8비트 값을 인코딩합니다. |
| BINARY | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. <br/>            Unicode 문자가 발견되면 예외가 발생합니다. |
| ECI | ECI 모드에서는 전체 메시지가 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다.<br/>            선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다.<br/>            일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있다는 점에 유의하십시오. |

### 또 보기

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

