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


3. Дальше я поставил варгард <br>
   1). Создал ключи на хосте <br>
      ![image](https://github.com/user-attachments/assets/c3829f7a-e259-4ba7-b9b1-081877265f9b)
   
   2). Дальше напсал конфигурационный файл <br>
      ![image](https://github.com/user-attachments/assets/b0c47437-0dad-4b84-8be3-8387f09d7a9f)

   3). Потом создал ключи для клиента и написал конфигурацию для клиента <br>
      ![image](https://github.com/user-attachments/assets/716f4c84-6555-433c-b1e2-160a02800d84)
      ![image](https://github.com/user-attachments/assets/509db032-065a-4072-82b4-a6a36fdd8981)

4. Делаю ping до приватного сервака <br>
      ![image](https://github.com/user-attachments/assets/c077bb60-57ac-4bdc-a8fe-b893fc875249)

