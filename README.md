Polityka prywatności – GigChronicle

Data wejścia w życie: 28 marca 2026

Aplikacja GigChronicle szanuje prywatność użytkowników. Niniejsza polityka prywatności wyjaśnia, jakie dane są przetwarzane, w jaki sposób są przechowywane i wykorzystywane.

1. Zakres przetwarzanych danych

Aplikacja nie zbiera ani nie przesyła danych osobowych użytkowników. Wszystkie dane wprowadzane przez użytkownika są przetwarzane i przechowywane wyłącznie lokalnie na urządzeniu użytkownika. Twórca aplikacji nie ma dostępu do tych danych.

Dane przechowywane lokalnie obejmują:

• Odliczania — nazwa artysty/wydarzenia, miejsce, miasto, kraj, festiwal, data, godzina, link, notatki, ustawienia powiadomień i alarmu, ustawienia powtarzalności, ustawienia ekranu blokady.
• Wydarzenia (Historia) — nazwa artysty/wydarzenia, miejsce, miasto, kraj, festiwal, data, godzina, link, notatki, oznaczenie jako ulubione.
• Zdjęcia i filmy — pliki multimedialne dodane przez użytkownika do galerii odliczań i wydarzeń, przechowywane w katalogu wewnętrznym aplikacji. Miniatury filmów są generowane i przechowywane lokalnie.
• Okładki — zdjęcie lub kolor ustawiony jako tło karty wydarzenia/odliczania.
• Ustawienia — język, motyw kolorystyczny, kolor akcentu, format daty, nawigacja przesuwaniem, strzałki nawigacyjne, dźwięk alarmu, układ statystyk, widok listy/kafelków, flagi jednorazowych wskazówek.

2. Przechowywanie danych

Dane są przechowywane w trzech lokalizacjach, wszystkie wyłącznie na urządzeniu użytkownika:

• Baza danych Hive — odliczania, wydarzenia i ustawienia, w katalogu wewnętrznym aplikacji.
• Pliki multimedialne — zdjęcia i filmy w podkatalogu media/ oraz miniatury w podkatalogu thumbs/ katalogu wewnętrznego aplikacji.
• SharedPreferences — dane widgetów ekranu głównego (powiązanie widgetu z odliczaniem oraz dane wyświetlane na widgecie).

Twórca aplikacji nie ma dostępu do żadnych z powyższych danych. Dane są przetwarzane wyłącznie na urządzeniu użytkownika.

3. Brak przesyłania danych

Aplikacja sama nie przesyła żadnych danych do serwerów zewnętrznych. Nie nawiązuje żadnych połączeń sieciowych. Nie korzysta z usług analitycznych, reklamowych, śledzących ani żadnych usług chmurowych. Wyjątkiem jest automatyczna kopia zapasowa systemu Android opisana w punkcie 8.

4. Uprawnienia

Aplikacja może wymagać następujących uprawnień systemowych:

• Powiadomienia (POST_NOTIFICATIONS) — wyświetlanie przypomnień o nadchodzących wydarzeniach. Powiadomienia działają wyłącznie lokalnie.
• Dokładne alarmy (SCHEDULE_EXACT_ALARM, USE_EXACT_ALARM) — precyzyjne planowanie przypomnień i alarmów dźwiękowych.
• Wibracje (VIBRATE) — wibracje towarzyszące alarmom dźwiękowym.
• Wyświetlanie na pełnym ekranie (USE_FULL_SCREEN_INTENT) — wyświetlanie alarmu na pełnym ekranie.
• Restart automatyczny (RECEIVE_BOOT_COMPLETED) — przywracanie zaplanowanych powiadomień i alarmów po ponownym uruchomieniu lub aktualizacji telefonu.
• Aparat (CAMERA) — robienie zdjęć oraz nagrywanie filmów (maks. 30 sekund) bezpośrednio z poziomu aplikacji.
• Dostęp do zdjęć (READ_MEDIA_IMAGES) — wybieranie zdjęć i filmów z galerii telefonu w celu dodania ich do galerii wydarzenia/odliczania. Oryginały pozostają w galerii telefonu; do aplikacji kopiowana jest kopia.
• Zapis do galerii telefonu — użytkownik może ręcznie zapisać zdjęcie lub film z galerii aplikacji do galerii telefonu. Wymaga to jednorazowej zgody na dostęp do galerii.
• Pamięć urządzenia (READ/WRITE_EXTERNAL_STORAGE na starszych wersjach Androida) — importowanie i eksportowanie plików (CSV, XLSX, ZIP).
• Dostęp do dzwonków systemowych — wybór dźwięku alarmu z listy dzwonków zainstalowanych na telefonie.

Żadne z powyższych uprawnień nie powoduje przesyłania danych poza urządzenie.

5. Eksport i udostępnianie danych

Użytkownik może dobrowolnie eksportować dane z aplikacji. Eksport jest zawsze inicjowany przez użytkownika i nigdy nie następuje automatycznie:

