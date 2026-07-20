# Zásady ochrany osobných údajov – Nearla

> **DRAFT — pred verejným spustením appky musí prejsť kontrolou právnika/DPO.**
> Tento text pripravil AI asistent ako poctivý štartovací bod (presný popis
> toho, čo appka aktuálne reálne robí s údajmi), nie je to finálny právny
> dokument. Najmä sekcia "Kto sme" a časť o medzinárodnom prenose údajov
> (Firebase/Google, USA) potrebujú overenie právnikom pred App Store
> submitom, presne ako je zapísané v CLAUDE.md appky ("Známa GDPR nuansa").

Posledná aktualizácia: [DOPLNIŤ DÁTUM]

## 1. Kto sme

Prevádzkovateľom appky Nearla je [DOPLNIŤ: meno/názov spoločnosti, adresa,
IČO — v čase písania tohto draftu appka beží pod osobným vývojárskym účtom,
nie pod založenou s.r.o.].

Kontakt vo veciach ochrany osobných údajov: [DOPLNIŤ EMAIL]

## 2. Aké údaje spracúvame

- **Profilové údaje**: meno, vek, pohlavie, bio text, záujmy, fotky, ktoré
  nahráte do profilu.
- **Poloha**: appka nikdy neukladá ani neprenáša vašu presnú polohu.
  Pri zapnutí zdieľania polohy ("Boli ste tu" alebo "Live") appka zistí
  vašu aktuálnu polohu na zariadení a okamžite ju rozmaže na kruh s
  polomerom približne 300 m — presná súradnica sa nikdy neuloží ani
  neprenesie. V móde "Vypnuté" sa poloha vôbec nezisťuje.
- **Autentifikácia**: prihlásenie cez Sign in with Apple (Apple ID token),
  appka nedostáva vaše heslo Apple účtu.
- **Správy a interakcie**: chatové správy medzi zhodnutými používateľmi,
  swipe akcie (páči sa mi/nepáči sa mi/mávnutie), zoznam zhôd.
- **Bezpečnostné údaje**: nahlásenia iných používateľov, zoznam
  zablokovaných používateľov.
- **Podnikový profil** (voliteľné): názov podniku, kategória, adresa,
  otváracie hodiny, ponuky — ak si appku nastavíte aj ako podnik.

## 3. Prečo tieto údaje spracúvame

Aby appka mohla plniť svoj základný účel: prepájať vás s ľuďmi a podnikmi
vo vašej fyzickej blízkosti, umožniť vzájomné zhody a komunikáciu, a
udržiavať appku bezpečnú (nahlasovanie, blokovanie).

## 4. Právny základ spracúvania

Spracúvanie je založené na vašom súhlase (registrácia a používanie
appky) a na plnení zmluvy (poskytovanie funkcií appky, ktoré ste si
vyžiadali).

## 5. Komu údaje sprístupňujeme (tretie strany)

- **Firebase / Google Cloud** (Firestore, Authentication, Storage) —
  hosting v EU regióne (europe-west). Firebase/Google je americká
  materská spoločnosť; aj pri hostingu v EU regióne preto môže ísť o
  otázku prístupu na základe amerického CLOUD Act. Toto sa rieši
  štandardnou GDPR zmluvou o spracúvaní (DPA) s Google, plné vyriešenie
  cezhraničného aspektu je predmetom právnej konzultácie pred verejným
  spustením appky.
- **Apple** — v rozsahu Sign in with Apple (autentifikácia).

Vaše údaje sa nikdy nepredávajú tretím stranám na marketingové účely.

## 6. Ako dlho údaje uchovávame

Kým máte účet aktívny. **Appka k dátumu tejto verzie zásad NEMÁ funkciu na
samoobslužné zmazanie účtu ani dát priamo v appke.** Ak chcete svoje účet
alebo údaje zmazať, kontaktujte nás na [DOPLNIŤ EMAIL] a zmažeme ich
manuálne. Samoobslužné zmazanie účtu je plánovaná, zatiaľ neimplementovaná
funkcia.

## 7. Vaše práva

Máte právo na prístup k svojim údajom, ich opravu, vymazanie, obmedzenie
spracúvania, prenositeľnosť a právo namietať proti spracúvaniu. Na
uplatnenie týchto práv nás kontaktujte na [DOPLNIŤ EMAIL].

## 8. Bezpečnosť údajov

Vaša presná poloha sa nikdy neukladá ani nezobrazuje iným používateľom —
appka pracuje výhradne s rozmazanou polohou (kruh neistoty). Prístup k
údajom vo Firestore je obmedzený bezpečnostnými pravidlami na strane
servera. Blokovanie iného používateľa je obojstranné a okamžité.

## 9. Zmeny týchto zásad

Tieto zásady môžeme priebežne aktualizovať. O významných zmenách vás
budeme informovať v appke.

## 10. Kontakt

Otázky k týmto zásadám alebo k spracúvaniu vašich údajov posielajte na:
[DOPLNIŤ EMAIL]
