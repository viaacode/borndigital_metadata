## 1. Inhoud

[[TOC]]

## 2. Tabel basisannotatie VIAA datamodel

### 1. Administratieve en beschrijvende metadata

<table>
  <tr>
    <td></td>
    <td>Veldnaam</td>
    <td>Herkomst metadata born digital</td>
    <td>Herkomst metadata digitalisatie</td>
    <td>V/O</td>
    <td>Mapping</td>
  </tr>
  <tr>
    <td>ALGEMEEN</td>
    <td>CP naam</td>
    <td>Automatisch</td>
    <td>Automatisch</td>
    <td>V</td>
    <td>/</td>
  </tr>
  <tr>
    <td></td>
    <td>CP ID</td>
    <td>Automatisch</td>
    <td>AMS</td>
    <td>V</td>
    <td>/</td>
  </tr>
  <tr>
    <td></td>
    <td>PID</td>
    <td>Automatisch</td>
    <td>Automatisch</td>
    <td>V</td>
    <td>dc:identifier
ebucore:identifier
pbcore:pbcoreIdentifier</td>
  </tr>
  <tr>
    <td></td>
    <td>Hoofd lokale CP ID</td>
    <td>Manueel / mapping</td>
    <td>AMS</td>
    <td>V</td>
    <td>dc:identifier
ebucore:identifier
pbcore:pbcoreIdentifier</td>
  </tr>
  <tr>
    <td>TITEL</td>
    <td>Hoofdtitel</td>
    <td>Manueel / mapping</td>
    <td>AMS</td>
    <td>V</td>
    <td>dc:title
ebucore:title/dc:title
pbcore:pbcoreTitle/title</td>
  </tr>
  <tr>
    <td>DATUM</td>
    <td>Datum creatie</td>
    <td>Manueel / mapping</td>
    <td>AMS</td>
    <td>V</td>
    <td>dcterms:created
ebucore:date/created/@*</td>
  </tr>
  <tr>
    <td>PRODUCTIE</td>
    <td>Maker</td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>VA</td>
    <td>dc:creator
ebucore:creator
pbcore:pbcoreCreator/creator</td>
  </tr>
  <tr>
    <td>INHOUD</td>
    <td>Hoofdbeschrijving</td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>V*</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td></td>
    <td>Trefwoorden</td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>V*</td>
    <td>dc:subject
ebucore:subject/dc:subject
pbcore:pbcoreSubject</td>
  </tr>
  <tr>
    <td></td>
    <td>Taal</td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>V</td>
    <td>dc:language
ebucore:language
pbcore:pbcoreInstantiation/instantiationLanguage</td>
  </tr>
  <tr>
    <td>RECHTEN</td>
    <td>Licentie</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>V</td>
    <td>dc:rights
dc:license
odrl:permission
odrl:policy
premis:copyrightStatus
premis:rightsStatement/licenseInformation/licenseIdentifier/licenseIdentifierValue</td>
  </tr>
  <tr>
    <td></td>
    <td>Auteursrechthouder</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>V</td>
    <td>dc:rightsHolder
premis:linkingAgentIdentifier
plus:CopyrightOwnerName</td>
  </tr>
</table>


<b>3. Tabel uitgebreide annotatie VIAA datamodel</b>


<table>
  <tr>
    <td></td>
    <td>Veldnaam</td>
    <td></td>
    <td>Herkomst metadata born digital</td>
    <td>Herkomst metadata digitalisatie</td>
    <td>V/O</td>
    <td>Mapping</td>
  </tr>
  <tr>
    <td>ALGEMEEN</td>
    <td>CP naam</td>
    <td></td>
    <td>Automatisch</td>
    <td>Automatisch</td>
    <td>V</td>
    <td>/</td>
  </tr>
  <tr>
    <td></td>
    <td>CP ID</td>
    <td></td>
    <td>Automatisch</td>
    <td>AMS</td>
    <td>V</td>
    <td>/</td>
  </tr>
  <tr>
    <td></td>
    <td>PID</td>
    <td></td>
    <td>Automatisch</td>
    <td>Automatisch</td>
    <td>V</td>
    <td>dc:identifier
ebucore:identifier
pbcore:pbcoreIdentifier</td>
  </tr>
  <tr>
    <td></td>
    <td>Hoofd lokale CP ID 
</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>AMS</td>
    <td>VA</td>
    <td>dc:identifier
ebucore:identifier
pbcore:pbcoreIdentifier</td>
  </tr>
  <tr>
    <td></td>
    <td>Overige lokale CP ID</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dc:identifier
ebucore:identifier
pbcore:pbcoreIdentifier</td>
  </tr>
  <tr>
    <td>RELATIES 
dit digitaal object …</td>
    <td>is deel van
</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dcterms:isPartOf
ebucore:part</td>
  </tr>
  <tr>
    <td></td>
    <td>Bevat</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dcterms:hasPart
ebucore:hasPart</td>
  </tr>
  <tr>
    <td></td>
    <td>is verwant aan</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dc:relation</td>
  </tr>
  <tr>
    <td>TITEL</td>
    <td>Hoofdtitel</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>AMS</td>
    <td>V</td>
    <td>dc:title
ebucore:title/dc:title
pbcore:pbcoreTitle/title</td>
  </tr>
  <tr>
    <td></td>
    <td>SECONDAIRE  TITEL</td>
    <td>   Alternatieve 
   Titel</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td></td>
    <td>
</td>
    <td>   Archief</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>ISAD(G):archief</td>
  </tr>
  <tr>
    <td></td>
    <td>
</td>
    <td>   Deelarchief</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>ISAD(G):deelarchief</td>
  </tr>
  <tr>
    <td></td>
    <td>
</td>
    <td>   Reeks</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>ISAD(G):reeks</td>
  </tr>
  <tr>
    <td></td>
    <td>
</td>
    <td>   Deelreeks</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>ISAD(G):deelreeks</td>
  </tr>
  <tr>
    <td></td>
    <td>
</td>
    <td>   Titel Serie</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td></td>
    <td>
</td>
    <td>   Serie  
   Nummer</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td></td>
    <td>
</td>
    <td>   Titel 
   Seizoen</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td></td>
    <td>
</td>
    <td>  Seizoen  
  Nummer</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td>TITEL</td>
    <td></td>
    <td>   Titel  
   Programma</td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td>DATUM</td>
    <td>Datum creatie</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>AMS</td>
    <td>V</td>
    <td>dcterms:created
