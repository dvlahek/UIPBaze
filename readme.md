## OPIS
Popis skupova podataka za predmet PUI

## Sadržaj

## Skupovi podataka
* bikesharing_daily - bikesharing_daily.csv: Skup u kojem se predviđa dnevni broj iznajmljenih bicikala (regresijski problem)
* credit_data - credit_data.csv: Skup podataka u kojem se klasificira kreditni rizik korisnika bankarskih usluga
## Opisi

## Značajke bikesharing_daily 
instant: indeks zapisa
dteday: datum
season: godišnje doba (1: proljeće, 2: ljeto, 3: jesen, 4: zima)
yr: godina (0: 2011., 1: 2012.)
mnth: mjesec (1 do 12)
hr: sat (0 do 23)
holiday: pokazatelj je li dan blagdan ili ne (izvor: poveznica)
weekday: dan u tjednu
workingday: ako dan nije vikend ni blagdan, vrijednost je 1, inače je 0.
weathersit:
    1: Vedro, malo oblaka, djelomično oblačno
    2: Magla + oblačno, magla + djelomično oblačno, magla + malo oblaka, magla
    3: Lagani snijeg, lagana kiša + grmljavina + raspršeni oblaci, lagana kiša + raspršeni oblaci
    4: Jaka kiša + ledene kuglice + grmljavina + magla, snijeg + magla
temp: Normalizirana temperatura u stupnjevima Celzijusa (vrijednosti su podijeljene s 41 – maksimum)
atemp: Normalizirana osjetna temperatura u stupnjevima Celzijusa (vrijednosti su podijeljene s 50 – maksimum)
hum: Normalizirana vlažnost zraka (vrijednosti su podijeljene s 100 – maksimum)
windspeed: Normalizirana brzina vjetra (vrijednosti su podijeljene s 67 – maksimum)
casual: broj povremenih korisnika
registered: broj registriranih korisnika
cnt: Značajka koju predviđamo -  
ukupni broj iznajmljenih bicikala, uključujući i povremene i registrirane korisnike
## Značajke credit_data 
Age: Starost
Sex: Spol
Job: 
Housing: Ima svoju nekretninu
Saving accounts: Visina štednje (kategorična)
Checking account: Visina iznosa na tekućem računu (kategorična)
Credit amount: Visina iznosa kredita
Duration: Rok otplate
Purpose: 
Risk: Značajka koju predviđamo
