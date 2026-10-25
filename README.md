# Portfolio

- Python / SQL / Power BI / Excel / API

### ETL DMI vejrdata (Python, PostgreSQL, Docker)
Dette er en extract, transform og load pipeline, som henter data fra DMI Open Data API (Frie Data), transformerer og loader vejrdata til SQL database. 

Danmarks Meteorologiske Institut: https://www.dmi.dk/frie-data

Repo: https://github.com/hbanhx/etl_dmi

### myDmi Open Data API (Python, FastAPI, PostgreSQL)
myDmi er et API projekt, der udstiller det data, som bliver hentet fra DMI Open Data API i etl_dmi app. 

myDmi API er udviklet i forlængelse af projektet: etl_dmi. 
DMI Open Data API -> etl_dmi: database -> myDmi API

Repo: https://github.com/hbanhx/my_dmi


### ETL Amazon Orders Integration (Python, FastAPI, SQL)
ETL‑proces der henter ordredata fra en mock Amazon database, transformerer rå data, beregner enhedspriser og moms, validerer data og genererer NAV/BC salgsordrer loader ordrerne til:

        - SQL database, 
        
        - mock NAV/Business Central API og 
        
        - til excel

Repo: https://github.com/hbanhx/etl_amazon_orders


### ETL Amazon Transactions & Payments Integration (Python, SQL)
Løsning at automatisere manuel bogføringsprocess af Amazon‑betalinger. Der genereres bogføringsjournal udligning af betaling og faktura.
Der bogføres gebyr, moms og nettoindbetaling.  

Repo: https://github.com/hbanhx/etl_amazon_transactions


### ETL Intercompany Transactions & VAT Reconciliation (Python, SQL)
ETL‑pipeline til synkronisering af fakturaer og kreditnotaer mellem to NAV/Business Central‑selskaber.  
Indeholder momsindberetning og afstemning.  

Repo: https://github.com/hbanhx/etl_intercompany_transactions

### FastAPI (to-do)
Arbejder med mock‑API’er i FastAPI (fx Amazon, Business Central og SAP), der udveksler data mellem systemerne, og er tænkt som grundlag for ETL‑projekter i Python og SQL.

        - mock_amazon_api

        - mock_bc_api
        
        - mock_sap_api

Repo: https://github.com/hbanhx/FastAPI