• Eksport do CSV/XLSX — wydarzenia, odliczania lub statystyki mogą być eksportowane do plików CSV lub XLSX. Pliki są zapisywane w wybranej przez użytkownika lokalizacji na urządzeniu.
• Pełna kopia zapasowa (ZIP) — użytkownik może utworzyć pełną kopię zapasową zawierającą wszystkie wydarzenia, odliczania, ustawienia, zdjęcia i filmy. Kopia jest zapisywana jako plik ZIP w wybranej lokalizacji.
• Przywracanie kopii zapasowej — użytkownik może przywrócić kopię zapasową z pliku ZIP. Przywrócenie zastępuje wszystkie istniejące dane w aplikacji.
• Udostępnianie zdjęć i filmów — użytkownik może udostępnić pojedyncze zdjęcie lub film za pomocą systemowego arkusza udostępniania (np. wysłać przez komunikator lub e-mail). Udostępnianie jest inicjowane wyłącznie przez użytkownika.
• Kopiowanie linku — użytkownik może skopiować link do schowka systemowego poprzez długie przytrzymanie linku w widoku szczegółów.

6. Otwieranie linków zewnętrznych

Jeśli użytkownik doda link do wydarzenia lub odliczania, może go otworzyć klikając na niego. Link jest otwierany w domyślnej przeglądarce systemowej. Aplikacja obsługuje wyłącznie linki HTTP i HTTPS. Aplikacja nie śledzi ani nie rejestruje otwieranych linków.

7. Widgety ekranu głównego

Aplikacja umożliwia dodanie widgetów na ekran główny telefonu (w rozmiarach 1x1, 2x1, 3x1 i 2x2). Widgety wyświetlają odliczanie do wybranego wydarzenia. Dane widgetów (nazwa wydarzenia, liczba dni) są przechowywane lokalnie w SharedPreferences na urządzeniu.

8. Automatyczna kopia zapasowa systemu Android

System Android może automatycznie tworzyć kopię zapasową danych aplikacji na koncie Google Drive użytkownika (funkcja Auto Backup). Jest to funkcja systemu operacyjnego, niezależna od aplikacji — aplikacja sama nie inicjuje tego procesu. Użytkownik może wyłączyć tę funkcję w ustawieniach systemu Android (Ustawienia > System > Kopia zapasowa). Dane przechowywane w kopii zapasowej Google Drive podlegają polityce prywatności firmy Google.

9. Usługi zewnętrzne

Aplikacja nie korzysta z żadnych usług zewnętrznych. W szczególności:

• Brak analityki i śledzenia (brak Google Analytics, Firebase Analytics itp.).
• Brak reklam.
• Brak usług chmurowych (brak Firebase, brak synchronizacji).
• Brak raportowania błędów do zewnętrznych serwisów.
• Brak logowania przez konta zewnętrzne.

10. Biblioteki zewnętrzne

Aplikacja korzysta z bibliotek open-source wyłącznie do obsługi funkcji lokalnych (m.in. baza danych, powiadomienia, widgety, obsługa zdjęć i filmów, eksport plików). Według wiedzy twórcy aplikacji żadna z używanych bibliotek nie zbiera ani nie przesyła danych użytkownika.

11. Bezpieczeństwo danych

Dane są przechowywane lokalnie i pozostają pod pełną kontrolą użytkownika. Użytkownik może w każdej chwili:

• Wyeksportować swoje dane (CSV, XLSX lub pełna kopia zapasowa ZIP).
• Usunąć pojedyncze wydarzenia, odliczania, zdjęcia lub filmy.
• Usunąć wszystkie dane poprzez wyczyszczenie pamięci aplikacji w ustawieniach systemu Android.
• Odinstalować aplikację, co usunie wszystkie dane lokalne.

Aplikacja nie stosuje szyfrowania danych na urządzeniu ponad standardowe mechanizmy ochrony systemu Android.

12. Treści użytkownika

Aplikacja umożliwia użytkownikom dodawanie własnych treści (zdjęcia, filmy, notatki, linki). Twórca aplikacji nie ma dostępu do treści tworzonych przez użytkowników i nie moderuje ich. Odpowiedzialność za treści dodawane do aplikacji spoczywa na użytkowniku.

Aplikacja nie wymaga rejestracji ani podawania danych osobowych. Nie zawiera reklam, zakupów, funkcji społecznościowych ani czatu.

13. Zmiany w polityce prywatności

Polityka prywatności może być aktualizowana wraz z nowymi wersjami aplikacji. Zmiany będą dostępne w aplikacji w sekcji Ustawienia > Polityka prywatności.

14. Kontakt

W przypadku pytań prosimy o kontakt: gigchronicleapp@gmail.com

Twórca aplikacji: Szymon Dobroczyński

----------

Privacy Policy - GigChronicle

Effective date: March 28, 2026

GigChronicle respects your privacy. This Privacy Policy explains what data is processed, how it is stored, and how it is used.

1. Data Processing

The app does not collect or transmit personal data. All data entered by the user is processed and stored exclusively on the user's device. The app developer has no access to this data.

Data stored locally includes:

• Counters — artist/event name, venue, city, country, festival, date, time, link, notes, notification and alarm settings, recurring settings, lock screen settings.
• Events (History) — artist/event name, venue, city, country, festival, date, time, link, notes, favorite marking.
• Photos and videos — media files added by the user to counter and event galleries, stored in the app's internal directory. Video thumbnails are generated and stored locally.
• Covers — a photo or color set as the card background for an event/counter.
• Settings — language, color theme, accent color, date format, swipe navigation, navigation arrows, alarm sound, statistics layout, list/grid view, one-time tip flags.

