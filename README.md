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
│   │   ├── Cosenza
│   │       ├── Cosenza.xlsx
│   │       ├── Cosenza.csv
│   │       ├── comuni
│   │           ├── Marzo_2020
│   │               ├── ASP_CS_2020-03-24.csv
│   │                   ...
│   │           ├── Aprile_2020
│   │               ├── ASP_CS_2020-04-01.csv
│   │               ...
│   │           ...
│   │   ├── Crotone
│   │       ├── Crotone.xlsx
│   │       ├── Catanzaro.csv
│   │   ├── Reggio Calabria
│   │       ├── Reggio Calabria.xlsx
│   │       ├── Reggio Calabria.csv
│   │   ├── Vibo Valentia
│   │       ├── Vibo Valentia.xlsx
│   │       ├── Vibo Valentia.csv
│   ├── regione
│   │   ├── Calabria.xlsx
│   │   ├── Calabria.csv
│   ├── vaccinazione
│   │   ├── dosi_consegnate_consumate_per_settimana.csv
│   │   ├── dosi_consegnate_per_settimana.csv
│   │   ├── somministrazioni_giornaliere.csv
│   │   ├── somministrazioni_giornaliere_per_categoria.csv
│   │   ├── somministrazioni_giornaliere_per_eta_prima_dose.csv
│   │   ├── somministrazioni_giornaliere_tipo_dose.csv
│   │   ├── somministrazioni_per_eta_prima_dose.csv
│   │   ├── somministrazioni_per_eta_seconda_dose.csv

```

# Descrizione dataset

Nella cartella dati si possono trovare le seguenti tabelle in formato xlsx e csv: 
*   **Calabria**: dati sull'andamento del COVID-19 a livello regionale. 
*   **Catanzaro**: dati sull'andamento del COVID-19 a Catanzaro.
*   **Cosenza**: dati sull'andamento del COVID-19 a Cosenza.
*   **Crotone**: dati sull'andamento del COVID-19 a Crotone.
*   **Reggio Calabria**: dati sull'andamento del COVID-19 a Reggio Calabria.
*   **Vibo Valentia**: dati sull'andamento del COVID-19 a Vibo Valentia.
*   **ASP_PROVINCIA_ANNO-MESE-GIORNO**: dati sull'andamento del COVID-19 suddivisi per data e comune. 
*   **dosi_consegnate_per_settimana**: dati sul numero di dosi dei vaccini anti-COVID-19 consegnate settimanalmente.
*   **dosi_consegnate_consumate_per_settimana**: dati sul numero di dosi di vaccino consegnate e quelle somministrate su base settimanale.
*   **somministrazioni_giornaliere**: dati sul numero assoluto di dosi somministrate al giorno.
*   **somministrazioni_giornaliere_per_categoria**: dati sul numero assoluto di dosi di vaccino somministrate al giorno per categoria di popolazione.
*   **somministrazioni_giornaliere_per_eta_prima_dose**: dati sul numero assoluto di dosi di vaccino somministrate (prima dose) al giorno per età.
*   **somministrazioni_giornaliere_per_tipo_dose**: dati sul numero assoluto di dosi somministrate al giorno, suddiviso per prima dose e seconda dose.
*   **somministrazioni_per_eta_prima_dose**: dati sulla percentuale di popolazione che ha ricevuto solo la prima dose di vaccino. 
*   **somministrazioni_per_eta_seconda_dose**: dati sulla percentuale di popolazione che ha completato il ciclo vaccinale (2 dosi di vaccino). 




I campi di ogni tabella sono schematizzati come riportato di seguito:

**Calabria** - **Catanzaro** - **Cosenza** - **Crotone** - **Reggio Calabria** - **Vibo Valentia**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Data in cui si registrano nuovi casi. |
| Nuovi casi | integer | Numero totale di persone risultate positive nelle ultime 24 ore. |
| Media 7 giorni | integer | Vengono considerati i dati di un determinato periodo e ne viene calcolata la media sommandoli fra loro e dividendo per il numero totale di valori.|
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


## Licenza

[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [Visualizza licenza](https://github.com/pcm-dpc/COVID-19/blob/master/LICENSE)

## Author / Copyright 

[2021 (c) Francesco Branda](https://francescobranda.netlify.app/) 


