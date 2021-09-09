Dataprincipes
=============

Er zijn veel organisaties in de sector actief die data kunnen gaan delen met DSGO.
Daardoor is het op elkaar aansluiten van aanbod en vraag van gegevenssets niet eenvoudig.
Elke organisatie heeft weer behoefte aan verschillende soorten gegevens.

Het gebrek aan beschikbaar hebben van
de juiste data op de juiste plek is niet alleen een uitdaging om
stikstofreductie doelen te halen maar is noodzakelijk voor alle maatschappelijke
en/of sector-overstijgende doelen.

Ontwerpprincipes
----------------

In dit hoofdstuk worden de ontwerpprincipes voor (meta)data(sets) in het DSGO
beschreven aan de hand van de FAIR-principes: 
*Findable* (vindbaar), *Accessible* (toegankelijk), *Interoperable* (uitwisselbaar) en *Reusable* (herbruikbaar).
Deze zijn geletterd en genummerd, aan de hand waarvan ze worden doorgenomen. 

### Vindbaar

De eerste stap bij het (her)gebruiken van data is om de data te vinden. Metadata
en data moeten gemakkelijk te vinden zijn voor zowel mensen als computers.
Machineleesbare metadata zijn essentieel voor het ontdekken van datasets en
services. Vindbaarheid begint met bekendheid om te weten dat data gevonden kan
worden. Hiervoor is communicatie over het DSGO-uitgangspunt en een centraal
loket voor vragen essentieel.

**F1. (Meta)data krijgen een wereldwijd unieke en persistente identifier**

