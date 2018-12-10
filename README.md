# Curs-Battery-Management-System-BMS-
Sistem de gestionare si monitorizare a consumului de energie electrica.


 Introducere
    
Vehiculele electrice sunt deja parte din proiectele de dezvoltare ale multor producători de mașini și sunt văzute ca o soluție pentru viitorul apropiat în ce privește reducerea emisiilor de gaze, implicit a efectului de seră, deci și a încălzirii globale.
Sistemele de stocare a energiei electrice sunt componente cheie ale acestor tipuri de mașini. Aceste sisteme au în componență, pe lângă baterii, subsisteme cu rol în monitorizarea bateriilor în funcțiune, dar și la încărcarea lor, așanumitul Sistemul de Management al Energiei într-o mașină(Battery Management System - BMS).
Conform lucrării lui José Miguel Branco Marque [1] , monitorizarea și managementul energiei într-un vehicul electric necesită utilizarea unor algoritmi cu ajutorul cărora se identifică starea bateriilor ( SOC - State of Charge). Cu ajutorul acestor algoritmi utilizatorul află informații despre energia din baterii, temperatura acestora, sau distanța care mai poate fi parcursă cu mașina.

 Descrierea sistemului
    
    Sistemul de management al energiei într-o mașină electrică are rolul de garanta siguranța funcționării acestora în condiții de siguranță și totodată de a prelungi viața bateriilor prin asigurarea unui regim de funcționare corespunzător. Conform articolului intitulat Battery-Management System (BMS) and SOC Development for Electrical Vehicles [2], partea de Battery Management System(BMS) este o componentă esențială în structura unei mașini electrice. Prin urmare, toate vehiculele electrice prezintă un astfel de sistem prin care se gestionează consumul de energie din acumulatori. Monitorizarea bateriilor este vitală pentru toate mașinile electrice în primul rând din motive de siguranță pentru pasageri, dar și pentru cei din jurul autovehiculului.    
 Bateriile

    Bateriile sunt cele mai comune dispozitive de stocare a energiei electrice în vehiculele electrice. Performanța unei baterii atunci când este conectată la o sursă se bazează pe reacțiile chimice din interiorul acesteia. Produsele chimice se degradează în funcție de timp și utilizare, ceea ce reflectă reducerea treptată a capacității de stocare a energiei a bateriei. Procesul de amortizare a bateriei trebuie redus prin condiționarea bateriei într-o manieră adecvată, prin controlul profilului său de încărcare și descărcare. În general, durata de viață a bateriei va fi diminuată atunci când bateria funcționează într-o gamă largă de condiții termice și cicluri frecvente de încărcare și descărcare profundă, în special în condiții de curent în impulsuri mari.

    O baterie este un dispozitiv electrochimic care convertește energia chimică direct în energie electrică. În sistemele reîncărcabile din industria auto, bateria
este reîncărcată prin inversarea acestui proces.




    Celula de Litiu-Ion este formată din trei elemente majore care se regăsesc în orice baterie:
 Anodul sau electrodul negativ - electrodul de reducere - care eliberează electroni la circuitul extern și este oxidat în timpul reacției electrochimice;

 Catodul sau electrodul pozitiv - electrodul de oxidare - care acceptă electroni de la
             circuitul extern și este redus în timpul reacției electrochimice;

      3.   Electrolitul - conductorul ionic - care asigură mediul pentru transferul încărcării în                  
             interiorul celulei dintre anod și catod. 

Bateriile pentru vehiculele electrice

    Vehiculele electrice necesită o sursă portabilă de energie electrică. Toată această energie electrică este stocată într-un sistem de stocare a energiei  care ar trebui să corespundă cerințelor energetice ale diferitelor vehicule(sisteme de tracțiune, iluminat, climatizare), iar în același timp să garanteze o autonomie rezonabilă. Cu tehnologia de ultimă generație existentă, cea mai mare parte a acestei energii este stocată în baterii (uneori completată cu supercondensatoare sau volante pentru a îmbunătăți răspunsul la cerințele de vârf ale diverșilor producători de mașini).
    Conform lucrării Battery Management System (BMS) for Lithium-Ion Batteries [1]producătorii de vehicule electrice au nevoie de următoarele caracteristici de la baterii pentru ca vehiculul să aibă o bună funcționalitate:
