# capstone_project

In questa repository è possibile trovare i vari file e il lavoro finale, presentato in power bi, per il completamento del corso Data Analyst DAPT0123 della scuola tech Epicode.
- I file in python sono quelli che riportano il codice che, a partire dai dati presenti su Kaggle, mi hanno permesso di creare ed estrarre 3 file csv differenti e customizzati per la mia analisi finale.
  In particolare, ho scelto un di creare un file che riportasse la produzione elettrica per varie fonti energetiche; un file per mostrare lo share delle varie risorse nel market energetico generale;
  un file con dati legati all'energia pro-capite, popolazione, pil. I 3 csv che ho creato sono stati, quindi, rimodellati per avere queste informazioni in relazione ai Paesi OPEC e ad altri stati come: Russia, Cina,   Giappone, India, Canada, Stati Uniti; tutto a partire dagli anni 2000.
- La cartella Kaggle contiene il file originario: "World Energy Consumption" su cui ho implementato il codice python e i file csv che ho creato ed estrapolato tramite python.
- La cartella in formato zip: "revisionati" contiene tutti i file di cui mi sono servita per il lavoro in Power BI, comprese le immagini
- Il lavoro finale di presentazione è visibile nel file "CAPSTONE PROJECT. pbix" .
- In Power BI, attraverso l'utilizzo di formule DAX, sono state create delle misure per considerare e valutare la presenza di dati non disponibili sul totale. In pratica, attraverso le misure "blank" e
  "%  blank", calcolate per ogni query, è possibile valutare il numero e la percentuale di dati non disponibili per ogni set di dati. Questa analisi può essere svolta direttamente in Power BI, attraverso l'uso di     tabelle che permettono di valutare la % di NaN per ogni Paese, risorsa, anno o una combinazione di questi parametri; oppure è possibile estrapolare questi dati e creare questi "raggruppamenti" con SQL attraverso    dei group by. L'analisi è stata effettuata e presentata durante i check settimanali ma non è stata inserita nelle dashboard di Power BI per evitare di appesantire troppo la presentazione.
- La scelta di non sostituire -o eliminare i valori nulli- è data dal fatto che anche l'assenza di dati rappresenta un'informazione, ci dà un'indicazione precisa di quali Paesi è stato possibile analizzare con        maggiore certezza e presenza di dati. In alcuni casi è stato anche possibile verifiicare come i dati fossero meno presenti in determinati anni o, piuttosto, per determinate risorse energetiche (es.       
  risorsa nucleare).

  N.B. La presentazione finale e definitiva è contenuta nel file Power BI: "CAPSTONE PROJECT"
