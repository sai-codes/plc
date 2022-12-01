### Delta  PLC Uygulama  Notları
---
**Örnek Uygulama için Tıklayın**

---
1-Timer
2-Counter
3-Special Memory Register

* ADD
* SUB
* MUL
* DIV

Görevler
- [X] Terminal Bağlantıları
- [ ] Test verileri
- [X] ADC

![DELTA](SX2.JPG)

> Alındı Yapılmıştır.

[PLC Program1] (http://github.com/sai-codes)

| X | Y |
|--|--|
| Buton1 | Motor 1 |
| Buton2 | Valf 1 |

#### Kod Elemanı   

```
  LD XO
     LDI X1
  OUT Y0
```

M1013 Dahili kontak için `Saniyede 1 pals` verir.


<div style="color: red; text-align: center;">
  
  Renklendirmek için