• Capacitate mare a bateriilor care este necesară pentru a parcurge o distanță rezonabilă.  Un vehicul electric tipic utilizează în jur de 100 până la 150 Wh pe kilometru, în funcție de teren și de stilul de condus.
• Bateria trebuie să fie capabilă să funcționeze cu descărcare regulată profundă (operațiune de descărcare în adâncime de 80% sau mai mare);
• Un sistem conceput pentru a minimiza pierderile de energie și pentru a furniza o putere completă, chiar și în timpul unei descărcări profunde.
• Trebuie să poată accepta curenți de încărcare pulsatorii foarte înalți atunci când se aplică frânarea regenerativă;
• capacitatea de a primi în mod obișnuit o încărcare completă;
• Avertizare privind indicatorul de combustibil în apropierea punctului "gol";
• Nevoia unui sistem de gestionare a bateriilor (BMS);
• Necesitatea gestionării termice;
• Tensiune tipică> 300V;
• Capacitate tipică> 20 - 60kWh.
    
Bateriile din cadrul vehiculelor electrice sau bateriile de tracțiune diferă de bateria tipică din categoria automobilelor cu motoare care au combustie internă. Cele din urmă sunt cunoscute ca baterii de putere, deoarece acestea sunt folosite pentru a porni motorul și sistemul de lumini al unei mașini convenționale.  Acestea sunt de regulă baterii plumb-acid și sunt fabricate din șase celule galvanice înseriate pentru a furniza un sistem de 12V. Ele trebuie să furnizeze vârfuri de curent ridicat pentru o perioadă scurtă de timp, acestea funcționând în mare măsură aproape de capacitatea de încărcare completă.
    Bateriile pentru vehiculele electrice se caracterizează prin raportul lor relativ ridicat între putere - greutate, greutate energetică - densitatea energetică. Bateriile mai mici, mai ușoare reduc greutatea vehiculului și îi îmbunătățesc performanțele. 
De obicei cele două tipuri de baterii coexistă pe un vehicul electric, dar cu funcții diferite. Bateriile pentru tracțiune trebuie proiectate pentru a furniza energie pentru motorul electric pentru perioade lungi de timp. De asemenea, acestea au nevoie și de o putere de vârf în timpul unei accelerații rapide, iar aici intervin bateriile de putere.
În comparație cu combustibilii fosili, în zilele noastre, tehnologiile acumulatorilor oferă energie mai putina și acest lucru  influențează distanța care poate fi parcursă de vehicule.





În industria auto, în ceea ce privește bateriile. așa cum se poate vedea în Figura 3, tendința primară este creșterea densității de energie. Acest lucru a favorizat o mișcare către chimia litiu-ion, deși alte chimii pot demonstra o longevitate mai mare și costuri specifice mai mici.




Tipuri de baterii

Pentru vehiculele electrice pot fi folosite mai multe tipuri de baterii. Astfel, în cadrul acestui subcapitol vor fi prezentate principalele tipuri de baterii, făcând referință la articolul lui Alireza Khaligh [3].

Bateriile Plumb-Acid

Plumbul spongios funcționează ca material activ negativ al bateriei, oxidul de plumb este materialul activ pozitiv și acidul sulfuric diluat este electrolitul. Pentru descărcare, atât părțile pozitive cât și cele negative sunt transformate în sulfat de plumb. Acumulatorul plumb-acid prezintă mai multe avantaje pentru vehiculele electrice. Acestea sunt disponibile în prezent și sunt foarte ușor de accesat, întrucât prezintă o sursă de energie relativ ieftină. În plus, tehnologia cu plumb-acid este o tehnică matură datorită utilizării sale largi în ultimii 50 de ani. Cu toate acestea, bateria plumb-acid nu este adecvată pentru descărcări de peste 20% din capacitatea nominală. Atunci când funcționează la o viteză mare de încărcare, bateria ar avea un ciclu de viață limitat. Densitatea energetică și de putere a bateriei este scăzută datorită greutății colectorilor de plumb. Eforturile de cercetare au constatat că densitatea energetică poate fi îmbunătățită prin utilizarea colectoarelor necorozive mai ușoare.

