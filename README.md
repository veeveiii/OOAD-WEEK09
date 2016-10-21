# OOAD-WEEK09 Homework
##Usecase Diagram
 
 ## แก้ไขเพิ่มเติม (code and picture)
 
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLl38pqtbSabCKT05CnMi57Boor8LxBXoytDHnUoum1nTNOMKnDBqZ9BK8g24Ho9GiIb2AZW_3oPgPiVba9gN0h8A0000)

1.at home 

Code :

@startuml

class Home

Dad - Home : love >

mom - Home : love>

Home -- daughter : Have 5>

Home -- Son : Have 6>

@enduml

------------------------------------------------------------------------------------------------------------------------

![](http://www.plantuml.com/plantuml/img/RP312i8m38RlUueULUWBUDeGz3044L-WD44BRLAI5jdRkvscgn12yltm_oIz5YUbfjZfYtCEz4mkHiFMPEGSyHSV3Rc4k_sM3W22gblXOAtHmZAxB7rn7S-dTRbwO78HliYuplf6qhbQpo68Pu9G0jEVHFHLGfakrGcqyeD3nDASUnCteToPKzSZmVAH3m00)

2.at shopping mall

@startuml
shoppingmall o- people

shoppingmall *-- store

store o- KFC

store o- Mcdonald

store o- MK

store o- swensens

shoppingmall *-- Aircondition

shoppingmall *-- securityGuard

shoppingmall *-- Toilet

shoppingmall o- PrayerRoom

@enduml

---------------------------------------------------------------------------------------------------------
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU8AJix8pyzHqDBLLIX9JKpEI2r24IikAKr9pIk1Yrafv2Ncfcfe8WaufgGKfHON8uc1DBfa5gKcb-GZJCi76PPVbCh5vP2QbmAo6m00)

3.at school

code :

@startuml

School *-- teacher

School *-- student

School : name()

School : Address()

School *-- Director

School o- store

@enduml
--------------------------------------------------------------------------------------------------------------------

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuVB8Box8B4dCKT3IrLLmoKykoIz25Gj8BCbCpIj125efv2Ncfcfe8eiufgGKfHON8mk2zFgL5XMd8eJoTHMAWUQZYYJdfwMbfXPdv1TmEQJcfO3S1000)

4.at hospital

code :

@startuml

shoppingmall o- people

shoppingmall : name()

shoppingmall : Address()

shoppingmall *-- store

store o- KFC

store o- Mcdonald

store o- MK

store o- swensens

shoppingmall *-- Aircondition

shoppingmall *-- securityGuard

shoppingmall *-- Toilet

shoppingmall o- PrayerRoom

@enduml


----------------------------------------------------------------------------------------

![](http://www.plantuml.com/plantuml/img/RSwn3O0m30NHdYbI8sK72YG6O88FE50aiMKxGcmFFQdV5JUPGxsLFAoS_8RIpaLGdp36652H7_EkYVAfA8MqozP4M7s6OuDHjrdGzFW9nx1pIaHsiGmJrUFRUm40)

5.at software company

code :
@startuml

Softwarecompany *-- analyst

Softwarecompany *-- programmer

Softwarecompany *-- supportDatabase

Softwarecompany *-- Gaurd

Softwarecompany o- coffeeshop

@enduml
