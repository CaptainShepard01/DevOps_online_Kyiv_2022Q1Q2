# Task 3.2

## Ex. 1
Додав маршрутизатори та налаштував їх інтерфейси  
![Networks](./screenshots/1.png)

## Ex. 2
Реалізував мережу Internet  
![Internet](./screenshots/2.png)

## Ex. 3
Призначення IP-адрес інтерфейсам маршрутизаторів  
![ISP1](./screenshots/5.png)
![ISP2_GE0/0](./screenshots/4.png)  
![ISP2_GE1/0](./screenshots/3.png)  

## Ex. 4
Default Gateway на комп'ютерах  
![DefaultGateway](./screenshots/6.png)

## Ex. 5
Перевірка зв'язку комп’ютерів з власними шлюзами за допомогою команди `ping` (з Client 2)  
![ping1](./screenshots/7.png)

## Ex. 6
`ping` та `tracert` в Data Center  
![ping2](./screenshots/8.png)
![tracert1](./screenshots/9.png)

## Ex. 7
Змінив маску підмережі на серверах на 255.255.255.192  
![mask](./screenshots/10.png)

## Ex. 8
`tracert` з Web Server 1 до Web Server 2 і 3  
![tracert2](./screenshots/11.png)
Now packets go through Router ISP3 because Web Server 1 and Web Server 2 are in different subnets and Switch can not forward packets while Router can.   

## Ex. 9
Зміна VLAN Switch Data Center   
![VLAN](./screenshots/12.png)

## Ex. 10
`ping` DNS Server з Web Server 1  
![ping3](./screenshots/13.png)
Не проходить, оскільки Router ISP3 не вміє перенаправляти тегований трафік між різними VLAN  

## Ex. 11 -> 12
![Trunc](./screenshots/14.png)

## Ex. 13
![RemovingIpISP3](./screenshots/15.png)

## Ex. 14
![CLI](./screenshots/16.png)

## Ex. 15
![DefaultGetawaysNew](./screenshots/17.png)

## Ex. 16
`ping` DNS Server з Web Server 1
![ping4](./screenshots/18.png)