B.  Bateriile Nichel-Metal Hidrură (NiMH)

Bateria NiMH utilizează o soluție alcalină ca electrolit. Bateria NiMH este compusă din hidroxid de nichel pe electrodul pozitiv, iar electrodul negativ este format dintr-un aliaj fabricat din vanadiu, titan, nichel și altele metale. Densitatea energetică a bateriei NiMH este de două ori mai mare decât cea a bateriei plumb-acid. Componentele NiMH nu poluează mediul înconjurător; în plus, bateriile pot fi reciclate. Bateria NiMH este sigură la funcționarea la tensiuni înalte și are avantaje distincte, cum ar fi stocarea energiei volumetrice, putere, durată lungă de funcționare, gamă lară de temperaturi în care poate funcționa, dar și  rezistență la supraîncărcare și descărcare completă. 
Pe de altă parte, dacă este descărcată complet în mod repetat, durata de viață a NiMH este redusă la circa 200-300 de cicluri. Performanța optimă a funcționării este realizată atunci când este descărcată de la 20% până la 50% din capacitatea nominală.

C.  Bateriile Litiu-Ion

Bateriile litiu-ion s-au dovedit a fi excelente ca performanță în electronică și dispozitive medicale portabile. Acestea au o densitate mare de energie, au performanțe bune la temperatură ridicată și se pot recicla.
Electrodul pozitiv este realizat dintr-un material de cobalt oxidat, iar cel negativ dintr-un material de carbon. Sarea de litiu într-un solvent organic este utilizată ca electrolit. Aspectele promițătoare ale bateriilor Li-ion includ un efect de memorie redus, putere specifică ridicată de 300 W / kg, energie specifică ridicată de 100 Wh / kg, și o durată lungă de viață a bateriei de 1000 de cicluri. 
Aceste caracteristici dau bateriei litiu-ion o posibilitate mare de înlocuire a bateriilor NiMH pe următoarele generații de vehicule. Bateriile  NiMH au fost evaluate la aproximativ 1500 $ / kWh în 2007.  Deoarece prețul nichelului este în creștere, reducerea potențială a costurilor de baterii NiMH nu este promițătoare. Bateriile Li-ion au de două ori densitatea de energie a bateriilor NiMH, la prețul de 750 până la 1000 USD / kWh. 

    D.  Bateriile Nichel-Zinc

    Bateriile cu nichel-zinc au o densitate mare de energie, sunt realizate din materiale cu costuri reduse și sunt prietenoase cu mediul ecologic. Temperatura de funcționare a bateriilor Ni-Zn variază de la -10 grade C la 50 grade C, ceea ce înseamnă că pot să fie folosite în condiții mai aspre. Cu toate acestea, ele suferă de cicluri de viață reduse din cauza creșterii rapide a dendritelor, care împiedică dezvoltarea bateriilor Ni-Zn în vehicule.

    E.  Bateriile Nichel - Cadmiu

    Bateriile cu nichel-cadmiu au o durată lungă de viață și pot fi complet descărcate fără  deteriorare. Energia specifică a bateriilor Ni-Cd este în jur de 55 Wh / kg. Aceste baterii pot fi reciclate, dar cadmiul este un metal greu care ar putea cauza daune mediului dacă nu este aruncat în mod corespunzător. Un dezavantaj al bateriilor Ni-Cd este costul. De obicei costa mai mult de $ 20 000 pentru a instala aceste baterii în vehicule. 


Ultracondensatorii

