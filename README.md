# Project Title
Catasto Impianti Termici (CIT ex SIGIT)

# Project Description
Il CIT è lo strumento informativo per la gestione del Catasto degli Impianti Termici e di Condizionamento della Regione Piemonte che consente la gestione informatizzata del libretto d'impianto, dei rapporti di controllo e delle ispezioni.
Il CIT permette di gestire i dati degli impianti termici presenti sul territorio regionale e di condividerli con la Pubblica Amministrazione, in linea con la normativa che prevede che dal 5 ottobre 2014 si utilizzino i nuovi modelli di libretto di impianto e di rapporto di efficienza per le attività di installazione o manutenzione degli impianti termici.
La Regione Piemonte istituisce il CIT con l'obiettivo di organizzare in modo unitario i dati relativi agli impianti termici e di favorire l'attività di ispezione sugli impianti stessi in tutto il territorio regionale. Il sistema permette agli operatori degli impianti termici di adempiere agli obblighi amministrativi e alle autorità competenti di organizzare le attività relative alle ispezioni sugli impianti termici. Inoltre consente anche ai cittadini, attraverso l'accesso via web, di verificare la situazione del proprio impianto e ottenere tutte le informazioni in materia di impianti termici ed efficienza energetica.
Gli obiettivi del CIT sono: 
- realizzare la dematerializzazione delle pratiche amministrative
- uniformare le procedure per la gestione degli impianti termici
- assicurare la raccolta e la condivisione di dati omogenei sul territorio regionale
- realizzare servizi per i soggetti che a vario titolo sono coinvolti nella gestione dell'impianto termico nel corso del suo intero ciclo di vita
- fornire alle autorità competenti e agli ispettori strumenti per le attività ispettive e per la predisposizione degli eventuali provvedimenti sanzionatori
- gestire le anomalie e le prescrizioni per gli impianti termici che non risultino in regola e il conseguente iter di sospensione dell'esercizio degli impianti fino alla loro regolarizzazione.

Le funzionalità del CIT sono: 
- compilazione digitale del libretto di impianto
- compilazione digitale dei rapporti di controllo
- subentro impresa / responsabile
- consultazione degli impianti
- ispezioni
- assunzione o revoca di responsabilità da parte del terzo responsabile
- delega per il caricamento dei dati
- acquisizione dei dati dei distributori
	  
# Getting Started
Il prodotto SIGIT è composto dalle seguenti componenti:
- [SIGITWEBN](https://github.com/regione-piemonte/sigit-sigitwebn) (web application che consente la gestione degli impianti termici)
- [SIGITWEBA](https://github.com/regione-piemonte/sigit-sigitweba) (web application che consente l'accreditamento alla gestione degli impianti termici)
- [SIGITEXT](https://github.com/regione-piemonte/sigit-sigitext) (web service di pubblicazione servizi)
- [ELENCOM](https://github.com/regione-piemonte/sigit-elencom) (web application che consente la ricerca dei manutentori)
- [SIGITBATCHN](https://github.com/regione-piemonte/sigit-sigitbatchn) (batch per gestione import dati dei distributori)
- [SIGITDBNEW](https://github.com/regione-piemonte/sigit-sigitdbnew) (script per creazione e mantenimento DB proprietario)

Nei file README.md delle singole componenti verranno elencate le variabili per la loro configurazione.

# Prerequisites
I prerequisiti per l'installazione della componente sono i seguenti:
## Software
- [JDK 8](https://www.apache.org)
- [Apache 2.4](https://www.apache.org)
- [RedHat JBoss 6.4 GA](https://developers.redhat.com)  
- [PostgreSQL 9.6.11](https://www.postgresql.org/download/)  

- Tutte le librerie elencate nel BOM.csv devono essere accessibili per compilare il progetto. Le librerie sono pubblicate su http://repart.csi.it, ma per semplicità sono state incluse nella cartella lib/ di ogni singola componente, ad esclusione della libreria weblogic-client-3.0.0.jar che deve essere scaricata autonomamente dal sito di Oracle.

# Versioning
Per la gestione del codice sorgente viene utilizzata Git. Per la gestione del versioning si fa riferimento alla metodologia [Semantic Versioning](https://semver.org/) 

# Copyrights
(C) Copyright 2021 Regione Piemonte

# License
Questo software è distribuito con licenza EUPL-1.2
Consultare i file EUPL v1_2 IT-LICENSE.txt e EUPL v1_2 EN-LICENSE.txt per maggiorni dettagli.
