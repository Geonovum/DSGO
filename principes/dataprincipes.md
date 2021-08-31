Data principes
==============

Het data aanbod en de data vraag op elkaar aansluiten is voor het DGSO niet
eenvoudig, omdat er zeer veel organisaties in de sector actief zijn met veel
verschillende soorten data en -behoeftes. Het gebrek aan beschikbaar hebben van
de juiste data op de juiste plek is niet alleen een uitdaging om
stikstofreductie doelen te halen maar is noodzakelijk voor alle maatschappelijke
en/of sector-overstijgende doelen.

FAIR-principes
--------------

### Vindbaar

Actuele data over beheer, onderhoud en gebruik van vastgoedportefeuilles ligt momenteel versnipperd bij een groot aantal partijen en kost tijd en geld om te verkrijgen. DSGO voorziet in het ophalen van data die verspreid ligt over een groot aantal partijen. Hierdoor kunnen vastgoedbeheerders op een eenvoudige, veilige en gecontroleerde manier toegang krijgen tot de gebouwdata van hun vastgoedportefeuille, waaronder de werkelijke uitstoot van stikstof, gedurende de levensfase van gebouwen.

De eerste stap bij het ophalen van data en het (her)gebruiken van data is om de data te vinden. Metadata
en data moeten gemakkelijk vindbaar zijn voor zowel mensen als computers.
Machine-readable metadata zijn essentieel voor het ontdekken van datasets en
services.

Bekendheid: Vindbaar begint met bekendheid om te weten dat data gevonden kan
worden. DSGO moet op de hoogte zijn van de van de vindplaats en door de data en in contact staan met de eigenaar van de data. 