Ultracondensatorii stochează energia prin separarea fizică a sarcinilor pozitive de cele negative. Sarcinile sunt stocate pe două plăci paralele despărțite de un izolator. Deoarece nu există variații chimice pe electrozi, UC au o durată de viață lungă, dar o densitate a energiei scăzută . Figura 5 prezintă structura unui ultracondensator.

 Potențialul aplicat pe electrodul pozitiv atrage ionii negativi ai electrolitului, în timp ce potențialul pe electrodul negativ atrage ionii pozitivi. Densitatea de putere a UC este considerabil mai mare decât cea a bateriei; acest lucru se datorează faptului că sarcinile sunt depozitate fizic pe electrozi. Rezistența internă scăzută oferă ultracondensatorului o eficiență ridicată, dar poate duce la o descărcare  mare a curenților dacă UC este încărcat necorespunzător.
Ultracondensatorii pot fi utilizațica dispozitive ajutătoare de stocare a energiei într-un vehicul electric. În condusul urban, există multe opriri și porniri, iar puterea totală necesară este relativ scăzută. Ultracondensatorii sunt foarte adecvați pentru captarea energiei electrice de la sistemul de frânare regenerativă și livrarea rapidă a energiei pentru accelerare, toate acestea datorită vitezei lor rapide de încărcare și descărcare. 
 Bateriile au densitate mare de energie, în timp ce UC au densitate mare de putere. Durata lungă de viață și mentenanța redusă duce la economii de costuri. În cadrul vehiculelor electrice hibride, atât bateriile, cât și UC pot fi combinate pentru a maximiza beneficiile ambelor componente. Se estimează că peste 30 000 UC-uri sunt în lucru în unitățile hibride, livrând peste 75 000 000 Farazi în urma condusului pe modul electric și a obținerii energiei din frânarea regenerativă.

Încărcarea bateriilor

    Încărcarea acumulatorilor constituie o parte esențială în ceea ce privește vehiculele electrice. Pentru a realiza acest proces, conform articolului Încărcarea unui vehicul electric [4], există următoarele soluții:
încărcarea la priză : autovehiculul electric se poate încărca direct de la rețea(230V). La fel ca la smartphone, trebuie să se introducă cablul în priză şi celălalt capăt în doza pentru încărcare a automobilului. Mașina se va încuia cu cheia şi va începe încărcarea. Pentru a se putea realiza încărcarea este nevoie de un cablu special oferit de fiecare producător. Aceasta este opțiunea cea mai puțin costisitoare, dar care necesită și cel mai mult timp pentru a încărca bateria mașinii.    
încărcarea de la staţia de alimentare în curent alternativ :  pentru staţiile publice de alimentare în curent alternativ există un cablu special, care se poate comanda separat, odată cu maşina. În acest caz: încuind maşina se va bloca şi cablul de alimentare, astfel încât nimeni să nu poată întrerupe alimentarea. Acestea încarcă bateriile în circa  doua ore, fiind mult mai rapide decât încărcarea la priză, deoarece introduc în baterii tensiuni și cureți mai mari.Caracteristici:
Putere de încărcare între: 3,7 – 22 kW.
Tensiune de funcționare: 230V – 400V.
Putere maximă de funcționare: 10A – 32A, la alegerea utilizatorului.
            
încărcarea de la staţia de alimentare în curent continuu : turbo-alimentare:  aşanumitele staţii de alimentare CSS (abrevierea pentru: Combined Charging System - sistem combinat de încărcare) permit alimentarea în curent continuu. Deoarece curentul continuu permite intensităţi mai ridicate ale curentului, acumulatorul va fi încărcat mult mai rapid. Nu toate vehiculele electrice pot fi încărcate la astfel de stații de încărcare rapidă. Cele mai multe vehicule hibride plug-in nu au această capacitate de încărcare, iar unele vehicule electrice integral nu pot fi încărcate cu un încărcător rapid de curent continuu. Mitsubishi "i" și Nissan Leaf sunt două exemple de mașini electrice care pot fi încărcate astfel. Caracteristici:
Putere: 50 KW.
Tensiune de funcționare: 400V.
Putere maximă de funcționare: 128A, la alegerea utilizatorului.