2. Data Storage

Data is stored in three locations, all exclusively on the user's device:

• Hive database — counters, events, and settings, in the app's internal directory.
• Media files — photos and videos in the media/ subdirectory and thumbnails in the thumbs/ subdirectory of the app's internal directory.
• SharedPreferences — home screen widget data (widget-to-counter mapping and displayed data).

The app developer has no access to any of the above data. Data is processed exclusively on the user's device.

3. No Data Transmission

The app itself does not transmit any data to external servers. It does not make any network connections. It does not use analytics, advertising, tracking, or any cloud services. The exception is the Android system auto backup described in section 8.

4. Permissions

The app may require the following system permissions:

• Notifications (POST_NOTIFICATIONS) — displaying reminders for upcoming events. Notifications work entirely locally.
• Exact alarms (SCHEDULE_EXACT_ALARM, USE_EXACT_ALARM) — precise scheduling of reminders and sound alarms.
• Vibration (VIBRATE) — vibration accompanying sound alarms.
• Full-screen display (USE_FULL_SCREEN_INTENT) — displaying alarms in full screen.
• Auto-restart (RECEIVE_BOOT_COMPLETED) — restoring scheduled notifications and alarms after the phone restarts or the app is updated.
• Camera (CAMERA) — taking photos and recording videos (max 30 seconds) directly from the app.
• Photo access (READ_MEDIA_IMAGES) — selecting photos and videos from the phone gallery to add to an event/counter gallery. Originals remain in the phone gallery; a copy is stored in the app.
• Save to phone gallery — the user can manually save a photo or video from the app gallery to the phone gallery. This requires a one-time permission to access the gallery.
• Device storage (READ/WRITE_EXTERNAL_STORAGE on older Android versions) — importing and exporting files (CSV, XLSX, ZIP).
• System ringtone access — selecting an alarm sound from the system ringtone list.

None of these permissions cause any data to be transmitted outside the device.

5. Data Export and Sharing

The user may voluntarily export data from the app. Export is always initiated by the user and never happens automatically:

• CSV/XLSX export — events, counters, or statistics can be exported to CSV or XLSX files. Files are saved to a location chosen by the user.
• Full backup (ZIP) — the user can create a full backup containing all events, counters, settings, photos, and videos. The backup is saved as a ZIP file to a chosen location.
• Backup restore — the user can restore a backup from a ZIP file. Restoring replaces all existing data in the app.
• Photo and video sharing — the user can share individual photos or videos using the system share sheet (e.g., send via messenger or email). Sharing is initiated only by the user.
• Link copying — the user can copy a link to the system clipboard by long-pressing the link in the details view.

6. Opening External Links

If the user adds a link to an event or counter, they can open it by tapping it. The link is opened in the default system browser. The app only supports HTTP and HTTPS links. The app does not track or log opened links.

7. Home Screen Widgets

The app allows adding widgets to the phone's home screen (in sizes 1x1, 2x1, 3x1, and 2x2). Widgets display a countdown to a selected event. Widget data (event name, number of days) is stored locally in SharedPreferences on the device.

8. Android Auto Backup

The Android operating system may automatically back up app data to the user's Google Drive account (Auto Backup feature). This is an operating system feature independent of the app — the app itself does not initiate this process. The user can disable this in Android system settings (Settings > System > Backup). Data stored in Google Drive backup is subject to Google's Privacy Policy.

9. Third-Party Services

The app does not use any third-party services. In particular:

• No analytics or tracking (no Google Analytics, Firebase Analytics, etc.).
• No advertisements.
• No cloud services (no Firebase, no sync).
• No crash reporting to external services.
• No login via external accounts.

10. Third-Party Libraries

The app uses open-source libraries solely for local functionality (including database, notifications, widgets, photo and video handling, file export). To the best of the developer's knowledge, none of the libraries used collect or transmit user data.

11. Data Security

All data is stored locally and fully controlled by the user. The user can at any time:

• Export their data (CSV, XLSX, or full ZIP backup).
• Delete individual events, counters, photos, or videos.
• Delete all data by clearing the app's storage in Android system settings.
• Uninstall the app, which removes all local data.

The app does not apply data encryption beyond the standard security mechanisms provided by the Android operating system.

12. User Content

The app allows users to add their own content (photos, videos, notes, links). The app developer has no access to user-generated content and does not moderate it. The user is responsible for the content they add to the app.

The app does not require registration or personal information. It contains no ads, purchases, social features, or chat.

13. Changes to This Policy

This Privacy Policy may be updated with new app versions. Changes will be available in the app under Settings > Privacy Policy.

14. Contact

If you have questions please contact: gigchronicleapp@gmail.com

App developer: Szymon Dobroczyński

----------

Zásady ochrany osobních údajů – GigChronicle

Datum účinnosti: 28. března 2026

Aplikace GigChronicle respektuje vaše soukromí. Tyto zásady ochrany osobních údajů vysvětlují, jaké údaje jsou zpracovávány, jak jsou ukládány a jak jsou využívány.

1. Zpracování údajů

Aplikace neshromažďuje ani nepřenáší osobní údaje. Všechny údaje zadané uživatelem jsou zpracovávány a ukládány výhradně na zařízení uživatele. Vývojář aplikace k těmto údajům nemá přístup.

