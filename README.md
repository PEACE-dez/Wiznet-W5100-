Wiznet-W5100-
=============

PIC Ethernet
// если W5100  получает от клиента запрос на соединение, он отсылает ему пакет 
// с  установленным флагом ACK и  изменяет свой статуст на SOCK_ESTABLISHED
// («соединение с сокетом установлено)
// Проверить это можно либо  проверкой бита в регистре прерываний, 
// либо 