Battery Management System (BMS)
    Conform articolului Battery-Management System (BMS) and SOC Development for Electrical Vehicles unul dintre parametrii importanți care sunt necesari pentru a asigura încărcarea și descărcarea în siguranță este dat capacitatea actuală a bateriei, exprimată în funcție de capacitatea nominală(State-of-charge (SOC)). Estimarea exactă a SOC previne deteriorarea bateriei sau îmbătrânirea rapidă, evitând supraîncărcarea și supradescărcarea. Evaluarea convențională SOC utilizând metoda de numărare Coulomb întâmpină adesea erori, ceea ce duce la o estimare inexactă. În plus, reacția chimică care are loc în timpul încărcării și descărcării provoacă creșterea temperaturii, ceea ce influențează estimarea SOC. Prin urmare, sunt necesari algoritmi exacți pentru estimarea SOC. În industria automotive, bateriile utilizate sunt în mare parte de tehnologie litiu-ion, creându-se un ansamblu de baterii conectate în serie-paralel și paralel-serie pentru a oferi curentul și tensiunea dorite.

“Battery Management System” este o entitate separată formată din elemente hardware și software și este mai degrabă conectată la partea de încărcare/descărcare a bateriilor,  decât integrată în acestea. “Battery Management System” (BMS) constă dintr-un număr de dispozitive de detectare pentru monitorizarea parametrilor bateriei care vor fi utilizați în algoritmul de estimare SOC.

Blocul de măsurare  surprinde tensiunile individuale ale celulelor, curentul acumulatorului și temperatura bateriei în diferite puncte ale ansamblului bateriilor, precum și temperatura ambientală și le transformă în valori digitale. Toate aceste date sunt apoi utilizate pentru a estima starea bateriei în etapele ulterioare. Blocul de măsurare a tensiunii celulelor care este prezentat în figura 7 include o matrice relee optoelectrice. În fiecare perioadă de eșantionare, numai una dintre tensiunile celulare este conectată la interfața analogică-digitală (A-D) a unității centrale de procesare. Avantajul măsurării tensiunilor individuale ale celulelor justifică costul suplimentar al hardware-ului, deoarece permite balansarea celulelor și protecția la supraîncărcare la nivelul celulelor.
    
    După determinarea SOC(State-Of-Charge) și SOH(State-Of-Health), BMS trebuie să deducă în orice moment sarcina maximă și curentul de descărcare, în conformitate cu un algoritm. Ieșirea acestui bloc este furnizată la ECU-ul vehiculului astfel încât bateria să nu fie supusă încărcării sau descărcării peste limitele specificate.

    Funcția blocului de estimare a capacității  este de a trimite informații către ECU despre nivelul actual de siguranță al încărcării și descărcării curentului bateriei. Aceste informații sunt foarte importante pentru funcționarea în siguranță a bateriei și împiedică încălcarea accidentală a specificațiilor bateriei.

odul prin care se determină capacitatea maximă de încărcare și descărcare pe baza intrărilor, care descriu relația dintre curenții de încărcare admiși și curenții de descărcare, exprimate în termeni de curent maxim de încărcare / descărcare pentru diferite valori ale diferiților parametri ai bateriei. Factorii de încărcare / descărcare sunt curenții de încărcare / descărcare permiși, exprimate în curenți maximi de încărcare și de descărcare, respectiv. (Factorul de încărcare reprezintă procentajul curentului maxim de încărcare.)

 BMS va limita curentul de încărcare în funcție de o funcție care depinde de temperatură, SOC și tensiunea celulei. De exemplu, curentul de încărcare trebuie să fie redus dacă temperatura este în intervalul de 30 ° C-40 ° C. În mod similar, curentul maxim cu care bateria poate fi încărcată este o funcție a SOC și a tensiunii celulare.

    Diagrama de limitare a blocului de gestionare termică din BMS estimează temperatura bateriei și este prezentată în figura 11. Estimarea temperaturii se bazează pe o metodă foarte simplă de evaluare a temperaturii. Gestionarea termică se referă la monitorizarea și controlul temperaturii bateriei astfel încât bateria să nu fie afectată de temperatură foarte ridicată sau foarte scăzută. Ieșirile acestui bloc controlează un ventilator și un încălzitor electric, care încearcă să mențină temperatura bateriei în intervalul optim.

    Blocul de gestionare termică citește temperaturile ambientale și ale bateriilor, inițiază funcționarea de răcire sau încălzire și trimite un semnal de urgență la ECU în cazul unei creșteri anormale a temperaturii.


 Stadiul actual pe piață

