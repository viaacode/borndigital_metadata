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
* Hoofdtitel 
Algemene benaming of hoofdtitel gebruikt om naar een bepaald item te zoeken. Het gaat hier om een nette titel die op externe platformen als zoektoegang zal worden gebruikt.
```xml
<dc_title>Alaska: Eskimo’s</dc_title>
```

* Alternatief

* Registratie	20
* Archief	21
* Deelarchief	21
* Reeks	21
* Deelreeks	22
* Serie	22
* Serienummer	23
* Seizoen	23
* Seizoennummer	24
* Programma	24

#### Datum	25
* Datum creatie	25
* Datum uitgave / uitzending	26

#### Productie	27
* Maker	27
* Bijdrager	27
* Publisher	28

#### Inhoud
* Hoofdbeschrijving	29
* Lange beschrijving	30
* Programmabeschrijving	30
* Rolverdeling	31
* Ondertitels	31
* Transcriptie	31
* Genre	32
* Coverage (ruimtelijk)	32
* Coverage (tijd)	33
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
