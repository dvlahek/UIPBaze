## OPIS
Popis skupova podataka za predmet PUI

## Sadržaj

## Skupovi podataka
* bikesharing_daily - bikesharing_daily.csv: Skup u kojem se predviđa dnevni broj iznajmljenih bicikala (regresijski problem)
* credit_data - credit_data.csv: Skup podataka u kojem se klasificira kreditni rizik korisnika bankarskih usluga
* housing - housing.csv: Skup podataka za predviđanje cijene stana 
* traffic - traffic.csv Skup podataka za predviđanje prometa
* online_news_pop - online_news_pop.csv: Skup podataka za predviđanja dijeljenja vijesti 
* flight_satisfaction - flight_satisfaction.csv: Skup za predvižanje zadovoljstva putnika letom
* heat_load - heat_load.csv: Skup za predviđanje potrebe grijanja -  Npr. za prodaju grijačih jedinica
* cooling_load - heat_load.csv: Skup za predviđanje potrebe hlađenja - Npr. za prodaju rasladnih uređaja
* cement - cement.csv. Skup podataka za predviđanje tlačne čvrstoće betona (concrete copressive strength - MPa)
* bankruptcy - bankruptcy.csv: Skup podataka za predviđanje stečaja poduzeća
* steel_industry_energy_consuption - steel_industry_energy_consuption.csv: Podaci prikupljeni iz pametne čeličane za predikciju potrošnje energije u industriji čelika
* water_potability - water_potability.csv: Skup za predviđanje je li voda za piće ili ne
## Opisi

## Značajke bikesharing_daily 
* instant: indeks zapisa
* dteday: datum
* season: godišnje doba (1: proljeće, 2: ljeto, 3: jesen, 4: zima)
* yr: godina (0: 2011., 1: 2012.)
* mnth: mjesec (1 do 12)
* hr: sat (0 do 23)
* holiday: pokazatelj je li dan blagdan ili ne (izvor: poveznica)
* weekday: dan u tjednu
* workingday: ako dan nije vikend ni blagdan, vrijednost je 1, inače je 0.
* weathersit:
    1: Vedro, malo oblaka, djelomično oblačno
    2: Magla + oblačno, magla + djelomično oblačno, magla + malo oblaka, magla
    3: Lagani snijeg, lagana kiša + grmljavina + raspršeni oblaci, lagana kiša + raspršeni oblaci
    4: Jaka kiša + ledene kuglice + grmljavina + magla, snijeg + magla