ebucore:date/created/@*</td>
  </tr>
  <tr>
    <td></td>
    <td>Datum uitgave / uitzending</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dcterms:issued
ebucore:date/issued/@*</td>
  </tr>
  <tr>
    <td>PRODUCTIE</td>
    <td>Maker</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>VA</td>
    <td>dc:creator
ebucore:creator
pbcore:pbcoreCreator/creator</td>
  </tr>
  <tr>
    <td></td>
    <td>Bijdrager</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>O</td>
    <td>dc:contributor
ebucore:contributor
pbcore:pbcoreContributor/contributor</td>
  </tr>
  <tr>
    <td></td>
    <td>Publisher</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>O</td>
    <td>dc:publisher
ebucore:publisher
pbcore:pbcorePublisher/publisher</td>
  </tr>
  <tr>
    <td>INHOUD</td>
    <td>Hoofdbeschrijving</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>V*</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td></td>
    <td>Uitgebreide beschrijving</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>O</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td></td>
    <td>Ondertitels</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel/ Mapping</td>
    <td>O</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription </td>
  </tr>
  <tr>
    <td></td>
    <td>Programma-
beschrijving</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel/ Mapping</td>
    <td>O</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription </td>
  </tr>
  <tr>
    <td></td>
    <td>Rolverdeling</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>O</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td></td>
    <td>Transcriptie</td>
    <td></td>
    <td>Mapping / software</td>
    <td>Mapping / software</td>
    <td>O</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td></td>
    <td>Genre</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>O</td>
    <td>dc:type
ebucore:type/genre
pbcore:pbcoreGenre</td>
  </tr>
  <tr>
    <td></td>
    <td>Coverage (ruimte)</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>O</td>
    <td>dc:coverage
dcterms:spatial
ebucore:coverage/spatial</td>
  </tr>
  <tr>
    <td></td>
    <td>Coverage (tijd)</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>O</td>
    <td>dc:coverage
dcterms:temporal
ebucore:coverage/temporal </td>
  </tr>
  <tr>
    <td></td>
    <td>Trefwoorden</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>V*</td>
    <td>dc:subject
ebucore:subject/dc:subject
pbcore:pbcoreSubject</td>
  </tr>
  <tr>
    <td></td>
    <td>Taal</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / Mapping</td>
    <td>V</td>
    <td>dc:language
ebucore:language
pbcore:pbcoreInstantiation/instantiationLanguage</td>
  </tr>
  <tr>
    <td>RECHTEN</td>
    <td>Licentie</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>V</td>
    <td>dc:rights
dc:license
odrl:permission
odrl:policy
premis:copyrightStatus
premis:rightsStatement/licenseInformation/licenseIdentifier/licenseIdentifierValue</td>
  </tr>
  <tr>
    <td></td>
    <td>Auteursrechthouder</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>V</td>
    <td>dc:rightsHolder
premis:linkingAgentIdentifier
plus:CopyrightOwnerName</td>
  </tr>
  <tr>
    <td></td>
    <td>Licentiehouder</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>plus:LicensorName</td>
  </tr>
  <tr>
    <td></td>
    <td>Credit</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>hiervoor hebben we nog geen mapping naar een standaard / eventueel mappen naar dc_rights</td>
  </tr>
  <tr>
    <td></td>
    <td>Gebruiksbeperking 1
Regio
Medium
Licentie
Duur</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>plus:Constraints</td>
  </tr>
  <tr>
    <td></td>
    <td>Gebruiksbeperking 2
Regio
Medium
Licentie
Duur</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>plus:Constraints</td>
  </tr>
  <tr>
    <td></td>
    <td>Gebruiksbeperking 3
•	Regio
•	Medium
•	Licentie
•	Duur</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>Plus:Constraints</td>
  </tr>
  <tr>
    <td></td>
    <td>Opmerkingen Rechten</td>
    <td></td>
    <td>Manueel / mapping</td>
    <td>Manueel / mapping</td>
    <td>O</td>
    <td>dc_rights</td>
  </tr>
</table>

<b>3. Kwaliteitscontrole (QC)</b>

<table>
  <tr>
    <td></td>
    <td>Veldnaam</td>
    <td>Herkomst metadata born digital</td>
    <td>Herkomst metadata digitalisatie</td>
    <td>V/O</td>
    <td>Mapping</td>
  </tr>
  <tr>
    <td>QC</td>
    <td>Batch id</td>
    <td>N/A</td>
    <td>Manueel</td>
    <td>VA</td>
    <td>PREMIS</td>
  </tr>
  <tr>
    <td></td>
    <td>Resultaat Manuele controle</td>
    <td>N/A</td>
    <td>Manueel</td>
    <td>VA</td>
    <td>PREMIS</td>
  </tr>
  <tr>
    <td></td>
    <td>Audio</td>
    <td>N/A</td>
    <td>Manueel</td>
    <td>VA</td>
    <td>PREMIS</td>
  </tr>
  <tr>
    <td></td>
    <td>Video</td>
    <td>N/A</td>
    <td>Manueel</td>
    <td>VA</td>
    <td>PREMIS</td>
  </tr>
  <tr>
    <td></td>
    <td>Opmerkingen</td>
    <td>N/A</td>
    <td>Manueel</td>
    <td>VA</td>
    <td>PREMIS</td>
  </tr>
</table>


**→ Voor meer details zie VIAA- archiefhandleiding. **

<b>4. Technische metadata</b>

<table>
  <tr>
    <td></td>
    <td>Veldnaam</td>
    <td>Herkomst metadata born digital</td>
    <td>Herkomst metadata digitalisatie</td>
    <td>V/O</td>
    <td>Mapping</td>
  </tr>
  <tr>
    <td></td>
    <td>Bestandstype</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><type/></td>
  </tr>
  <tr>
    <td></td>
    <td>Formaat</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><format/></td>
  </tr>
  <tr>
    <td></td>
    <td>Barcode drager</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><carrier_barcode/></td>
  </tr>
  <tr>
    <td></td>
    <td>Originele locatie</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><original_location/></td>
  </tr>
  <tr>
    <td>DRAGER</td>
    <td>Merk</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><brand/></td>
  </tr>
  <tr>
    <td></td>
    <td>Productiedatum drager</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><date/>*
