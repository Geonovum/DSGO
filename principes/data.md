Data, datasets en metadata
--------------------------

De uitwisseling van gegevens staat bij het DSGO centraal.
Dat uitwisselen kan eenmalig, herhaaldelijk of continu zijn, maar wat bedoelen we hier met gegevens?
Voor een digitaal stelsel gebouwde omgeving zijn er drie termen essentieel wanneer we het hebben over gegevens of *data*.

<dfn>Data</dfn> zijn die gegevens die over het gebouwde object beschrijven. 
Dat kan bijvoorbeeld een bouwtekening zijn, een inspectierapport of een rapportage van het energiegebruik.
Deze gegevens zijn in verschillende formaten beschreven, waarbij sommige formaten leesbaar zijn voor mens en computer (zoals een PDF-inspectierapport), maar niet altijd interpreteerbaar voor een computersysteem.
Hoe gestructureerder een bestandsformaat, hoe meer mogelijkheden het biedt in een digitaal stelsel.
Het heeft daarom de voorkeur om zo’n inspectierapport ook als bijv. spreadsheet aan te bieden. 
Dan kan een computersysteem wel de tabel met gebreken ‘zien’ en interpreteren.

<aside class='def'>
Data is een representatie van observaties, objecten of andere entiteiten.
Data refereert naar iets dat is verzameld, geobserveerd, gegenereerd of afgeleid.
Data wordt gebruikt als een basis om te redeneren, discussieren of calculeren. 

Data kan gestructureerd of ongestructureerd zijn.
Data kan worden gerepresenteerd in kwantitatieve, kwalitatieve of fysieke vormen.

Data is het object dat door het process van plan en vergunningverlening, tot
realisatie en beheer heengaat.
</aside>

De <dfn>metadata</dfn> helpt mens en computer bij het vinden van de juiste gegevens en bij het juist interpreteren van het document.
Bij een bouwtekening beschrijft metadata welke schaal is gebruikt, wie de tekenaar was, welke versie van de tekening dit is en wanneer deze versie is opgeleverd. 
Dat staat dan ook vaak in de rechteronderhoek, maar ook het digitale bestand van de tekening bevat deze gegevens op een vaste plek.
Bij een inspectierapport zijn gebruikelijke metagegevens het geïnspecteerde object, de inspecteur, de datum van de inspectie. 
In PDF-vorm staat dat dan op de voorkant van het rapport, maar in een digitaal bestand staat dat op eveneens vaste plekken. 
Bij een energierapport zijn metagegevens informatie over de EAN-aansluiting, maar ook misschien adres of netbeheerder of vergelijking met andere gebruikers.

De scheidslijn tussen metadata en data zelf is soms lastig te trekken.
Wat voor de ene toepassing randzaken zijn, kan centraal staan in de andere.
Bijvoorbeeld om vergelijkingen tussen tekeningen van een verschillende schalen te maken of om door de energiebesparende suggesties uit het inspectierapport te vergelijken met het daadwerkelijke verbruik. 
Daarom is het belangrijk zowel juiste data als metadata te verzamelen.

De interpretatie van gegevens is afhankelijk van het bestandsformaat waarin het is opgeslagen.
Een PDF-bestand is slecht interpreteerbaar voor een computersysteem: slechts de titel en auteur van het document staat op een vaste plek bewaard.
Een spreadsheet daareentegen kan worden genavigeerd, met vaste cellen voor bepaalde informatie.
Andere bestandsformaten, in XML of linked data, zijn nog meer zelfbeschrijvend.
Deze formaten kunnen een interpretatieschema toevoegen aan de data, zodat een computersysteem zelf kan achterhalen waar de relevante informatie staat.

<aside class="def">

Metadata zijn gegevens over andere gegevens.
Metadata zijn gegevens over onder meer de herkomst, kwaliteit en gebruik van data.

</aside>

Een <dfn>dataset</dfn> is de laatste data-gerelateerde term en tegelijk ook de minst duidelijke. 
Een dataset is een ad-hoc of specifieke groepering van gegevens en/of metagegevens.
Sommige datasets zijn contractueel afgesproken, zoals een bouwtekeningen en inspectierapporten bij het voltooien van een bepaalde bouwfase.
Of het halfjaarlijks opleveren (bijwerken) van een kaart van het beheerde areaal.

De dataset komt daarmee vaak overeen met een dossier.
Die worden ook opgesteld voor een bepaald doel, maar kunnen documenten ad-hoc worden overgedragen.

Er is in de zin van DSGO niet een minimale (laat staan maximale) grootte van een dataset.
Uit praktische overwegingen zijn er misschien wel beperkingen.

<aside class="def">

Om data (gegevens) of datasets (gegevensets) met / binnen het DSGO uit te
wisselen zijn afspraken nodig over de vindbaarheid, toegankelijkheid,
herbruikbaarheid en uitwisselbaarheid.
Dat komt overeen met de FAIR-uitgangspunten.

Een dataset is een identificeerbare verzameling van data die als een geheel kan
worden verwerkt, bewerkt en gepubliceerd door een enkel subject. Dit leidt ertoe
dat de levenscyclus van de dataset is samen te vatten in vier fasen,
geillustreerd door figuur ‘Levenscyclus van de dataset’:

1.  Definitie: hoe goed het model of algoritme dat de dataset voortbrengt, is
    gedefinieerd, ontwikkeld en gevalideerd voor bedoeld gebruik.

2.  Productie: hoe goed het product dat daaruit ontstaat word geproduceerd,
    geëvalueerd en vrijgegeven.

3.  Beheer: hoe goed de dataset wordt bewaard, voorzien van metadata en
    toegankelijk gemaakt.

4.  Gebruik: hoe goed de data als service ter beschikking wordt gesteld,
    ondersteund en hergebruikt.

![Levenscyclus van de dataset](media/Levenscyclus-dataset.png)

</aside>
