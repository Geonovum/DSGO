Bijlagen
========

Data, datasets en metadata
--------------------------

De uitwisseling van gegevens staat bij het DSGO centraal. Dat uitwisselen kan
eenmalig, herhaaldelijk of continu zijn, maar wat bedoelen we hier met gegevens?
Voor een digitaal stelsel gebouwde omgeving zijn er drie termen essentieel
wanneer we het hebben over gegevens of *data*. 

In deze paragraaf geven we een zoveel mogelijk niet-technische toelichting en context aan de in dit rapport veel gebruikte begrippen data, datasets en metadata. De basis voor deze begrippen liggen mede in het [NEN 2660](https://www.nen.nl/nen-2660-1-2020-ontw-nl-278048) en het [Metamodel Informatiemodellering (MIM)](https://docs.geostandaarden.nl/mim/def-st-mim-20201023/).  

**Data** zijn die gegevens die over het gebouwde object beschrijven. Dat kan
bijvoorbeeld een bouwtekening zijn, een inspectierapport of een rapportage van
het energiegebruik. Deze gegevens zijn in verschillende formaten beschreven,
waarbij sommige formaten leesbaar zijn voor zowel mens en computer (zoals een
PDF-inspectierapport), maar niet altijd interpreteerbaar voor een
computersysteem. Data kan gestructureerd of ongestructureerd zijn. Hoe
gestructureerder een bestand, hoe meer mogelijkheden het biedt in een digitale
omgeving. Het heeft daarom de voorkeur om zo’n inspectierapport als spreadsheet
ook voor de computer leesbaar aan te bieden. Dan kan een computersysteem wel de
tabel met gebreken ‘zien’ en interpreteren.

Data is een representatie van observaties, objecten of andere entiteiten uit de
werkelijkheid. Denk aan het bouwobject dat door het proces van plan en
vergunningverlening, tot realisatie en beheer, heengaat. Data refereert naar
iets dat is verzameld, geobserveerd, gegenereerd of afgeleid. Data wordt door de
mens gebruikt als een basis om te redeneren, discussiëren of calculeren.

**Metadata** zijn gegevens die de karakteristieken van bepaalde gegevens
beschrijven. Het zijn dus eigenlijk data over data. De metadata bij een bepaald
document (de gegevens) kunnen bijvoorbeeld zijn: de auteur, de datum van
schrijven, de uitgever, het aantal pagina's en de taal waarin de gegevens zijn
opgesteld. De metadata helpt mens en computer bij het vinden van de juiste
gegevens en bij het juist interpreteren van het document. Bij een bouwtekening
beschrijft metadata welke schaal is gebruikt, wie de tekenaar was, welke versie
van de tekening dit is en wanneer deze versie is opgeleverd. Dat staat dan ook
vaak in de rechter onderhoek, maar ook het digitale bestand van de tekening
bevat deze gegevens op een vaste plek. Bij een inspectierapport zijn
gebruikelijke metadata het geïnspecteerde object, de inspecteur, de datum van de
inspectie. In PDF-vorm staat dat dan op de voorkant van het rapport, maar in het
voor de computer leesbare bestand staat dat eveneens op vaste plekken. Bij een
energierapport zijn metadata informatie over de EAN-aansluiting, maar ook
misschien adres of netbeheerder of vergelijking met andere gebruikers.

Het op een gestructureerde en afgesproken manier van toevoegen van metadata aan
data heeft als resultaat dat data vindbaar en doorzoekbaar is. Denk daarbij aan
de systematiek van bibliotheken en archieven.

De scheidslijn tussen metadata en data zelf is soms lastig te trekken. Wat voor
de ene toepassing randzaken zijn, kan centraal staan in de andere. Bijvoorbeeld
om vergelijkingen tussen tekeningen van een verschillende schalen te maken of om
door de energiebesparende suggesties uit het inspectierapport te vergelijken met
het daadwerkelijke verbruik. Daarom is het belangrijk zowel juiste data als
metadata te verzamelen.

De interpretatie van gegevens is afhankelijk van het bestandsformaat waarin het
is opgeslagen. Een Pdf-bestand is slecht interpreteerbaar voor een
computersysteem: slechts de titel en auteur van het document staat op een vaste
plek bewaard. Een spreadsheet daarentegen kan worden genavigeerd, met vaste
cellen voor bepaalde informatie. Andere bestandsformaten, zoals XML of linked
data-talen, zijn nog meer zelf beschrijvend. Deze formaten kunnen een
interpretatieschema toevoegen aan de data, zodat een computersysteem zelf kan
achterhalen waar de relevante informatie staat.

Een **dataset** is de derde en laatste data-gerelateerde term. Een dataset is
een identificeerbare verzameling van data die als een geheel kan worden
verwerkt, bewerkt en gepubliceerd door een enkel subject. Een verzameling van
datasets kan ook op zich weer een dataset zijn. Bijvoorbeeld de verzamelde
gegevens vanuit de verschillende disciplines die opgenomen worden in een
*Digitaal Dossier Bevoegd Gezag* zijn elk een dataset. Het dossier bevoegd gezag, wordt
gevormd door de verzameling van deze datasets en is zelf ook een dataset.

Data en datasets ontstaan niet zomaar. Ze kennen een **levenscyclus**. Deze
levenscyclus van de dataset is samen te vatten in vier fasen, geïllustreerd door
figuur ‘Levenscyclus van de dataset’:

1.  Definitiefase: in deze fase is de dataset gedefinieerd en krijgt ze betekenis.
    Van belang is dat het algoritme de juiste data voortbrengt zodat de inhoud
    van de dataset overeenkomst met zoals deze vooraf gedefinieerd was. De
    ontwikkelaar van een dataset is daarmee verantwoordelijk voor de juistheid
    van de inhoud.

2.  Productiefase: in deze fase wordt de dataset geproduceerd. In deze fase is
    bepalend dat de dataset volledig en in het juiste formaat wordt vrijgegeven.
    De producent van de dataset is verantwoordelijkheid voor de volledigheid van
    de dataset.

3.  Beheerfase: in deze fase wordt de dataset beheerd. In deze fase is bepalend hoe
    goed de dataset wordt bewaard, voorzien van metadata en toegankelijk
    gemaakt. De beheerder van de dataset is verantwoordelijk voor de metadata
    van de dataset.

4.  Gebruiksfase: in deze fase wordt de data gebruikt. In deze fase is bepalend hoe
    goed de dataset als service ter beschikking wordt gesteld en ondersteund en
    herbruikbaar is. De exploitant van de dataset is verantwoordelijk voor het
    ondersteunen van het gebruik van de dataset.

**Figuur: Levenscyclus van de dataset**

![](media/c6058c91cab22df12ca9ed805872cca4.png)

Sommige datasets zijn contractueel afgesproken, (tegenwoordig meer en meer via
Informatieleveringsspecificaties, afgekort ILS’en) zoals een bouwtekeningen,
modellen, berekeningen en inspectierapporten bij het voltooien van een bepaalde
bouwfase. Of het halfjaarlijks update van een kaart met verschillende kaartlagen
met gekoppelde informatie van een beheerd areaal. De dataset komt daarmee vaak
overeen met een dossier. Door een afgesproken structuur is een dataset voor de
computer een samenhangende set van bestanden.

Er is in de zin van DSGO niet een minimale (laat staan maximale) grootte van een
dataset. Uit praktische overwegingen zijn er misschien wel beperkingen, maar
door technologische ontwikkelingen speelt dat steeds minder een rol. Om data
(gegevens) of datasets (gegevensets) met/ binnen het DSGO uit te wisselen gaat
het niet zozeer over de grootte van een dataset maar juist over de
vindbaarheid, toegankelijkheid, herbruikbaarheid en uitwisselbaarheid. Dat komt
overeen met het maken van afspraken op basis van de FAIR-uitgangspunten.


Uitgangspunten, randvoorwaarden en eisen
----------------------------------------
Uitgangspunten zijn die zaken die door het project als basis moeten worden meegenomen. Een uitgangspunt is iets waar het project niet omheen kan, zoals wet- en regelgeving. Randvoorwaarden zijn zijdelingse beperkingen aan het project. Randvoorwaarden stellen eisen aan het project die vanuit het project niet kunnen worden beïnvloed. Eisen zijn criteria waar het eindresultaat aan moet voldoen. 
De in hoofdstukken vier en vijf benoemde uitgangspunten, randvoorwaarden en eisen zijn in deze paragraaf samengevat.

**Publiek waarden**

*Open en transparant*
- Randvoorwaarde: Alle betrokkenen bij een use case bespreken de ontwerpprincipes, om concreet te maken wat deze voor een use case betekenen. De keuzes die hieruit volgen worden vastgesteld en ingericht, bijgesteld en zo lerend ontwikkeld, zodat anderen daarop kunnen voortbouwen. 
Open en transparante uitkomsten
- Eis: Usecases leggen voor elke data(set) die tussen partijen uitgewisseld wordt, vast wat de oorsprong van deze dataset is en welke bewerkingen deze heeft ondergaan.

*Inclusiviteit*
- Randvoorwaarde: Maak de ontwikkeling van het DSGO inclusief, zodat er geen groepen worden buitengesloten door de manier waar op de afspraken gemaakt worden over het delen van data. De belangen van alle stakeholders zijn in beeld bij elke use case. De inzet van een onafhankelijk voorzitter is daarbij een aanrader.
- Om te voorkomen dat  groepen worden buitengesloten of dat data verkeerd wordt geïnterpreteerd of dat verkeerde berekeningen worden toegepast, is een onafhankelijke voorzitter vereist.

*Rechtvaardigheid*
- Eis: Ontwerp elke use case binnen het DSGO rechtvaardig, zodat alle belanghebbenden een eerlijke en volledige weergave van de feiten kunnen inzien. 

*Doelgerichtheid*
- Eis: Ontwerp elke use case binnen het DSGO doelgericht, zodat de uit te wisselen data, gebruikt wordt in lijn met het doel waarvoor de eigenaar van de data, 
de data ter beschikking stelt aan andere partijen. 

*Betrokkenheid*
- Randvoorwaarde: Voor elke use case worden de afspraken met alle direct betrokkenen gemaakt en vastgelegd. Dat geldt in het bijzonder voor partijen die de data ter beschikking stellen.

*Controleerbaarheid*
- Eis: Ontwerp elke use case zo dat er kan worden ingegrepen in de geautomatiseerde processen. 

*Soevereiniteit*
- Uitgangspunt: Binnen het DSGO wordt bepaald welke belanghebbende (in juridische termen natuurlijke persoon of rechtspersoon) eigenaar is en/of zeggenschap en controle uitoefent over en/of gebruik maakt van de data(set), standaard, algoritme of voorziening die van belang zijn binnen de use cases. Met deze belanghebbenden kunnen vervolgens afspraken worden gemaakt om de data(set), standaard, algoritme of voorziening FAIR te kunnen (her)gebruiken, tenzij wet- en regelgeving anders bepaalt.
- Uitgangspunt: Samen met de sector co-creëren van een samenhangende set afspraken op business, functioneel, operationeel, juridisch en technisch gebied, om gemakkelijker gebruik te kunnen maken van elkaars data.

*Informatiebeveiliging*
- Eis: Binnen het DSGO worden maatregelen getroffen om de integriteit te waarborgen.
- Eis: Het DSGO voorziet in autorisatie- en authenticatiemogelijkheden, zodat alleen de rechthebbenden inzage krijgen in de data(sets) die uitgewisseld worden. 
- Eis: Het DSGO geeft transparant weer wat de bron is van elke dataset en welke bewerkingen deze heeft ondergaan en/of aan welke kwaliteitseisen deze voldoet in termen van actualiteit, volledigheid en juistheid), zodat de eindgebruiker de betrouwbaarheid kan vaststellen.

