# Task7
1. Создать 2 сервера, 1-ый паблик ( бастион хост) 2-ой сервер в приватке ( только приватный ИП, публичного нет)
   
   1). Cоздал VPC<br>
      ![Image alt](https://github.com/vazikk/Task7/blob/main/image1.png) <br>

   2). Добавление Internet gateway и подключение его к VPC<br>
      ![Image alt](https://github.com/vazikk/Task7/blob/main/image2.png) <br>

   3). Создание Subnets <br>
    ![image](https://github.com/user-attachments/assets/d1da9229-9981-4816-ac10-4273d30a8f23) <br>

   4). Создание Route tables <br>
   ![image](https://github.com/user-attachments/assets/515c4535-4116-4dc5-bacc-a10761f6d25a) <br>

   5). Создание NAT gateway для приватного сервера
   ![image](https://github.com/user-attachments/assets/c63b80c7-8fa6-4b0d-8e52-a7ba145cd34a) <br>
   
   6). Запустил 2 машины
   ![image](https://github.com/user-attachments/assets/c62c24e9-af1a-4027-ac28-c20a2427a906)

2. Скрипт , который при обращении на бастион, будет логиниться на приватный сервер и выполнять там команду апт гет апдейт ssh <br>
   ![image](https://github.com/user-attachments/assets/39f47c42-cf53-4db4-9a98-4b5073a91955) <br>


   
