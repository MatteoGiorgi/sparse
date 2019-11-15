# Sparse

## Progetto di midterm per l'esame di *Sistemi operativi e laboratorio*
Il progetto prevede la realizzazione di un **insieme di funzioni C che lavorano su matrici sparse di double**. Si intendono *sparse* la matrici che contengo una bassissima percentuale di elementi diversi da 0. Queste matrici vengono solitamente rappresentate registrando solo gli elementi diversi da 0 e la loro posizione. Nel nostro caso utilizzeremo un array di puntatori a righe che contiene NULL se la riga contiene tutti valori uguali a zero o la lista delle colonne e dei valori diversi da zero.

---

Le **strutture dati da utilizzare** per la realizzazione delle matrici sparse e i prototipi delle funzioni da implementare sono definiti nel file sparse.h. Consigliamo di leggere accuratamente sparse.h prima di proseguire. L'implementazione della funzione di stampa e' fornita nel file *sparse_docenti.c*. Le funzioni definite in sparse.h possono essere implementate in un unico file *sparse.c*.  Se si vogliono usare piu' file si deve modificare il Makefile in modo che la compilazione avvenga automaticamente in modo corretto e tutti i file sviluppati vengano consegnati nel tar finale.

I commenti in *sparse.h* spiegano in dettaglio il comportamento delle varie funzioni, il significato dei parametri ed i valori restituiti secondo il formato Doxygen (chi e' interessato puo' leggere README.doxygen per i dettagli). Conviene testare le funzioni man mano che vengono sviluppate con dei *main()* di test evitando di scrivere tutto il codice prima di testarne il funzionamento. Questo permette di localizzare molto meglio errori ed anomalie. Solo quando siamo ragionevolmente convinti della correttezza del codice si puo' passare al testing automatico del codice con i test forniti dai docenti.
