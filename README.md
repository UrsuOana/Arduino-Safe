
# I. Motivatie

## A. De ce am ales acest proiect?
Am ales acest proiect dupa ce am cautat pe Google mai multe idei de proiecte ce pot fi realizate cu ajutorul placii Arduino. Fiind primul meu proiect de acest gen, mi s-a parut destul de simplu de realizat si mi-a placut faptul ca foloseste mai multe componente diferite, ajutandu-ma astfel sa invat si sa-mi dezvolt abilitatile de hardware.

## B. Utilitate
Dupa o eventuala schimbare a cutiei de carton cu una de lemn sau de plastic, proiectul poate fi folosit ca un seif pentru depozitarea oricarui lucru de valoare pe care nu vrem sa-l pierdem.

## C. Cum se foloseste?
Pentru a putea deschide seiful trebuie introdus codul 0000.
In cazul in care codul nu este corect, putem reintroduce codul pana il ghicim.
Daca dorim sa schimbam parola se apasa tasta #, se introduce parola veche (0000), iar apoi parola noua.




# II. Arhitectura hardware
<img width="746" alt="Schema proiect" src="https://user-images.githubusercontent.com/103102760/161979258-14c09eaf-49c2-420b-8a0f-77ced30fbc35.png">

# III. Cheltuieli

1. Arduino Uno – 29,75 lei -  https://ardushop.ro/ro/home/29-placa-de-dezvoltare-uno-r3.html?search_query=arduino+uno&results=254	
2. LCD 1602 verde + IIC - 24,12 lei  - https://ardushop.ro/ro/home/1893-lcd-1602-verde-iic.html?search_query=ecran+lcd&results=56
3. Tastatura matriciala 4x3 - 11,04 lei - https://ardushop.ro/ro/home/128-tastatura-matriciala-4x3.html?search_query=tastatura&results=17
4. Blocaj electronic inchidere usa - 33,28 lei - https://ardushop.ro/ro/home/841-blocaj-electronic-inchidere-usa.html?search_query=incuietoare&results=3	
5. Buzzer pasiv – 2,45 lei - https://ardushop.ro/ro/electronica/194-buzzer.html?search_query=buzzer&results=10
6. Pereche mufe alimentare – 3,53 lei - https://ardushop.ro/ro/home/365-pereche-mufe-alimentare.html?search_query=adaptor+alimentare&results=343
7. Mufa alimentare DC-022 5.5-2.1 – 0,88 lei - https://ardushop.ro/ro/home/776-mufa-alimentare-dc-022-55-21.html?search_query=mufa+alimentare+dc&results=324
8. CABLU USB A-B 0.3M – 8.22 lei - https://cleste.ro/cablu-usb-a-b-05m.html
9. Breadboard 400 – 12,08 lei - https://ardushop.ro/ro/electronica/34-breadboard-400.html?search_query=breadboard&results=15
10. 40 x Fire Dupont tată-tată 10cm - 11,14 lei - https://ardushop.ro/ro/home/1831-10-x-fire-dupont-tata-tata-10cm.html?search_query=fire+tata+tata&results=297
11. 40 x Fire Dupont mamă-tată 20cm – 15,90 lei - https://ardushop.ro/ro/electronica/24-40-x-fire-dupont-tata-mama-10-cm2.html?search_query=fire+mama+tata&results=315
12. Set Jumper breadboard 140 – 11,49 lei - https://ardushop.ro/ro/home/1374-set-jumper-breadboard-140.html
13. Tranzistor IRFZ44N, 49A, 55V, TO-220 – 5 lei - https://www.emag.ro/tranzistor-irfz44n-49a-55v-to-220-ai632-s629/pd/D9QY0DMBM/?cmpid=86724&gclid=Cj0KCQiAqbyNBhC2ARIsALDwAsDIUHL1s5nrjqfMk6eg7W08CzTtA615yQwX_S_D9i5MOD1yE8VubBcaAnstEALw_wcB
Total : 168.88 RON




# IV. Arhitectura software
1. Keypad.h – necesara pentru tastatura matriceala
2. LiquidCrystal_I2C.h – necesara pentru ecranul LCD
3. EEPROM.h – necesara pentru a accesa memoria Arduino 




# V. Bibliografie: 
1.	https://ardushop.ro/ro/electronica/36-lcd-1602.html?search_query=lcd&results=38  – sectiunea descarcari 
2.	http://nicuflorica.blogspot.com/2013/02/arduino-si-o-tastatura-cu-12-butoane.html
3.	https://playground.arduino.cc/Main/KeypadTutorial/
4.	https://bgsu.instructure.com/courses/1157282/pages/tutorial-passive-buzzer
5.	https://techatronic.com/arduino-music-player-using-piezo-buzzer/
6.	https://www.youtube.com/watch?v=u1Uiw4OZtvc
7.	https://www.instructables.com/Arduino-Based-Digital-SAFE-BOX/
8.	https://www.arduino.cc/

