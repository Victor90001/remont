# Remont (Discord)
## Windows
**1.** Скачать и установить https://github.com/amnezia-vpn/amneziawg-windows-client/releases/download/1.0.0/amneziawg-amd64-1.0.0.msi (форк wireguard от amnezia)  
**2.** Нажать на треугольник справа от "Добавить туннель" и выбрать "Добавить пустой туннель"
 ![1](https://github.com/user-attachments/assets/17c9e611-2527-49ad-bf51-cbaf4edf2dc3)  
**3.** Вставить код для туннеля WARP (конфиг настрое только на российские сервера Discord)  
```cfg
[Interface]
PrivateKey = qOI0bayYAd3GOCxgiEDCYCyxmkCvvjmh4Mw1Utg9x1g=
Jc = 4
Jmin = 40
Jmax = 70
H1 = 1
H2 = 2
H3 = 3
H4 = 4
Address = 172.16.0.2/32, 2606:4700:110:89de:326b:d298:c0b1:8370/128
DNS = 1.1.1.1, 2606:4700:4700::1111, 1.0.0.1, 2606:4700:4700::1001
MTU = 1420

[Peer]
PublicKey = bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=
AllowedIPs = 66.22.216.0/23, 128.0.0.0/32, 104.17.117.93/32, 104.17.51.93/32, 104.18.37.76/32, 104.21.25.51/32, 142.250.186.219/32, 142.250.203.155/32, 142.250.203.219/32, 142.250.75.27/32, 162.159.128.0/22, 172.217.16.0/24, 172.64.150.180/32, 172.67.222.182/32, 18.165.140.0/24, 188.114.96.0/22, 204.11.56.48/32, 216.58.208.219/32, 216.58.215.91/32, 23.227.38.74/32, 34.126.226.51/32
Endpoint = engage.cloudflareclient.com:2408
```
![2](https://github.com/user-attachments/assets/16aba4e9-af61-4eae-8dcc-0b8aea6524be)  
**4.** Запускаем и ДС работает  
![3](https://github.com/user-attachments/assets/3021ff6f-24c3-4a7f-9f27-58cfbad3bd59)  
