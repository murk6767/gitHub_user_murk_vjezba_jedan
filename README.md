# gitHub_user_murk_vje-ba_jedan
upoznavanje s osnovama gita
1. Što je Visual Studio Code i za što se najčešće koristi?
1- VS Code je besplatan i otvoreni uređivač izvornog koda. Najčešće se koristi za web razvoj, uključujući rad s JavaScriptom, TypeScriptom, HTML i CSS, te za razvoj lakših aplikacija i skripti.

2. Kako se zove panel u kojem vidiš sve datoteke i mape svog projekta?
2- Explorer.

3. Kako možeš instalirati ekstenzije u VS Codeu i čemu one služe?
3- Ekstenzije u VS Code-u su dodaci koji proširuju funkcionalnost uređivača koda. Za instalaciju ekstenzija u VS Codeu, prvo otvorite uređivač koda i pristupite prikazu ekstenzija klikom na ikonicu „Extensions“ na lijevoj bočnoj traci ili korištenjem prečaca „Ctrl+Shift+X“ (Windows/Linux) ili „Cmd+Shift+X“ (Mac). U traci za pretraživanje unesite naziv ekstenzije koju želite instalirati. Nakon što pronađete željenu ekstenziju, kliknite gumb „Instaliraj“.

4. Kako otvoriti postojeći projekt ili mapu u VS Code-u?
4- Da biste otvorili postojeći projekt ili mapu u VS Codeu, kliknite na Explorer na bočnoj traci za navigaciju i odaberite opciju "Otvori mapu".

5. Što se sve može raditi u Exploreru?
5- U VS Codeu, Explorer je dio navigacijskog sidebara koji omogućuje upravljanje datotekama i mapama u trenutnoj radnoj mapi. U Exploreru možete otvoriti i pregledavati sve datoteke i mape koje su dio projekta, a koje su učitane u radnu mapu.

6. Kako možeš brzo pronaći određenu datoteku u projektu?
6- Za brzo pronađenje određene datoteke u projektu u VS Codeu možete koristiti funkciju pretraživanja CTRL + P.

7. Kako možeš istovremeno gledati dvije različite datoteke u editoru?
7- U VS Codeu možete istovremeno gledati dvije različite datoteke koristeći CTRL + \

8. Kako pokrećeš automatsko formatiranje koda u VS Code-u?
8- Da biste omogućili automatsko formatiranje koda u VS Code-u prilikom spremanja datoteke, potrebno je prvo instalirati alat za formatiranje, poput Prettier-a, koji je jedan od najpopularnijih dodataka za ovu svrhu. Nakon instalacije, otvorite postavke (Settings) i u polju za pretraživanje upišite „format on save“. Uključite opciju „Editor: Format On Save“ tako da je vrijednost postavljena na true. Ova postavka osigurava da se kod automatski formatira svaki put kada spremite promjene u datoteci.

9. Što je version control i zašto se koristi?
9- Kontrola verzija (engl. version control) je sustav koji prati promjene u datotekama, posebno u izvornom kodu softvera, tijekom vremena. On omogućuje da se svaka promjena zabilježi, uključujući tko ju je napravio, kada je napravljena i što je promijenjeno. 

10. Kako se u VS Code-u otvara panel za Git (Source Control)?
10- Panel za Git (Source Control) u VS Code-u može se otvoriti na više načina. Najčešći način je klikom na ikonu Source Control u lijevom gornjem dijelu sučelja, koja izgleda kao lista papira s strelicom naviše.

11. Što znače commit, push, pull?
11- U VS Code-u commit znači snimanje promjena koje ste napravili u lokalnom repozitoriju. Push znači slanje lokalnih commit-a na udaljeni repozitorijum, kao što je GitHub, Bitbucket ili druga platforma. Pull znači preuzimanje promjena s udaljenog repozitorija na vaš lokalni računalo.

12. Čemu služi commit poruka i kako treba izgledati?
12- Commit poruka služi za kratki opis promjena koje ste učinili u kodu prije nego što ih poslužite u lokalnom repozitoriju Git-a. Ova poruka trebala bi biti jasna, koncizna i opisna, a najbolje je da bude kratka, obično jedan red, i da objasni što je promijenjeno i zašto.

13. Kako možeš vidjeti koje si promjene napravio u pojedinoj datoteci?
13- U VS Code, promjene koje ste napravili u pojedinoj datoteci mogu se vidjeti kroz ikonicu za kontrolu izvora na lijevoj strani aktivne trake, koja uvijek prikazuje broj promjena u vašem repozitoriju.

14. Kreiraš novu datoteku. Koji su koraci da se promjena pošalje na GitHub?
14- Slijedite ove korake:
-Otvorite projekt u VS Code koji je povezan s lokalnim Git spremištem.
-U pregledniku datoteka u VS Codeu, kliknite desnim tipkom miša u direktorij u kojem želite stvoriti novu datoteku i odaberite opciju "New File" ili "Nova datoteka".
-Unesite ime nove datoteke i pritisnite Enter.
-Ukucajte sadržaj datoteke.
-Kliknite na ikonu "Source Control" (kontrola izvora) u lijevom gornjem dijelu VS Code-a.
-U sekciji "Changes", vidjet ćete novu datoteku označenu kao "Untracked". Kliknite na plus (+) uz njezin naziv da biste je dodali u predaju.
-U polje za komentar u gornjem dijelu "Source Control" unesite opis promjene (npr. "Dodana nova datoteka za funkcionalnost X").
-Kliknite na ikonu "Commit" (potvrdi) ili pritisnite Ctrl+Enter (Cmd+Enter na Macu) da biste potvrdili promjene lokalno.
-Kliknite na ikonu "Push" (gurni) u gornjem dijelu "Source Control" da biste poslali promjene na udaljeno spremište na GitHubu.

15. Kako se vraćaš na stariju verziju datoteke ako si pogriješio?
15- Ako ste pogriješili u VS Codeu i želite se vratiti na stariju verziju datoteke, možete koristiti nekoliko pristupa. Jedan od načina je korištenje funkcije Git: Open Changes, koja omogućuje prebacivanje između trenutnog prikaza promjena i izvorne datoteke.

16. Na koji način možeš provjeriti status projekta i koje datoteke su izmijenjene?
16- Status projekta i izmijenjene datoteke u VS Codeu mogu se provjeriti kroz integrirani sustav upravljanja izvorom (Source Control Management – SCM) koji je ugrađen u editor.