# HW-CANBUS-MODULE
## TJA1051 entegresi kullanarak Altium üzerinden modül tasarımı
Projede can bus modülü olan TJA1051 entegresi kullanılarak asansör ve araç endüstrisinde fazlaca kullanılan can haberleşme 
protokolünün test edilmesi işlemlerinin kolaylaştırılması amaçlanmıştır. 

## TJA1051 PIN

| Sembol | Pin | Açıklama |
| ------ | --- | -------- |
|  TXD   |  1  |  Veri girişini iletme |
|  GND   |  2  |  Topraklama |
|  VCC   |  3  |  Giriş voltajı |
|  RXD   |  4  | Veri çıkışı almak; veri yolu hatlarından verileri okur |
| n.c.   |  5  | Bağlantı yapılmayan bacak ; TJA1051T versiyonunda |
| CANL   |  6  | DÜŞÜK seviye  CAN veri yolu hattı |
| CANH   |  7  | YÜKSEK seviye CAN veri yolu hattı|
|   S    |  8  | Sessiz mod kontrol girişi |

  ## Komponentler
- TJA1051
- 47  µF Tantal kondansatör
- 0.1 µF kondansatör
- 100 pF kondansatör
- 15  pF kondansatör
- 10  Kohm direnç
- 120 ohm  direnç
  
## Şematik
![can](https://github.com/KOBASTAR-IME-2024/HW-CANBUS-MODULE/assets/115595244/69e5f68c-960d-4a3e-98a8-066b5d85997d)

## PCB
![Can_Bus_PCB](https://github.com/KOBASTAR-IME-2024/CanBus_Module_HW/assets/119225109/25ad43e4-eaad-4a5d-9c16-41b2792c4c21)
![Can_Bus_PCB_visible](https://github.com/KOBASTAR-IME-2024/CanBus_Module_HW/assets/119225109/e2c3928a-6aad-4e8c-9c0c-7828b5f8e6a3)

## PCB 3D
![Can_Bus_up](https://github.com/KOBASTAR-IME-2024/CanBus_Module_HW/assets/119225109/d6f51d38-e43a-4a2c-8990-1471f13edd80)
![Can_Bus](https://github.com/KOBASTAR-IME-2024/CanBus_Module_HW/assets/119225109/69146131-03a6-411f-8e8d-15fffade6abe)

![Tja1051](https://github.com/KOBASTAR-IME-2024/HW-CANBUS-MODULE/assets/119225109/8074c2b0-93b8-4711-a0b0-bed4fe802852)

