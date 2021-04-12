<h1 align="center">Covid-19 Opendata Regione Calabria</h1>

<div align="center">
<img src="calabria-regione-1.svg" width="150">
</div>
<br />

# Descrizione repository

Questo repository contiene i dati in formato aperto relativi all'andamento del COVID-19 in Calabria e mette a disposizione, le seguenti informazioni aggiornate quotidianamente:

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
│   │       ── Catanzaro.xlsx
│   │   ├── Cosenza
│   │       ├── Cosenza.xlsx
│   │       ├── comuni
│   │           ├── Marzo_2020
│   │               ├── ASP_CS_Marzo_2020.csv
│   │               ...
│   │   ├── Crotone
│   │       ├── Crotone.xlsx
│   │   ├── Reggio Calabria
│   │       ├── Reggio Calabria.xlsx
│   │   ├── Vibo Valentia
│   │       ├── Vibo Valentia.xlsx
│   ├── regione
│   │   ├── Calabria.xlsx

```

# Descrizione dataset

Nella cartella dati si possono trovare le seguenti tabelle in formato xlsx e csv: 
*   **Calabria**: dati relativi all'andamento del COVID-19 a livello regionale. 
*   **Catanzaro**: dati relativi all'andamento del COVID-19 a Catanzaro.
*   **Cosenza**: dati relativi all'andamento del COVID-19 a Cosenza.
*   **Crotone**: dati relativi all'andamento del COVID-19 a Crotone.
*   **Reggio Calabria**: dati relativi all'andamento del COVID-19 a Reggio Calabria.
*   **Vibo Valentia**: dati relativi all'andamento del COVID-19 a Vibo Valentia.
*   **ASP_CS_Mese_Anno**: dati relativi all'andamento del COVID-19 suddivisi per comuni della provincia di Cosenza. 



I campi di ogni tabella sono schematizzati come riportato di seguito:

**Calabria** - **Catanzaro** - **Cosenza** - **Crotone** - **Reggio Calabria** - **Vibo Valentia**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Data in cui si registrano nuovi casi. |
| Nuovi casi | integer | Andamento dei nuovi casi registrati quotidianemente. |
| Media 7 giorni | integer | Vengono considerati i dati di un determinato periodo e ne viene calcolata la media sommandoli fra loro e dividendo per il numero totale di valori.|
| Deceduti | integer | Numero totale di persone morte e risultate positive al COVID-19. |
| Dimessi/Guariti | integer | Numero di pazienti dimessi dagli ospedali, o perché non necessitano più di cure ospedaliere e quindi vengono isolate presso il loro domicilio, o perché ne è stata verificata la negatività attraverso il tampone. |
| Ricoverati | integer | Numero totale di persone ricoverate in ospedale con sintomi connessi al COVID-19. |
| Terapia intensiva | integer | Numero totale di posti letto di TI occupati da pazienti positivi al COVID-19. |

**ASP_CS_Mese_Anno**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Comune | string | Nome completo del comune. |
| A domicilio | integer | Numero di persone positive al COVID-19 che non necessitano di cure ospedaliere e si trovano in isolamento presso il loro domicilio. |
| Guariti | integer | Numero di pazienti dimessi dagli ospedali, o perché non necessitano più di cure ospedaliere e quindi vengono isolate presso il loro domicilio, o perché ne è stata verificata la negatività attraverso il tampone. |
| Deceduti | integer | Numero totale di persone morte e risultate positive al COVID-19. |
| Ricoverati | integer | Numero totale di persone ricoverate in ospedale con sintomi connessi al COVID-19. |
| Totale casi| integer | Numero totale di nuovi casi registrati nelle ultime 24 ore (a domicilio + guariti + deceduti + ricoverati). |







## Author / Copyright 

[2021 (c) Francesco Branda](https://francescobranda.netlify.app/)
