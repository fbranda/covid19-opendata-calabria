<h1 align="center">COVID-19 Open Data Regione Calabria</h1>

<div align="center">
<img src="calabria-regione-1.svg" width="180">


[Questo repository contiene i dati aperti relativi all'andamento del COVID-19 in Calabria.](http://covida19.herokuapp.com/calabria.html)
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
│   │       ├── Catanzaro.csv
│   │
│   │   ├── Cosenza
│   │       ├── Cosenza.csv
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
│   │       ├── Crotone.csv
│   │
│   │   ├── Reggio Calabria
│   │       ├── Reggio Calabria.csv
│   │
│   │   ├── Vibo Valentia
│   │       ├── Vibo Valentia.csv
│   │
│   ├── regione
│   │   ├── Calabria.csv
│   │
│   ├── vaccinazione
│   │   ├── somministrazioni_giornaliere_tipo_dose.csv
│   │   ├── somministrazioni_giornaliere_tipo_vaccino.csv
│   │   ├── storico_prime_dosi_per_eta.csv
│   │   ├── storico_seconde_dosi_per_eta.csv
│   │   ├── storico_terze_dosi_per_eta.csv

```

# Descrizione dataset

Nella cartella dati si possono trovare le seguenti tabelle in formato csv: 
*   **Calabria**: dati sull'andamento dei contagi e delle ospedalizzazioni COVID-19 a livello regionale. 
*   **Catanzaro**: dati sull'andamento del COVID-19 nella provincia di Catanzaro.
*   **Cosenza**: dati sull'andamento del COVID-19 nella provincia di Cosenza.
*   **Crotone**: dati sull'andamento del COVID-19 nella provincia di Crotone.
*   **Reggio Calabria**: dati sull'andamento del COVID-19 nella provincia di Reggio Calabria.
*   **Vibo Valentia**: dati sull'andamento del COVID-19 nella provincia di Vibo Valentia.
*   **ASP_PROVINCIA_ANNO-MESE-GIORNO**: dati sull'andamento del COVID-19 suddivisi per data e comune. 
*   **somministrazioni_giornaliere_tipo_vaccino**: dati sul numero assoluto di dosi somministrate al giorno, suddiviso per tipo di vaccino.
*   **somministrazioni_per_copertura_vaccinale**: dati sulla percentuale di popolazione che ha completato il ciclo vaccinale con due dosi o con vaccino monodose, o che ha ricevuto una sola dose di vaccino, o nessuna dose.
*   **storico_prime_dosi_per_eta**: numero totale di somministrazione di prime dosi per fascia d'età.
*   **storico_seconde_dosi_per_eta**: numero totale di somministrazione di seconde dosi per fascia d'età.
*   **storico_terze_dosi_per_eta**: numero totale di somministrazione di terze dosi (booster) per fascia d'età.




I campi di ogni tabella sono schematizzati come riportato di seguito:

**Calabria/Catanzaro/Cosenza/Crotone/Reggio Calabria/Vibo Valentia**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Giorno in cui si registrano nuovi casi. |
| Nuovi casi | integer | Numero totale di persone risultate positive nelle ultime 24 ore. |
| Deceduti | integer | Numero totale di persone morte e risultate positive al COVID-19. |
| Guariti/Dimessi | integer | Numero di pazienti dimessi dagli ospedali, o perché non necessitano più di cure ospedaliere e quindi vengono isolate presso il loro domicilio, o perché ne è stata verificata la negatività attraverso il tampone. |
| Ricoverati | integer | Numero totale di persone ricoverate in ospedale con sintomi connessi al COVID-19. |
| Terapia intensiva | integer | Numero totale di posti letto di TI occupati da pazienti positivi al COVID-19. |

**ASP_PROVINCIA_ANNO-MESE-GIORNO**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Comune | string | Nome completo del comune. |
| A domicilio | integer | Numero di persone positive al COVID-19 che non necessitano di cure ospedaliere e si trovano in isolamento presso il loro domicilio. |
| Deceduti | integer | Numero totale di persone morte e risultate positive al COVID-19. |
| Guariti/Dimessi | integer | Numero di pazienti dimessi dagli ospedali, o perché non necessitano più di cure ospedaliere e quindi vengono isolate presso il loro domicilio, o perché ne è stata verificata la negatività attraverso il tampone. |
| Ricoverati | integer | Numero totale di persone ricoverate in ospedale con sintomi connessi al COVID-19. |
| Totale casi| integer | Numero totale di nuovi casi registrati nelle ultime 24 ore (A domicilio + Guariti + Deceduti + Ricoverati). |

**somministrazioni_giornaliere_tipo_dose**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Giorno in cui è avvenuta la somministrazione. |
| Prima dose | integer | Numero totale di prime somministrazioni per giorno. |
| Seconda dose | integer | Numero totale di seconde somministrazioni per giorno. |
| Pregressa infezione | integer | Numero di somministrazioni effettuate a soggetti con pregressa infezione da COVID-19 nel periodo 3-6 mesi e che, pertanto, concludono il ciclo vaccinale con un'unica dose.  |
| Monodose | integer | Numero totale di somministrazioni del vaccino monodose per giorno. |
| Terza dose | integer | Numero totale di somministrazioni dei vaccini che richiedono una dose aggiuntiva/richiamo per giorno. |
| Quarta dose | integer | Numero totale di somministrazioni a soggetti che hanno già completato il ciclo vaccinale primario con tre dosi (di cui la terza addizionale), dopo un intervallo minimo di almeno quattro mesi (120 giorni) dalla dose addizionale stessa. |



**somministrazioni_giornaliere_tipo_vaccino**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Giorno in cui è avvenuta la somministrazione. |
| Dosi totali somministrate | integer | Numero totale di somministrazioni dall'inizio della campagna vaccinale. |
| Dosi giornaliere somministrate | integer | Numero totale di somministrazioni per giorno. |
| Pfizer/BioNTech | integer | Numero totale di somministrazioni di Pfizer/BioNTech per giorno. |
| Moderna | integer | Numero totale di somministrazioni di Moderna per giorno. |
| Vaxzevria (AstraZeneca) | integer | Numero totale di somministrazioni di Vaxzevria (AstraZeneca) per giorno. |
| Janssen | integer | Numero totale di somministrazioni di Janssen per giorno. |

**storico_prime_dosi_per_eta/storico_seconnde_dosi_per_eta/storico_terze_dosi_per_eta**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Settimana del | string | Settimana in cui è avvenuta la somministrazione. |
| 05_11 | string | Numero totale di prime/seconde/terze somministrazioni nella fascia d'età 05-11. |
| 12_19 | string | Numero totale di prime/seconde/terze somministrazioni nella fascia d'età 12-19. |
| 20_29 | string | Numero totale di prime/seconde/terze somministrazioni nella fascia d'età 20-29. |
| 30_39 | string | Numero totale di prime/seconde/terze somministrazioni nella fascia d'età 30-39. |
| 40_49 | string | Numero totale di prime/seconde/terze somministrazioni nella fascia d'età 40-49. |
| 50_59 | string | Numero totale di prime/seconde/terze somministrazioni nella fascia d'età 50-59. |
| 60_69 | string | Numero totale di prime/seconde/terze somministrazioni nella fascia d'età 60-69. |
| 70_79 | string | Numero totale di prime/seconde/terze somministrazioni nella fascia d'età 70-79. |
| 80+ | string | Numero totale di prime/seconde/terze somministrazioni nella fascia d'età 80+. |

## Licenza

[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [Visualizza licenza](https://github.com/pcm-dpc/COVID-19/blob/master/LICENSE)

## Author / Copyright 

[2021 (c) Francesco Branda](https://francescobranda.netlify.app/) 


