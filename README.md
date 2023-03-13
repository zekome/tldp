# Trust List Distribution Point

This is unofficial distribution point for trusted lists of certain non-EU countries. Sometimes, trust lists are published with incorrect format according to schema definition (it just happens) or are unavailable at the source due other reasons. This all makes it difficult for 3rd party software to use directly trusted lists at source in automated manner. The solution is to propose necessary fix and use more reliable distribution point. Trust lists, corresponding signer certificates, and optionally fix are altogether stored in folders following ccTLD naming pattern. Sections down below are marked with colored circles. Red means broken signature due to proposed format fix. The green circle means all is good. The proposed fix will be communicated to the trust list operator. Meanwhile, until the fix is implemented at the source by operator, the 3rd party software loading trust lists with proposed fix should report the broken signature. 

The goal is to enhance customers' perceptions of the quality of the trusted service and the organization.

 
Common files in repository:

- signer1.crt, signer2.crt... - signer PEM certificates
- trustlist-src.xml - signed TrustList from the source
- trustlist.xml - distributed TrustList which is same as the source or implements proposed fix but with broken signature


## Montenegro (ME) &#x1F7E2;

Source: https://wapi.gov.me/download/07706c7d-0e90-483d-b7af-502ff743b57d

Date: 2023-03-13T02:00:00Z

NextUpdate: 2023-09-12T23:00:00Z

Sequence number: 9

Status: Ok.



## Serbia (RS) &#x1F7E2;

Source: https://epotpis.mtt.gov.rs/eng/home/ 

Date: 2022-12-26T02:00:00Z

NextUpdate: 2023-06-26T00:00:00Z

Sequence number: 11

Status: Ok.



## North Macedonia (MK) &#x1F534;

Source: https://trusteid.mioa.gov.mk/en/home/register-and-lists/

Date: 2022-01-10T09:00:00Z

NextUpdate: 2022-06-01T08:00:00Z

Sequence number: 3

Status: TL Operator notified about fix proposal.