Lokálně uložené údaje zahrnují:

• Odpočty — název umělce/události, místo konání, město, země, festival, datum, čas, odkaz, poznámky, nastavení oznámení a budíku, nastavení opakování, nastavení zamykací obrazovky.
• Události (Historie) — název umělce/události, místo konání, město, země, festival, datum, čas, odkaz, poznámky, označení jako oblíbené.
• Fotografie a videa — mediální soubory přidané uživatelem do galerií odpočtů a událostí, uložené ve vnitřním adresáři aplikace. Náhledy videí jsou generovány a ukládány lokálně.
• Obálky — fotografie nebo barva nastavená jako pozadí karty události/odpočtu.
• Nastavení — jazyk, barevný motiv, barva zvýraznění, formát data, navigace přejetím, navigační šipky, zvuk budíku, rozložení statistik, zobrazení seznamu/dlaždic, příznaky jednorázových tipů.

2. Ukládání údajů

Údaje jsou uloženy na třech místech, všechna výhradně na zařízení uživatele:

• Databáze Hive — odpočty, události a nastavení ve vnitřním adresáři aplikace.
• Mediální soubory — fotografie a videa v podadresáři media/ a náhledy v podadresáři thumbs/ vnitřního adresáře aplikace.
• SharedPreferences — data widgetů domovské obrazovky (přiřazení widgetu k odpočtu a zobrazovaná data).

Vývojář aplikace nemá přístup k žádným z výše uvedených údajů. Údaje jsou zpracovávány výhradně na zařízení uživatele.

3. Žádný přenos údajů

Aplikace sama nepřenáší žádné údaje na externí servery. Nenavazuje žádná síťová spojení. Nepoužívá analytiku, reklamu, sledování ani žádné cloudové služby. Výjimkou je automatická záloha systému Android popsaná v bodě 8.

4. Oprávnění

Aplikace může vyžadovat následující systémová oprávnění:

• Oznámení (POST_NOTIFICATIONS) — zobrazování připomínek nadcházejících událostí. Oznámení fungují zcela lokálně.
• Přesné budíky (SCHEDULE_EXACT_ALARM, USE_EXACT_ALARM) — přesné plánování připomínek a zvukových budíků.
• Vibrace (VIBRATE) — vibrace doprovázející zvukové budíky.
• Zobrazení na celou obrazovku (USE_FULL_SCREEN_INTENT) — zobrazení budíku na celé obrazovce.
• Automatický restart (RECEIVE_BOOT_COMPLETED) — obnovení naplánovaných oznámení a budíků po restartu telefonu nebo aktualizaci aplikace.
• Fotoaparát (CAMERA) — pořizování fotografií a nahrávání videí (max. 30 sekund) přímo z aplikace.
• Přístup k fotografiím (READ_MEDIA_IMAGES) — výběr fotografií a videí z galerie telefonu pro přidání do galerie události/odpočtu. Originály zůstávají v galerii telefonu; do aplikace se ukládá kopie.
• Uložení do galerie telefonu — uživatel může ručně uložit fotografii nebo video z galerie aplikace do galerie telefonu. Vyžaduje jednorázové povolení přístupu ke galerii.
• Úložiště zařízení (READ/WRITE_EXTERNAL_STORAGE na starších verzích Androidu) — import a export souborů (CSV, XLSX, ZIP).
• Přístup k systémovým vyzváněcím tónům — výběr zvuku budíku ze seznamu vyzváněcích tónů nainstalovaných v telefonu.

Žádné z výše uvedených oprávnění nezpůsobuje přenos údajů mimo zařízení.

5. Export a sdílení údajů

Uživatel může dobrovolně exportovat údaje z aplikace. Export je vždy iniciován uživatelem a nikdy neprobíhá automaticky:

• Export do CSV/XLSX — události, odpočty nebo statistiky lze exportovat do souborů CSV nebo XLSX. Soubory jsou uloženy na místo zvolené uživatelem.
• Úplná záloha (ZIP) — uživatel může vytvořit úplnou zálohu obsahující všechny události, odpočty, nastavení, fotografie a videa. Záloha je uložena jako soubor ZIP na zvolené místo.
• Obnovení zálohy — uživatel může obnovit zálohu ze souboru ZIP. Obnovení nahradí všechna stávající data v aplikaci.
• Sdílení fotografií a videí — uživatel může sdílet jednotlivé fotografie nebo videa pomocí systémového sdílení (např. odeslat přes messenger nebo e-mail). Sdílení je iniciováno výhradně uživatelem.
• Kopírování odkazu — uživatel může zkopírovat odkaz do systémové schránky dlouhým podržením odkazu v zobrazení podrobností.

6. Otevírání externích odkazů

Pokud uživatel přidá odkaz k události nebo odpočtu, může jej otevřít klepnutím. Odkaz se otevře ve výchozím systémovém prohlížeči. Aplikace podporuje pouze odkazy HTTP a HTTPS. Aplikace nesleduje ani nezaznamenává otevřené odkazy.

7. Widgety domovské obrazovky