<carrier_date/>**</td>
  </tr>
  <tr>
    <td></td>
    <td>Kern/Spoel</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><core_reel/></td>
  </tr>
  <tr>
    <td></td>
    <td>OTC start</td>
    <td>N/A</td>
    <td>AMS (SP)</td>
    <td>VA</td>
    <td><OTC_start/></td>
  </tr>
  <tr>
    <td></td>
    <td>Duur</td>
    <td>N/A</td>
    <td>AMS (SP)</td>
    <td>VA</td>
    <td><file_duration/></td>
  </tr>
  <tr>
    <td></td>
    <td>Recording speed</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><audio_carrier_speed/></td>
  </tr>
  <tr>
    <td></td>
    <td>Audio noise reduction</td>
    <td>N/A</td>
    <td>AMS (SP)</td>
    <td>VA</td>
    <td><audio_noise_reduction/></td>
  </tr>
  <tr>
    <td></td>
    <td>Audio IEC type</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><audio_iec_type/></td>
  </tr>
  <tr>
    <td></td>
    <td>Audio tracks</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><audio_tracks/></td>
  </tr>
  <tr>
    <td></td>
    <td>Deterioratiefenomenen</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>O</td>
    <td><preservation_problems/></td>
  </tr>
  <tr>
    <td>LOGISTIEKE INFO</td>
    <td>Registratiedatumdrager</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><created_on/></td>
  </tr>
  <tr>
    <td></td>
    <td>Barcode verzameldoos</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><collection_box_barcode/></td>
  </tr>
  <tr>
    <td></td>
    <td>Batch ID</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><batch_id/></td>
  </tr>
  <tr>
    <td></td>
    <td>Shipment ID</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><shipment_id/></td>
  </tr>
  <tr>
    <td>EVENTS  DIGITALISATIE  
 (enkel van toepassing voor analoge audiovisuele dragers)</td>
    <td>Service Provider</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><sp_name/></td>
  </tr>
  <tr>
    <td></td>
    <td>Service Provider ID</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><sp_id/></td>
  </tr>
  <tr>
    <td></td>
    <td>Datum inspectie analoge drager</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><inspection_date/></td>
  </tr>
  <tr>
    <td></td>
    <td>Uitkomst inspectie analoge dragger</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><inspection_outcome/></td>
  </tr>
  <tr>
    <td></td>
    <td>Opmerking inspectie analoge dragger</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><inspection_note/></td>
  </tr>
  <tr>
    <td></td>
    <td>Datum herstel analoge drager</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><repair_date/></td>
  </tr>
  <tr>
    <td></td>
    <td>Uitkomst herstel analoge drager</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><repair_outcome/></td>
  </tr>
  <tr>
    <td></td>
    <td>Opmerking herstel analoge drger</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><repair_note/></td>
  </tr>
  <tr>
    <td></td>
    <td>Datum reiniging analoge drager</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><cleaning_date/></td>
  </tr>
  <tr>
    <td></td>
    <td>Uitkomst reiniging analoge dragger</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><cleaning_outcome/></td>
  </tr>
  <tr>
    <td></td>
    <td>Opmerking reiniging analoge dragger</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><cleaning_note/></td>
  </tr>
  <tr>
    <td></td>
    <td>Datum bakken analoge drager</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><baking_date/></td>
  </tr>
  <tr>
    <td></td>
    <td>Uitkomst bakken analoge drager</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><baking_outcome/></td>
  </tr>
  <tr>
    <td></td>
    <td>Digitalisatiedatum</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><digitization_date/></td>
  </tr>
  <tr>
    <td></td>
    <td>Tijdstip digitalisatie</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><digitization_time/></td>
  </tr>
  <tr>
    <td></td>
    <td>Uitkomst digitalisatie</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><digitization_outcome/></td>
  </tr>
  <tr>
    <td></td>
    <td>Opmerking digitalisatie</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><digitization_note/></td>
  </tr>
  <tr>
    <td></td>
    <td>Datum kwaliteitscontrole SP</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><qc_date/></td>
  </tr>
  <tr>
    <td></td>
    <td>Uitkomst kwaliteitscontrole SP</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><qc_outcome/></td>
  </tr>
  <tr>
    <td></td>
    <td>Opmerking kwaliteitscontrole SP</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><qc_note/></td>
  </tr>
  <tr>
    <td></td>
    <td>Agent kwaliteitscontrole SP</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><qc_by/></td>
  </tr>
  <tr>
    <td></td>
    <td>Datum transfer naar LTO tape</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><transfer_lto_date/></td>
  </tr>
  <tr>
    <td></td>
    <td>LTO ID</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><lto_id/></td>
  </tr>
  <tr>
    <td>DIGTALISATIEKETEN
(enkel voor analoge audiovisuele dragers)</td>
    <td>Digitalisatie-formaat</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><digitization_format/></td>
  </tr>
  <tr>
    <td></td>
    <td>Player fabrikant</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><player_manufacturer/></td>
  </tr>
  <tr>
    <td></td>
    <td>Player serienummer</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><player_serial_number/></td>
  </tr>
  <tr>
    <td></td>
    <td>Player model</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><player_model/></td>
  </tr>
  <tr>
    <td></td>
    <td>Timebase corrector fabricant</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><timebase_corrector_manufacturer/></td>
  </tr>
  <tr>
    <td></td>
    <td>Timebase corrector serienummer</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><timebase_corrector_serial_number/></td>
  </tr>
  <tr>
    <td></td>
    <td>Timebase corrector model</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><timebase_corrector_model/></td>
  </tr>
  <tr>
    <td></td>
    <td>AD fabrikant</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><AD_manufacturer/></td>
  </tr>
  <tr>
    <td></td>
    <td>AD serienummer</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><AD_serial_number/></td>
  </tr>
  <tr>
    <td></td>
    <td>AD model</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><AD_model/></td>
  </tr>
  <tr>
    <td></td>
    <td>Encoder fabrikant</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><encoder_manufacturer/></td>
  </tr>
  <tr>
    <td></td>
    <td>Encoder serienummer</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><encoder_serial_number/></td>
  </tr>
  <tr>
    <td></td>
    <td>Encoder model</td>
    <td>N/A</td>
    <td>AMS</td>
    <td>VA</td>
    <td><encoder_model/></td>
  </tr>
  <tr>
    <td>TECHNISCHE SPECIFICATIES</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>PREMIS</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>EXIF</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>


<b>4. Gedetailleerde veldomschrijving VIAA datamodel</b>