Așadar, în cele menționate mai sus, observăm ca BMS-ul nu poate lipsi atunci când vine vorba despre vehiculele electrice. Prin urmare, toți producătorii de vehicule electrice folosesc un astfel de sistem.
    
Tesla
    Cel mai cunoscut producător de vehicule electrice este Tesla, aceștia oferind și una dintre cele mai bune autonomii. Celulele sunt monitorizate cu atenție la un nivel destul de detaliat. Tesla controlează cu atenție încărcarea și ia în considerare și controlează temperaturile acumulatorului prin încălzire și răcire activă pentru a obține o viață și o performanță optimă. Este o parte semnificativă a avantajului competitiv al Teslei. Mașinile Tesla care au acumulat sute de mii de kilometri au aproximativ 90% sau mai mult din capacitatea lor originala. Temerile că bateriile vor trebui înlocuite înainte ca mașina să fie uzată sunt, așadar, eliminate. Toate acestea sunt datorate unui BMS foarte eficient.


Modelul S de la Tesla a fost premiat cu titlul "mașina anului 2012" în Statele Unite, fiind primul model 100% electric din istorie care primește aceasta titulatură Tesla S se poate încărca în 45 de minute la stațiile speciale, dar se poate alimenta și la surse 110, 220 sau 320 V, fiind necesare în acest caz 4 ore pentru un "plin".
    Tesla Model S dispune de trei versiuni: un model standard care se poate parcurge 370 km pe o singură încărcare, un model cu tracțiune integrală ce rulează 380 km pe o singură încărcare și un model care atinge 465 km pe o singură încărcare. 
    Conform articolului prezentat ca referință [7], mașinile Tesla au 3 nivele de încărcare(Fig 12):
Nivelul 1 (120 volți) de încărcare;
Nivelul 2 (240 volți) de încărcare;
Nivelul 3 (480 volți) Supraîncărcare sau încărcare rapidă cu curent continuu;


Utilizatorii mașinilor Tesla au posibilitatea de a vedea în timp real informații despre starea de încărcare a bateriilor chiar pe telefonul mobil, grație unul sistem de monitorizare si gestionare a energiei foarte bine conceput

Observăm că din ce în ce mai mulți producători de mașini se orientează către mașinile electrice. De exemplu, marca Volkswagen deja produce vehicule 100% electrice, cum ar fi VW e-Golf , sau e-Up.


Aceștia utilizează tehnologia litiu-ion consacrată.  Volkswagen e-Golf (Fig.14.1) are o autonomie care poate începe de la 190 de km și poate ajunge până la 300 de km, conform informațiilor de pe site-ul oficial [9]. Această mașină se poate încărca în mai multe feluri, iar pentru fiecare dintre acestea este o durată de timp aferentă:
încărcarea de la priză : 17 h 00 min
încărcarea de la staţia de alimentare în curent alternativ : 5 h 20 min
încărcarea de la staţia de alimentare în curent continuu : 45 min (80%)
    Datorită dispozitivului Combined Charging System (CCS), e-Golf are nevoie doar de o priză de alimentare pentru încărcarea cu două ştechere diferite: curent alternativ prin cablul de alimentare pentru priza uzuală, precum şi încărcarea rapidă de la o sursă de curent continuu la staţiile publice de alimentare CCS. 
    Nivelul de încărcare şi autonomia sunt afişate clar în toate automobilele electrice Volkswagen, chiar în mai multe locuri. La e-Golf (consum energie electrică în kWh/100 km: mixt 12,7; emisii de CO₂ mixt, g/km: 0; Clasa de eficienţă: A+*), afişarea se face, de exemplu, pe panoul de instrumente şi pe ecranul sistemului de navigaţie, respectiv maps + more. Cu aplicaţia Car-Net e-Remote, puteţi urmări toate informaţiile importante, chiar şi atunci când nu vă aflaţi în maşină.
