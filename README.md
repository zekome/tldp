# Trust List Distribution Point

This is unofficial distribution point for trusted lists of non-EU countries. Sometimes, lists could be published at source with incorrect format according to XSD schema definition (it just happens), or are unavailable at the source due specific reasons. This all makes it difficult to direct 3rd party software to use source as automatted distribution point. It's necessary to propose format fix if necessary and use more reliable distribution point. Trust lists, signer certificateds and optionally proposed fixes are stored in separate folders following ccTLD naming scheme.

 
Common files in repository:

- signer1.crt, signer2.crt... - signer PEM certificates
- trustlist-src.xml - signed TrustList at the source
- trustlist.xml - distributed TrustList which is same as the source or contains proposed fixes but with broken signature


** Montenegro **

Source: https://www.gov.me/dokumenta/eea75b66-dac0-4937-bc6b-0bb4016d9510

Date: 2022-07-20T01:00:00Z

NextUpdate: 2023-01-20T00:00:00Z

Fix proposed: yes


** Serbia **

Source: https://epotpis.mtt.gov.rs/eng/home/ 

Date: 022-09-16T01:00:00Z

NextUpdate: 2023-03-15T01:00:00Z

Fix proposed: no