<b>5. Algemeen</b>

### CP

<table>
  <tr>
    <td>Veld</td>
    <td>Content Partner (CP)</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><CP></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>/</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De naam van de Content Partner (CP).</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><CP>MKHA</CP></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Content Partner ID</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><CP_id></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>/</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De unieke identifier van een Content Partner.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><CP_id>1245</CP_id></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>PID</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><PID></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:identifier
ebucore:identifier
pbcore:pbcoreIdentifier</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De Persistent Identifier. Een door VIAA toegekende unieke naam.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht (automatisch)</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><PID>294805325</PID></td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Aan elke gedigitaliseerde analoge drager wordt een PID toegekend, ook al vormen verschillende dragers één intellectueel geheel. Zo vormen drie audiotapes die één lang interview capteren in totaal drie PIDs. Ook fragmenten die uit een ‘moeder-PID’ worden afgeleid hebben elk een eigen PID.</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Hoofd lokale CP ID </td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_identifier_localid/></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:identifier
ebucore:identifier
pbcore:pbcoreIdentifier</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De hoofd ID van de analoge drager of het born digital item. Dit is de registratiecode die het meest courant wordt gebruikt door de CP binnen het eigen archiefsysteem/CMS.</td>
  </tr>
  <tr>
    <td>Data type</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing (VA)</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>AMSAB:
<dc_identifier_localid>audiocassette 365</dc_identifier_localid></td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Dit is de unieke ID die gebruikt zal worden om metadata voor born digital bestanden te reconciliëren. Voor digitalisatie AV zit deze ID (indien van toepassing) al in Mediahaven aangezien deze mee wordt gegeven in AMS <original_carrier_id/>
Het kan gebeuren dat voor sommige objecten de CP geen relevante ID of registratienummer bijhoudt (ook al raadt VIAA aan om vóór registratie in AMS dit alsnog toe te kennen). In dat geval blijft dit veld leeg.</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Lokale ID(‘s)</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Overige lokale CP ID </td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_identifier_localids type="list”>
      <ARDOME/>
      <priref/>
      ...
</dc_identifier_localids></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:identifier
ebucore:identifier
pbcore:pbcoreIdentifier</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Alternatieve ID’s van de analoge drager of het born digital item, gebruikt door de CP binnen het eigen archiefsysteem/CMS.</td>
  </tr>
  <tr>
    <td>Data type</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel </td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja </td>
  </tr>
  <tr>
    <td>Gecontroleerde lijst</td>
    <td>Ja (zie bijlage)</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>VRT:
<dc_identifier_localids type=”list”>
      <ARDOME>ABC135</ARDOME>
</dc_identifier_localids>
AMSAB:
<dc_identifier_localids type=”list”>
    <reproduction.reference>audiocassette_420</reproduction.reference>
    <acquisition.number>S/2005/051</acquisition.number>
    <alternative_number>MG/05/051-102/1</alternative_number>
</dc_identifier_localids>	</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Lokale ID(‘s)</td>
  </tr>
</table>

<b>6. Relaties</b>

<table>
  <tr>
    <td>Veld</td>
    <td>(Dit digitaal object) is deel van</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_relations type="list”>
      <is_deel_van/>
</dc_relations></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dcterms:isPartOf
ebucore:part</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Dit veld geeft aan van welke PID (parent) het digitale object of item (child) deel uitmaakt.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ID (PID)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Een digitaal object kan opgeknipt worden in aparte fragmenten, die dan elk een eigen PID krijgen. Zo kunnen de fragmenten PID1 en PID2 deel uitmaken van de ‘moeder’ PID3.</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>(Dit digitaal object) bevat</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_relations type="list”>
      <bevat/>
</dc_relations></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>ebucore:hasPart
dcterms:hasPart</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Dit veld geeft aan in welke fragmenten (PIDs) dit digitaal object is opgedeeld.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Een digitaal object kan opgeknipt worden in aparte fragmenten, die dan elk een eigen PID krijgen. Zo kan een ‘moeder’ PID3 opgedeeld zijn in de fragmenten PID1 en PID2.</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>(Dit digitaal object) is verwant aan</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_relations type="list”>
      <is_verwant_aan/>
</dc_relations></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>In dit veld worden verwante digitale objecten (PIDs) aangegeven.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Hiermee worden onder meer verwante PIDs, die uit eenzelfde moeder-PID zijn afgeleid aangegeven. Zo zijn fragmenten PID1 en PID2 met elkaar verwant omdat ze beiden zijn afgeleid uit PID3. 
Ook de verwantschap tussen episodes uit eenzelfde of programma kan hiermee worden aangegeven.</td>
  </tr>
</table>


<b>7. Titels</b>

<table>
  <tr>
    <td>Veld</td>
    <td>Hoofdtitel</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><title/></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:title
ebucore:title/dc:title
pbcore:pbcoreTitle/title</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Algemene benaming of hoofdtitel, gebruikt om naar een bepaald object te zoeken. Het gaat hier om een nette titel die op externe platformen als zoektoegang zal worden gebruikt.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>TV Limburg
<title>nieuws 19-09-94</title>
KADOC
<title>Alaska: Eskimo's</title></td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Voor andere versies (lange titels, vertalingen) kan het veld ‘Alternatieve Titel’ worden gebruikt.</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Programma- reekstitel (indien materiaal deel is van reeks of coherent geheel van items)
Itemtitel (titel van te beschrijven archiefitem)</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Alternatief</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
      <alternatief/>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De alternatieve titel. Dit is een alternatieve benaming voor het object of item. Een alternatieve titel kan ook een archieftitel of een vertaling van de titel zijn.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_titles type=”list”>
      <alternatief>The Three Musketeers</alternatief>
      <alternatief>Les Trois Mousquetaires</alternatief>
</dc_titles></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Archief</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
      <archief/>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>ISAD(G):archief</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Het hoogste beschrijvingsniveau: het archief waar het object deel van uitmaakt.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_titles type=”list”>
      <archief>Archief Gezinsbond</archief>
</dc_titles</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Deelarchief</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
      <deelarchief/>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>ISAD(G):deelarchief</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een deel van een archief dat bestaat uit een geheel van onderling gerelateerde archiefstukken</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_titles type=”list”>
      <deelarchief/>
