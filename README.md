# <h1>MPAndroidDutchPlayer</h1>
<h2>Hoe een Android MP3 te installeren</h2>

<b>Toepassingsvereisten:</b>
-Java JDK
-Eclipse IDE
-Android ADT Eclipse-plugin

<h2>1) Installatie van de Java JDK</h2>
Een van de voordelen is de JDK. Klik op de volgende links om de JDK te downloaden

o Download JDK hier

Na het downloaden van het bestand, open het en volg de installatie-instructies om het te installeren.

Mogelijk moet u uw systeem opnieuw opstarten om ervoor te zorgen dat de JDK
is correct geladen.

<h2>2) Downloaden van JAVA SDK-startpakket</h2>
We hebben het SDK-startpakket nodig, dus laten we het downloaden.

Installeer Java nu.

Als u geen installatieprogramma hebt, maar een zipbestand. Pak het uit en onthoud de locatie. Op Windows moeten we de locatie op de Android SDK plaatsen in de omgevingsvariabelen. Dit is hoe we dat doen.

o Klik met de rechtermuisknop op "Computer"
o Ga naar eigenschappen
o (Klik bij Win 7 op "Geavanceerde systeemeigenschappen")
o Klik op het tabblad "Geavanceerd"
o Klik op "Omgevingsvariabelen"
o Ga in de onderste helft naar "PATH"
o Klik erop en klik op de knop "Bewerken"
o Typ een puntkomma ";" het type in het pad naar uw SDK-installatie
o na dat type "\ sdk \ tools"
Dus als uw installatiepad "C: \ Program is
Bestanden \ Android "type" C: \ Program Files \ Android \ tools "

Klik op OK op alle schermen. Laten we nu testen of alles goed is verlopen.

Ga om te beginnen, voer cmd in (er wordt een opdrachtprompt geopend). In het prompttype: android. Indien geconfigureerd, start de AVD (Andoid Virtual Device) Manager.

<h2>3) Android SDK installeren</h2>
Open de Android SDK Manager

Selecteer de Android-API en klik op het installatiepakket

<h2>4) Installatie van Ecplise</h2>
Download Eclipse en extraheer de inhoud.

o Windows 32
o Windows 64

Na het extraheren van Eclipse, navigeer je naar de map en open je Eclipse door te dubbelklikken op eclipse.exe

Eclipse wordt geopend.

<h2>5) Installatie van de ADT-plug-in voor Eclipse</h2>

1. Start Eclipse en selecteer vervolgens Help> Nieuwe software installeren ....

2. Klik op Toevoegen in de rechterbovenhoek.

3. Voer in het dialoogvenster Repository toevoegen de optie 'ADT-plug-in' voor de naam en de volgende URL in
de locatie:
https://dl-ssl.google.com/android/eclipse/

4. Klik op OK
Opmerking: als u problemen ondervindt bij het verkrijgen van de plug-in, probeert u 'http' in de locatie-URL, in plaats van 'https' (https heeft om veiligheidsredenen de voorkeur).

5. Selecteer in het dialoogvenster Beschikbare software het selectievakje naast Developer Tools en klik op Volgende.

6. In het volgende venster ziet u een lijst met de te downloaden hulpmiddelen. Klik volgende.

7. Lees en accepteer de licentieovereenkomsten en klik op Voltooien.
Opmerking: als u een beveiligingswaarschuwing krijgt waarin staat dat de authenticiteit of de geldigheid van de software niet kan zijn
vastgesteld, klik op OK.

8. Start Eclipse opnieuw wanneer de installatie is voltooid.

<h2>6) De ADT-plug-in configureren</h2>
Nadat u de ADT met succes hebt gedownload zoals hierboven beschreven, is de volgende stap om uw ADT aan te passen
voorkeuren in Eclipse wijzen naar de Android SDK-directory:

1. Selecteer Venster> Voorkeuren ... om het paneel Voorkeuren te openen (Mac OS X: Eclipse> Voorkeuren).

2. Selecteer Android in het linkerpaneel.
Mogelijk ziet u een dialoogvenster waarin u wordt gevraagd of u gebruiksstatistieken naar Google wilt verzenden. Als dat zo is, maakt u uw
keuze en klik op Doorgaan. U kunt niet doorgaan met deze procedure totdat u op Doorgaan klikt.

3. Klik voor de SDK-locatie in het hoofdvenster op Bladeren ... en zoek de gedownloade SDK-map.

4. Klik op Toepassen en vervolgens op OK.
Gedaan! Als u nog geen problemen hebt ondervonden, is de installatie voltooid. Als u de Android SDK voor de eerste keer installeert, gaat u terug naar de SDK installeren om uw installatie te voltooien.

<h2>7) Toepassing importeren</h2>
Nu bent u klaar, alles gaat in de verduistering, klikt u op bestand en selecteert u vervolgens importeren:

Selecteer bestaande projecten in werkruimte:
Selecteer nu de hoofdmap (mp3-map in de zip):

Klik op OK en dan klaar. Nu zie je de app op het tabblad Projecten. Vouw de bron uit, vouw src uit, rechts
klik com.mp3wiz klik op refractor-> hernoemen. Selecteer nu Hernoem Sub-pakketten en verander de naam
van com.euroasia.nl naar com.renamepackage

App_name naar wat je de app noemt. MP3NL
topappsurl naar uw app-URL.

<h2>8) Exporteren van de applicatie</h2>
Nu is het tijd om de applicatie te exporteren. Selecteer bestand -> exporteren -> Android-applicatie exporteren -> Volgende ->
KIES NU UW APP:

<h2>9) Officiële website</h2>
https://euroasia.company