**Dataprincipes**

*Vindbaar*
- Uitgangspunt: Het DSGO is een set uniforme afspraken voor de uitwisseling van gegevens over de gebouwde omgeving tussen organisaties, en geen landelijk registratiesysteem.
- Uitgangspunt: Het DSGO beschrijft de afspraken waaronder de toegang tot de datasets bij de bron wordt verleend, de toegang wordt bij de bron bepaald tenzij wet- en regelgeving anders bepaalt. Het DGSO catalogiseert metadata die de datasets beschrijven.
- Eis: De data die het DSGO ontsluit, zijn identificeerbaar aan de hand van een UOI. Elke dataset verwijst/beschrijft naar één of meerdere UOI's en is zelf ook uniek identificeerbaar aan de hand van een persistente identifier. Ook metadata krijgt zo'n unieke en persistente identifier. Persistent betekent dat maar één ding zo'n identifier krijgt en dat een ding die identifier z'n hele levensloop behoudt.
- Eis: Van elk gegeven in het DSGO is meta-informatie over onder meer de herkomst, kwaliteit, status en gebruik (licentie en toepassing) beschikbaar. De wijze van metadatering sluit aan bij vigerende (inter)nationale standaarden voor informatiemanagement en metadata. Ook de wijze van toegang, de gebruikte gegevensformaten en schema’s worden beschreven in de metadata van een dataset.
- Eis: Bij de metadata(set) wordt de unieke identificatie (UOI) van de betreffende data(set) opgenomen.
- Eis: Het DSGO fungeert onder meer als een doorzoekbare catalogus c.q. register met gedistribueerde data(sets) over de gebouwde omgeving. Bijvoorbeeld Gebouwdossier (Digitaal Dossier Bevoegd Gezag - DDBG), Energie labels, en geo-basisregistraties.

