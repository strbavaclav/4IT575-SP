# Deplyment View

V tomto pohledu je zobrazena infrastruktura rezervačního systému hotelu dle architektury MMTA (Monolitic Multi-tier architecture).

## UML Diagram nasazení

![Deployment diagram](./../../assets/deployment_diagram_MMTA.png "Diagram nasazení")

## Katalog komponent

### Client Tier

- _webová aplikace_: Klientská aplikace běžící ve webovém prohlížeči, která komunikuje se serverovými komponentami.

### 3rd Party Service

#### IoT (Internet of Things)

- _Chytré zámky_: IoT zařízení sloužící k zabezpečení a kontrolám přístupu.
- _Chytrý vozík_: IoT zařízení, pro automatizaci úklidových služeb.

#### AWS S3

- Služba pro ukládání obrázků a dokumentů v cloudovém úložišti poskytovaném Amazon Web Services.

### Logic Tier

#### Hosting rezervační společnosti

- _web server_: Server, který hostuje web a jeho komponenty.
- _Express server_: Specifický webový serverový framework Node.js, který zpracovává požadavky.
- _Aplikace webové API_: Aplikace poskytující webové API, které slouží jako rozhraní pro komunikaci mezi klientskou a serverovou částí.

### Data Tier

- _ODBC_: Open Database Connectivity, standardní API pro přístup k databázi.

#### Databázový server

- _MySQL Server_: Systém řízení báze dat (DBMS), který spravuje databázi.
- _Databáze_: Konkrétní databáze využívaná systémem, obsahuje data.
