# Vaja12-UART-NEXTION-DISCOVERY

2.

d) Nextion je objekt poimenoval z0

3.

b)  Zelena LED: PC9 (LD3)
Modra LED: PC8 (LD4)

c) RX=PA10
TX=PA9

Z nextion zaslonom smo povezali ravno obratno torej TX=RX in RX=TX.

d) IN10


4.

e) Enkratna pretvorba 

TABELA:<img width="786" height="222" alt="image" src="https://github.com/user-attachments/assets/3e476313-ad7b-42ef-962c-54aee59b2cd2" />


Nextion za konec vsakega ukaza ki ga prejme preko UART zahteva tri zaporedne bajte 0xFF 0xFF 0xFF. Tako on ve da smo mu nehali pošiljati ukaz in ga lahko izvrši.

Nextion sprejme ASCII znake za števke od 0 do 9, s katerimi se sestavi trimestno število.






