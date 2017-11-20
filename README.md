# Metadata model for digital intake
***Work In Progress!***

This guide gives the Content Partners (CPs) of VIAA more insight how metadata is structured inside VIAAs MAM and how they should deliver metadata for digital intake. CPs that have  borndigital or digitised material will need to deliver metadata about these essences. This is done by supplying a sidecar XML for every essence, e.g. test.xml + test.mxf. VIAAs ingest proces expects metadata that is already mapped to the VIAA metadata model that is explained below. In future work we would like to support standards like Dublin Core. If you have remarks, questions... let us know at support@viaa.be!

Here you can find a XSD to validate your mapping, examples and explanation of all the metadata fields.

## Validation

You can validate your mapped metadata with our XSD `viaa_metadatamodel_xsd.xsd`.
An easy way to do this is with xmllint, which is part of [libxml](http://xmlsoft.org/).
Open a Terminal and run following command:

```bash
xmllint --noout --schema viaa_metadatamodel_voor_cp.xsd viaa_metadatamodel_voorbeeld_voor_cp.xml
```

## Full metadata example

See `viaa_metadatamodel_voorbeeld_voor_cp.xml` for a full metadata XML.

## Metadata model

See https://viaa.be/nl/portaal/support-category/item/handleiding-metadatamodel 