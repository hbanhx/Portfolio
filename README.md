# Portfolio

- Python / SQL / Power BI / Excel / API

### etl_dmi (Python, PostgreSQL, Docker)
Dette er en extract, transform og load pipeline, som henter data fra DMI Open Data API (Frie Data), transformerer og loader vejrdata til SQL database. 

Danmarks Meteorologiske Institut: https://www.dmi.dk/frie-data

Repo: https://github.com/hbanhx/etl_dmi

### myDmi Open Data API (Python, FastAPI, PostgreSQL)
myDmi er et API projekt, der udstiller det data, som bliver hentet fra DMI Open Data API i etl_dmi app. 

myDmi API er udviklet i forlængelse af projektet: etl_dmi. 
DMI Open Data API -> etl_dmi: database -> myDmi API

Repo: https://github.com/hbanhx/my_dmi


### ETL Amazon Orders Integration (Python, FastAPI, SQL)
ETL‑proces der henter ordredata fra en egenudviklet FastAPI Amazon Orders‑API,  
renser og beriger rå Amazon‑eksporter, beregner enhedspriser og VAT‑procenter,  
validerer ordredata og genererer strukturerede Sales Header og Sales Line‑datasets  
til videre indlæsning i mock Business Central.

Repo: https://github.com/hbanhx/etl_amazon_orders


### ETL Amazon Transactions & Payments Integration (Python, SQL)
Løsning til match mellem Amazon‑betalinger og ERP‑posteringer.  
Indeholder transaktionsmatch, beløbsmeltning, journalgenerering og datamaskering.  

Repo: https://github.com/hbanhx/etl_amazon_transactions


### ETL Intercompany Transactions & VAT Reconciliation (Python, SQL)
ETL‑pipeline til synkronisering af fakturaer og kreditnotaer mellem to Business Central‑selskaber.  
Indeholder VAT‑afstemning, import‑ordre‑identifikation, datamaskering og master‑dataset baseret på konfigurationsstyrede SQL‑udtræk.  

Repo: https://github.com/hbanhx/etl_intercompany_transactions

### FastAPI (to-do)
Arbejder med mock‑API’er i FastAPI (fx Amazon, Business Central og SAP), der udveksler data mellem systemerne, og er tænkt som grundlag for ETL‑projekter i Python og SQL.

        - mock_amazon_api

        - mock_bc_api
        
        - mock_sap_api

Repo: https://github.com/hbanhx/FastAPI