Aplikace umožňuje přidání widgetů na domovskou obrazovku telefonu (ve velikostech 1x1, 2x1, 3x1 a 2x2). Widgety zobrazují odpočet do vybrané události. Data widgetů (název události, počet dní) jsou uložena lokálně v SharedPreferences na zařízení.

8. Automatická záloha systému Android

Operační systém Android může automaticky zálohovat data aplikace na účet Google Drive uživatele (funkce Auto Backup). Jedná se o funkci operačního systému nezávislou na aplikaci — aplikace sama tento proces neiniciuje. Uživatel může tuto funkci vypnout v nastavení systému Android (Nastavení > Systém > Záloha). Údaje uložené v záloze Google Drive podléhají zásadám ochrany osobních údajů společnosti Google.

9. Služby třetích stran

Aplikace nepoužívá žádné služby třetích stran. Konkrétně:

• Žádná analytika ani sledování (žádný Google Analytics, Firebase Analytics apod.).
• Žádné reklamy.
• Žádné cloudové služby (žádný Firebase, žádná synchronizace).
• Žádné hlášení chyb externím službám.
• Žádné přihlašování přes externí účty.

10. Knihovny třetích stran

Aplikace používá open-source knihovny výhradně pro lokální funkce (včetně databáze, oznámení, widgetů, zpracování fotografií a videí, exportu souborů). Podle nejlepšího vědomí vývojáře žádná z použitých knihoven neshromažďuje ani nepřenáší údaje uživatele.

11. Zabezpečení údajů

Všechny údaje jsou uloženy lokálně a plně pod kontrolou uživatele. Uživatel může kdykoli:

• Exportovat své údaje (CSV, XLSX nebo úplná záloha ZIP).
• Smazat jednotlivé události, odpočty, fotografie nebo videa.
• Smazat všechna data vymazáním úložiště aplikace v nastavení systému Android.
• Odinstalovat aplikaci, čímž se odstraní všechna lokální data.

Aplikace nepoužívá šifrování údajů nad rámec standardních bezpečnostních mechanismů operačního systému Android.

12. Uživatelský obsah

Aplikace umožňuje uživatelům přidávat vlastní obsah (fotografie, videa, poznámky, odkazy). Vývojář aplikace nemá přístup k obsahu vytvořenému uživateli a nemoderuje jej. Odpovědnost za obsah přidaný do aplikace nese uživatel.

Aplikace nevyžaduje registraci ani poskytnutí osobních údajů. Neobsahuje reklamy, nákupy, sociální funkce ani chat.

13. Změny těchto zásad

Tyto zásady ochrany osobních údajů mohou být aktualizovány s novými verzemi aplikace. Změny budou dostupné v aplikaci v sekci Nastavení > Zásady ochrany osobních údajů.

14. Kontakt

V případě dotazů nás prosím kontaktujte na: gigchronicleapp@gmail.com

Autor aplikace: Szymon Dobroczyński

----------

Datenschutzrichtlinie – GigChronicle

Gültig ab: 28. März 2026

Die App GigChronicle respektiert Ihre Privatsphäre. Diese Datenschutzrichtlinie erklärt, welche Daten verarbeitet werden, wie sie gespeichert und wie sie verwendet werden.

1. Datenverarbeitung

Die App erhebt und überträgt keine personenbezogenen Daten. Alle vom Benutzer eingegebenen Daten werden ausschließlich auf dem Gerät des Benutzers verarbeitet und gespeichert. Der App-Entwickler hat keinen Zugriff auf diese Daten.

Lokal gespeicherte Daten umfassen:

• Countdowns — Künstler-/Veranstaltungsname, Veranstaltungsort, Stadt, Land, Festival, Datum, Uhrzeit, Link, Notizen, Benachrichtigungs- und Alarmeinstellungen, Wiederholungseinstellungen, Sperrbildschirm-Einstellungen.
• Veranstaltungen (Archiv) — Künstler-/Veranstaltungsname, Veranstaltungsort, Stadt, Land, Festival, Datum, Uhrzeit, Link, Notizen, Favoriten-Markierung.
• Fotos und Videos — Mediendateien, die vom Benutzer zu Countdown- und Veranstaltungsgalerien hinzugefügt wurden, gespeichert im internen App-Verzeichnis. Video-Vorschaubilder werden lokal generiert und gespeichert.
• Cover — Foto oder Farbe als Kartenhintergrund einer Veranstaltung/eines Countdowns.
• Einstellungen — Sprache, Farbdesign, Akzentfarbe, Datumsformat, Wisch-Navigation, Navigationspfeile, Alarmton, Statistik-Layout, Listen-/Kachelansicht, einmalige Tipp-Flags.

2. Datenspeicherung

Daten werden an drei Orten gespeichert, alle ausschließlich auf dem Gerät des Benutzers:

• Hive-Datenbank — Countdowns, Veranstaltungen und Einstellungen im internen App-Verzeichnis.
• Mediendateien — Fotos und Videos im Unterverzeichnis media/ und Vorschaubilder im Unterverzeichnis thumbs/ des internen App-Verzeichnisses.
• SharedPreferences — Daten der Startbildschirm-Widgets (Widget-zu-Countdown-Zuordnung und angezeigte Daten).

Der App-Entwickler hat keinen Zugriff auf die oben genannten Daten. Die Daten werden ausschließlich auf dem Gerät des Benutzers verarbeitet.