șadar, observăm că și Volkswagen utilizează un sistem foarte precis de monitorizare a bateriilor cu afișaj atât în mașină, cât și pe telefonul mobil.

Nissan
    
Cei de la Nissan reprezintă încă un exemplu care reușește să aibă cifre de vânzări impresionante la capitolul mașini 100% electrice. Modelul lor de succes se numește Nissan Leaf (Fig,16)și este propulsat de un motor electric de 110 kW.

Conform site-ului oficial [10], Nissan LEAF utilizează  două tipuri de baterii. Una este o baterie plumb – acid de 12V care este de același tip cu bateria cu care sunt dotate vehiculele alimentate cu motoare cu combustie internă și care alimentează dispozitivele de joasă tensiune ale mașinii. Celălalt, este bateria litiu-ion (cu înaltă tensiune) (Li-ion) care furnizează energia electrică pentru motorul de tracțiune care propulsează autovehiculul. Bateria Li-ion este încastrată în oțel și este montată sub podeaua vehiculului.
Vehiculul trebuie conectat la un încărcător electric pentru a reîncărca bateria Li-ion. În plus, bateria Li-ion se mai poate încărca prin transformarea forței motrice în electricitate în timp ce vehiculul este decelerat sau în timp ce este condus în pantă. Aceasta se numește "încărcare regenerativă".
Bateria Li-ion are un voltaj de 360V și este compusă din 48 de module individuale, ceea ce înseamnă că în cazul unei defecțiuni se va interveni doar pe modulul defect, Bateria are dimensiuni impresionante – 1547 x 1188 x 264 mm – și o greutate cuprinsă între 273 și 296 kg în funcție de tip.
    De asemenea, această mașină se poate încărca în mai multe feluri, iar pentru fiecare dintre acestea este o durată de timp aferentă:
încărcarea de la priză : 16 h;
încărcarea de la staţia de alimentare în curent alternativ : 7,5 h;
încărcarea de la staţia de alimentare în curent continuu : 40 min (80%);

    Producătorii de la Nissan oferă un sistem de monitorizare a energiei electrice din baterii foarte precis. Acesta poate afișa informații atât pe consola centrală a mașinii, cât și pe telefonul mobil, prin intermediul unei aplicații dedicate.
    
    Așadar, se remarcă faptul ca fiecare producător de vehicule electrice pune un deosebit accent pe partea de monitorizare a bateriilor. Se observă ca fiecare vehicul electric modern oferă informații despre baterii atât local, în interiorul mașinii, cât și de la distanță, pe telefonul mobil.
Fiecare baterie va avea o anumită tensiune în funcție de gradul de utilizare al acesteia. Cu ajutorul senzorilor vom cunoaște tensiunea pe fiecare baterie, urmând ca în funcție de tensiunea lor, fie că ne referim la tensiunea din timpul încărcării, fie că ne referim la tensiunea din timpul descărcării, să adaptăm sistemul în funcție de informațiile corelate, toate acestea în timp real.

Astfel, câte un senzor de tensiune cu izolare galvanică va citi date de la fiecare baterie și va transmite informația la micrcontroller, unde urmează să fie prelucrată (semnalul analogic obținut de la senzor va fi convertit într-un semnal digital cu ajutorul ADC-ului). 

De asemenea, conform studiului critic prezentat în capitolul 1, am identificat ca prin  legarea bateriilor în serie se produce o tensiune mai mare, dar la aceeași intensitate a curentului. Prin urmare, este nevoie de un singur senzor de curent care va fi montat la ieșirea celor 8 baterii înseriate, urmând să citească intensitatea curentului.

În ceea ce privește senzorii de temperatură, aceștia vor fi implementați într-o zonă în care se poate măsura cât mai sigur temperatura bateriilor și vor fi 8 la număr; câte unul pentru fiecare baterie. 

Prin îmbinarea părții hardware cu partea software se vor prelucra toate aceste informații obținute de la senzori. În funcție de aceste prelucrări și de anumiți parametri presetați, se va realiza partea de management a energiei.

