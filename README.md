# Trust List Distribution Point

This is unofficial distribution point for trusted lists of non-EU countries. Sometimes, trust lists could be published at source with incorrect format according to XSD schema definition (it just happens), or are unavailable at the source due other reasons. This all makes it difficult to direct 3rd party software to use source as distribution point in automatted manner. It's necessary to propose format fix if necessary and use more reliable distribution point. Trust lists, signer certificates and optionally proposed fixes are alltogether stored in folders following ccTLD naming pattern. Next to ccTLD down bellow we'll mark with red circle if the distributed list is with broken signature due to proposed format fixes. All proposed fixes will be communicated to the trust list operator. Meanwhile, until the fix is implemented at the source by operator, the 3rd party software relying on  trust lists should continue providing designated functionallity and somehow convey the situation. The ultimate goal is to enhance customers' perceptions of the quality of the trusted service and the organization.

 
Common files in repository:

- signer1.crt, signer2.crt... - signer PEM certificates
- trustlist-src.xml - signed TrustList at the source
- trustlist.xml - distributed TrustList which is same as the source or contains proposed fixes but with broken signature


## Montenegro (ME) &#x1F534;

Source: https://www.gov.me/dokumenta/eea75b66-dac0-4937-bc6b-0bb4016d9510

Date: 2022-07-20T01:00:00Z

NextUpdate: 2023-01-20T00:00:00Z

Sequence number: 5



## Serbia (RS) 

Source: https://epotpis.mtt.gov.rs/eng/home/ 

Date: 2022-09-16T01:00:00Z

NextUpdate: 2023-03-15T01:00:00Z

Sequence number: 10



