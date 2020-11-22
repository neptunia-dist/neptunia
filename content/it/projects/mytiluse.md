---
date: 2020-11-17
description: "MytiluSE, Modelling mytilus farming System with Enhanced web technologies"
featured_image: "/images/mytiluse001.png"
tags: ["progetto","meteo","HPSCSmartLab"]
title: "MytiluSE"
website: http://meteo.uniparthenope.it/mytiluse
pi: "Raffaele Montella"
---
Evoluzione del precedente progetto denominato "Sviluppo di un sistema software per la modellistica di eventi d'inquinamento basato su tecnologie di calcolo distribuito ad alte prestazioni e dotato di interfaccia web avanzata".
Questo progetto ha come obiettivo la creazione di un sistema modellistico accoppiato atmosfera-mare-dispersione di inquinanti capace di fornire uno strumento di semplice uso dedicato agli operatori del settore pianificazione e mantenimento di impianti di miticoltura e itticoltura.
L'interazione con il sistema è resa possibile attraverso una interfaccia web per la consultazione ubiquitaria secondo il paradigma del Web-GIS.

Il sistema software è costituito dalle seguenti component:
- Modello WRF (Weather Research and Forecast) per la produzione di forzanti atmosferici per il modello di dinamica marina
- Modello ROMS (Regional Ocean Model System) per la produzione dei campi di correnti marine in 3 dimensioni;
- Modello di dispersione di inquinanti passivi
- Portale web per l'interazione con strumenti tipo Web-GIS.

Il lavoro di sviluppo del software è costituito dall'integrazione di modelli community con componenti software create ad hoc in modo da realizzare un sistema efficace ed efficiente unico nel suo genere.

# MytiluSE
Il progetto MytiluSE è convenzione di ricerca fra il Dipartimento di Scienze e Tecnologie e l'Unità Operativa Dirigenziale Prevenzione e Sanità Pubblica Veterinaria della Regione Campania avente come oggetto  sviluppo, miglioramento e sperimentazione di un sistema software per la modellistica di eventi di inquinamento marino basato su tecnologie di calcolo distribuito ad alte prestazioni, facente anche uso di tecnologie relative ai sistemi embedded, ai dispositivi mobili e alla internet of things, dotato di interfaccia web avanzata e con domini spaziali ad alta risoluzione estesi alla Regione Campania.
Nell'ambito di questo progetto sono state svolte attività di ricerca in collaborazione con RDCEP e CI (2016 -- 2019).

## Obiettivo
L'obiettivo è lo sviluppo, il miglioramento e la sperimentazione del sistema modellistico accoppiato atmosfera-mare-dispersione di inquinanti capace di fornire uno strumento di semplice uso dedicato agli operatori del settore pianificazione e mantenimento di impianti di mitilicoltura e itticoltura già operazionale.

Il progetto prevede lo sviluppo, il miglioramento e la sperimentazione di un sistema prototipale, già operazionale, costituito da una catena modellistica previsionale su tre comparti funzionali, atmosfera, mare, inquinanti, secondo le seguenti linee di ricerca:

- Estensione del dominio computazionale del modello numerico di simulazione delle correnti marine ROMS (Regional Ocean Model System) alle coste campane;
- Aggiornamento e miglioramento del modello di dispersione d'inquinanti passivi;
- Miglioramento del portale web tecnico per il monitoraggio del sistema con strumenti web dinamici;
- Sviluppo delle componenti software per la gestione dei dati atti alla valutazione e validazione dei risultati con tecniche di data science;
- Realizzazione dell'hardware per l'implementazione di un sistema di data crowdsourcing per dati marini costieri e implementazione del relativo software e sperimentazione raccolta dei dati;
- Realizzazione di una app per dispositivi mobili per semplificare le operazioni di campionamento e analisi dei dati in situ.

## Alcuni risultati
* Implementazione della catena modellistica operazionale previsionale con accesso privato ai risultati;
* Acquisizione di risorse computazionali da integrare nel cluster HPC-GPU denominato BlackJeans (http://rcf.uniparthenope.it) attualmente in produzione;
* Integrazione del modello implementato (ROMS) e del modello per il calcolo previsionale della dispersione di inquinanti passivi denominato WaComM, sviluppato in questo progetto, nella catena modellistica implementata nell'ambito del progetto CMMMA.
* Progettazione e sviluppo del sistema di acquisizione dati batimetrici in crowd-sourcing.
* Progettazione e sviluppo di algoritmi per l'elaborazione dei dati batimetrici con tecniche di cloud computing e vitualizzazione GPGPU fruttando parte dei risultati del progetto RAPID (H2020).
* Progettazione ed implementazione di un'applicazione di tipo workflow basata su Galaxy-ES e sfruttando parte dei risultati del progetto FACE-IT (NFS).
* Risultati sperimentali che confortano l'efficacia del sistema sviluppato dal confronto dei risultati dei modelli con dati acquisiti sul campo.
* Sviluppo di una app mobile ad uso tecnico sfuttando l'interazione con il progetto CMMMA.
* Sperimentazione di tecniche innovative basate sull'intelligenza artificiale per la predizione dell'accumulo degli inquinanti nei molluschi.

{{< figure src="/images/cmmma004.png" title="Golfo di Napoli, previsione di corrente superficiale." >}}

{{< figure src="/images/cmmma005.png" title="Golfo di Pozzuoli, previsione di trasporto e diffusione di inquinanti." >}}

## Funanziamento
Unità Operativa Dirigenziale Prevenzione e Sanità Pubblica Veterinaria della Regione Campania, € 85.000,00 (2016-2019).