(Meta)data(set) in het DSGO krijgen een unieke object identificatie
([UOI](#toegankelijk)) welke tijdens de hele levensloop van de (meta)data(set) hetzelfde blijft.

Het [Unieke Object Identificator (UOI)][uoinieuws] ‘systeem’
is een digitale sleutel waarmee je op basis van je rol en toegangsrechten
informatie over gebouwen en objecten in de gebouwde omgeving kunt raadplegen.

[uoinieuws]: https://www.geonovum.nl/over-geonovum/actueel/onderzoek-unieke-object-identificatie-en-omgevingsinformatie

Ook identificeerbare datasets, documenten, etc. worden een middels een UOI geïdentificeerd.

Het ‘systeem’ als gedachte is ontwikkeld binnen de bouw- en vastgoedsector. De
gedachte achter een UOI-code is dat er domein-overstijgend verbindingen mee
gelegd kunnen worden die het beantwoorden van vragen over objecten in de
gebouwde omgeving vereenvoudigen.
De UOI-code wordt ook genoemd in de lopende consultatie van de [Samenhangende Objecten Registratie (SOR)][sorinfo].
Experts uit de bouw- en geo-wereld hebben het UOI als systeem getoetst aan de
nieuwe Geo- & Bouw-informatiestandaarden (NEN 3610, NEN 2660 en BIM gerelateerde
standaarden) en de [principes die DiSGeo hanteert][disgeoemso] voor
de Samenhangende Objecten Registratie (SOR). 
Ook is gekeken naar de instrumenten
van de Wet kwaliteitsborging Bouw (Wkb) en het ontwerp Digitaal Stelsel Gebouwde
Omgeving DSGO (binnen DigiGo).

[sorinfo]: https://www.geobasisregistraties.nl/basisregistraties/doorontwikkeling-in-samenhang/objectenregistratie
[disgeoemso]: https://docs.geostandaarden.nl/disgeo/emso/#identificatie-van-objecten

*Noot van de schrijvers: Tussen november 2020 en april 2021 heeft het ministerie
van BZK onderzoek laten doen naar het ontwerp van een Unieke Object
Identificatie (UOI). Vraag aan Geonovum was de UOI te verkennen in relatie tot
standaarden in de bouw- en geo-sector en de ontwikkelingen rond
objectidentificatie in de fysieke leefomgeving. Ten tijde van het schrijven dit
rapport is er een concept onderzoeksrapport over UOI.*

**F2. Gegevens worden beschreven met uitgebreide metadata**

Van elk gegeven in het DSGO is meta-informatie over onder meer de herkomst,
kwaliteit en gebruik (licentie + toepassing) beschikbaar. De wijze van
metadatering sluit aan bij vigerende (inter)nationale standaarden voor metadata.

Ook de wijze van toegang, de gebruikte gegevensformaten en schema’s worden beschreven in de metadata van een dataset.

**F3. Metadata bevatten duidelijk en expliciet de identifier van de gegevens die
ze beschrijven**

Metadata is beschikbaar op het niveau van data en dataset. Een data(set) in het
DSGO heeft een UOI, en bij metadata wordt het UOI van de data(set) vastgelegd.
*N.B. de relatie is dus ‘Metadata beschrijft 0..\* data(set)’ en niet ‘Data(set)
wordt beschreven in 0..\* Metadata’*

**F4. (Meta)data worden geregistreerd of geïndexeerd in een doorzoekbare bron**

Het DSGO fungeert ondermeer als een doorzoekbare catalogus c.q. register met gedistribueerde
data(sets) over de gebouwde omgeving.
Bijvoorbeeld Gebouwdossier, Energielabels, geobasisregistraties.

Daarmee lijkt deze functie van DSGO op een metadata-register à la [Nationaal Geo
Register][ngr] (NGR).

[ngr]: https://nationaalgeoregister.nl/

Het DSGO als catalogus c.q. register van datasets over de gebouwde omgeving
sluit aan bij principe van ‘data bij de bron’. Dataset zelf wordt niet
aangeleverd aan ofwel gekopiëerd in DSGO; er worden wel gegevens over de
data(set) (ofwel: metadata) aan het DSGO aangeleverd. Over deze metadata van
data(sets) wordt metadata vastgelegd, bijvoorbeeld data over de herkomst en
actualiteit van de metadata over de data(set).

>   Bijvoorbeeld BAG: De Basisregistratie Adressen en Gebouwen (BAG) is de
>   authentieke bron voor officiële adressen en bouwjaren van panden. De
>   ‘eigenaar’ van de BAG draagt gegevens aan over de dataset BAG aan het DSGO
>   ondermeer over de herkomst, kwaliteit (bijvoorbeeld actualiteit 4 dagen,
>   geometrische nauwkeurigheid van 30-60 cm, volledigheid 100%) en gebruik
>   (wettelijk verplicht voor overheden) van de data in de BAG. In het DSGO
>   wordt vastgelegd de herkomst (eigenaar BAG) en kwaliteit (wanneer metadata
>   voor het laatst is bijgewerkt) over de BAG vastgelegd.

### Toegankelijk

Zodra de gebruiker de benodigde gegevens heeft gevonden bij een of meerdere
databronnen, moet hij/zij weten hoe deze kunnen worden geraadpleegd en kan
worden toegepast, mogelijk inclusief authenticatie en autorisatie.

**A1. (Meta)gegevens kunnen worden opgehaald door hun identifier met behulp van
een gestandaardiseerd communicatieprotocol**

De UOI is de sleutel naar het Dossier van een Object dat middels de UOI wordt
geidentificeerd.

*Samenbrengen van gegevens vanuit basisregistraties als BGT en BAG. Ook Digitaal
Stelsel Omgevingswet voor de ruimtelijke besluiten als een omgevingsplan (nu
conform de Wro: bestemmingsplan). UOI Verschil tussen diensten en projectdossier
beschrijven*

**A1.1 Het protocol is open, gratis en universeel toepasbaar**

De gegevens in de data(sets) die in de catalogus DSGO zijn met een open en
gratis protocol bij de bron toegankelijk.

Dat betekent slechts dat de wijze van de toegang gratis is, niet per se bijv. de toegangscodes.

>   Bijvoorbeeld met [Linked
>   Data](#koppelen-van-heterogene-datasets-met-linked-data). De overheid
>   beschikt over veel verschillende datasets met gegevens die wel een relatie
>   hebben, maar nu niet aan elkaar zijn gelinkt. Door bijvoorbeeld
>   beleidsstukken, voorlichting, jurisprudentie en uitvoeringsaanwijzingen te
>   koppelen aan wet- en regelgeving creëer je samenhang. Door relaties
>   zichtbaar te maken, kan linked data ook fungeren als lijm tussen de
>   verschillende (basis)registraties. Met linked data breng je samenhang aan in
>   informatie. Linked data maakt van woorden, zoals de stad ‘Den Haag’, unieke
>   concepten. Elk concept wint aan betekenis als er meer beschrijvingen aan
>   gelinkt worden. Daardoor krijgt de inhoud van webdocumenten meer betekenis
>   en worden zoekresultaten nauwkeuriger.

**A1.2 Het protocol maakt een authenticatie- en autorisatieprocedure mogelijk,
waar nodig**

Het DSGO geeft gecontroleerde toegang tot data over de gebouwde omgeving. In de
*authenticatie*procedure wordt de identiteit van de leverancier of afnemer van
gegevens vastgesteld. In de *autorisatie*procedure wordt bepaald of de
leverancier of afnemer recht heeft tot het wijzigen of gebruiken van de
gegevens.

> DigiD en e-Herkenning

**A2. Metadata zijn toegankelijk, ook als de data niet meer beschikbaar zijn**

Data kan niet meer beschikbaar zijn voor afnemer om verschillende redenen:
gegevens zijn verwijderd, gebruiker is niet meer geautoriseerd, of de koppeling
met de gedistribueerde bronnen liggen eruit. In het DSGO fungeert het
metadata-register als referentie naar welke data(sets) beschikbaar zijn, of zijn
geweest.

### Uitwisselbaar

Interoperabiliteit betekent het kunnen uitwisselen van digitale gegevens tussen
overheden onderling en tussen de overheid, bedrijven en burgers. Door uit te
wisselen kunnen gegevens geïntegreerd met andere gegevens. Bovendien moeten de
gegevens samenwerken met applicaties of workflows voor analyse, opslag en
verwerking.

Op eenduidige manieren samenwerken om zo informatie beter te kunnen beveiligen
en makkelijker en toegankelijker te maken voor iedereen: dat is hoe open
standaarden de samenwerking bevorderen tussen het bedrijfsleven, de burger en
overheid. Een standaard is een afspraak over informatie of een proces,
vastgelegd in een specificatiedocument. Als computersystemen gegevens
uitwisselen, dan moeten zij die dezelfde afspraken of processen hanteren. Doen
ze dat niet, dan kunnen er fouten ontstaan, kan het systeem misbruikt worden of
wordt verkeerde data overgenomen.

**I1. (Meta)data gebruiken een formele, toegankelijke, gedeelde en breed
toepasbare taal voor kennisrepresentatie.**

In het DSGO worden voor de beschrijving van de datasets (metadata) en de data
van datasets zelf open standaarden gebruikt.

In Nederland zet het [Forum
Standaardisatie](https://forumstandaardisatie.nl/over-ons) zich in voor open
ICT-standaarden. Standaarden ondersteunen gegevensuitwisseling tussen
ICT-systemen. De openheid zorgt ervoor dat iedereen de standaard kan
gebruiken. [Open
standaarden](https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/standaardisatie/open-standaarden/) dragen
bij aan interoperabiliteit en leveranciersonafhankelijkheid. Het gebruik van
open standaarden in ICT-systemen bespaart kosten en verlicht administratieve
lasten.

Het Forum Standaardisatie hanteert twee type [lijsten open
standaarden](https://forumstandaardisatie.nl/open-standaarden): de verplichte
(‘pas toe of leg uit’) en aanbevolen open standaarden voor de publieke sector.

**I2. (Meta)data gebruiken vocabulaires die FAIR-principes volgen**

In het DSGO vindt domein overstijgende uitwisseling van data plaats. Als
verschillende domeinen data willen uitwisselen, dan is er vaak sprake van
verschil in definities en begrippen.

Betekenisverwarring kan op twee wijzes overbrugd worden.
Enerzijds door gebruik te maken van een bovenliggende identifier die in beide
domeinen wordt toegepast. De UOI biedt in dat geval uitkomst om data van het ene
domein te combineren met data van het andere domein. Voorbeelden van
overstijgende domeinen zijn: het geodomein waaronder de geo-basisregistraties,
het energiedomein, ....

Anderzijds door de wijze waarop de gegevens zijn opgeslagen, te beschrijven.
Zulke beschrijven worden ook wel OTL’s, ontologieën of informatiemodellen genoemd.

>   Bijvoorbeeld [CB-NL](https://public.cbnl.org/over-cb-nl): Verschillende
>   definiëring, beschrijvingen en interpretaties door betrokken partijen leiden
>   ertoe dat bouwpartijen in de sector een verschillende taal ‘spreken’.
>   Hierdoor zijn objectgegevens niet efficiënt (geautomatiseerd) herbruikbaar.
>   De conceptenbibliotheek Nederland (CB-NL) is een soort digitaal woordenboek
>   voor de bouw, eenvoudig bruikbaar voor elke gebruiker. De CB-NL is een
>   digitale beschrijving van generieke, herbruikbare concepten (typen of
>   soorten), die betrekking hebben op onder meer fysieke gebouwde objecten, de
>   gebruiksruimten en –gebieden en ruimtelijke omgeving. De beschrijving geldt
>   bovendien gedurende de hele levenscyclus.

**I3. (Meta)data bevatten gekwalificeerde verwijzingen naar andere (meta)data**

In het DSGO is de **metadataredacteur** verantwoordelijk voor aanmaken metadata
van een dataset, en voert wijzigingen door in de metadata. De metadata voldoet
aan de gestelde kwaliteitseisen (o.m. actueel, juist en volledig).

### Herbruikbaar

Het uiteindelijke doel van FAIR is het hergebruik van data te optimaliseren. Om
dit te bereiken moeten metadata en data goed worden beschreven, zodat ze in
verschillende situaties kunnen worden gerepliceerd en/of gecombineerd. Denk
daarbij aan de basisregistraties en landelijke voorzieningen.

**R1. (Meta)data zijn rijkelijk beschreven met groot aantal nauwkeurige en
relevante attributen**

Het DSGO sluit aan op de [Wet Kwaliteitsborging voor het Bouwen](#section).
Onderdeel van deze wet is het *dossier bevoegd gezag*.

Op dit moment is de opdrachtgever verantwoordelijk voor de bouwkwaliteit van een
object bij overhandiging van de sleutel. De Wet Kwaliteitsborging (WKB) is erop
gericht om bouwkwaliteit te verbeteren, door de bewijslast van geleverde
kwaliteit bij de aannemer te beleggen. Deze dient dat vast te leggen in
het *dossier bevoegd gezag*, waarbij de data die voor dit dossier benodigd is
door alle ketenpartners aangeleverd moet worden. Dit digitale bouwdossier bevat
informatie over het gerealiseerde bouwwerk en de verklaring van de
kwaliteitsborger dat het gerealiseerde bouwwerk voldoet aan de bouwtechnische
vereisten van het Bouwbesluit. Het op orde hebben van dit dossier, gaat op
termijn een voorwaarde worden voor gunning van een opdracht.

Het verkrijgen van deze data is op dit moment een tijdrovend en kostbaar karwei.
De data liggen bij een groot aantal partijen en is niet gestandaardiseerd en/of
automatisch verkrijgbaar. Door uniforme afspraken faciliteert het DSGO het
toegankelijk maken van alle gebouw gerelateerde data op een eenvoudige, veilige
en gecontroleerde manier. Dit heeft een aantal voordelen:

• Risico’s worden teruggedrongen

• Besparing van tijd en kosten voor delen van data

• Makkelijker om te voldoen aan WKB

• Verhogen van kwaliteit

• Verhogen van veiligheid

**R2. (Meta)data worden vrijgegeven met een duidelijke en toegankelijke
datagebruikslicentie**

In het DSGO worden met een datagebruikslicentie voorwaarden oplegd wie welke
gegevens voor welke doel mag gebruiken.

Wie (geo-)informatie van een ander gebruikt, moet weten of daarvoor voorwaarden
gelden en zo ja welke voorwaarden dat zijn. De Nederlandse overheid wil
overheidsinformatie zoveel mogelijk gratis en zonder gebruiksvoorwaarden
beschikbaar stellen. In de bouwwereld wordt veel geïnvesteerd in
objectenbibliotheek waar ontwikkelende marktpartijen het exclusieve
gebruiksrecht op willen behouden.

**R3. (Meta)data worden geassocieerd met hun herkomst**

**R4. (Meta)data voldoen aan domein-relevante Standaarden**

Standaarden zijn de afsprakenstelsels van domeinen die specificaties en eisen
aan de (meta)data beschrijven. De standaarden voor (meta)data(sets) in het DSGO
worden in de domeinen beheerd en doorontwikkeld.
