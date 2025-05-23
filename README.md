# IDN Keeping Place Catalogue

This is the source data of the [Indigenous Data Network](https://idnau.org/)'s Keeping Place catalogue which has been established as part of 
the IDN's Catalogue Project. This catalogue lists resource of high interest to Australian Indigenous communities that the IDN is keeping long-term archived copies of, to ensure they are not lost due to system or institutional failure.

This catalogue is online at:

* _**coming soon!**_


## Catalogue Resources

| Name                 | Location                                                                                                                   | Role                                                                                                                    | Description                                                                                                  |                                                                                     
|----------------------|----------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| Catalogue Definition | [`catalogue.ttl`](catalogue.ttl)                                                                                           | [Catalogue Data](https://prez.dev/ManifestResourceRoles/CatalogueData)                                                  | The definition of, and medata for, the container which here is a dcat:Catalog object                         |
| Resource Data        | [`resources/*.ttl`](resources/*.ttl)                                                                                       | [Resource Data](https://prez.dev/ManifestResourceRoles/ResourceData)                                                    | sdo:CreativeWork objects in RDF (Turtle) files in the resources/ folder                                      |
| Profile Definition   | [`ogc_records_profile.ttl`](https://github.com/RDFLib/prez/blob/main/prez/reference_data/profiles/ogc_records_profile.ttl) | [Catalogue & Resource Model](https://prez.dev/ManifestResourceRoles/CatalogueAndResourceModel)                          | The default Prez profile for Records API                                                                     |
| Labels               | [`_background/labels.ttl`](_background/labels.ttl)                                                                         | [Incomplete Catalogue and Resource Labels](https://prez.dev/ManifestResourceRoles/IncompleteCatalogueAndResourceLabels) | An RDF file containing labels for catalogue's content, auto-extracted from KurrawongAI's Semantic Background |
| Labels - manual      | [`_background/labels-manual.ttl`](_background/labels-manual.ttl)                                                           | [Incomplete Catalogue and Resource Labels](https://prez.dev/ManifestResourceRoles/IncompleteCatalogueAndResourceLabels) | An RDF file containing labels for catalogue's content, manually created                                      |