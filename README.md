Headers 
    accept-encoding: gzip
    authorization: Basic QGczbnQzczIwMTgkJDpQd2QodTNudEAyMDE4JCQ=
    connection: Keep-Alive
    content-length: 462
    content-type: application/json; charset=UTF-8
    host: www4.bcp.com.bo
    user-agent: okhttp/3.12.1
------------------------------------------------------------------------------
Pantallas que se utilizan 
- FragmentSlider
- FragmentLogin
- FragmentInformation
- FragmentPINReset
- FragmentLocation
- FragmentCashoutGenerate
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/device/identification

 Request
{
  "event": 100,
  "notification_id": "evLzgNcbTuSu3Rs6UogdLl:APA91bF8_XdG0BIRVE752g9InVIJDTovJRYgd-ud1OvMF_rAL_PgUi_npBM5BIe0tsQlHkNwQHxOZNtZxXHkoJOb5lA0X_sL5tXscmVtoJLgB_gc05KJjwaER1srb9phoSDrQ6Vnl1-N",
  "product": "Xiaomi|Redmi Note 8|6.4.3|  30",
  "reference": "00000000",
  "version": "6.4.3",
  "certificate": true,
  "device_id": "3d36e231ac41676f",
  "device_type": "android",
  "encrypted_device": "ec3b3598ee666d0f9dc05cb27807a0b929d054a723ef801edc620ea952dfc740",
  "send_id": "rads1k8s"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------
 

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/device/authenticate

 Request
{
  "certificate": false,
  "device_id": "3d36e231ac41676f",
  "device_type": "android",
  "encrypted_device": "ec3b3598ee666d0f9dc05cb27807a0b929d054a723ef801edc620ea952dfc740",
  "send_id": "rads1k8s"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------


https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/device/register/extension/get

 Request
{
  "auth_token": "a81aa0cf-ca22-42f4-806f-74833176fe42"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/device/deposit/get

 Request
{
  "auth_token": "c6b727c2-05f7-4826-9c50-9dca6274e24c"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/device/deposit/pay

Request 
{
  "account": "75211660",
  "amount": 2,
  "certified_id": 3578991,
  "currency": "BOL",
  "deposit_type": "01",
  "document_extension": "LP",
  "document_number": "6824874",
  "document_type": "Q",
  "full_name": "XIMENA TAMBO",
  "mobile_encrypted": "67|105|98|66|116|110|102|105|106|87|88|77|76|54|67|48|75|118|67|105|55|52|112|113|113|78|116|43|85|114|74|77|10",
  "money_destiny": "TRABAJO",
  "money_origin": "TRABAJO",
  "auth_token": "66fcde77-95ca-4b6d-b42e-6667ab426681"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/password/reset/information

Request 
{
  "auth_token": "31449588-aeda-4ec7-a1aa-320e10bc2882"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/password/reset/execute

Request
{
  "certified_id": 3578991,
  "mobile_encrypted": "67|105|114|67|116|110|102|104|105|109|48|73|88|116|54|89|80|74|49|110|78|88|108|75|79|77|88|73|87|57|88|53|10",
  "pin": "67|105|47|72|116|51|65|68|81|73|51|83|82|53|102|48|56|113|68|77|117|115|119|98|56|49|103|61|10",
  "verification_code": "68|83|47|65|116|55|101|50|78|112|101|76|120|50|89|52|75|47|51|122|102|104|88|73|80|117|52|61|10",
  "auth_token": "31449588-aeda-4ec7-a1aa-320e10bc2882"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/device/encrypt/qr

Request
{
  "account_number": "75211660",
  "amount": 0,
  "currency": "BOL",
  "document_number": "6966963",
  "expiration_date": "2023-07-02",
  "gloss": "",
  "multiple_usage": true,
  "name": "Rodrigo Jauregui Choque",
  "auth_token": "e5f7c4b9-317d-4077-bc79-f767bc68ff00"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/login/get

Request
{
  "application": "com.bcp.bo.wallet",
  "certified_id": 3578991,
  "device_id": "68|110|118|68|115|83|80|108|106|50|121|49|48|43|109|117|118|76|105|101|105|105|122|81|110|71|113|89|119|48|68|81|52|48|73|82|88|108|78|65|43|121|85|61|10",
  "device_name": "98|51|113|85|54|105|47|51|56|106|75|103|49|102|50|110|68|101|115|43|105|112|107|82|47|88|65|90|66|56|76|73|115|120|104|120|77|103|61|61|10",
  "device_os": "android",
  "is_root": false,
  "mobile_number": "75211660",
  "notification_id": "evLzgNcbTuSu3Rs6UogdLl:APA91bF8_XdG0BIRVE752g9InVIJDTovJRYgd-ud1OvMF_rAL_PgUi_npBM5BIe0tsQlHkNwQHxOZNtZxXHkoJOb5lA0X_sL5tXscmVtoJLgB_gc05KJjwaER1srb9phoSDrQ6Vnl1-N",
  "pin": "67|105|47|72|116|116|106|54|76|54|71|66|70|120|113|54|47|56|104|89|84|80|69|47|106|43|73|61|10",
  "version": "6.4.3",
  "auth_token": "31449588-aeda-4ec7-a1aa-320e10bc2882"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/reference/welcome

Request
{
  "private_token": "44c8e2e8-3d1e-43dc-ae31-5a5a553b0a76",
  "auth_token": "31449588-aeda-4ec7-a1aa-320e10bc2882"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/walletcards/information/get

Request
{
  "private_token": "44c8e2e8-3d1e-43dc-ae31-5a5a553b0a76",
  "auth_token": "31449588-aeda-4ec7-a1aa-320e10bc2882"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/location/near/get

Request
{
  "channels": [
    "AGENTE"
  ],
  "latitude": -16.498350299999998469502315856516361236572265625,
  "longitude": -68.1335983999999967863914207555353641510009765625,
  "quantity": 100,
  "private_token": "d20a7353-e1dc-493e-82a6-353d9880a8f1",
  "auth_token": "e5f7c4b9-317d-4077-bc79-f767bc68ff00"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/walletcards/bank/get

Request
{
  "private_token": "d20a7353-e1dc-493e-82a6-353d9880a8f1",
  "auth_token": "e5f7c4b9-317d-4077-bc79-f767bc68ff00"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/walletcards/link
Request
{
  "cvv": "67|105|51|72|74|57|56|51|71|51|53|68|78|47|47|105|68|102|122|77|73|82|114|98|115|81|61|61|10",
  "card_code": "1005",
  "certified_id": 3578991,
  "expiration_date": "68|83|55|102|116|88|55|82|89|83|69|84|97|103|83|103|80|47|81|54|112|51|105|74|75|81|107|48|10",
  "pan": "67|83|118|74|116|110|47|108|106|71|110|103|103|79|43|109|115|55|113|100|50|47|114|77|73|108|52|89|122|113|75|74|121|53|79|102|54|117|50|122|68|80|77|61|10",
  "pin": "67|105|47|72|116|116|106|54|76|54|71|66|70|120|113|54|47|56|104|89|84|80|69|47|106|43|73|61|10",
  "private_token": "d20a7353-e1dc-493e-82a6-353d9880a8f1",
  "auth_token": "e5f7c4b9-317d-4077-bc79-f767bc68ff00"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/cashout/code/get

{
  "certified_id": 3578991,
  "private_token": "de6b1380-b38a-42d7-96c3-d3f0eac31a5f",
  "auth_token": "a65a10ed-55f5-490a-8cff-5d20307167c0"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/payment/service/recharge/infomation

{
  "private_token": "d6173fb5-aa2e-4258-ae7a-e886185f52e4",
  "auth_token": "dc7762a6-783b-4834-ae3f-80036096e4c1"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/payment/service/tigo/pre/pay

Request
{
  "name_bill": "RODRIGO JAUREGUI CHOQUE",
  "nit_bill": "6966963",
  "card_code": "",
  "id": 1004,
  "destination_account": "75211660",
  "account_type": "BIL",
  "amount": 1.00,
  "address_bill": "",
  "currency": "BOL",
  "origin_account": "75211660",
  "with_commission": false,
  "certified_id": 3578991,
  "pan": "",
  "pin": "67|105|47|72|116|116|106|54|76|54|71|66|70|120|113|54|47|56|104|89|84|80|69|47|106|43|73|61|10",
  "private_token": "d6173fb5-aa2e-4258-ae7a-e886185f52e4",
  "auth_token": "dc7762a6-783b-4834-ae3f-80036096e4c1"
}


------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/payment/service/recharge/entel

Request
{
  "account_type": "BIL",
  "bill_name": "RODRIGO JAUREGUI CHOQUE",
  "bill_nit": "6966963",
  "card_code": "",
  "code": "71589503",
  "currency": "BOL",
  "origin_account": "75211660",
  "total_amount": 5,
  "certified_id": 3578991,
  "pan": "",
  "pin": "67|105|47|72|116|116|106|54|76|54|71|66|70|120|113|54|47|56|104|89|84|80|69|47|106|43|73|61|10",
  "private_token": "fef3e9ca-f000-4120-83d3-cb50e6188a42",
  "auth_token": "d51f2051-5711-46ac-ae15-db3b378ccdd6"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/payment/service/recharge/viva

Request
{
  "account_type": "BIL",
  "bill_name": "RODRIGO JAUREGUI CHOQUE",
  "bill_nit": "6966963",
  "card_code": "",
  "code": "75211660",
  "currency": "BOL",
  "origin_account": "75211660",
  "total_amount": 1,
  "certified_id": 3578991,
  "pan": "",
  "pin": "67|105|47|72|116|116|106|54|76|54|71|66|70|120|113|54|47|56|104|89|84|80|69|47|106|43|73|61|10",
  "private_token": "fef3e9ca-f000-4120-83d3-cb50e6188a42",
  "auth_token": "d51f2051-5711-46ac-ae15-db3b378ccdd6"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/transfer/account/validate

Request
{
  "account": "79111518",
  "private_token": "fef3e9ca-f000-4120-83d3-cb50e6188a42",
  "auth_token": "d51f2051-5711-46ac-ae15-db3b378ccdd6"
}


------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/token/generate

Request
{
  "certified_id": 3578991,
  "pin": "67|105|47|72|116|116|106|54|76|54|71|66|70|120|113|54|47|56|104|89|84|80|69|47|106|43|73|61|10",
  "private_token": "fef3e9ca-f000-4120-83d3-cb50e6188a42",
  "auth_token": "d51f2051-5711-46ac-ae15-db3b378ccdd6"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/wallet/transfer

{
  "amount": 0.01,
  "card_code": "",
  "certified_id": 3578991,
  "currency": "BOL",
  "detail": "Test",
  "minor_form": {
    "person": {
      "document_extension": "LP",
      "document_number": "6966963",
      "document_type": "Q",
      "first_last_name": "CHOQUE",
      "names": "RODRIGO JAUREGUI",
      "second_last_name": ""
    },
    "destination": "",
    "origin": ""
  },
  "origin_account": "75211660",
  "origin_account_type": "BIL",
  "pan": "",
  "pin": "67|105|47|72|116|116|106|54|76|54|71|66|70|120|113|54|47|56|104|89|84|80|69|47|106|43|73|61|10",
  "target_account": "79111518",
  "target_account_name": "XIMENA TANIA TAMBO CHOQUE",
  "target_account_type": "BIL",
  "target_currency": "BOL",
  "token": "67|67|47|72|115|110|88|109|53|80|74|82|97|119|99|82|120|54|86|106|55|117|109|110|106|100|49|55|70|103|61|61|10",
  "private_token": "fef3e9ca-f000-4120-83d3-cb50e6188a42",
  "auth_token": "d51f2051-5711-46ac-ae15-db3b378ccdd6"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V2/client/interbank/banks/get

Request
{
  "private_token": "fef3e9ca-f000-4120-83d3-cb50e6188a42",
  "auth_token": "d51f2051-5711-46ac-ae15-db3b378ccdd6"
}

------------------------------------------------------------------------------
------------------------------------------------------------------------------

https://www4.bcp.com.bo/BIL_Service2/ServiceBilletera.svc//V1/client/interbank/transfer

Request
{
  "account_type": "BIL",
  "amount": 0.01,
  "amount_currency": "BOL",
  "bank_name": "Banco Nacional de Bolivia",
  "card_code": "",
  "code_branch_destination": "LPZ",
  "code_bank": "1001",
  "currency_destination": "BOL",
  "destination_account": "1501550201",
  "destination_founds": "",
  "detail": "Test",
  "headline_destination": "Jauregui ",
  "origin_account": "75211660",
  "origin_account_name": "RODRIGO JAUREGUI CHOQUE",
  "sources_founds": "",
  "token": "66|83|98|68|115|110|102|118|78|73|47|50|122|79|113|104|102|120|73|87|47|115|81|54|51|66|83|78|70|103|61|61|10",
  "type_account_destination": "CCAD",
  "certified_id": 3578991,
  "minor_form": {
    "person": {
      "document_extension": "LP",
      "document_number": "6966963",
      "document_type": "Q",
      "first_last_name": "CHOQUE",
      "names": "RODRIGO JAUREGUI",
      "second_last_name": ""
    },
    "destination": "",
    "origin": ""
  },
  "pan": "",
  "pin": "67|105|47|72|116|116|106|54|76|54|71|66|70|120|113|54|47|56|104|89|84|80|69|47|106|43|73|61|10",
  "private_token": "fef3e9ca-f000-4120-83d3-cb50e6188a42",
  "auth_token": "d51f2051-5711-46ac-ae15-db3b378ccdd6"
}


------------------------------------------------------------------------------
------------------------------------------------------------------------------
