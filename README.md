# Metadata model for digital intake
***Work In Progress!***

This guide gives the Content Partners (CPs) of VIAA more insight how metadata is structured inside VIAAs MAM and how they should deliver metadata for digital intake. CPs that have  borndigital or digitised material will need to deliver metadata about these essences. This is done by supplying a sidecar XML for every essence, e.g. test.xml + test.mxf. VIAAs ingest proces expects metadata that is already mapped to the VIAA metadata model that is explained below. In future work we would like to support standards like Dublin Core. If you have remarks, questions... let us know at support@viaa.be!

Here you can find a XSD to validate your mapping, examples and explanation of all the metadata fields.

## Validation

You can validate your mapped metadata with our XSD `viaa_metadatamodel_xsd.xsd`.
An easy way to do this is with xmllint, which is part of [libxml](http://xmlsoft.org/).
Open a Terminal and run following command:

```bash
xmllint --noout --schema viaa_metadatamodel_xsd.xsd YOUR_XML_FILE
```

## Full metadata example

See `viaa_metadatamodel_voorbeeld.xml` for a full metadata XML.

## Metadata model

We'll seperate this in two parts.
The first part is for metadata that needs to be filled in by the content provider.
Second part is metadata that is added by VIAA.

### For Content Partners

#### Algemeen

##### Hoofd lokale CP ID 
Dit is de unieke ID die gebruikt zal worden om metadata voor born digital bestanden te reconciliëren.  
```xml
<dc_identifier_localid>id_123</dc_identifier_localid>
```

##### Overige lokale CP ID
Overige belangrijke identifiers zoals URIs, link naar API, bestandsnaam etc. 
```xml
<dc_identifier_localids type=”list”>
    <api>http://api.example.org/id/123</api>
    <uri>http://example.org/123</uri>
    <reproduction.reference>audiocassette_420</reproduction.reference>
  </dc_identifier_localids>
```

#### Titels

##### Hoofdtitel
Algemene benaming of hoofdtitel gebruikt om naar een bepaald item te zoeken. Het gaat hier om een nette titel die op externe platformen als zoektoegang zal worden gebruikt.
```xml
<dc_title>Alaska: Eskimo’s</dc_title>
```

##### Alternatief
De alternatieve titel. Dit is een alternatieve benaming voor het item. Een alternatieve titel kan ook een archieftitel of een vertaling van de titel zijn.
```xml
<dc_titles type=”list”> <alternatief/>
</dc_titles>
```

##### Registratie
Dit is de registratie-titel zoals ingegeven in AMS.
```xml
<dc_titles type=”list”> <registratie/>
</dc_titles>
```

##### Archief
Het hoogste beschrijvingsniveau: het archief waar het object deel van uitmaakt.
```xml
<dc_titles type=”list”>
<archief>Archief Gezinsbond</archief>
</dc_titles
```

##### Deelarchief
Een deel van een archief dat bestaat uit een geheel van onderling gerelateerde archiefstukken
```xml
<dc_titles type=”list”> <deelarchief/>
</dc_titles>
```

##### Reeks
Het hoogste beschrijvingsniveau: het archief waar het object deel van uitmaakt.
```xml
<dc_titles type=”list”>
<archief>Archief Gezinsbond</archief>
</dc_titles>
```

##### Archief
Documenten gerangschikt volgens een ordeningsplan of beheerd als een eenheid omdat ze het resultaat zijn van een zelfde proces van archiefvorming of opslag, of van eenzelfde activiteit, of omdat ze een bepaalde vorm hebben, of wegens enige andere samenhang die voort- komt uit creatie, ontvangst of gebruik.
```xml
<dc_titles type=”list”> <reeks/>
</dc_titles>
```

##### Serie
De serietitel. Dit is de titel van de serie waar het item deel van uit- maakt.
```xml
<dc_titles type=”list”>
<serie>Het Journaal</serie>
</dc_titles>
```

##### Serienummer
Het nummer van de serie waarvan het item deel uitmaakt.
```xml
<dc_titles type=”list”> <serienummer/>
</dc_titles>
```

##### Seizoen
Het seizoen/jaargang waarvan het item deel uitmaakt.
```xml
<dc_titles type=”list”> <seizoen>
</dc_titles>
```

##### Seizoennummer
Het nummer van het seizoen waarvan het item deel uitmaakt.
```xml
<dc_titles type=”list”> <seizoennummer>
</dc_titles>
```

##### Programma
De programmatitel. Dit is de titel van het programma waarvan het item deel uitmaakt.
```xml
<dc_titles type=”list”> <programma/>
</dc_titles>
```


#### Datum


##### Datum creatie
De datum waarop de intellectuele inhoud van het item werd gecreeerd.
```xml
<dcterms_created/>
```

##### Datum uitgave / uitzending
De datum waarop het item is uitgegeven of uitgezonden.
```xml
<dcterms_issued/>
```

#### Productie	27

##### Maker
De persoon of instelling die (in hoofdzaak) verantwoordelijk is voor de creatie van de inhoud van het item.
```xml
<dc_creators type=”list”> <maker/>
<regisseur/> <archiefvormer/>
</dc_creators>
```

##### Bijdrager
De persoon of instelling die een substantiële creatieve bijdrage tot de intellectuele inhoud van het item heeft geleverd.
```xml
<dc_contributors type=”list”> <bijdrager/>
<geluidsman/> <pianist/>
</dc_contributors>
```

##### Publisher
De entiteit in hoofdzaak verantwoordelijk voor het verdelen en het toegankelijk maken van een item voor derden door omroep, verkoop, verhuur,...
```xml
<dc_publishers type=list/> <publisher/>
<omroep/> <distributeur/> <persagentschap/> ...
</dc_publishers>
```

#### Inhoud

##### Hoofdbeschrijving
Een korte, algemene omschrijving van de intellectuele inhoud van het item.
```xml
<description/>
```

##### Lange beschrijving
Een gedetailleerde beschrijving van de inhoud van het item. Dit kan bijvoorbeeld door puntsgewijs de voornaamste scènes, stockshorts,... te beschrijven. Voor ondertitels is evenwel een apart veld voorzien.
```xml
<dc_description_long/>
```

##### Programmabeschrijving
Een korte beschrijving van het programma waar het item een onderdeel van vormt.
```xml
<dc_description_programme/>
```

##### Rolverdeling
Een oplijsting van de voornaamste acteurs/performers en hun respectievelijke rol.
```xml
<dc_description_cast/>
```

* Ondertitels	31

##### Ondertitels
Een weergave van de ondertitels die bij het digitale object horen.
```xml
<dc_description_ondertitels/>
```

* Transcriptie	31

##### Transcriptie
Een weergave van de transcriptie van het digitale object.
```xml
<dc_description_transcriptie/>
```

* Genre	32

##### Genre
Omschrijving van de aard, het genre of het doelpubliek van het item.
```xml
<dc_types type=”list”> <genre/>
</dc_types>
```

* Coverage (ruimtelijk)	32

##### Coverage (ruimtelijk)
Een beschrijvende a akening van het geogra sch gebied (straat, stad, land, continent) waar de inhoud van het item betrekking op heeft.
```xml
<dc_coverages type=”list”> <ruimte/>
</dc_coverages>
```

* Coverage (tijd)	33

##### Coverage (tijd)
Een beschrijvende a akening van de tijdsperiode waar de inhoud van het item betrekking op heeft.
```xml
<dc_coverages type=”list”> <tijd/>
</dc_coverages>
```

* Trefwoorden	33
* Taal	34

####	Rechten	35
* Licentie	35
* Auteursrechthouder	36
* Licentiehouder	36
* Credit	37
* Gebruiksbeperking 1	37
* Opmerkingen rechten

### For VIAA

#### Algemeen
* CP	14
* Content Partner (CP)	14
* Content Partner ID	14
* PID

#### Relaties
* (Dit digitaal object) is deel van	17
* (Dit digitaal object) bevat	17
* (Dit digitaal object) is verwant aan