| FAIR-Principe                                                                                 | Toepassing op DSGO                                                                                                                                                                                                                                                                   |
|-----------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| F1. Objecten krijgen een wereldwijd unieke en persistente identifier                        | Deze ([UOI](#unieke-object-identificatie)) is onderdeel van de (Meta)data bij ieder fysiek object binnen het DSGO welke geldig blijft tijdens de hele levenscyclus van het object                                                                                                                    |
| F2. Data en datasets worden beschreven met uitgebreide metadata                                       | Van elke dataset in het DSGO is meta-informatie over onder meer de herkomst, kwaliteit en gebruiksrechten (licentie + toepassing) beschikbaar. De wijze van metadatering sluit aan bij vigerende (inter)nationale standaarden voor metadata.                                                  |
| F3. Metadata bevatten duidelijk en expliciet de identifier van de data die ze beschrijven | Data en datasets moeten kunnen worden gevonden op basis van de UOI’s van de objecten die ze beschrijven |
| F4. (Meta)data worden geregistreerd of geïndexeerd in een doorzoekbare bron                   | Het DSGO heeft een [catalogusfunctie](#dsgo-als-catalogus) met gedistribueerde data(sets) over de gebouwde omgeving                                                                                                                                                                            |

**Unieke object identificatie**

UOI zou moeten zijn UGI: Unieke Gegeven Identificatie, gegeven eis over
‘Metadata bevatten duidelijk en expliciet de identifier van de gegeven(s) die ze
beschrijven’.

Het [Unieke Object Identificator
(UOI)](https://www.geonovum.nl/over-geonovum/actueel/onderzoek-unieke-object-identificatie-en-omgevingsinformatie) ‘systeem’
is een digitale sleutel waarmee je op basis van je rol en toegangsrechten
informatie over gebouwen en objecten in de gebouwde omgeving kunt raadplegen.
Het ‘systeem’ als gedachte is ontwikkeld binnen de bouw- en vastgoedsector. De
gedachte achter een UOI-code is dat er domein-overstijgend verbindingen mee
gelegd kunnen worden die het beantwoorden van vragen over objecten in de
gebouwde omgeving vereenvoudigen. De UOI-code wordt ook genoemd in de lopende
consultatie van de [Samenhangende Objecten Registratie
(SOR)](https://www.geobasisregistraties.nl/basisregistraties/doorontwikkeling-in-samenhang/objectenregistratie).
Experts uit de bouw- en geo-wereld hebben het UOI als systeem getoetst aan de
nieuwe Geo- & Bouw-informatiestandaarden (NEN 3610, NEN 2660 en BIM gerelateerde
standaarden) en de [principes die DiSGeo
hanteert](https://docs.geostandaarden.nl/disgeo/emso/#identificatie-van-objecten) voor
de Samenhangende Objecten Registratie (SOR). Ook is gekeken naar de instrumenten
van de Wet kwaliteitsborging Bouw (Wkb) en het ontwerp Digitaal Stelsel Gebouwde
Omgeving DSGO (binnen DigiGo).

*Noot van de schrijvers: Tussen november 2020 en april 2021 heeft het ministerie
van BZK onderzoek laten doen naar het ontwerp van een Unieke Object
Identificatie (UOI). Vraag aan Geonovum was de UOI te verkennen in relatie tot
standaarden in de bouw- en geo-sector en de ontwikkelingen rond
objectidentificatie in de fysieke leefomgeving. Ten tijde van het schrijven dit
rapport is er een concept onderzoeksrapport over UOI.*

**DSGO en de catalogusfunctie**

Het DSGO fungeert als doorzoekbare catalogus c.q. register met datasets over de
Gebouwde Omgeving, bijvoorbeeld Gebouwdossier, Energielabels,
geobasisregistraties.

Door de catalogus c.q. registerfunctie van het DSGO zijn de datasets vindbaar. 
Het DSGO als catalogus c.q. register van datasets over de gebouwde omgeving
sluit aan bij principe van ‘data bij de bron’. De dataset zelf wordt niet
aangeleverd aan ofwel gekopiëerd in DSGO; er worden wel gegevens over de
data(set) (ofwel: metadata) aan het DSGO aangeleverd. Over deze metadata van
data(sets) wordt metadata vastgelegd, bijvoorbeeld data over de herkomst en
actualiteit van de metadata over de data(set). Register voor datasets in het DSGO in een metadata-register à la [Nationaal Geo
Register](https://nationaalgeoregister.nl/) (NGR).

Bijvoorbeeld:
De Basisregistratie Adressen en Gebouwen (BAG) is de authentieke bron voor
officiële adressen en bouwjaren van panden. De ‘eigenaar’ van de BAG draagt
gegevens aan over de dataset BAG aan het DSGO ondermeer over de herkomst,
kwaliteit (bijvoorbeeld actualiteit 4 dagen, geometrische nauwkeurigheid van
30-60 cm, volledigheid 100%) en gebruik (wettelijk verplicht voor overheden) van
de data in de BAG. In het DSGO wordt vastgelegd de herkomst (eigenaar BAG) en
kwaliteit (wanneer metadata voor het laatst is bijgewerkt) over de BAG
vastgelegd.

### Toegankelijk

Zodra de gebruiker de benodigde gegevens heeft gevonden bij een of meerdere
databronnen, moet hij/zij weten hoe deze kunnen worden geraadpleegd en kan
worden toegepast, mogelijk inclusief authenticatie en autorisatie voor veilige, betrouwbare en gecontroleerde toegang tot data.

| FAIR-Principe                                                                                                            | Toepassing op DSGO                                                                                                                                                                                                                                          |
|--------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A1. (Meta)gegevens kunnen worden opgehaald door hun identifier met behulp van een gestandaardiseerd communicatieprotocol | *Samenbrengen van gegevens vanuit basisregistraties als BGT en BAG. Ook Digitaal Stelsel Omgevingswet voor de ruimtelijke besluiten als een omgevingsplan (nu conform de Wro: bestemmingsplan). UOI Verschil tussen diensten en projectdossier beschrijven* |
| A1.1 Het protocol is open, gratis en universeel toepasbaar                                                               | De gegevens in de data(sets) die in de catalogus DSGO zijn met een open protocol gratis protocol bij de bron toegankelijk. Bijvoorbeeld met [Linked Data](#koppelen-van-heterogene-datasets-met-linked-data).                                               |
| A1.2 Het protocol maakt een authenticatie- en autorisatieprocedure mogelijk, waar nodig                                  |                                                                                                                                                                                                                                                             |
| A2. Metadata zijn toegankelijk, ook als de data niet meer beschikbaar zijn                                               | De UOI is de sleutel naar het Dossier van een Object (data of datasets?) dat middels de UOI wordt geidentificeerd.                                                                                                                                          |

#### Koppelen van heterogene datasets met Linked Data

Is Linked Open Data hèt protocol voor het DSGO? Zeker bij het koppelen van
heterogene datasets, waarbij data bij de bron opvraagbaar is?

Protocol: JSON-LD, GraphQL,

*Linked open data (copy
Wikipedia: *<https://nl.wikipedia.org/wiki/Linked_data>*)*

*In 2009 sprak de pionier van het worldwide web, *[Tim
Berners-Lee](https://nl.wikipedia.org/wiki/Tim_Berners-Lee)*, op
de *[TED](https://nl.wikipedia.org/wiki/TED_(conferentie))*-conferentie over
linked data als de volgende fase op internet, soms ook wel *[Web
3.0](https://nl.wikipedia.org/wiki/Web_3.0)* genoemd.*[[3]](https://nl.wikipedia.org/wiki/Linked_data#cite_note-3)[[4]](https://nl.wikipedia.org/wiki/Linked_data#cite_note-4)* Linked
open data is een community-project dat onder toezicht staat van
de *[W3C](https://nl.wikipedia.org/wiki/World_Wide_Web_Consortium)*-organisatie
en heeft als doel het internet te verrijken door open datasets nog beter te
ontsluiten via de linked-datamethode. Dit ontsluiten wordt voorgesteld als
een *[wolk van gekoppelde
datasets](https://nl.wikipedia.org/wiki/Linking_Open_Data-wolkdiagram)*.*[[5]](https://nl.wikipedia.org/wiki/Linked_data#cite_note-5)*,
ook wel
een *[kennisgrafiek](https://nl.wikipedia.org/w/index.php?title=Kennisgrafiek&action=edit&redlink=1)* (knowledge
graph) genoemd.*

*Berners-Lee beschrijft vier ontwerpprincipes voor linked (open) data:*

*Gebruik URI's als namen voor gegevens ('dingen')*

*Gebruik HTTP URI's zodat gebruikers deze kunnen opzoeken*

*Als een gebruiker een URI opzoekt dient deze URI bruikbare informatie te geven,
waarbij gebruik gemaakt wordt van de
standaarden *[RDF](https://nl.wikipedia.org/wiki/RDFS)* en *[SPARQL](https://nl.wikipedia.org/wiki/SPARQL)

*Voeg links naar andere URI's toe zodat gebruikers meer gegevens kunnen vinden*

*Bij linked data
is *[metadata](https://nl.wikipedia.org/wiki/Metadata)* (semantiek) essentieel
voor de gebruiker. Hierbij wordt gebruik gemaakt van de principes
van *[FAIR-data](https://nl.wikipedia.org/wiki/FAIR-principes)*.*

*Vijfsterrenmodel*

*Om partijen die open data publiceren te stimuleren om hun data in een zo
herbruikbaar mogelijk formaat beschikbaar te stellen, heeft Berners-Lee een
vijfsterrenmodel voorgesteld. Hierbij worden de volgende sterren toegekend:*

*Eén ster: De informatie is beschikbaar op het internet, in welk formaat dan ook
(b.v. PDF).*

*Twee sterren: De informatie is online beschikbaar in een gestructureerd
formaat, dat geschikt is voor geautomatiseerd hergebruik (zoals Excel in plaats
van een plaatje van een tabel).*

*Drie sterren: De informatie is online beschikbaar in een open bestandsformaat
(zoals CSV in plaats van Excel).*

*Vier sterren: Al het bovenstaande, en bovendien wordt gebruikgemaakt van de
open standaarden *[Resource Description
Framework](https://nl.wikipedia.org/wiki/Resource_Description_Framework)* (RDF)
en *[SPARQL](https://nl.wikipedia.org/wiki/SPARQL)*, zodat anderen makkelijk
naar de dataobjecten kunnen verwijzen.*

*Vijf sterren: Al het bovenstaande, en bovendien wordt er naar data van anderen
verwezen voor meer context van de data
(*[metadata](https://nl.wikipedia.org/wiki/Metadata)*).*

#### Authenticatie en autorisatie met Linked Data

Authenticatie: foaf+ssl uses a WebID and LinkedData to create a web of trust
authentication architecture

Autorisatie: Authorization Capabilities for Linked Data v0.3

*CHECK: Navragen bij Linda naar de mogelijkheden voor DSGO?*

#### Historie in DSGO?

Data kan niet meer beschikbaar zijn om verschillende redenen:

-   Gegevens zijn verwijderd.

-   Gebruiker is niet meer geautoriseerd.

-   Database bronhouder is offline…

Uitgangspunt?: DSGO houdt historie vast, dus (meta)data blijft altijd
beschikbaar.

Hoe past dit bij databij de bron: architect failliet?

In geval van gegevens zijn verwijderd (komt bij geobasisregistraties niet
voor!), dan metadata over data wel beschikbaar? Wat voegt dat toe?

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

| FAIR-Principe                                                                                                    | Toepassing op DSGO                                                                                                         |
|------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| I1. (Meta)data gebruiken een formele, toegankelijke, gedeelde en breed toepasbare taal voor kennisrepresentatie. | In het DSGO worden voor de beschrijving van de datasets (metadata) en de data van datasets zelf open standaarden gebruikt. |
| I2. (Meta)data gebruiken vocabulaires die FAIR-principes volgen                                                  | *Aansluiten op concepten CB-NL*                                                                                            |
| I3. (Meta)data bevatten gekwalificeerde verwijzingen naar andere (meta)data                                      |                                                                                                                            |

#### Open standaarden

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

#### Domein overstijgende uitwisseling van data. 

als verschillende domeinen data willen uitwisselen, dan is er vaak sprake van
verschil in definities en begrippen. Dit verschil in semantiek kan overbrugt
worden door gebruik te maken van een bovenliggende identifier die in beide
domeinen wordt toegepast. De UOI biedt in dat geval uitkomst om data van het ene
domein te combineren met data van het andere domein. Voorbeelden van
overstijgende domeinen zijn: het geodomein waaronder de geo-basisregistraties,
het energiedomein, ....

### Herbruikbaar

Het uiteindelijke doel van FAIR is het hergebruik van data te optimaliseren. Om
dit te bereiken moeten metadata en data goed worden beschreven, zodat ze in
verschillende situaties kunnen worden gerepliceerd en/of gecombineerd. Denk
daarbij aan de basisregistraties en landelijke voorzieningen.

| FAIR-Principe                                                                                 | Toepassing op DSGO                                                                                                                                      |
|-----------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| R1. (Meta)data zijn rijkelijk beschreven met groot aantal nauwkeurige en relevante attributen | Sluit aan op de [Wet Kwaliteitsborging voor het Bouwen](#wet-kwaliteitsborging-voor-het-bouwen). Onderdeel van deze wet is het *dossier bevoegd gezag*. |
| R2. (Meta)data worden vrijgegeven met een duidelijke en toegankelijke datagebruikslicentie    |                                                                                                                                                         |
| R3. (Meta)data worden geassocieerd met hun herkomst                                           |                                                                                                                                                         |
| R4. (Meta)data voldoen aan domein-relevante Standaarden                                       |                                                                                                                                                         |

#### Wet Kwaliteitsborging voor het Bouwen

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