</dc_titles></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Reeks</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
      <reeks/>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>ISAD(G):reeks</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Documenten gerangschikt volgens een ordeningsplan of beheerd als een eenheid omdat ze het resultaat zijn van een zelfde proces van archiefvorming of opslag, of van eenzelfde activiteit, of omdat ze een bepaalde vorm hebben, of wegens enige andere samenhang die voortkomt uit creatie, ontvangst of gebruik.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_titles type=”list”>
      <reeks>Mondelinge Bronnen</reeks>
</dc_titles></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Deelreeks</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
      <deelreeks/>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>ISAD(G):deelreeks</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een reeks, een onderdeel van een bovenliggende reeks zoals hierboven omschreven.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_titles type=”list”>
      <deelreeks>Over bloemetjes en bijtjes : seksuele voorlichting in  
        en rond het socialistisch milieu</deelreeks>
</dc_titles></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Serie</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
         <serie/>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De serietitel. Dit is de titel van de serie waar het item deel van uitmaakt.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_titles type=”list”>
         <serie>Het Journaal</serie>
</dc_titles></td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Programma- reekstitel (indien materiaal deel is van reeks of coherent geheel van items)
Itemtitel (titel van te beschrijven archiefitem)</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Serienummer</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
          <serienummer/>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Het nummer van de serie waarvan het item deel uitmaakt.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>???</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Seizoen</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
           <seizoen>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Het seizoen/jaargang waarvan het item deel uitmaakt.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_titles type=”list”>
           <seizoen>Journaal 1300 P2016</seizoen>
</dc_titles></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Seizoennummer</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
           <seizoennummer>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Het nummer van het seizoen waarvan het item deel uitmaakt.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>???</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Programma</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_titles type="list”>
      <programma/>
</dc_titles></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dcterms:alternative
ebucore:alternativeTitle/@typeLabel
pbcore:titleType</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De programmatitel. Dit is de titel van het programma waarvan het item deel uitmaakt.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_titles type=”list”>
      <programma>Journaal 1300 20160301 Di</programma>
</dc_titles></td>
  </tr>
</table>


<b>8. Datum</b>

<table>
  <tr>
    <td>Veld</td>
    <td>Datum creatie</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dcterms_created/></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dcterms:created