*Toegankelijk*
- Uitgangspunt: Gegevens worden in het DSGO aangeboden op basis van de bestaande (semantische) standaarden. Vanuit DSGO kan dit als randvoorwaarde worden geformuleerd aan broneigenaren die hun data(sets) via DSGO wensen te ontsluiten.
- Uitgangspunt: In het DSGO verloopt de authenticatie van natuurlijke personen en (overheids)organisaties met een publieke taak zich middels DigiD, van bedrijven middels eHerkenning. 
- Eis: Voor het DSGO zijn (vooral) afspraken nodig over de technische uitwisseling van (meta)data(sets) op de koppelvlakken, zodat bestaande systemen en datastructuren zo min mogelijk hoeven te worden aangepast, om de data te laten stromen.
- Eis: De toegang tot het DSGO wordt geboden middels een open, gratis en universeel toepasbaar protocol.
- Eis: Het DSGO houdt een duurzame metadata registratie bij, waarbij metadata langdurig bewaard en toegankelijk blijft. De datasets zelf worden niet noodzakelijk door DSGO bewaard.

*Interoperabel*
- Uitgangspunt: Elke dataset beschrijft het informatiemodel of ontologie waarmee de data is beschreven. Als die niet aanbevolen is door Forum Standaardisatie of het BIM Loket, moet het uitgangspunt zijn dat ze publiekelijk te raadplegen zijn.
- Randvoorwaarde: Het DSGO helpt koppelingen te realiseren tussen datasets, belegd bij de metadata redacteur. 
- Eis: Datasets worden aangeboden in standaarden die zijn aanbevolen door Forum Standaardisatie of door het BIM Loket. 
- Eis: De eigenaar van de (meta)data(set) is zelf verantwoordelijk voor een goede kwaliteit van de (meta)data(set).

