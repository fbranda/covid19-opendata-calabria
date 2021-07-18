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
│   │
│   ├── regione
│   │   ├── Calabria.xlsx
│   │   ├── Calabria.csv
│   │   ├── Incidenza_per_centomila_abitanti.csv
│   │   ├── Tamponi_per_centomila_abitanti.csv
│   │   ├── Tamponi_per_settimana.csv
│   │   ├── Trend_settimanale_nuovi_casi.csv
│   │   ├── Trend_settimanale_decessi.csv
│   │   ├── Trend_settimanale_guariti.csv
│   │   ├── Trend_settimanale_ricoveri.csv
│   │   ├── Trend_settimanale_terapie_intensive.csv
│   │
│   ├── vaccinazione
│   │   ├── dosi_consegnate_per_tipo_vaccino_per_settimana.csv
│   │   ├── dosi_consegnate_somministrate_per_settimana.csv
│   │   ├── dosi_somministrate_per_tipo_vaccino_per_settimana.csv
│   │   ├── somministrazioni_giornaliere_per_eta_prima_dose.csv
│   │   ├── somministrazioni_giornaliere_tipo_dose.csv
│   │   ├── somministrazioni_giornaliere_tipo_vaccino.csv
│   │   ├── somministrazioni_per_copertura_vaccinale.csv

```

# Descrizione dataset

Nella cartella dati si possono trovare le seguenti tabelle in formato xlsx e csv: 
*   **Calabria**: dati sull'andamento del COVID-19 a livello regionale. 
*   **Incidenza_per_centomila_abitanti**: dati sul numero di nuovi casi positivi al COVID-19 ogni 100.000 abitanti su base settimanale.
*   **Tamponi_per_centomila_abitanti**: dati sul numero dei tamponi fatti ogni 100.000 abitanti su base settimanale.
*   **Tamponi_per_settimana**: dati sul numero di nuovi casi positivi al COVID-19 in rapporto al numero totale di tamponi fatti su base settimanale.
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
*   **dosi_consegnate_per_tipo_vaccino_per_settimana**: dati sul tipo di vaccino anti-COVID-19 consegnato settimanalmente.
*   **dosi_consegnate_somministrate_per_settimana**: dati sul numero di dosi di vaccino consegnate e somministrato su base settimanale.
*   **dosi_somministrate_per_tipo_vaccino_per_settimana**: dati sul tipo di vaccino anti-COVID-19 somministrato su base settimanale.
*   **somministrazioni_giornaliere_per_tipo_dose**: dati sul numero assoluto di dosi somministrate al giorno, suddiviso per prima dose, seconda dose e monodose.
*   **somministrazioni_giornaliere_per_tipo_vaccino**: dati sul numero assoluto di dosi somministrate al giorno, suddiviso per tipo di vaccino.
*   **somministrazioni_per_copertura_vaccinale**: dati sulla percentuale di popolazione che ha completato il ciclo vaccinale con due dosi o con vaccino monodose, o che ha ricevuto una sola dose di vaccino, o nessuna dose.


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

**Tamponi_per_centomila_abitanti** 

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Settimana di riferimento. |
| Tamponi per settimana | integer |  Numero di tamponi fatti ogni 100.000 abitanti su base settimanale. |

**Tamponi_per_settimana** 

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Settimana di riferimento. |
| Rapporto positivi / casi testati | double |  Nuovi casi positivi al COVID-19 in rapporto al numero totale di tamponi. |
| Casi per settimana | integer |  Numero di persone positive al COVID-19 su base settimanale. |
| Tamponi fatti | integer |  Numero di tamponi fatti su base settimanale. |

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

**dosi_somministrate_per_settimana**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Settimana di riferimento. |
| Dosi somministrate | integer | Numero totale di dosi somministrate per settimana. |

**somministrazioni_giornaliere**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Giorno in cui è avvenuta la somministrazione. |
| Somministrazioni | integer | Numero totale di somministrazioni per giorno. |


**somministrazioni_giornaliere_per_tipo_dose**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Giorno in cui è avvenuta la somministrazione. |
| Prima dose | integer | Numero totale di prime somministrazioni per giorno. |
| Seconda dose | integer | Numero totale di seconde somministrazioni per giorno. |
| Pregressa infezione | integer | Numero di somministrazioni effettuate a soggetti con pregressa infezione da COVID-19 nel periodo 3-6 mesi e che, pertanto, concludono il ciclo vaccinale con un'unica dose.  |
| Monodose | integer | Numero totale di somministrazioni del vaccino monodose per giorno. |

**somministrazioni_giornaliere_per_tipo_vaccino**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Giorno in cui è avvenuta la somministrazione. |
| Dosi totali somministrate | integer | Numero totale di somministrazioni dall'inizio della campagna vaccinale. |
| Dosi giornaliere somministrate | integer | Numero totale di somministrazioni per giorno. |
| Pfizer/BioNTech | integer | Numero totale di somministrazioni di Pfizer/BioNTech per giorno. |
| Moderna | integer | Numero totale di somministrazioni di Moderna per giorno. |
| Vaxzevria (AstraZeneca) | integer | Numero totale di somministrazioni di Vaxzevria (AstraZeneca) per giorno. |
| Janssen | integer | Numero totale di somministrazioni di Janssen per giorno. |

**somministrazioni_per_copertura_vaccinale**:

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Età | string | Fascia d'età di riferimento. |
| Solo 1ᵃ dose | double | Percentuale di popolazione che ha ricevuto solo la prima dose di vaccino. |
| Ciclo completo | double | Percentuale di popolazione che ha completato il ciclo vaccinale con due dosi o con vaccino monodose. |
| Nessuna dose | double | Percentuale di popolazione che non ha ricevuto ancora nessuna dose. |

**tipo_vaccino_per_settimana**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string | Settimana di riferimento. |
| Pfizer/BioNTech | integer | Numero totale di somministrazioni di Pfizer/BioNTech. |
| Moderna | integer | Numero totale di somministrazioni di Moderna. |
| Vaxzevria (AstraZeneca) | integer | Numero totale di somministrazioni di Vaxzevria (AstraZeneca). |
| Janssen | integer | Numero totale di somministrazioni di Janssen. |


## Licenza

[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [Visualizza licenza](https://github.com/pcm-dpc/COVID-19/blob/master/LICENSE)

## Author / Copyright 

[2021 (c) Francesco Branda](https://francescobranda.netlify.app/) 


