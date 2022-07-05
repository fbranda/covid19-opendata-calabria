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
│   │   ├── catanzaro.csv
│   │
│   │   ├── Cosenza
│   │       ├── cosenza.csv
│   │       ├── comuni
│   │           ├── Marzo_2020
│   │               ├── ASP_CS_2020-03-24.csv
│   │                   ...
│   │           ├── Aprile_2020
│   │               ├── ASP_CS_2020-04-01.csv
│   │               ...
│   │           ...
│   │
│   │   ├── crotone.csv
│   │
│   │   ├── reggio_calabria.csv
│   │
│   │   ├── vibo_valentia.csv
│   │
│   ├── regione
│   │   ├── calabria.csv

```

I campi di ogni tabella sono schematizzati come riportato di seguito:

**Calabria**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Giorno in cui si registrano nuovi casi. |
| Nuovi casi | integer | Numero totale di persone risultate positive nelle ultime 24 ore. |
| Deceduti | integer | Numero totale di persone morte e risultate positive al COVID-19. |
| Guariti/Dimessi | integer | Numero di pazienti dimessi dagli ospedali, o perché non necessitano più di cure ospedaliere e quindi vengono isolate presso il loro domicilio, o perché ne è stata verificata la negatività attraverso il tampone. |
| Ricoverati | integer | Numero totale di persone ricoverate in ospedale con sintomi connessi al COVID-19. |
| Terapia intensiva | integer | Numero totale di posti letto di TI occupati da pazienti positivi al COVID-19. |
| Rt_positivi | float | Tasso di contagio Rt dei casi positivi. |
| Rt_sintomatici | float | Tasso di contagio Rt dei casi sintomatici. |
| Nuovi_casi_{0-5}{6_12}{13_19}{20_29}{30_39}{40_49}{50_59}{60_69}{70_79}{80_89}{90+} | float | Media mobile (7 giorni) dei nuovi casi positivi per fascia d'età |
| Ricoveri_{0-5}{6_12}{13_19}{20_29}{30_39}{40_49}{50_59}{60_69}{70_79}{80_89}{90+} | float | Media mobile (7 giorni) dei ricoveri per fascia d'età |  
| Terapia_intensiva_{0-5}{6_12}{13_19}{20_29}{30_39}{40_49}{50_59}{60_69}{70_79}{80_89}{90+} | float | Media mobile (7 giorni) dei ricoveri in terapia intensiva per fascia d'età |
| Deceduti_{0-5}{6_12}{13_19}{20_29}{30_39}{40_49}{50_59}{60_69}{70_79}{80_89}{90+} | float | Media mobile (7 giorni) dei decessi per fascia d'età |

**Catanzaro-Cosenza-Crotone-Reggio Calabria-Vibo Valentia**

| Campo | Tipo di dati | Descrizione |
| --- | --- | --- |
| Data | string |  Giorno in cui si registrano nuovi casi. |
| Nuovi casi | integer | Numero totale di persone risultate positive nelle ultime 24 ore. |
| Deceduti | integer | Numero totale di persone morte e risultate positive al COVID-19. |
| Guariti/Dimessi | integer | Numero di pazienti dimessi dagli ospedali, o perché non necessitano più di cure ospedaliere e quindi vengono isolate presso il loro domicilio, o perché ne è stata verificata la negatività attraverso il tampone. |
| Ricoverati | integer | Numero totale di persone ricoverate in ospedale con sintomi connessi al COVID-19. |
| Terapia intensiva | integer | Numero totale di posti letto di TI occupati da pazienti positivi al COVID-19. |
| Rt_positivi | float | Tasso di contagio Rt dei casi positivi. |
| Rt_sintomatici | float | Tasso di contagio Rt dei casi sintomatici. |

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

[2022 (c) Francesco Branda](https://francescobranda.netlify.app/) 


