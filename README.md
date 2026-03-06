## Opis projekta
Ovaj projekat ima za cilj da obuči više modela mašinskog učenja za predlaganje odgovarajuće karijere.
## Potrebni python moduli i njihove verzije
joblib                            1.5.2  
keras                             3.13.2  
matplotlib                        3.10.6  
numpy                             2.3.5  
pandas                            2.3.3  
scikit-learn                      1.7.2  
tensorflow                        2.20.0  
xgboost                           3.2.0  
### Modeli
Modeli koji su obučavani u okviru projekta su:
1. Multinomijalna logistička regresija
2. Ansambli drveta odlučivanja (Random Forest, AdaBoost, XGBoost)
3. KNN
4. Ansambl KNN-ova
5. Potpuno povezana neuronska mreža
## Opis skupa podataka
Skup podataka je sintetički generisan i sastoji se od 5000 instanci, 5 atributa i ciljne promenljive. Atributi su:
1. Education level(Nivo obrazovanja)
Nivo obrazovanja je ordinalni kategorički atribut jer se nivoi obrazovanja mogu upoređivati međusobno i može imati sledeće vredosti: Intermidiate(srednja škola), Matric(viša škola), Bachelor's(fakultet, osnovne studije), Master's(fakultet, master studije), Phd(fakultet, doktorske studije). Ovaj atribut može biti važan pri određivanju predloga karijere jer neka zanimanja kao što su na primer profesor ili inženjer zahtevaju određen nivo obrazovanja.
2. Specialization(Specijalizacija)
Specijalizacija je nominalni kategorički atribut i predstavlja užu specijalizaciju osobe. Može imati sledeće vrednosti: Engineering(Inženjerstvo), Finance(Finansije), Psychology(Psihologija), Buisness(Poslovanje), Computer science(Računarske nauke), Arts(Umetnost), Commerce(Trgovina), Science(Nauka). Ovaj atribut svakako može imati veliki uticaj na određivanje predloga karijere, ali svakako da postoje i osobe koje se specijaliziraju za neku oblast, a ipak izaberu drugačiju karijeru.
3. Skills(Veštine)
Veštine su nominalni kategorički atribut koji se sastoji od više veština odvojenih zarezom, što će u pretprocesiranju podataka predstavljati poteškoću. Ukoliko bi se sve jedinstvene vrednosti ovog atributa razdvojile one bi bile: Counseling(Savetovanje), MS office, Machine learning(Mašinsko učenje), Accounting(Računovodstvo), SQL, Data analysis(Analiza podataka), Communication(Komunikacija), Financial analysis(Finansijska analiza), Python, Marketing. Ovaj atribut svakako treba da ima veliki uticaj na izbor karijere, jer različite karijere zahtevaju različite veštine.
4. Certificates(Sertifikati)
Sertifikati su nominalni kategorički atribut i predstavljaju različite sertifikate koje osoba poseduje. Vrednosti ovog atributa mogu biti: Mental health basics, Tally ERP, AWS certified, Google data analytics, Digital marketing, CFA level 1, Creative writing. Sertifikati potvrđuju određene kvalitete osobe pa mogu biti korisni za lakše napredovanje u okviru neke karijere i samim tim mogu imati uticaj na predlog karijere. 
5. CGPA/Percentage(Prosek u procentima)
Ovo je jedini (diskretni) numerički atribut u skupu podataka koji predstavlja prosek u procentima na nivoima obrazovanja. Ovaj atribut u ovom skupu podataka ima vrednosti u opsegu od 60 do 95 procenata. Ovaj atribut se može kombinovati sa atributom Education level kako bi još bolje objasnio uspeh osobe na različitim nivoima školovanja, što je svakako važno za predlaganje karijere.

Ciljna promenljiva je Recommended Career. U datom skupu podataka ova promenljiva može imati vrednosti: Clerk(Prodavac), Marketing executive(Rukovodilac marketinga), ML engeenier(Inženjer mašinskog učenja), Research scientist(Naučnik istraživač), Software engeenier(Softverski inženjer), School counselor(Školski savetnik), Financial analyst(Finansijski analitičar), Sales asistent(Prodajni asistent), Junior accountant(Juniorski računovođa), Data entry operator(Operator za unos podataka), Professor, Business analyst(Poslovni analitičar). Dakle ciljna promenljiva je nominalna kategorička i ima 12 klasa.
## Važni linkovi
Link ka skupu podataka: https://www.kaggle.com/datasets/ahsanneural/career-path-recommendations-dataset/data

Link ka modelima mašinskog učenja: https://drive.google.com/drive/folders/1b6HGUlu7wGwC08Lv7Sm74YGcWcY7tImq
## Literatura
Skripta za mašinsko učenje: https://ml.matf.bg.ac.rs/readings/ml.pdf
## Članovi tima:
Nikola Kuvekalović 4001/2024, Nemanja Stošić 4002/2024