3. Keine Datenübertragung

Die App selbst überträgt keine Daten an externe Server. Sie stellt keine Netzwerkverbindungen her. Sie verwendet keine Analyse-, Werbe-, Tracking- oder Cloud-Dienste. Die Ausnahme ist die automatische Android-Systemsicherung, beschrieben in Abschnitt 8.

4. Berechtigungen

Die App kann folgende Systemberechtigungen erfordern:

• Benachrichtigungen (POST_NOTIFICATIONS) — Anzeige von Erinnerungen an bevorstehende Veranstaltungen. Benachrichtigungen funktionieren vollständig lokal.
• Exakte Alarme (SCHEDULE_EXACT_ALARM, USE_EXACT_ALARM) — präzise Planung von Erinnerungen und akustischen Alarmen.
• Vibration (VIBRATE) — Vibration bei akustischen Alarmen.
• Vollbildanzeige (USE_FULL_SCREEN_INTENT) — Anzeige von Alarmen im Vollbildmodus.
• Automatischer Neustart (RECEIVE_BOOT_COMPLETED) — Wiederherstellung geplanter Benachrichtigungen und Alarme nach Neustart oder App-Update.
• Kamera (CAMERA) — Aufnahme von Fotos und Videos (max. 30 Sekunden) direkt aus der App.
• Fotozugriff (READ_MEDIA_IMAGES) — Auswahl von Fotos und Videos aus der Telefon-Galerie zum Hinzufügen zu einer Veranstaltungs-/Countdown-Galerie. Originale verbleiben in der Telefon-Galerie; eine Kopie wird in der App gespeichert.
• Speichern in Telefon-Galerie — Der Benutzer kann manuell ein Foto oder Video aus der App-Galerie in die Telefon-Galerie speichern. Dies erfordert eine einmalige Zugriffsberechtigung.
• Gerätespeicher (READ/WRITE_EXTERNAL_STORAGE bei älteren Android-Versionen) — Import und Export von Dateien (CSV, XLSX, ZIP).
• Zugriff auf System-Klingeltöne — Auswahl eines Alarmtons aus der Liste der auf dem Telefon installierten Klingeltöne.

Keine dieser Berechtigungen führt zur Übertragung von Daten außerhalb des Geräts.

5. Datenexport und Teilen

Der Benutzer kann freiwillig Daten aus der App exportieren. Der Export wird immer vom Benutzer initiiert und erfolgt niemals automatisch:

• CSV/XLSX-Export — Veranstaltungen, Countdowns oder Statistiken können in CSV- oder XLSX-Dateien exportiert werden. Dateien werden an einem vom Benutzer gewählten Ort gespeichert.
• Vollständige Sicherung (ZIP) — Der Benutzer kann eine vollständige Sicherung erstellen, die alle Veranstaltungen, Countdowns, Einstellungen, Fotos und Videos enthält. Die Sicherung wird als ZIP-Datei am gewählten Ort gespeichert.
• Sicherung wiederherstellen — Der Benutzer kann eine Sicherung aus einer ZIP-Datei wiederherstellen. Die Wiederherstellung ersetzt alle vorhandenen Daten in der App.
• Foto- und Video-Teilen — Der Benutzer kann einzelne Fotos oder Videos über das System-Teilen-Menü teilen (z.B. per Messenger oder E-Mail). Das Teilen wird ausschließlich vom Benutzer initiiert.
• Link kopieren — Der Benutzer kann einen Link in die Zwischenablage kopieren, indem er den Link in der Detailansicht lange drückt.

6. Öffnen externer Links

Wenn der Benutzer einen Link zu einer Veranstaltung oder einem Countdown hinzufügt, kann er ihn durch Antippen öffnen. Der Link wird im Standard-Systembrowser geöffnet. Die App unterstützt nur HTTP- und HTTPS-Links. Die App verfolgt oder protokolliert keine geöffneten Links.

7. Startbildschirm-Widgets

Die App ermöglicht das Hinzufügen von Widgets zum Startbildschirm des Telefons (in den Größen 1x1, 2x1, 3x1 und 2x2). Widgets zeigen einen Countdown zu einer ausgewählten Veranstaltung an. Widget-Daten (Veranstaltungsname, Anzahl der Tage) werden lokal in SharedPreferences auf dem Gerät gespeichert.

8. Automatische Android-Sicherung

Das Android-Betriebssystem kann automatisch App-Daten auf dem Google-Drive-Konto des Benutzers sichern (Auto-Backup-Funktion). Dies ist eine Betriebssystemfunktion, unabhängig von der App — die App selbst initiiert diesen Vorgang nicht. Der Benutzer kann dies in den Android-Systemeinstellungen deaktivieren (Einstellungen > System > Sicherung). In der Google-Drive-Sicherung gespeicherte Daten unterliegen der Datenschutzrichtlinie von Google.

9. Drittanbieter-Dienste

Die App verwendet keine Drittanbieter-Dienste. Insbesondere:

• Keine Analyse oder Verfolgung (kein Google Analytics, Firebase Analytics usw.).
• Keine Werbung.
• Keine Cloud-Dienste (kein Firebase, keine Synchronisierung).
• Keine Fehlerberichterstattung an externe Dienste.
• Keine Anmeldung über externe Konten.

