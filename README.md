# DP-203_Lab10
## 📊 Azure Synapse Analytics: Product Data Pipeline

### 📝 Overzicht
Dit project bevat een oefening waarin een gegevenspijplijn wordt gebouwd in **Azure Synapse Analytics**. De pijplijn laadt productgegevens vanuit een CSV-bestand in een **dedicated SQL Pool** van een gegevensmagazijn. Deze oefening is onderdeel van de Microsoft Learn DP-203 cursus.

### 🎯 Doelstellingen
- Een **Synapse Analytics Workspace** met een **dedicated SQL Pool** opzetten
- Een CSV-bestand met productgegevens laden vanuit **Data Lake Storage Gen2**
- Een **gegevensstroom (Data Flow)** configureren om nieuwe producten in te voegen en bestaande producten bij te werken
- De pijplijn **debuggen**, **publiceren** en **uitvoeren**
- **Verwijderen van resources** om kosten te besparen

### 📂 Gegevensbronnen
- **Bron**: `Product.csv` bestand opgeslagen in een Azure Data Lake Storage Gen2 container
- **Bestemming**: `dbo.DimProduct` tabel in een dedicated SQL Pool

### 🔧 Belangrijke stappen
1. Synapse workspace implementeren met een PowerShell script en ARM-template
2. Synapse Studio openen en SQL Pool starten
3. CSV-bestand en bestaande SQL-tabel bekijken
4. Gegevenspijplijn aanmaken met een **Data Flow**
5. Twee bronnen toevoegen: CSV-bestand en SQL-tabel
6. Lookup uitvoeren om bestaande producten te vinden
7. **Alter Row** gebruiken om invoegen of bijwerken te bepalen
8. Sink configureren om de gegevens in `DimProduct` op te slaan
9. Pijplijn debuggen en uitvoeren
10. Resultaten controleren en resources opruimen

### 🖥️ Benodigdheden
- Een actieve **Azure-abonnement**
- Toegang tot **Azure Cloud Shell (PowerShell)**
- Basiskennis van **Azure Synapse Studio**

### ⏳ Tijdsduur
Ongeveer **45 minuten**

### 📦 Opgeruimd staat netjes
Na voltooiing van de oefening worden alle aangemaakte Azure-resources verwijderd om extra kosten te voorkomen.

### 🧠 Opmerking
Deze oefening is ideaal voor data engineers die praktijkervaring willen opdoen met het bouwen van ETL-processen in Azure Synapse Analytics.

![Schermafbeelding 2025-04-14 110446](https://github.com/user-attachments/assets/b3fd8468-065a-4648-a8a2-1068d9894836)

![Schermafbeelding 2025-04-14 112131](https://github.com/user-attachments/assets/9cd2f36f-d128-4a5c-aac2-210778d1a2fc)

![Schermafbeelding 2025-04-14 124250](https://github.com/user-attachments/assets/4ade5f2a-a4f3-4633-9c9e-a0a2eb2e5571)

![Schermafbeelding 2025-04-14 125430](https://github.com/user-attachments/assets/4ca5d20f-0177-4fa6-8309-f6542a3344cd)

![Schermafbeelding 2025-04-14 130448](https://github.com/user-attachments/assets/e455f4a9-14af-492d-b2ef-5d52c15714ff)

![Schermafbeelding 2025-04-14 131459](https://github.com/user-attachments/assets/0df22251-6039-4e68-bfe3-36e991f0596d)

![Schermafbeelding 2025-04-14 131806](https://github.com/user-attachments/assets/41029695-a35e-473f-94d9-ce59a0db4290)


![Schermafbeelding 2025-04-14 133050](https://github.com/user-attachments/assets/fb28d654-eed4-48b7-b744-4e33652c749c)


![Schermafbeelding 2025-04-14 133752](https://github.com/user-attachments/assets/a4f6a933-6fc3-42b1-9584-84749b5819df)


![Schermafbeelding 2025-04-14 133930](https://github.com/user-attachments/assets/8b2b4851-c21c-4a44-b380-170fae495d37)