* temp: Normalizirana temperatura u stupnjevima Celzijusa (vrijednosti su podijeljene s 41 – maksimum)
* atemp: Normalizirana osjetna temperatura u stupnjevima Celzijusa (vrijednosti su podijeljene s 50 – maksimum)
* hum: Normalizirana vlažnost zraka (vrijednosti su podijeljene s 100 – maksimum)
* windspeed: Normalizirana brzina vjetra (vrijednosti su podijeljene s 67 – maksimum)
* casual: broj povremenih korisnika
* registered: broj registriranih korisnika
* cnt: Značajka koju predviđamo -  broj bicikala
* ukupni broj iznajmljenih bicikala, uključujući i povremene i registrirane korisnike
## Značajke credit_data 
* Age: Starost
* Sex: Spol
* Job: broj poslova
* Housing: Ima svoju nekretninu
* Saving accounts: Visina štednje (kategorična)
* Checking account: Visina iznosa na tekućem računu (kategorična)
* Credit amount: Visina iznosa kredita
* Duration: Rok otplate
* Purpose: Za što se podiže kredit
* Risk: Značajka koju predviđamo - rizični korisnik 
## Značajke housing
* price: Značajka koju predviđamo -  cijena nekretnine
* area: veličina nekretnine
* bedrooms: broj spavaćih soba
* bathrooms: broj kupaonica
* stories: broj trgovina u blizini
* mainroad: blizina glavne ceste
* guestroom: broj gostinjskih soba
* basement: podrum
* hotwaterheating: grijač tople vode?
* airconditioning: klima?
* parking: parking?
* prefarea: preferirano područje kupca
* furnishingstatus: stanje namještenosti
## Značajke traffic
date_time 
* is_holiday 
* air_pollution_index
* humidity
* wind_speed
* wind_direction
* visibility_in_miles
* dew_point
* temperature
* rain_p_h
* snow_p_h
* clouds_all
* weather_type 
* weather_description
* traffic_volume: Značajka koju predviđamo - broj vozila
##
*  url : URL članka (ne-prediktivno)
*  timedelta : Broj dana između objave članka i preuzimanja skupa podataka (ne-prediktivno)
*  n_tokens_title : Broj riječi u naslovu
*  n_tokens_content : Broj riječi u sadržaju
*  n_unique_tokens : Postotak jedinstvenih riječi u sadržaju
*  n_non_stop_words : Postotak riječi koje nisu zaustavne (stop words) u sadržaju
*  n_non_stop_unique_tokens : Postotak jedinstvenih riječi koje nisu zaustavne u sadržaju
*  num_hrefs : Broj poveznica (linkova)
*  num_self_hrefs : Broj poveznica na druge članke objavljene od strane Mashable-a
*  num_imgs : Broj slika
*  num_videos : Broj videozapisa
*  average_token_length : Prosječna duljina riječi u sadržaju
*  num_keywords : Broj ključnih riječi u metapodacima
*  data_channel_is_lifestyle : Je li članak u kategoriji 'Lifestyle'?
*  data_channel_is_entertainment : Je li članak u kategoriji 'Zabava' (Entertainment)?
*  data_channel_is_bus : Je li članak u kategoriji 'Poslovanje' (Business)?
*  data_channel_is_socmed : Je li članak u kategoriji 'Društveni mediji' (Social Media)?
*  data_channel_is_tech : Je li članak u kategoriji 'Tehnologija' (Tech)?
*  data_channel_is_world : Je li članak u kategoriji 'Svijet' (World)?
*  kw_min_min : Najlošija ključna riječ (min)
*  kw_max_min : Najlošija ključna riječ (max)
*  kw_avg_min : Najlošija ključna riječ (prosjek)
*  kw_min_max : Najbolja ključna riječ (min)
*  kw_max_max : Najbolja ključna riječ (max)
*  kw_avg_max : Najbolja ključna riječ (prosjek)
*  kw_min_avg : Prosjek
*  kw_max_avg : Prosjek
*  kw_avg_avg : Prosjek
*  self_reference_min_shares : Min
*  self_reference_max_shares : Max
*  self_reference_avg_sharess : Prosjek
*  weekday_is_monday : Je li članak objavljen u ponedjeljak?
*  weekday_is_tuesday : Je li članak objavljen u utorak?
*  weekday_is_wednesday : Je li članak objavljen u srijedu?
*  weekday_is_thursday : Je li članak objavljen u četvrtak?
*  weekday_is_friday : Je li članak objavljen u petak?
*  weekday_is_saturday : Je li članak objavljen u subotu?
*  weekday_is_sunday : Je li članak objavljen u nedjelju?
*  is_weekend : Je li članak objavljen vikendom?
*  LDA_00 : Blizina LDA (Latent Dirichlet Allocation) temi 0
*  LDA_01 : Blizina LDA temi 1
*  LDA_02 : Blizina LDA temi 2
*  LDA_03 : Blizina LDA temi 3
*  LDA_04 : Blizina LDA temi 4
*  global_subjectivity : Subjektivnost teksta
*  global_sentiment_polarity : Polaritet sentimenta teksta
*  global_rate_positive_words : Udio pozitivnih riječi u sadržaju
*  global_rate_negative_words : Udio negativnih riječi u sadržaju
*  rate_positive_words : Udio pozitivnih riječi među ne-neutralnim tokenima
*  rate_negative_words : Udio negativnih riječi među ne-neutralnim tokenima
*  avg_positive_polarity : Prosjek
*  min_positive_polarity : Min
*  max_positive_polarity : Max
*  avg_negative_polarity : Prosjek
*  min_negative_polarity : Min
*  max_negative_polarity : Max
*  title_subjectivity : Subjektivnost naslova
*  title_sentiment_polarity : Polaritet naslova
*  abs_title_subjectivity : Apsolutna razina subjektivnosti
*  abs_title_sentiment_polarity : Apsolutna razina polariteta
*  shares : Značajka koju predviđamo - Broj dijeljenja članka
## Značajke flight_satisfaction
* Gender: Spol putnika (Žensko, Muško)
* Customer Type: Tip kupca (Vjerni kupac, Nevjerni kupac)
* Age: Stvarna dob putnika
* Type of Travel: Svrha leta putnika (Osobno putovanje, Poslovno putovanje)
* Class: Klasa putovanja u avionu (Poslovna, Ekonomična, Ekonomična Plus)
* Flight distance: Udaljenost putovanja leta
* Inflight wifi service: Razina zadovoljstva WiFi uslugom u letu 
* Departure/Arrival time convenient: Razina zadovoljstva vremenom polaska/dolaska
* Ease of Online booking: Razina zadovoljstva online rezervacijom
* Gate location: Razina zadovoljstva lokacijom izlazne kapije
* Food and drink: Razina zadovoljstva hranom i pićem
* Online boarding: Razina zadovoljstva online prijavom na let
* Seat comfort: Razina zadovoljstva udobnošću sjedala
* Inflight entertainment: Razina zadovoljstva zabavom u letu
* On-board service: Razina zadovoljstva uslugom na brodu
* Leg room service: Razina zadovoljstva prostorom za noge
* Baggage handling: Razina zadovoljstva rukovanjem prtljagom
* Check-in service: Razina zadovoljstva uslugom prijave na let
* Inflight service: Razina zadovoljstva uslugom u letu
* Cleanliness: Razina zadovoljstva čistoćom
* Departure Delay in Minutes: Kašnjenje pri polasku u minutama
* Arrival Delay in Minutes: Kašnjenje pri dolasku u minutama
* Satisfaction: Značajka koju predviđamo - Razina zadovoljstva zrakoplovnom kompanijom (Zadovoljstvo, Neutralno, Nezadovoljstvo)
## Značajke heat_load
* Relative Compactness: Relativna kompaktnost stana
* Surface Area:	Površina
* Wall Area: Površina zida
* Roof Area: Površina krova
* Overall Height: Ukupna visina
* Orientation:	Orijentacija 
* Glazing Area: Površina ostakljenja 
* Glazing Area Distribution: Raspodjela površine ostakljenja
* Heating load: Značajka koju predviđamo - Toplinski učinak grijanja 
## Značajke cooling_load
* Relative Compactness: Relativna kompaktnost stana
* Surface Area:	Površina
* Wall Area: Površina zida
* Roof Area: Površina krova
* Overall Height: Ukupna visina
* Orientation:	Orijentacija 
* Glazing Area: Površina ostakljenja 
* Glazing Area Distribution: Raspodjela površine ostakljenja
* Cooling load: Značajka koju predviđamo - Toplinski učinak hlađenja 
## Značajke cement
* Cement: Cement
* Blast Furnace Slag: Troska visoke peći
* Fly Ash: Količina pepela
* Water: Količina vode
* Superplasticizer: Količina superplastifikatora
* Coarse Aggregate: Količina grubih agregata (šoder)
* Fine Aggregate: Količina finih agregata (pijesak)
* Age: starost cementa
* Concrete compressive strength: Značajka koju predviđamo - Tlačna čvrstoća betona
## Značajke bankruptcy
* Bankrupt :  Značajka koju predviđamo - bankrot ili ne
* ROA(C) before interest and depreciation before interest: Return On Total Assets(C) : ROA(C) prije kamata i amortizacije prije kamata- Povrat na ukupnu imovinu (C)
* ROA(A) before interest and % after tax: Return On Total Assets(A) : ROA(A) prije kamata i % nakon oporezivanja- Povrat na ukupnu imovinu (A)
* ROA(B) before interest and depreciation after tax: Return On Total Assets(B) : ROA(B) prije kamata i amortizacije nakon oporezivanja- Povrat na ukupnu imovinu (B)
* Operating Gross Margin: Gross Profit/Net Sales : Bruto profitna marža poslovanja- Bruto dobit/Neto prodaja
* Realized Sales Gross Margin: Realized Gross Profit/Net Sales : Ostvarena bruto profitna marža prodaje- Ostvarena bruto dobit/Neto prodaja
* Operating Profit Rate: Operating Income/Net Sales : Stopa operativnog profita- Operativni prihod/Neto prodaja
* Pre-tax net Interest Rate: Pre-Tax Income/Net Sales : Stopa neto interesa prije oporezivanja- Neto prihod prije oporezivanja/Neto prodaja
* After-tax net Interest Rate: Net Income/Net Sales : Stopa neto interesa nakon oporezivanja- Neto prihod/Neto prodaja
* Non-industry income and expenditure/revenue: Net Non-operating Income Ratio : Prihodi i rashodi izvan osnovne djelatnosti- Neto omjer neoperativnog prihoda
* Continuous interest rate (after tax): Net Income-Exclude Disposal Gain or Loss/Net Sales : Kontinuirana kamatna stopa (nakon oporezivanja)- Neto prihod bez dobiti/gubitka od otuđenja/Neto prodaja
* Operating Expense Rate: Operating Expenses/Net Sales : Stopa operativnih troškova- Operativni troškovi/Neto prodaja
* Research and development expense rate: (Research and Development Expenses)/Net Sales : Stopa troškova istraživanja i razvoja- (Troškovi istraživanja i razvoja)/Neto prodaja
* Cash flow rate: Cash Flow from Operating/Current Liabilities : Stopa novčanog toka- Novčani tok iz poslovanja/Tekuće obveze
* Interest-bearing debt interest rate: Interest-bearing Debt/Equity : Stopa kamata na dug s kamatom- Dug s kamatom/Kapital
* Tax rate (A): Effective Tax Rate : Stopa poreza (A)- Efektivna porezna stopa
* Net Value Per Share (B): Book Value Per Share(B) : Knjigovodstvena vrijednost po dionici (B)
* Net Value Per Share (A): Book Value Per Share(A) : Knjigovodstvena vrijednost po dionici (A)
* Net Value Per Share (C): Book Value Per Share(C) : Knjigovodstvena vrijednost po dionici (C)
* Persistent EPS in the Last Four Seasons: EPS-Net Income : Postojani EPS u posljednje četiri sezone- EPS-neto dobit
* Cash Flow Per Share : Novčani tok po dionici
* Revenue Per Share (Yuan ¥): Sales Per Share : Prihod po dionici (¥ juan)- Prodaja po dionici
* Operating Profit Per Share (Yuan ¥): Operating Income Per Share : Operativni profit po dionici (¥ juan)- Operativni prihod po dionici
* Per Share Net profit before tax (Yuan ¥): Pretax Income Per Share : Neto dobit prije poreza po dionici (¥ juan)- Neto prihod prije poreza po dionici
* Realized Sales Gross Profit Growth Rate : Stopa rasta ostvarene bruto dobiti prodaje
* Operating Profit Growth Rate: Operating Income Growth : Stopa rasta operativne dobiti- Rast operativnog prihoda
* After-tax Net Profit Growth Rate: Net Income Growth : Stopa rasta neto dobiti nakon oporezivanja- Rast neto prihoda
* Regular Net Profit Growth Rate: Continuing Operating Income after Tax Growth : Stopa rasta redovite neto dobiti- Rast kontinuiranog operativnog prihoda nakon oporezivanja
* Continuous Net Profit Growth Rate: Net Income-Excluding Disposal Gain or Loss Growth : Stopa rasta kontinuirane neto dobiti- Rast neto prihoda bez dobiti/gubitka od otuđenja
* Total Asset Growth Rate: Total Asset Growth : Stopa rasta ukupne imovine- Rast ukupne imovine
* Net Value Growth Rate: Total Equity Growth : Stopa rasta neto vrijednosti- Rast ukupnog kapitala
* Total Asset Return Growth Rate Ratio: Return on Total Asset Growth : Stopa rasta povrata na ukupnu imovinu
* Cash Reinvestment %: Cash Reinvestment Ratio : Postotak reinvesticije gotovine- Omjer reinvesticije gotovine
* Current Ratio : Trenutni omjer likvidnosti
* Quick Ratio: Acid Test : Brzi omjer likvidnosti- Kiselinski test
* Interest Expense Ratio: Interest Expenses/Total Revenue : Omjer troškova kamata- Troškovi kamata/Ukupni prihod
* Total debt/Total net worth: Total Liability/Equity Ratio : Ukupni dug/Ukupna neto vrijednost- Omjer ukupnih obveza i kapitala
* Debt ratio %: Liability/Total Assets : Omjer duga %- Obveze/Ukupna imovina
* Net worth/Assets: Equity/Total Assets : Kapital/Imovina- Kapital/Ukupna imovina
* Long-term fund suitability ratio (A): (Long-term Liability+Equity)/Fixed Assets : Omjer dugoročnih izvora financiranja (A)- (Dugoročne obveze + kapital)/Stalna imovina
* Borrowing dependency: Cost of Interest-bearing Debt : Ovisnost o posudbama- Trošak duga s kamatom
* Contingent liabilities/Net worth: Contingent Liability/Equity : Uvjetne obveze/Neto vrijednost- Uvjetne obveze/Kapital
* Operating profit/Paid-in capital: Operating Income/Capital : Operativni profit/Uplaćeni kapital- Operativni prihod/Kapital
* Net profit before tax/Paid-in capital: Pretax Income/Capital : Neto profit prije oporezivanja/Uplaćeni kapital- Neto prihod prije poreza/Kapital
* Inventory and accounts receivable/Net value: (Inventory+Accounts Receivables)/Equity : Zalihe i potraživanja/Neto vrijednost- (Zalihe + Potraživanja)/Kapital
* Total Asset Turnover : Obrt imovine
* Accounts Receivable Turnover : Obrt potraživanja
* Average Collection Days: Days Receivable Outstanding : Prosječni dani naplate- Dani nenaplaćenih potraživanja
* Inventory Turnover Rate (times) : Stopa obrta zaliha (puta)
* Fixed Assets Turnover Frequency : Frekvencija obrta stalne imovine
* Net Worth Turnover Rate (times): Equity Turnover : Stopa obrta kapitala (puta)- Obrt kapitala
* Revenue per person: Sales Per Employee : Prihod po zaposleniku- Prodaja po zaposleniku
* Operating profit per person: Operation Income Per Employee : Operativni profit po zaposleniku- Operativni prihod po zaposleniku
* Allocation rate per person: Fixed Assets Per Employee : Omjer alokacije po zaposleniku- Stalna imovina po zaposleniku
* Working Capital to Total Assets : Radni kapital/Ukupna imovina
* Quick Assets/Total Assets : Brza imovina/Ukupna imovina
* Current Assets/Total Assets : Tekuća imovina/Ukupna imovina
* Cash/Total Assets : Novac/Ukupna imovina
* Quick Assets/Current Liability : Brza imovina/Tekuće obveze
* Cash/Current Liability : Novac/Tekuće obveze
* Current Liability to Assets : Tekuće obveze/Imovina
* Operating Funds to Liability : Operativna sredstva/Obveze
* Inventory/Working Capital : Zalihe/Radni kapital
* Inventory/Current Liability : Zalihe/Tekuće obveze
* Current Liabilities/Liability : Tekuće obveze/Obveze
* Working Capital/Equity : Radni kapital/Kapital
* Current Liabilities/Equity : Tekuće obveze/Kapital
* Long-term Liability to Current Assets : Dugoročne obveze/Tekuća imovina
* Retained Earnings to Total Assets : Zadržana dobit/Ukupna imovina
* Total income/Total expense : Ukupni prihodi/Ukupni troškovi
* Total expense/Assets : Ukupni troškovi/Imovina
* Current Asset Turnover Rate: Current Assets to Sales : Stopa obrta tekuće imovine- Tekuća imovina/Prodaja
* Quick Asset Turnover Rate: Quick Assets to Sales : Stopa obrta brze imovine- Brza imovina/Prodaja
* Working capitcal Turnover Rate: Working Capital to Sales : Stopa obrta radnog kapitala- Radni kapital/Prodaja
* Cash Turnover Rate: Cash to Sales : Stopa obrta novca- Novac/Prodaja
* Cash Flow to Sales : Novčani tok/Prodaja
* Fixed Assets to Assets : Stalna imovina/Imovina
* Current Liability to Liability : Tekuće obveze/Obveze
* Current Liability to Equity : Tekuće obveze/Kapital
* Equity to Long-term Liability : Kapital/Dugoročne obveze
* Cash Flow to Total Assets : Novčani tok/Ukupna imovina
* Cash Flow to Liability : Novčani tok/Obveze
* CFO to Assets : Novčani tok od operacija/Imovina
* Cash Flow to Equity : Novčani tok/Kapital
* Current Liability to Current Assets : Tekuće obveze/Tekuća imovina
* Liability-Assets Flag: 1 if Total Liability exceeds Total Assets, 0 otherwise : Zastavica obveze-imovina- 1 ako su ukupne obveze veće od ukupne imovine, 0 inače
* Net Income to Total Assets : Neto prihod/Ukupna imovina
* Total assets to GNP price : Ukupna imovina/GNP cijena
* No-credit Interval : Interval bez kredita
* Gross Profit to Sales : Bruto dobit/Prodaja
* Net Income to Stockholder's Equity : Neto prihod/Vlasnički kapital dioničara
* Liability to Equity : Omjer obveza i kapitala
* Degree of Financial Leverage (DFL) : Stupanj financijske poluge (DFL)
* Interest Coverage Ratio (Interest expense to EBIT) : Pokazatelj pokrića kamata (Trošak kamata prema EBIT-u)
* Net Income Flag: 1 if Net Income is Negative for the last two years, 0 otherwise : Zastavica neto prihoda- 1 ako je neto prihod negativan u posljednje dvije godine, 0 inače
* Equity to Liability : Kapital/Obveze
## Značajke steel_industry_energy_consuption
* Date: datum
* Usage_kWh:  Industrijska potrošnja energije (kontinuirano, kWh)
* Lagging_Current_Reactive.Power_kVarh: Zaostala jalova snaga (kontinuirano, kVarh)
* Leading_Current_Reactive_Power_kVarh: Prednjačeća jalova snaga (kontinuirano, kVarh)
* CO2(tCO2): Koncentracija CO2 (kontinuirano, ppm)
* Lagging_Current_Power_Factor: 
* Leading_Current_Power_Factor
* NSM: Broj sekundi od ponoći (kontinuirano, s)
* WeekStatus:  Kategorična varijabla (Vikend (0) ili Radni dan (1))
* Day_of_week: Kategorična varijabla - dan u tjednu
* Load_Type:  Značajka koju predviđamo - Kategorična varijabla (Malo opterećenje, Srednje opterećenje, Maksimalno opterećenje)
## Značajke water_potability
* ph: kiselost vode
* Hardness: tvrdoća vode
* Solids: količina krutih stvari u vodi
* Chloramines: količina kloramina u vodi
* Sulfate: količina sulfata u vodi
* Conductivity: električna vodljivost vode
* Organic_carbon: količina organskog ugljik u vodi
* Trihalomethanes: Trihalometani  u vodi
* Turbidity: turbiditet označava zamućenost vode uzrokovanu prisutnošću suspendiranih čestica
* Potability: Značajka koju predviđamo - Pitka ili ne