10. Drittanbieter-Bibliotheken

Die App verwendet Open-Source-Bibliotheken ausschließlich für lokale Funktionen (einschließlich Datenbank, Benachrichtigungen, Widgets, Foto- und Videoverarbeitung, Dateiexport). Nach bestem Wissen des Entwicklers sammelt oder überträgt keine der verwendeten Bibliotheken Benutzerdaten.

11. Datensicherheit

Alle Daten werden lokal gespeichert und vollständig vom Benutzer kontrolliert. Der Benutzer kann jederzeit:

• Seine Daten exportieren (CSV, XLSX oder vollständige ZIP-Sicherung).
• Einzelne Veranstaltungen, Countdowns, Fotos oder Videos löschen.
• Alle Daten löschen, indem er den App-Speicher in den Android-Systemeinstellungen leert.
• Die App deinstallieren, wodurch alle lokalen Daten entfernt werden.

Die App verwendet keine Datenverschlüsselung über die Standard-Sicherheitsmechanismen des Android-Betriebssystems hinaus.

12. Benutzerinhalte

Die App ermöglicht Benutzern, eigene Inhalte hinzuzufügen (Fotos, Videos, Notizen, Links). Der App-Entwickler hat keinen Zugriff auf von Benutzern erstellte Inhalte und moderiert diese nicht. Die Verantwortung für die in der App hinzugefügten Inhalte liegt beim Benutzer.

Die App erfordert keine Registrierung und keine Angabe persönlicher Daten. Sie enthält keine Werbung, Käufe, soziale Funktionen oder Chat.

13. Änderungen dieser Richtlinie

Diese Datenschutzrichtlinie kann mit neuen App-Versionen aktualisiert werden. Änderungen sind in der App unter Einstellungen > Datenschutzrichtlinie verfügbar.

14. Kontakt

Bei Fragen kontaktieren Sie uns bitte unter: gigchronicleapp@gmail.com

App-Entwickler: Szymon Dobroczyński

----------

Política de privacidad – GigChronicle

Fecha de entrada en vigor: 28 de marzo de 2026

GigChronicle respeta tu privacidad. Esta Política de privacidad explica qué datos se procesan, cómo se almacenan y cómo se utilizan.

1. Procesamiento de datos

La aplicación no recopila ni transmite datos personales. Todos los datos introducidos por el usuario se procesan y almacenan exclusivamente en el dispositivo del usuario. El desarrollador de la aplicación no tiene acceso a estos datos.

Los datos almacenados localmente incluyen:

• Cuentas atrás — nombre del artista/evento, lugar, ciudad, país, festival, fecha, hora, enlace, notas, ajustes de notificaciones y alarma, ajustes de repetición, ajustes de pantalla de bloqueo.
• Eventos (Historial) — nombre del artista/evento, lugar, ciudad, país, festival, fecha, hora, enlace, notas, marcado como favorito.
• Fotos y vídeos — archivos multimedia añadidos por el usuario a las galerías de cuentas atrás y eventos, almacenados en el directorio interno de la aplicación. Las miniaturas de vídeos se generan y almacenan localmente.
• Portadas — una foto o color establecido como fondo de la tarjeta de un evento/cuenta atrás.
• Ajustes — idioma, tema de color, color de acento, formato de fecha, navegación por deslizamiento, flechas de navegación, sonido de alarma, disposición de estadísticas, vista de lista/cuadrícula, indicadores de consejos únicos.

2. Almacenamiento de datos

Los datos se almacenan en tres ubicaciones, todas exclusivamente en el dispositivo del usuario:

• Base de datos Hive — cuentas atrás, eventos y ajustes, en el directorio interno de la aplicación.
• Archivos multimedia — fotos y vídeos en el subdirectorio media/ y miniaturas en el subdirectorio thumbs/ del directorio interno de la aplicación.
• SharedPreferences — datos de widgets de la pantalla de inicio (asignación de widget a cuenta atrás y datos mostrados).

El desarrollador de la aplicación no tiene acceso a ninguno de los datos mencionados. Los datos se procesan exclusivamente en el dispositivo del usuario.

3. Sin transmisión de datos

La aplicación no transmite ningún dato a servidores externos. No establece ninguna conexión de red. No utiliza servicios de análisis, publicidad, seguimiento ni servicios en la nube. La excepción es la copia de seguridad automática del sistema Android descrita en la sección 8.

4. Permisos

La aplicación puede requerir los siguientes permisos del sistema:

• Notificaciones (POST_NOTIFICATIONS) — mostrar recordatorios de eventos próximos. Las notificaciones funcionan completamente de forma local.
• Alarmas exactas (SCHEDULE_EXACT_ALARM, USE_EXACT_ALARM) — programación precisa de recordatorios y alarmas sonoras.
• Vibración (VIBRATE) — vibración que acompaña a las alarmas sonoras.
• Visualización en pantalla completa (USE_FULL_SCREEN_INTENT) — mostrar alarmas en pantalla completa.
• Reinicio automático (RECEIVE_BOOT_COMPLETED) — restaurar notificaciones y alarmas programadas tras el reinicio del teléfono o la actualización de la aplicación.
• Cámara (CAMERA) — tomar fotos y grabar vídeos (máx. 30 segundos) directamente desde la aplicación.
• Acceso a fotos (READ_MEDIA_IMAGES) — seleccionar fotos y vídeos de la galería del teléfono para añadirlos a la galería de un evento/cuenta atrás. Los originales permanecen en la galería del teléfono; se almacena una copia en la aplicación.
• Guardar en la galería del teléfono — el usuario puede guardar manualmente una foto o vídeo de la galería de la aplicación en la galería del teléfono. Requiere un permiso único de acceso a la galería.
• Almacenamiento del dispositivo (READ/WRITE_EXTERNAL_STORAGE en versiones anteriores de Android) — importación y exportación de archivos (CSV, XLSX, ZIP).
• Acceso a tonos del sistema — selección de un sonido de alarma de la lista de tonos instalados en el teléfono.

