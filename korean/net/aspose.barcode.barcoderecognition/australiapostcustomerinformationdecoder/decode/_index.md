---
title: "AustraliaPostCustomerInformationDecoder.Decode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "AustraliaPostCustomerInformationDecoder 메서드. AustraliaPost 심볼로부터 고객 정보 필드를 디코딩합니다. NTable 및 CTable 인코딩에서 서로 다른 데이터 해석에 사용할 수 있습니다. 데이터는 0 1 2 또는 3의 막대 값 행으로 제공됩니다"
type: docs
weight: 10
url: /ko/net/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder.Decode method

AustraliaPost 심볼로지에서 고객 정보 필드를 디코딩합니다. NTable 및 CTable 인코딩에서 다양한 데이터 해석에 사용할 수 있습니다. 데이터는 0, 1, 2 또는 3의 바 값 행으로 제공됩니다.

```csharp
public string Decode(string customerInformationField)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| customerInformationField | String | 고객 정보 필드가 원시 막대 값 행으로 인코딩되었습니다: 0, 1, 2 또는 3 |

### 반환 값

디코딩된 고객 정보 필드 문자열

## 예제

이 샘플은 AustraliaPostCustomerInformationDecoder 인터페이스를 사용하여 데이터를 디코딩하는 방법을 보여줍니다

```csharp
[C#]
string[] N_Table = { "00", "01", "02", "10", "11", "12", "20", "21", "22", "30" };
public string Decode(string customerInformationField)
{
    StringBuilder bd = new StringBuilder();
    for (int i = 0; customerInformationField.Length > i; i += 2)
    {
        if (customerInformationField.Length >= i + 2)
        {
            string tmp = customerInformationField.Substring(i, 2);
            for (int j = 0; N_Table.Length > j; j++)
            {
                if (N_Table[j].Equals(tmp))
                {
                    bd.Append(j);
                    break;
                }
            }
        }
    }
     return bd.ToString();
}
```

### 또 보기

* interface [AustraliaPostCustomerInformationDecoder](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


