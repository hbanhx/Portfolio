# Portfolio

- Udvikling og automatiseringsprojekter
- Python / API / SQL / COBOL - Mainframe / Power BI / Excel 

### COBOL / Mainframe

Opgavesæt udarbejdet af Danske Bank: 
- Generer et kontoudskrift:
    - Inputfiler banker.txt og transaktioner.txt 
    - Statistik og analyser
- Fraud detection og AML-håndtering: 
    - Inputfiler KundeOplysninger.txt og SanctionList.txt.
    - Match kunder med navne på sanctionlist. Beregn match-procent med Levenshtein Distance og generer en rapport
        - SQL database, 
        
        - mock NAV/Business Central API og 
        
        - til excel

### ETL DMI vejrdata (Python, PostgreSQL, Docker)
Dette er en extract, transform og load pipeline, som henter data fra DMI Open Data API (Frie Data), transformerer og loader vejrdata til SQL database. 

Danmarks Meteorologiske Institut: https://www.dmi.dk/frie-data

Repo: https://github.com/hbanhx/etl_dmi

### myDmi Open Data API (Python, FastAPI, PostgreSQL)
myDmi er et API projekt, der udstiller det data, som bliver hentet fra DMI Open Data API i etl_dmi app. 

myDmi API er udviklet i forlængelse af projektet: etl_dmi. 
DMI Open Data API -> etl_dmi: database -> myDmi API

Repo: https://github.com/hbanhx/my_dmi


### Sales Orders Integration (Python, FastAPI, SQL)
Automatiseringsproces der henter ordredata fra en mock Amazon database, transformerer rå data, beregner enhedspriser og moms, validerer data og genererer NAV/BC salgsordrer indlæser ordrerne til:

        - SQL database, 
        
        - mock NAV/Business Central API og 
        
        - til excel

        

Repo: https://github.com/hbanhx/etl_amazon_orders


### Payments Integration (Python, SQL)
Løsning at automatisere manuel bogføringsprocess af Amazon‑betalinger. Der genereres bogføringsjournal udligning af betaling og faktura.
Der bogføres gebyr, moms og nettoindbetaling.  

Repo: https://github.com/hbanhx/etl_amazon_transactions


### Intercompany Transactions & VAT Reconciliation (Python, SQL)
Automatisk synkronisering af fakturaer og kreditnotaer mellem to NAV/Business Central‑selskaber.  
Indeholder momsindberetning og afstemning.  

Repo: https://github.com/hbanhx/etl_intercompany_transactions

### API-integration (to-do)
Arbejder med mock‑API’er i FastAPI (fx Amazon, Business Central og SAP), der udveksler data mellem systemerne, og er tænkt som grundlag for ETL‑projekter i Python og SQL.

        - mock_amazon_api

        - mock_bc_api
        
        - mock_sap_api

Repo: https://github.com/hbanhx/FastAPI