Ninguno de estos permisos provoca la transmisión de datos fuera del dispositivo.

5. Exportación y uso compartido de datos

El usuario puede exportar datos de la aplicación de forma voluntaria. La exportación siempre es iniciada por el usuario y nunca ocurre automáticamente:

• Exportación a CSV/XLSX — los eventos, cuentas atrás o estadísticas se pueden exportar a archivos CSV o XLSX. Los archivos se guardan en la ubicación elegida por el usuario.
• Copia de seguridad completa (ZIP) — el usuario puede crear una copia de seguridad completa que incluya todos los eventos, cuentas atrás, ajustes, fotos y vídeos. La copia se guarda como archivo ZIP en la ubicación elegida.
• Restauración de copia de seguridad — el usuario puede restaurar una copia de seguridad desde un archivo ZIP. La restauración reemplaza todos los datos existentes en la aplicación.
• Compartir fotos y vídeos — el usuario puede compartir fotos o vídeos individuales mediante la hoja de compartir del sistema (por ejemplo, enviar por mensajería o correo electrónico). El uso compartido es iniciado únicamente por el usuario.
• Copiar enlace — el usuario puede copiar un enlace al portapapeles del sistema manteniendo pulsado el enlace en la vista de detalles.

6. Apertura de enlaces externos

Si el usuario añade un enlace a un evento o cuenta atrás, puede abrirlo tocándolo. El enlace se abre en el navegador predeterminado del sistema. La aplicación solo admite enlaces HTTP y HTTPS. La aplicación no rastrea ni registra los enlaces abiertos.

7. Widgets de la pantalla de inicio

La aplicación permite añadir widgets a la pantalla de inicio del teléfono (en tamaños 1x1, 2x1, 3x1 y 2x2). Los widgets muestran una cuenta atrás hasta un evento seleccionado. Los datos del widget (nombre del evento, número de días) se almacenan localmente en SharedPreferences en el dispositivo.

8. Copia de seguridad automática de Android

El sistema operativo Android puede realizar automáticamente una copia de seguridad de los datos de la aplicación en la cuenta de Google Drive del usuario (función Auto Backup). Esta es una función del sistema operativo independiente de la aplicación: la aplicación no inicia este proceso. El usuario puede desactivar esta función en los ajustes del sistema Android (Ajustes > Sistema > Copia de seguridad). Los datos almacenados en la copia de seguridad de Google Drive están sujetos a la Política de privacidad de Google.

9. Servicios de terceros

La aplicación no utiliza ningún servicio de terceros. En particular:

• Sin análisis ni seguimiento (sin Google Analytics, Firebase Analytics, etc.).
• Sin publicidad.
• Sin servicios en la nube (sin Firebase, sin sincronización).
• Sin informes de errores a servicios externos.
• Sin inicio de sesión mediante cuentas externas.

10. Bibliotecas de terceros

La aplicación utiliza bibliotecas de código abierto exclusivamente para funciones locales (incluyendo base de datos, notificaciones, widgets, procesamiento de fotos y vídeos, exportación de archivos). Según el conocimiento del desarrollador, ninguna de las bibliotecas utilizadas recopila ni transmite datos del usuario.

11. Seguridad de los datos

Todos los datos se almacenan localmente y están completamente controlados por el usuario. El usuario puede en cualquier momento:

• Exportar sus datos (CSV, XLSX o copia de seguridad completa ZIP).
• Eliminar eventos, cuentas atrás, fotos o vídeos individuales.
• Eliminar todos los datos borrando el almacenamiento de la aplicación en los ajustes del sistema Android.
• Desinstalar la aplicación, lo que elimina todos los datos locales.

La aplicación no aplica cifrado de datos más allá de los mecanismos de seguridad estándar del sistema operativo Android.

12. Contenido del usuario

La aplicación permite a los usuarios añadir su propio contenido (fotos, vídeos, notas, enlaces). El desarrollador de la aplicación no tiene acceso al contenido generado por los usuarios y no lo modera. El usuario es responsable del contenido que añade a la aplicación.

La aplicación no requiere registro ni información personal. No contiene publicidad, compras, funciones sociales ni chat.

13. Cambios en esta política

Esta Política de privacidad puede actualizarse con nuevas versiones de la aplicación. Los cambios estarán disponibles en la aplicación en Ajustes > Política de privacidad.

14. Contacto

Si tiene alguna pregunta, por favor contáctenos en: gigchronicleapp@gmail.com

Creador de la aplicación: Szymon Dobroczyński
