# Lab 3: LLM for KNIME (News Classification)

## Traccia del Laboratorio

In questo esercizio l'obiettivo è classificare gli articoli del dataset `newsCorpora.csv` nelle quattro categorie (Business, Science and Technology, Entertainment, Health) basandosi sull'attributo `PUBLISHER`, esplorando l'uso di LLM per supportare la progettazione dei workflow in KNIME.

**Passaggi principali richiesti:**
1. Importazione del dataset e gestione dello sbilanciamento delle quattro classi.
2. Preprocessing e conversione della feature `PUBLISHER` da stringa a rappresentazione numerica.
3. Addestramento e ottimizzazione dell'Rprop MLP Learner (layer nascosti e neuroni per layer).
4. Configurazione e integrazione del Keras Network Learner previa trasformazione One-to-Many delle classi target.
5. Addestramento del Decision Tree Learner con ottimizzazione del parametro *Minimum Number of Records per Node*.
6. Consultazione dell'LLM per la risoluzione di problemi di configurazione (ambiente Python/Keras) e la selezione dei range di ottimizzazione degli iperparametri.
7. Valutazione e confronto dei modelli tramite Scorer, matrici di confusione, Accuracy e Cohen's Kappa.

## Report e Soluzione
Il report PDF completo di analisi dettagliate, grafici, metriche comparative e matrici di confusione è disponibile al link sottostante:

[Report Lab 3](./report_classification.pdf)
