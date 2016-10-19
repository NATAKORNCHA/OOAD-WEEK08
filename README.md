# OOAD-WEEK08

## Use Case Diagram (ภาษาไทย)

* ภาพที่ 1 การรับโทรศัพท์ที่มีสายเรียกซ้อน


code 

'''
@startuml

left to right direction
ratee .Left. (Answer the phone) 
(Call Waiting) ..> (Answer the phone) : extends

@enduml
'''

diagram

![](http://www.plantuml.com/plantuml/img/RSkn3O0W40NG_gRu9HGm08N1E0c95o61qy0P75y7i7hLYqDJrxjL8ZAhZCaTcXbNFeKjdFC8FIbp89WjrOgPYXOvBFo2dn70ZxBiWq3nysul)



* ภาพที่ 2 อธิบายการตรวจสอบ user ที่เข้ามาในระบบคอมพิวเตอร์


code 

'''
@startuml


Administrator -- (Validate Users ) 
(Check Password) <-- (Validate Users ) : users

@enduml
'''

diagram


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuT8eIyp9J4aiILK8BKujAjPKqDLLi0gkB2v9pLLmJCdDpCiiBYbABCalik9Im5Hhfw3Xd96QdAqGa5XSN9vVbAAfOALGMfnQpEMGcfS2D1y0)


* ภาพที่ 3 ลูกค้ากับตู้ ATM


![] (http://www.plantuml.com/plantuml/img/RSun3i8m34RXFQVuntJe1JfLH0X690PcAtP9H4YGOzJhK-RspT_mvcwazdqNjrLaCLY3vcSoS5Q9bbjrKo1bN5jXqGdZ27-k9eeRzRusvS7jY0z9uWidAbIZ7857jiHAAmBrT03WBsAub_mP_czkbihRvmy0)


* ภาพที่ 4 ลูกค้ากับพนักงานธนาคาร


![] (http://www.plantuml.com/plantuml/img/PT0x3eGm34NHFgjm2GKRICLM8cm6I_aWvo6sFoaDk3oMV2Ml7SbmbHp6PDb1Q6JwEq2i9XkqrH2tgwCLiKZBGXFBsRfYVlfqAmwsTByTbchVnURtdP665AduR18pQOMOzB4C8K9o_kQzkhfd5_ViqzwVuLKgZzVy0G00)


* ภาพที่ 5 การสั่งซื้อสินค้าทางโทรศัพท์


![] (http://www.plantuml.com/plantuml/img/ROyn3i8m34NtdEAFPUWTAbMm8P0uGKXC6zLDaEFSlmbY0ChytlkMXwnMjAniZ65wA3H1mZGhV11o6b8qW2jPqqg2laVdPd8BQgSb7txXbQqZNCIJxDYnDdSEUSOev8CsuNkjQJVBb9yaEKKquNCHVmHqfy3y5Yh6o2JBAzqTRFdPHZkH63DGzFNn3G00)
