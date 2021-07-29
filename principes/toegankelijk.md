Toegankelijk
============

Zodra de gebruiker de benodigde gegevens heeft gevonden bih een of meerdere
databronnen, moet hij/zij weten hoe deze kunnen worden geraadpleegd en kan
worden toegepast, mogelijk inclusief authenticatie en autorisatie.

Samenvatting
------------

In het kader van toegankelijkheid van de data adviseren we de volgende
uitgangspunten, randvoorwaarden en eisen.

**Uitgangspunten**

-   ..

-   ..

**Randvoorwaarden**

-   ..

-   ..

**Eisen**

-   ..

-   ..

(Meta)gegevens kunnen worden opgehaald door hun identifier met behulp van een gestandaardiseerd communicatieprotocol
--------------------------------------------------------------------------------------------------------------------

*Samenbrengen van gegevens vanuit basisregistraties als BGT en BAG. Ook Digitaal
Stelsel Omgevingswet voor de ruimtelijke besluiten als een omgevingsplan (nu
conform de Wro: bestemmingsplan).*

*UOI*

*Verschil tussen diensten en projectdossier beschrijven*

### Het protocol is open, gratis en universeel toepasbaar

Is Linked Open Data hèt protocol voor het DSGO? Zeker bij het koppelen van
heterogene datasets, waarbij data bij de bron opvraagbaar is?

Protocol: JSON-LD, GraphQL,

>   **Linked open data (copy Wikipedia:
>   https://nl.wikipedia.org/wiki/Linked_data)**

>   In 2009 sprak de pionier van het worldwide web, [Tim
>   Berners-Lee](https://nl.wikipedia.org/wiki/Tim_Berners-Lee), op
>   de [TED](https://nl.wikipedia.org/wiki/TED_(conferentie))-conferentie over
>   linked data als de volgende fase op internet, soms ook wel [Web
>   3.0](https://nl.wikipedia.org/wiki/Web_3.0) genoemd.[[3]](https://nl.wikipedia.org/wiki/Linked_data#cite_note-3)[[4]](https://nl.wikipedia.org/wiki/Linked_data#cite_note-4) Linked
>   open data is een community-project dat onder toezicht staat van
>   de [W3C](https://nl.wikipedia.org/wiki/World_Wide_Web_Consortium)-organisatie
>   en heeft als doel het internet te verrijken door open datasets nog beter te
>   ontsluiten via de linked-datamethode. Dit ontsluiten wordt voorgesteld als
>   een [wolk van gekoppelde
>   datasets](https://nl.wikipedia.org/wiki/Linking_Open_Data-wolkdiagram).[[5]](https://nl.wikipedia.org/wiki/Linked_data#cite_note-5),
>   ook wel
>   een [kennisgrafiek](https://nl.wikipedia.org/w/index.php?title=Kennisgrafiek&action=edit&redlink=1) (*knowledge
>   graph*) genoemd.

>   Berners-Lee beschrijft vier ontwerpprincipes voor linked (open) data:

>   Gebruik URI's als namen voor gegevens ('dingen')

>   Gebruik HTTP URI's zodat gebruikers deze kunnen opzoeken

>   Als een gebruiker een URI opzoekt dient deze URI bruikbare informatie te
>   geven, waarbij gebruik gemaakt wordt van de
>   standaarden [RDF](https://nl.wikipedia.org/wiki/RDFS) en [SPARQL](https://nl.wikipedia.org/wiki/SPARQL)

>   Voeg links naar andere URI's toe zodat gebruikers meer gegevens kunnen
>   vinden

>   Bij linked data
>   is [metadata](https://nl.wikipedia.org/wiki/Metadata) (semantiek) essentieel
>   voor de gebruiker. Hierbij wordt gebruik gemaakt van de principes
>   van [FAIR-data](https://nl.wikipedia.org/wiki/FAIR-principes).

>   Vijfsterrenmodel

>   Om partijen die open data publiceren te stimuleren om hun data in een zo
>   herbruikbaar mogelijk formaat beschikbaar te stellen, heeft Berners-Lee een
>   vijfsterrenmodel voorgesteld. Hierbij worden de volgende sterren toegekend:

>   Eén ster: De informatie is beschikbaar op het internet, in welk formaat dan
>   ook (b.v. PDF).

>   Twee sterren: De informatie is online beschikbaar in een gestructureerd
>   formaat, dat geschikt is voor geautomatiseerd hergebruik (zoals Excel in
>   plaats van een plaatje van een tabel).

>   Drie sterren: De informatie is online beschikbaar in een open
>   bestandsformaat (zoals CSV in plaats van Excel).

>   Vier sterren: Al het bovenstaande, en bovendien wordt gebruikgemaakt van de
>   open standaarden [Resource Description
>   Framework](https://nl.wikipedia.org/wiki/Resource_Description_Framework) (RDF)
>   en [SPARQL](https://nl.wikipedia.org/wiki/SPARQL), zodat anderen makkelijk
>   naar de dataobjecten kunnen verwijzen.

>   Vijf sterren: Al het bovenstaande, en bovendien wordt er naar data van
>   anderen verwezen voor meer context van de data
>   ([metadata](https://nl.wikipedia.org/wiki/Metadata)).

### Het protocol maakt een authenticatie- en autorisatieprocedure mogelijk, waar nodig

In geval Linked Data:

>   Authenticatie: [foaf+ssl](https://www.w3.org/wiki/Foaf%2Bssl) uses
>   a WebID and **LinkedData** to create a web of trust authentication
>   architecture

>   Autorisatie: [Authorization Capabilities for Linked Data
>   v0.3](https://w3c-ccg.github.io/zcap-ld/)

CHECK: Navragen bij Linda naar de mogelijkheden voor DSGO?

Metadata zijn toegankelijk, ook als de data niet meer beschikbaar zijn
----------------------------------------------------------------------

De UOI is de sleutel naar het Dossier van een Object dat middels de UOI wordt
geidentificeerd.

Data kan niet meer beschikbaar zijn om verschillende redenen:

-   Gegevens zijn verwijderd.

-   Gebruiker is niet meer geautoriseerd.

-   Database bronhouder is offline…

Uitgangspunt?: DSGO houdt historie vast, dus data blijft altijd beschikbaar.

Hoe past dit bij databij de bron: architect failliet?

In geval van gegevens zijn verwijderd (komt bij geobasisregistraties niet voor),
dan metadata over data wel beschikbaar? Wat voegt dat toe?

Als gebruiker niet meer geautoriseerd zijn,