ebucore:date/created/@*</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De datum waarop de intellectuele inhoud van het object werd gecreëerd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ISO 8601 - Date and time format  (http://www.iso.org/iso/home/store/catalogue_tc/catalogue_detail.htm?csnumber=40874) 
Extended Date Time Format (EDTF)
(https://www.loc.gov/standards/datetime/)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht (indien ‘datum uitgave’ niet is ingevuld).</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dcterms_created>192u</dcterms_created></td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Indien onbekend wordt (automatisch?) de datum van de creatie van de analoge drager (verplicht bij registratie in AMS) gekozen, aangezien deze doorgaans met de datum van de creatie van de originele inhoud samenvalt of er toch dicht bij aansluit. Het is evenwel mogelijk dat de intellectuele inhoud (‘content’) vastgelegd op de analoge drager een latere kopie is van een ouder origineel (bijvoorbeeld een kopie van een ¼" tape op VHS). In dit geval verschillen de datum van creatie van de datum van de originele drager.

EDTF laat verschillende vormen van verfijning, veralgemening en benaderende waarden toe. In MediaHaven worden volgende mogelijkheden aangeboden:
precies
precies tijd Z
precies tijd met tijd
precieze tijd met tijdzone
eeuw
decennium
onbekend jaar in eeuw (yyuu)
onbekend jaar in decennium (yyyu)
onbekende maand in jaar (yyyy-uu)
onbekende dag in een jaar (yyyy-uu-uu)
onbekende dag in een maand (yyyy-mm-uu)
onbekende datum (uuuu-uu-uu)
lege datum
</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Productiedatum en/of gebruiksdatum (bijv. datum eerste uitzending).</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Datum uitgave / uitzending</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dcterms_issued/></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dcterms:issued
ebucore:date/issued/@*</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De datum waarop het item is uitgegeven of uitgezonden.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ISO 8601 - Date and time format  (http://www.iso.org/iso/home/store/catalogue_tc/catalogue_detail.htm?csnumber=40874) 
Extended Date Time Format (EDTF)
(https://www.loc.gov/standards/datetime/)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht (indien ‘datum creatie’ niet is ingevuld). </td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee (dit zou wel mogelijk moeten zijn)</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dcterms_issued>2016-01-27T13:00</dcterms_issued></td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>EDTF laat verschillende vormen van verfijning, veralgemening en benaderende waarden toe. In MediaHaven worden volgende mogelijkheden aangeboden:
precies
precies tijd Z
precies tijd met tijd
precieze tijd met tijdzone
eeuw
decennium
onbekend jaar in eeuw (yyuu)
onbekend jaar in decennium (yyyu)
onbekende maand in jaar (yyyy-uu)
onbekende dag in een jaar (yyyy-uu-uu)
onbekende dag in een maand (yyyy-mm-uu)
onbekende datum (uuuu-uu-uu)
lege datum</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Productiedatum en/of gebruiksdatum (bijv. datum eerste uitzending).</td>
  </tr>
</table>


<b>9. Productie</b>

<table>
  <tr>
    <td>Veld</td>
    <td>Maker</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_creators type="list">
            <maker/>
            <regisseur/>
            <archiefvormer/>
             …
</dc_creators></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:creator
ebucore:creator
pbcore:pbcoreCreator/creator</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De persoon of instelling die (in hoofdzaak) verantwoordelijk is voor de creatie van de inhoud van het item. </td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Gecontroleerde lijst</td>
    <td>Zie bijlage. Aan de hand van een gecontroleerde lijst kan de rol van de maker worden gespecificeerd. VIAA biedt een standaard lijst van rollen aan. Deze kan afhankelijk van de partner worden aangepast. Indien geen van de rollen van toepassing is, kan het generieke ‘maker’ worden gebruikt, ofwel kan in overleg met VIAA de gecontroleerde lijst worden uitgebreid.</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien gekend (VA)</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_creators type="list">
            <maker>Paul de Vree</maker>
            <archiefvormer>Jef van Hoof</archiefvormer>
</dc_creators></td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Producent/Maker (indien gekend)</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Bijdrager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_contributors type="list">
            <bijdrager/>
            <geluidsman/>
            <pianist/>
            ...
</dc_contributors></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:contributor
ebucore:contributor
pbcore:pbcoreContributor/contributor</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De persoon of instelling die een substantiële creatieve bijdrage tot de intellectuele inhoud van het item heeft geleverd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Gecontroleerde lijst</td>
    <td>Zie bijlage. Aan de hand van een gecontroleerde lijst kan de rol van de bijdrager worden gespecificeerd. VIAA biedt een standaard lijst van rollen aan. Deze kan afhankelijk van de partner worden aangepast. Indien geen van de rollen van toepassing is, kan het generieke ‘bijdrager’ worden gebruikt, ofwel kan in overleg met VIAA de gecontroleerde lijst worden uitgebreid.</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_contributors type="list">
            <dirigent>Daniel Barenboim</dirigent>
            <pianist>Maurizio Pollini</pianist>
</dc_contributors></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Publisher</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_publishers type=list/>
            <publisher/>
            <omroep/>
            <distributeur/>
            <persagentschap/>
            …
</dc_publishers></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:publisher
ebucore:publisher
pbcore:pbcorePublisher/publisher</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De entiteit in hoofdzaak verantwoordelijk voor het verdelen en het toegankelijk maken van een item voor derden door omroep, verkoop, verhuur,... </td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Gecontroleerde lijst</td>
    <td>Zie bijlage. Aan de hand van een gecontroleerde lijst kan de rol van de bijdrager worden gespecificeerd. VIAA biedt een standaard lijst van rollen aan. Deze kan afhankelijk van de partner worden aangepast. Indien geen van de rollen van toepassing is, kan het generieke ‘bijdrager’ worden gebruikt, ofwel kan in overleg met VIAA de gecontroleerde lijst worden uitgebreid.</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_publishers type=list/>  
            <omroep>VRT</omroep>
</dc_publishers></td>
  </tr>
</table>


<b>10. Inhoud</b>

<table>
  <tr>
    <td>Veld</td>
    <td>Hoofdbeschrijving</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><description/></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een korte, algemene omschrijving van de intellectuele inhoud van een item.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien geen minimum van vijf trefwoorden.</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_description>Deze interviews zijn ingericht door het Universiteitsarchief en vormen een basis voor een onderzoek. Het eindresultaat is de publicatie 'Meisjestudenten aan de RUG</dc_description></td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Bij gebrek aan een manuele beschrijving kan hier de uitkomst van tekstherkenning (OCR) en speech-to-text worden opgenomen.</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Beschrijving (summiere beschrijving in tekst; tijdsgebaseerde annotatie optioneel) of een minimum van 5 trefwoorden die de inhoud van het item beschrijven</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Lange beschrijving</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_description_long/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een gedetailleerde beschrijving van de inhoud van het object. Dit kan bijvoorbeeld door puntsgewijs de voornaamste scènes, stock-shots, aparte items… te beschrijven. Voor ondertitels is een apart veld voorzien.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Beschrijving (summiere beschrijving in tekst; tijdsgebaseerde annotatie optioneel) of een minimum van 5 trefwoorden die de inhoud van het item beschrijven</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Programmabeschrijving</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_description_programme/></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een korte beschrijving van het programma waar het item een onderdeel van vormt. </td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Rolverdeling</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_description_cast/></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een oplijsting van de voornaamste acteurs/performers en hun respectievelijke rol. </td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_description_cast>Julien Schoenaert (Oedipus), Aafke Bruyninckx (Antigone)</dc_description_cast></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Ondertitels</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_description_ondertitels/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een weergave van de ondertitels die bij het digitale object horen.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Beschrijving (summiere beschrijving in tekst; tijdsgebaseerde annotatie optioneel) of een minimum van 5 trefwoorden die de inhoud van het item beschrijven</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Transcriptie</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_description_transcriptie/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>dc:description
ebucore:description/dc:description
pbcore:pbcoreDescription</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een weergave van de transcriptie van het digitale object.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Kan eventueel de uitkomst zijn van een speech-to-tekst toepassing.</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Beschrijving (summiere beschrijving in tekst; tijdsgebaseerde annotatie optioneel) of een minimum van 5 trefwoorden die de inhoud van het item beschrijven</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Genre</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_types type="list”>
      <genre/>
</dc_types></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:type
ebucore:type/genre
pbcore:pbcoreGenre</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Omschrijving van de aard, het genre of het doelpubliek van het item.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Gecontroleerde lijst (zie bijlage)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_types type=”list”>
      <genre>sportverslaggeving</genre>
</dc_types></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Coverage (ruimtelijk)</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_coverages type="list”>
      <ruimte/>
</dc_coverages></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:coverage
dcterms:spatial</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een beschrijvende afbakening van het geografisch gebied (straat, stad, land, continent) waar de inhoud van het item betrekking op heeft.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_coverages type=”list”>
      <ruimte>Wijnegem shopping center</ruimte>
      <ruimte>provincie Antwerpen</ruimte>
</dc_coverages></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Coverage (tijd)</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_coverages type="list”>
      <tijd/>
</dc_coverages></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:coverage
dcterms:temporal
ebucore:coverage/temporal</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een beschrijvende afbakening van de tijdsperiode waar de inhoud van het item betrekking op heeft.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_coverages type=”list”>
      <tijd>interbellum</tijd>
      <tijd>jaren 1920</tijd>
</dc_coverages></td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Let wel: het betreft hier de tijdsperiode waar het item inhoudelijk betrekking op heeft, niet de datum van creatie. Een documentaire uit de jaren 1950 over de Gulden Sporenslag heeft dus bijvoorbeeld als temporele coverage ‘middeleeuwen’.</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Trefwoorden</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_subjects type="list">
      <trefwoord/>
</dc_subjects></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:subject
ebucore:subject/dc:subject
pbcore:pbcoreSubject</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Thematische trefwoorden met betrekking tot de inhoud van het item.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht (minimaal 5 trefwoorden) indien geen (korte) beschrijving</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_subjects type="list">
      <trefwoord>seksuele voorlichting</trefwoord>
      <trefwoord>socialistische beweging</trefwoord>
</dc_subjects></td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Beschrijving (summiere beschrijving in tekst; tijdsgebaseerde annotatie optioneel) of een minimum van 5 trefwoorden die de inhoud van het item beschrijven</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Taal</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_languages type="list”>
      <multiselect/>
</dc_languages></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:language
ebucore:language
pbcore:pbcoreInstantiation/instantiationLanguage</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De (belangrijkste) taal/talen die in het item worden gesproken of gebruikt.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ISO 639-1 (gecontroleerde lijst)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_languages type=”list”>
      <multiselect>nl</multiselect>
      <multiselect>fr</multiselect>
</dc_languages></td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Het betreft de gesproken of gezongen taal, niet de taal van eventuele ondertitels. In het geval van een stomme film, is de taal van de eventuele tussentitels indicatief.</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Taal: taal van het item</td>
  </tr>
</table>


<b>11. Rechten</b>

<table>
  <tr>
    <td>Veld</td>
    <td>Licentie</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_licenses type="list”>
      <licentie/>
</dc_rights_licences></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:rights
dc:license
odrl:permission
odrl:policy
premis:copyrightStatus
premis:rightsStatement/licenseInformation/licenseIdentifier/licenseIdentifierValue</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Het type licentie waaronder de exploitatie (het gebruik, de reproductie en bewerking) van het item wordt geregeld.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Gecontroleerde lijst </td>
  </tr>
  <tr>
    <td>Gecontroleerde lijst</td>
    <td>Zie bijlage voor verdure toelichting.
VIAA-licentie
Alle rechten voorbehouden
CC BY
CC BY-SA
CC BY-ND
CC BY-NC
CC BY-NC-SA
CC BY-NC-ND</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_rights_license>CC BY-ND</dc_rights_licence></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Auteursrechthouder</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_rightsOwners type="list”>
      <auteursrechthouder/> 
</dc_rights_rightsOwners></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>dc:rightsHolder
premis:linkingAgentIdentifier
plus:CopyrightOwnerName</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De persoon of organisatie die de auteursrechten bezit. Dit kan de eigenlijke auteur zijn, zijn erfgenamen of een derde partij aan wie de rechten zijn overgedragen. </td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht (indien gekend)</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_rights_rightsOwner>Etienne Tordoir</dc_rights_rightsOwner>
<dc_rights_rightsOwner>KADOC</dc_rights_rightsOwner></td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Rechthebbende (indien gekend)</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Licentiehouder</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_rightsHolders type="list”>
      <licentiehouder/>
</dc_rights_rightsHolders></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>plus:LicensorName</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De persoon of organisatie die de rechten beheert.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_rights_rightsholder>SABAM</dc_rights_rightsholder></td>
  </tr>
  <tr>
    <td>Opmerkingen</td>
    <td>Soms wordt de het toezicht op het correcte gebruik, evenals het beheer van de inkomsten gegenereerd uit het gebruik van auteursrechtelijk beschermde werken uitbesteed aan een externe persoon of organisatie (een zogenaamd auteursrechtvennootschappen zoals SABAM, SEMU,...).</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Credit</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_credit/></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>dc:rights</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Tekst van de attributie of kennisgeving die bij het beeld moet verschijnen.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><dc_rights_credit>Copyright AMSAB. Onder de licentie Creative Commons CC-PD</dc_rights_credit/>
<dc_rights_credit/>Copyright SMAK. Alle rechten voorbehouden</dc_rights_credit>
<dc_rights_credit>Alle rechten voorbehouden. Gelieve contact op te nemen met reproductie@uu.be</dc_rights_credit></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Gebruiksbeperking 1</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><plus_constraints_1 type="list”>
      <regio/>
      <medium/>
      <licentie/>
      <duur/>
</plus_constraints_1></td>
  </tr>
  <tr>
    <td>Mapping</td>
    <td>Plus:Constraints</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Beperking van de gebruiksrechten tot een bepaalde regio, medium en/of periode.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst </td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja (driemaal)</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><plus_constraints_1 type=”list”>
      <regio>België</region>
      <medium>on-line streaming</medium>
      <duur>2016-02-01 tot 2016-05-01</duur>
</plus_constraints_1></td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Opmerkingen rechten</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>dc:rights</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<b>12. QC</b>

<table>
  <tr>
    <td>Veld</td>
    <td>Batch ID</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td>< QC_QC_Batch_ID/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Deze ID wordt gebruikt om de selectie van bestanden die deel uit maken van de kwaliteitscontrole te groeperen. Deze batch ID heeft enkel betekenis tijdens het proces van de kwaliteitscontrole.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst </td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Neen</td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Resultaat manuele QC</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td>< QCoutcome/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Na het uitvoeren van de manuele kwaliteitscontrole wordt de CP gevraagd de kwaliteit van het digitale bestand te beoordelen. Dit kan door aan te geven of de kwaliteit ‘ok’ is of ‘nok’. Hierbij kan de dropdownlist onder het veld ‘Resultaat manuele kwaliteitscontrole’ geraadpleegd worden. De waarden in de list ‘audio’ en ‘video’ geven aan wat er visueel en auditief gededecteerd kan worden. Deze lijsten zullen verder uitgebreid worden. Indien vragen of feedback kan dit steeds gemeld worden via support@viaa.be.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>OK / NOT OK</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel (enkel van toepassing op de statistische selectie van een volledige batch, VIAA adviseert om een statistische selectie van 10% te maken)</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Neen</td>
  </tr>
</table>


<b>13. Drager</b>

<table>
  <tr>
    <td>Veld</td>
    <td>Bestandstype</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><type/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>pbcore:instantiation/mediaType</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De algemene aard van de inhoud van de drager en hoe deze aan de ontvanger wordt gepresenteerd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Gecontroleerde lijst (zie AMS handleiding)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien gekend</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><type>video</type></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Formaat</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><format/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>EN 15744 (Metadata Standards for Cinematographic Work)</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Een omschrijving van het type drager waarop het item oorspronkelijk is vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Gecontroleerde lijst (zie AMS handleiding)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien gekend</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><format>Betacam SP</format></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Barcode drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><carrier_barcode/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Dit is de barcode die op de materiële drager werd aangebracht.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><carrier_barcode>AACC_AMS_000540</carrier_barcode></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Originele locatie</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><original_location/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Dit is de standplaats van de originele materiële drager. Dit kan een lokaal- of reknummer, een plaatskenmerk of de naam van een collectie zijn.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien gekend</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><original_location>10A</original_location>
<original_location>rek 12, plank 3</original_location>
<original_location>Erfenis Amaat Burssens</original_location></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Merk</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><brand/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Dit is het merk of de fabrikant van de materiële drager.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Gecontroleerde lijst (zie AMS handleiding)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien gekend</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><brand>Philips</brand></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Productiedatum drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><carrier_date/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Dit is de (geschatte) productiedatum van de materiële drager.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ISO 8601 - Date and time format  (http://www.iso.org/iso/home/store/catalogue_tc/catalogue_detail.htm?csnumber=40874) 
Extended Date Time Format (EDTF)
(https://www.loc.gov/standards/datetime/)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien gekend</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><carrier_date>1937-09-07</carrier_date></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Kern/Spoel</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><core_reel/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>In dit veld kan worden aangegeven of de tape op kern dan wel op open spoel is bevestigd. </td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Kern/Spoel (zie ook AMS handleiding – Annex dragers)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien gekend</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><core_reel>Spoel</core_reel></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>OTC start</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><OTC_start/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Het startpunt van de originele tijdscodering zoals die op de drager wordt bijgehouden.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>hh:mm:ss:sss (ISO 8601)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien bekend</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><OTC_start>01:00:00:000</OTC_start></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Duur</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><file_duration/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td>EN15744:Original Duration
SMPTE 12M</td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De totale duur van het digitale bestand.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>hh:mm:ss (ISO 8601)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien gekend</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><file_duration>00:30:01:21</file_duration></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Recording speed</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><audio_carrier_speed/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De opnamesnelheid van de drager. Dit is hoofdzakelijk van toepassing voor open spoel audiotapes. </td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>cm/s</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><audio_carrier_speed>4.75 cm/s</audio_carrier_speed></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Audio noise reduction</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><audio_noise_reduction/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De bij audiocassettes gebruikte technologie van ruisonderdrukking. </td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><audio_noise_reduction>Dolby A</audio_noise_reduction></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Audio IEC type</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><audio_iec_type/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Het type magnetische coating gebruikt voor de tape van een audiocassette.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>I-IV (IEC 60094) (zie ook AMS handleiding – Annex dragers)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><audio_iec_type>II</audio_iec_type></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Audio tracks</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><audio_tracks/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Het aantal geluidssporen dat op de drager kan worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Numeriek</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><audio_tracks>2</audio_tracks></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Deterioratiefenomenen</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><preservation_problems/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Fenomenen – doorgaans onder invloed van fysische of chemische factoren – die mogelijks de integriteit en raadpleegbaarheid van de gegevens op de drager in gevaar kunnen brengen.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Gecontroleerde lijst (zie AMS handleiding)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><preservation_problems>disc rot</preservation_problems></td>
  </tr>
</table>


<b>14. Logistieke info</b>

<table>
  <tr>
    <td>Veld</td>
    <td>Registratiedatum drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><created_on/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De datum waarom de drager in AMS werd geregistreerd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ISO 8601 - Date and time format  (http://www.iso.org/iso/home/store/catalogue_tc/catalogue_detail.htm?csnumber=40874) 
Extended Date Time Format (EDTF)
(https://www.loc.gov/standards/datetime/)</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><created_on>2014-11-27T14:11:11</created_on></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Barcode verzameldoos</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><collection_box_barcode/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De barcode die werd bevestigd op de verzameldoos waarin de drager werd geplaatst tijdens het digitaliseringsproces.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><collection_box_barcode>BBMX_AMS_000007</collection_box_barcode></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Batch ID</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><batch_id/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De ID van de batch waarin de drager van de content partner naar de service provider werd verstuurd. Deze is vooral van belang voor de service provider en VIAA.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing.</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><batch_id>BMXMJPGB01</batch_id></td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Shipment ID</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><shipment_id/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>De ID van de verzending waarin de drager van de content partner naar de service provider werd verstuurd. Deze is vooral van belang voor de service provider en VIAA.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>ID</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Verplicht indien van toepassing</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Nee</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td><shipment_id>14314364782</shipment_id></td>
  </tr>
</table>


    15. Events digitalisatie

<table>
  <tr>
    <td>Veld</td>
    <td>Service provider</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Service provider ID</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Datum inspectie analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Uitkomst inspectie analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Opmerking inspectie analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Datum herstel analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Uitkomst herstel analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Opmerking herstel analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Datum reiniging analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Uitkomst reiniging analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Opmerking reiniging analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Datum bakken analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Uitkomst bakken analoge drager</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Digitalisatiedatum</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Tijdstip digitalisatie</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Uitkomst digitalisatie</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Opmerking digitalisatie</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Datum kwaliteitscontrole</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Uitkomst kwaliteitscontrole</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Opmerking kwaliteitscontrole</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Agent kwaliteitscontrole</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Datum transfer naar LTO</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>LTO ID</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


    16. Digitalisatieketen

<table>
  <tr>
    <td>Veld</td>
    <td>Digitalisatieformaat</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Player fabrikant</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Player serienumer</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Player model</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Timebased corrector fabrikant</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Timebased corrector serienummer</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Timebased corrector model</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>AD fabrikant</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>AD serienummer</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>AD model</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Encoder fabrikant</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Encoder serienummer</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Encoder model</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


    17. Technische metadata

<table>
  <tr>
    <td>Veld</td>
    <td>Video Formaat</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Video Technisch</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Audio Technisch</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>TC in</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>TC out</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Duur</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>Image size</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


<table>
  <tr>
    <td>Veld</td>
    <td>MD5</td>
  </tr>
  <tr>
    <td>Metadata element</td>
    <td><dc_rights_comment/></td>
  </tr>
  <tr>
    <td>Mapping </td>
    <td><dc_rights/></td>
  </tr>
  <tr>
    <td>Definitie</td>
    <td>Hier kunnen bijkomende opmerkingen en voorwaarden met betrekking tot de gebruiksrechten van toepassing op het item worden vastgelegd.</td>
  </tr>
  <tr>
    <td>Format of content / datatype</td>
    <td>Vrije tekst</td>
  </tr>
  <tr>
    <td>Verplichting</td>
    <td>Optioneel</td>
  </tr>
  <tr>
    <td>Herhaalbaar</td>
    <td>Ja</td>
  </tr>
  <tr>
    <td>Voorbeeld</td>
    <td>?</td>
  </tr>
  <tr>
    <td>Gebruiksovereenkomst</td>
    <td>In het kader van de overeenkomst wordt uitgegaan van het invullen van minimaal volgende velden :
Gebruiksbeperkingen indien van toepassing (afwijking van de standaard policy: mag gebruikt worden voor VIAA doelgroepen conform de overeenkomst) </td>
  </tr>
</table>


