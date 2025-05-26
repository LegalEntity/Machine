## Other Links and Resources in the Parking Lot

* https://ipfs.io
* https://www.openabm.org/models
* https://en.wikipedia.org/wiki/Graph_database
* https://github.com/telehash/telehash.org

* https://distrowatch.com/dwres.php?resource=popularity
* https://elementary.io/get-involved

* https://github.com/HumanDynamics/LegalEntity/wiki/Notional-Architectural-Approach
* http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2485711&download=yes

* Harmonized Development of Legal and Regulatory Systems for E-commerce in ... - United Nations. Economic and Social Commission for Asia and the Pacific - Google Books
https://books.google.com/books?id=kzCCbZ-3s4EC&pg=PA50&lpg=PA50&dq=digital+legal+entity&source=bl&ots=Pf8CNZleVP&sig=Lt5OGTnbLWEl61uBu4BwaNiWidA&hl=en&sa=X&ved=0ahUKEwi5k_fzk-HOAhXKFh4KHZW9CYAQ6AEIPDAE#v=onepage&q=digital%20legal%20entity&f=false
* Data diagnostics for legal entity, Cognitive data automation, Hierarchy data cleansing - Accelerator Solutions
http://www.kingland.com/accelerator-solutions
* Entity Legal | Drupal.org
https://www.drupal.org/project/entity_legal
* EntityKeeper: Entity Management, Data Organization, Legal Entity Visualization
https://www.entitykeeper.com/
* https://www.omgeo.com/page/global_lei_alert
https://www.omgeo.com/page/global_lei_alert
* D2.13: Virtual Persons and Identities: Future of IDentity in the Information Society
http://www.fidis.net/resources/fidis-deliverables/identity-of-identity/d2600/doc/17/
* Cooperative Corporation | Digital Media Law Project
http://www.dmlp.org/legal-guide/cooperative-corporation
* Digital Identity, an Emergent Legal Concept: The Role and Legal Nature of ... - Clare Linda Sullivan - Google Books
https://books.google.com/books?id=DPn56Sl6bbIC&pg=PA49&lpg=PA49&dq=digital+legal+entity&source=bl&ots=olO9SubMrm&sig=5cLzb7FR1gVdqC8xorBv-pDHe64&hl=en&sa=X&ved=0ahUKEwi5k_fzk-HOAhXKFh4KHZW9CYAQ6AEIQzAG#v=onepage&q=digital%20legal%20entity&f=false

-- -- -- -- -- 

# Rough Concept of Steps for Automated Loan Fund

## FOR Automated Loan Fund!

The idea is to build software that will: disburse $500 worth of short term loans to to five test borrowers.. totally automated through AWS cloud service and logged on Ethereum blockchain... or that's the plan at least).   It it goes well, we hope to have something ready for a field-test of some type Caitlin can use in the DR later this winter. ...

1) With input of a few key variables about the person creating the loan fund (name/address/etc) and selection of the fund template, at a click the code will instal itself on a server at the Media Lab from an automated "Docker" image, and when it completes self-diagnostics, will:

2) Form a Delaware company (probably a non-prof of LLC) as the legal entity owning the fund using the API available from that state (and either we'll get the filing fee waived as a research project or may need to have the founder include ACH or credit card info at setup);

3) Create an account at the a US federally chartered Credit Union that will be capitalized with about $1,000 to make loan disbursals and receive loan paybacks and pay other fees/charges necessary to run the revolving loan fund (again, initial account funding may require ACH or cc info);

4) Configure PayPal and other web-friendly and widely accepted forms of payment to handle routine fees necessary for the loan fund (if a business credit card can quickly be issued to the legal entity for use to operate the loan fund, all the better but that will depend on what is possible and worth testing with the Credit Union as part of an initial Proof of Concept and what is left for testing in later version);

5) Create an AWS  account and install/configure/deploy the revolving loan fund code from yet another Docker image; 

6) Configure and integrate public-facing code generating web pages for brochure-style information, to receive loan applications by web-form; for web based communications with approved borrowers and for servicing the loans through an account management page for each borrowe to check balance and make payments; 

7) Configure and integrate back-end code for simple accounting, marketing (just a Google AdWords integration), and to make blockchain entries of key events (the contract reflecting origination of each loan, each loan payment by the borrower and each key legal notice such as loan payoff or notice of default); 

8) Configure and integrate back-end "rules-based, data-driven process code" to routing and initial analysis of loan applications, providing risk score and recommended action to the fund officer on a decision support page and handle key events like notices and account status updates accompanying final loan payment or elevating notices accompanying non-payment  (using simplified XBRL data tagging and BPML 2 workflow/approval rules) 
