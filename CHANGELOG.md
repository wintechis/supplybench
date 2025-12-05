# Changelog

## Snapshot [v#.#]

### Added

### Changed

### Fixed

### Removed

## Snapshot [v0.3]

### Added

- tbox: ontology metadata
- tbox: comment for n-ary statement class qb:Observation
- tbox: `rdf:Property` as type for all properties
- abox: label for headquarters
- abox: comment for supply flows
- abox: comment for observations
- abox: `sb:Enterprise` as class
- corpus: `n-ary` tag

### Changed

- tbox/abox/corpus: `sb` namespace for SupplyBench ontology
- tbox/abox/corpus: integrated `esn` namespace terms into `sb`
- abox: data update through crawling
- abox: URI for `org:Membership` instances
- corpus: format from .n3 to .yaml
- corpus: "suppliers" to "supplier companies"
- corpus: "customers" to "customer companies"
- corpus: "IDMs" to "IDM companies"
- corpus: "Chip fabs" to "Chip fab sites"
- corpus: question "City TSMC has its headquarter in" to "City that TSMC has its headquarter in"
- corpus: question "CEOs with publications" to "People in CEO position with publications"
- corpus: question "CEO publications in 2005" to "Publications of people in CEO position in 2005"

### Fixed

- tbox/abox/corpus: URI of `org` prefix


## Snapshot [v0.2]

### Added

- abox: type esn:Enterprise for org:Organization instances
- abox: type wgs1:SpatialThing for genoame:Feature instances
- corpus: question "Chip fabs"

### Changed

- tbox: :OrganizationClass to :OrganizationType
- tbox: :SiteClass to :SiteType
- tbox: comment of geonames:A to label
- tbox: comment of geonames:P to label
- tbox: comment of geonames:S to label
- tbox: comment of geonames:A.PCLI to label
- abox: according to tbox changes
- corpus: according to tbox changes
- corpus: query "Net profit of companies with assembly/test sites" to "Net profit of companies with chip fabs"

### Removed

- tbox: :enterpriseObservation
- tbox: geonames:parentCountry
- tbox: :ceoOf
- tbox: org:memberOf
- tbox: :hasCeo
- tbox: org:hasMember
- tbox: org:hasMembership
- corpus: query "Assembly/test sites of companies"
- corpus: query "Bavarian organisations"
- corpus: query "Large equipment suppliers of TSMC"
- corpus: queries for five or more triple patterns


## Snapshot [v0.1]

### Added

- init
