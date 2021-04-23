<h1 align="center">Covid-19 Opendata Regione Calabria</h1>

<div align="center">
<img src="calabria-regione-1.svg" width="180">


[Questo repository contiene i dati in formato aperto relativi all'andamento del COVID-19 in Calabria.](http://covida19.herokuapp.com/calabria.html)
<br />
</div>

# Descrizione repository

Per informare i cittadini e mettere a disposizione i dati raccolti, utili ai soli fini comunicativi e di informazione, questo repository mette a disposizione, le seguenti informazioni aggiornate quotidianamente:

*   Dati regione
*   Dati province
*   Dati comuni

## Struttura del repository
```

covid19-opendata-calabria/
│
├── dati/
│   ├── provincia
│   │   ├── Catanzaro
│   │       ├── Catanzaro.xlsx
│   │       ├── Catanzaro.csv
│   │       ├── Incidenza_per_centomila_abitanti.csv
│   │       ├── Trend_settimanale_nuovi_casi.csv
│   │       ├── Trend_settimanale_decessi.csv
│   │       ├── Trend_settimanale_guariti.csv
│   │       ├── Trend_settimanale_ricoveri.csv
│   │       ├── Trend_settimanale_terapie_intensive.csv
│   │
│   │   ├── Cosenza
│   │       ├── Cosenza.xlsx
│   │       ├── Cosenza.csv
│   │       ├── Incidenza_per_centomila_abitanti.csv
│   │       ├── Trend_settimanale_nuovi_casi.csv
│   │       ├── Trend_settimanale_decessi.csv
│   │       ├── Trend_settimanale_guariti.csv
│   │       ├── Trend_settimanale_ricoveri.csv
│   │       ├── Trend_settimanale_terapie_intensive.csv
│   │       ├── comuni
│   │           ├── Marzo_2020
│   │               ├── ASP_CS_2020-03-24.csv
│   │                   ...
│   │           ├── Aprile_2020
│   │               ├── ASP_CS_2020-04-01.csv
│   │               ...
│   │           ...
│   │
│   │   ├── Crotone
│   │       ├── Crotone.xlsx
│   │       ├── Crotone.csv
│   │       ├── Incidenza_per_centomila_abitanti.csv
│   │       ├── Trend_settimanale_nuovi_casi.csv
│   │       ├── Trend_settimanale_decessi.csv
│   │       ├── Trend_settimanale_guariti.csv
│   │       ├── Trend_settimanale_ricoveri.csv
│   │       ├── Trend_settimanale_terapie_intensive.csv
│   │
│   │   ├── Reggio Calabria
│   │       ├── Reggio Calabria.xlsx
│   │       ├── Reggio Calabria.csv
│   │       ├── Incidenza_per_centomila_abitanti.csv
│   │       ├── Trend_settimanale_nuovi_casi.csv
│   │       ├── Trend_settimanale_decessi.csv
│   │       ├── Trend_settimanale_guariti.csv
│   │       ├── Trend_settimanale_ricoveri.csv
│   │       ├── Trend_settimanale_terapie_intensive.csv
│   │
│   │   ├── Vibo Valentia
│   │       ├── Vibo Valentia.xlsx
│   │       ├── Vibo Valentia.csv
│   │       ├── Incidenza_per_centomila_abitanti.csv
│   │       ├── Trend_settimanale_nuovi_casi.csv
│   │       ├── Trend_settimanale_decessi.csv
│   │       ├── Trend_settimanale_guariti.csv
│   │       ├── Trend_settimanale_ricoveri.csv
│   │       ├── Trend_settimanale_terapie_intensive.csv
│   │
│   ├── regione
│   │   ├── Calabria.xlsx
│   │   ├── Calabria.csv
│   │   ├── Incidenza_per_centomila_abitanti.csv
│   │   ├── Trend_settimanale_nuovi_casi.csv
│   │   ├── Trend_settimanale_decessi.csv
│   │   ├── Trend_settimanale_guariti.csv
│   │   ├── Trend_settimanale_ricoveri.csv
│   │   ├── Trend_settimanale_terapie_intensive.csv
│   │
│   ├── vaccinazione
│   │   ├── dosi_consegnate_consumate_per_settimana.csv
│   │   ├── dosi_consegnate_per_settimana.csv
│   │   ├── dosi_somministrate_per_centomila_abitanti.csv
│   │   ├── somministrazioni_giornaliere.csv
│   │   ├── somministrazioni_giornaliere_per_categoria.csv
│   │   ├── somministrazioni_giornaliere_per_eta_prima_dose.csv
│   │   ├── somministrazioni_giornaliere_tipo_dose.csv
│   │   ├── somministrazioni_per_categoria_in_percentuale.csv
│   │   ├── somministrazioni_per_eta_prima_dose.csv
│   │   ├── somministrazioni_per_eta_seconda_dose.csv

```

# Descrizione dataset

Nella cartella dati si possono trovare le seguenti tabelle in formato xlsx e csv: 
*   **Calabria**: dati sull'andamento del COVID-19 a livello regionale. 
*   **Incidenza_per_centomila_abitanti**: dati sul numero di nuovi casi positivi al COVID-19 ogni 100.000 abitanti su base settimanale.
*   **Trend_settimanale_nuovi_casi**: dati sul numero di casi positivi al COVID-19 su base settimanale.
*   **Trend_settimanale_decessi**: dati sul numero dei decessi di persone positive al COVID-19 su base settimanale. 
*   **Trend_settimanale_guariti**: dati sul numero dei guariti di persone positive al COVID-19 su base settimanale. 
*   **Trend_settimanale_ricoveri**: dati sul numero dei ricoveri in area non critica di pazienti positivi al COVID-19 su base settimanale. 
*   **Trend_settimanale_terapie_intensive**: dati sul numero dei posti occupati in terapia intensiva da pazienti positivi al COVID-19 su base settimanale.
*   **Catanzaro**: dati sull'andamento del COVID-19 nella provincia di Catanzaro.
*   **Cosenza**: dati sull'andamento del COVID-19 nella provincia di Cosenza.
*   **Crotone**: dati sull'andamento del COVID-19 nella provincia di Crotone.
*   **Reggio Calabria**: dati sull'andamento del COVID-19 nella provincia di Reggio Calabria.
*   **Vibo Valentia**: dati sull'andamento del COVID-19 nella provincia di Vibo Valentia.
*   **ASP_PROVINCIA_ANNO-MESE-GIORNO**: dati sull'andamento del COVID-19 suddivisi per data e comune. 
*   **dosi_consegnate_per_settimana**: dati sul numero di dosi dei vaccini anti-COVID-19 consegnate settimanalmente.
*   **dosi_consegnate_consumate_per_settimana**: dati sul numero di dosi di vaccino consegnate e quelle somministrate su base settimanale.
*   **dosi_somministrate_per_centomila_abitanti**: dati sul numero di dosi di vaccino somministrate ogni 100.000 abitanti su base settimanale.
*   **somministrazioni_giornaliere**: dati sul numero assoluto di dosi somministrate al giorno.
*   **somministrazioni_giornaliere_per_categoria**: dati sul numero assoluto di dosi di vaccino somministrate al giorno per categoria di popolazione.
*   **somministrazioni_giornaliere_per_eta_prima_dose**: dati sul numero assoluto di dosi di vaccino somministrate (prima dose) al giorno per età.
*   **somministrazioni_giornaliere_per_tipo_dose**: dati sul numero assoluto di dosi somministrate al giorno, suddiviso per prima dose e seconda dose.
*   **somministrazioni_per_categoria_in_percentuale**: dati sulla percentuale di dosi di vaccino somministrate per categoria di popolazione.
*   **somministrazioni_per_eta_prima_dose**: dati sulla percentuale di popolazione che ha ricevuto solo la prima dose di vaccino. 
*   **somministrazioni_per_eta_seconda_dose**: dati sulla percentuale di popolazione che ha completato il ciclo vaccinale (2 dosi di vaccino). 




I campi di ogni tabella sono schematizzati come riportato di seguito:

**Calabria/Catanzaro/Cosenza/Crotone/Reggio Calabria/Vibo Valentia**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Giorno in cui si registrano nuovi casi. |
| Nuovi casi | integer | Numero totale di persone risultate positive nelle ultime 24 ore. |
| Media 7 giorni | integer | Vengono considerati i dati di un determinato periodo e ne viene calcolata la media sommandoli fra loro e dividendo per il numero totale di valori.|
| Deceduti | integer | Numero totale di persone morte e risultate positive al COVID-19. |
| Guariti/Dimessi | integer | Numero di pazienti dimessi dagli ospedali, o perché non necessitano più di cure ospedaliere e quindi vengono isolate presso il loro domicilio, o perché ne è stata verificata la negatività attraverso il tampone. |
| Ricoverati | integer | Numero totale di persone ricoverate in ospedale con sintomi connessi al COVID-19. |
| Terapia intensiva | integer | Numero totale di posti letto di TI occupati da pazienti positivi al COVID-19. |


**Incidenza_per_centomila_abitanti** 

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Settimana di riferimento. |
| Casi per settimana | integer |  Numero di persone positive al COVID-19 ogni 100.000 abitanti su base settimanale. |

**Trend_settimanale_nuovi_casi** 

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Settimana di riferimento. |
| Casi per settimana | integer |  Numero di persone positive al COVID-19 su base settimanale. |

**Trend_settimanale_decessi** 

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Settimana di riferimento. |
| Decessi per settimana | integer |  Numero dei decessi di persone positive al COVID-19 su base settimanale. |

**Trend_settimanale_guariti** 

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Settimana di riferimento. |
| Guariti per settimana | integer |  Numero dei guariti di persone positive al COVID-19 su base settimanale. |


**Trend_settimanale_ricoveri** 

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Settimana di riferimento. |
| Ricoveri per settimana | integer |  Numero dei ricoveri in area non critica di pazienti positivi al COVID-19 su base settimanale.  |

**Trend_settimanale_terapie_intensive** 

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Settimana di riferimento. |
| Guariti per settimana | integer |  Numero dei posti occupati in terapia intensiva da pazienti positivi al COVID-19 su base settimanale.  |

**ASP_PROVINCIA_ANNO-MESE-GIORNO**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Comune | string | Nome completo del comune. |
| A domicilio | integer | Numero di persone positive al COVID-19 che non necessitano di cure ospedaliere e si trovano in isolamento presso il loro domicilio. |
| Deceduti | integer | Numero totale di persone morte e risultate positive al COVID-19. |
| Guariti/Dimessi | integer | Numero di pazienti dimessi dagli ospedali, o perché non necessitano più di cure ospedaliere e quindi vengono isolate presso il loro domicilio, o perché ne è stata verificata la negatività attraverso il tampone. |
| Ricoverati | integer | Numero totale di persone ricoverate in ospedale con sintomi connessi al COVID-19. |
| Totale casi| integer | Numero totale di nuovi casi registrati nelle ultime 24 ore (A domicilio + Guariti + Deceduti + Ricoverati). |

**dosi_consegnate_per_settimana**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Settimana di riferimento. |
| Dosi consegnate | integer | Numero totale di dosi consegnate per settimana. |

**dosi_somministrate_per_centomila_abitanti**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Settimana di riferimento. |
| Dosi somministrate | integer |  Numero di dosi somministrate per settimana. |
| N. abitanti | integer |  Popolazione Regione Calabria (31/12/2019 - Istat). |
| Dosi per 100.000 abitanti | integer |  Numero di dosi somministrate ogni 100.000 abitanti. |

**dosi_consegnate_consumate_per_settimana**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Settimana di riferimento. |
| Dosi consegnate | integer | Numero totale di dosi consegnate per settimana. |
| Dosi consumate | integer | Numero totale di dosi somministrate per settimana. |

**somministrazioni_giornaliere**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Giorno in cui è avvenuta la somministrazione. |
| Somministrazioni | integer | Numero totale di somministrazioni per giorno. |

**somministrazioni_giornaliere_per_categoria**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Giorno in cui è avvenuta la somministrazione. |
| Operatori sanitari/sociosanitari | integer | Numero di somministrazioni effettuate agli operatori sanitari e sociosanitari indicate per giorno. |
| Personale non sanitario | integer | Numero di somministrazioni effettuate al personale non sanitario impiegato in strutture sanitarie e in attività lavorativa a rischio indicate per giorno. |
| Ospiti RSA | integer | Numero di somministrazioni effettuate ai soggetti ospiti di comunità residenziali indicate per giorno. |
| Personale scolastico | integer | Numero di somministrazioni effettuate al personale scolastico indicate per giorno. |
| 60 - 69 | integer | Numero somministrazioni effettuate ai soggetti con età anagrafica compresa tra 60 e 69 anni, non appartenenti ad altre categorie prioritarie ma ricevono la somministrazione esclusivamente sul criterio dell'età anagrafica, indicate per giorno. |
| 70 - 79 | integer | Numero somministrazioni effettuate ai soggetti con età anagrafica compresa tra 70 e 79 anni, non appartenenti ad altre categorie prioritarie ma ricevono la somministrazione esclusivamente sul criterio dell'età anagrafica, indicate per giorno. |
| Over 80 | integer | Numero somministrazioni effettuate ai soggetti con età anagrafica maggiore o uguale a 80 anni, non appartenenti ad altre categorie prioritarie ma ricevono la somministrazione esclusivamente sul criterio dell'età anagrafica, indicate per giorno. |
| Soggetti fragili | integer | Numero di somministrazioni effettuate ai soggetti fragili e loro caregiver indicate per giorno. |
| Forze armate | integer | Numero di somministrazioni effettuate al personale del comparto difesa e sicurezza indicate per giorno. |
| Altro | integer | Numero di somministrazioni effettuate ai soggetti non riconducibili alle precedenti categorie indicate per giorno. |


**somministrazioni_giornaliere_per_eta_prima_dose**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Giorno in cui è avvenuta la somministrazione. |
| 16-19 | integer | Totale dei soggetti appartenenti alla fascia d'età 16-19 a cui è stato somministrata la prima dose di vaccino per giorno. |
| 20-29 | integer | Totale dei soggetti appartenenti alla fascia d'età 20-29 a cui è stato somministrata la prima dose di vaccino per giorno. |
| 30-39 | integer | Totale dei soggetti appartenenti alla fascia d'età 30-39 a cui è stato somministrata la prima dose di vaccino per giorno. |
| 40-49 | integer | Totale dei soggetti appartenenti alla fascia d'età 40-49 a cui è stato somministrata la prima dose di vaccino per giorno. |
| 50-59 | integer | Totale dei soggetti appartenenti alla fascia d'età 50-59 a cui è stato somministrata la prima dose di vaccino per giorno. |
| 60-69 | integer | Totale dei soggetti appartenenti alla fascia d'età 60-69 a cui è stato somministrata la prima dose di vaccino per giorno. |
| 70-79 | integer | Totale dei soggetti appartenenti alla fascia d'età 70-79 a cui è stato somministrata la prima dose di vaccino per giorno. |
| 80-89 | integer | Totale dei soggetti appartenenti alla fascia d'età 80-89 a cui è stato somministrata la prima dose di vaccino per giorno. |
| 90+ | integer | Totale dei soggetti appartenenti alla fascia d'età 90+ a cui è stato somministrata la prima dose di vaccino per giorno. |

**somministrazioni_giornaliere_per_tipo_dose**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Categoria | string | Tipologia di categoria definita dal Piano vaccinale. |
| Percentuale | integer | Percentuale di dosi somministrate (sul totale delle dosi somministrate) suddivise per categoria. |

**somministrazioni_giornaliere_per_tipo_dose**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Giorno in cui è avvenuta la somministrazione. |
| Prima dose | integer | Numero prime somministrazioni per giorno. |
| Seconda dose | integer | Numero seconde somministrazioni per giorno. |

**somministrazioni_per_eta_prima_dose**:

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Età | string | Fascia d'età a cui è stata somministrata la prima dose di vaccino. |
| Vaccinazioni | integer | Percentuale di popolazione che ha ricevuto solo la prima dose di vaccino per età. |

**somministrazioni_per_eta_seconda_dose**:

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Età | string | Fascia d'età a cui è stata somministrata la prima dose di vaccino. |
| Vaccinazioni | integer | Percentuale di popolazione che ha completato il ciclo vaccinale (2 dosi di vaccino) per età. |








## Licenza

[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [Visualizza licenza](https://github.com/pcm-dpc/COVID-19/blob/master/LICENSE)

## Author / Copyright 

[2021 (c) Francesco Branda](https://francescobranda.netlify.app/) 


