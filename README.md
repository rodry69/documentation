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
