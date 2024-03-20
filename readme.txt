
--------------------------------------------
1. Tworzenie katalogow oraz plikow zrodlowych:
--------------------------------------------

mkdir komunikator_projekt
cd komunikator_projekt

mkdir serwer
cd serwer
touch serwer.c
cd ../..

mkdir klient
cd klient
touch klient.c
cd ../..


--------------------------------------------
2. Tworzenie kodow serwera i klienta:
--------------------------------------------

nano ~/komunikator_projekt/serwer/serwer.c

nano ~/komunikator_projekt/klient/klient.c



--------------------------------------------
3. Skopiowanie zalaczonych programow
--------------------------------------------



--------------------------------------------
4. Kompilacja:
--------------------------------------------

SERWER:
~/komunikator_projekt$ gcc ~/komunikator_projekt/serwer/serwer.c -o ~/komunikator_projekt/serwer/serwer -lsctp

KLIENT:
~/komunikator_projekt$ gcc ~/komunikator_projekt/klient/klient.c -o ~/komunikator_projekt/klient/klient -lsctp



--------------------------------------------
5. DZIALANIE
--------------------------------------------


**DANE DO LOGOWANIA DO KOMUNIKATORA**

a) user1
   pass1

b) user2
   pass2
   