*Herbruikbaar*
- Uitgangspunt: Het DSGO geeft gerapporteerde onjuistheden en onvolkomenheden door aan de eigenaars. DSGO biedt API's en formulieren aan voor eindgebruikers om rapportages zo eenvoudig mogelijk te maken.
- Uitgangspunt: In het DSGO worden Standaarden uit verschillende domeinen toegepast. Het is onmogelijk om al deze standaarden te harmoniseren op semantiek. Daarom stellen we de open standaarden van het BIM Loket en het Forum Standaardisatie als uitgangspunt.
- Randvoorwaarde: De leveranciers en de metadata redacteur zetten zich in voor een hoge kwaliteit data. Het platform kan statistieken gebruiken om de metadata redacteur te ondersteunen in haar/zijn werk. 
- Eis: De data en de metadata dienen van hoge kwaliteit te zijn en voldoen aan een hoge mate van nauwkeurigheid. 
- Eis: Elke gegevensset beschrijft de gebruikslicentie ervan. Minstens op een voor mensen leesbare wijze, bij voorkeur met (een link naar) een machine leesbare representatie.
- Eis: Het platform en de dataset aanbieders houden zorgvuldig bij waar welk gegevenspunt vandaan komt.

Met dank aan
------------

Bij de totstandkoming van dit adviesrapport hebben de schrijvers zeer waardevolle input en feedback mogen ontvangen van
experts werkzaam bij de volgende organisaties, die we hierbij hartelijk willen danken voor hun inbreng.

BIM Loket, Brink Climate Systems, CROW, Energie Nederland, Future Insight, Geonovum, Kadaster, Ministerie van BZK, Movares, Niels Vossebeld Advies, Programma DSGO, Rijksvastgoedbedrijf, Rijkswaterstaat, RVO, Stichting Platform BIM Legal, TNO, Twee Snoeken, VNG.

<details class='note'>
 Omwille van privacy (AVG) hebben we niet alle namen van de betrokkenen opgenomen in het document. Mocht u meer informatie willen of in contact willen komen met bepaalde personen, stuur dan een bericht aan info@geonovum.nl. 
</details>
