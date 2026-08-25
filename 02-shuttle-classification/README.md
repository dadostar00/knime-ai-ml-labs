# Lab 2: Exercises - Classification (Shuttle Dataset)

## Traccia del Laboratorio

In questo esercizio l'obiettivo è effettuare la classificazione multiclasse sul dataset Statlog Shuttle (dall'UCI Machine Learning Repository) confrontando diversi algoritmi su piattaforma KNIME Analytics e valutando la capacità dei modelli di gestire il forte sbilanciamento delle classi.

**Passaggi principali richiesti:**
1. Importazione del dataset Shuttle, pulizia dei dati e partizionamento in Train e Test Set.
2. Implementazione e valutazione del classificatore Naïve Bayes, con analisi di sensibilità ai parametri ($p$, $\sigma$) e calcolo delle curve ROC/AUC.
3. Addestramento del modello k-Nearest Neighbors (kNN), confrontando configurazioni pesate e non pesate sulla distanza al variare di $k$.
4. Implementazione delle Support Vector Machine (SVM), confrontando le prestazioni del kernel Polinomiale e RBF ($\sigma = 0.1$ e $\sigma = 0.5$).
5. Addestramento e ottimizzazione del Decision Tree Learner tramite Parameter Optimization Loop (iperparametri *MinRecordsPerNode* e *Gini Index*).
6. Valutazione e confronto delle prestazioni dei quattro modelli tramite metriche di scoring ($R^2$, Accuracy, Cohen's Kappa), matrici di confusione e recall sulle classi minoritarie.

## Documentazione Completa
Il report PDF completo di analisi dettagliate, grafici, metriche comparative e matrici di confusione è disponibile al link sottostante:

[Report Lab 2](./report_classification.pdf)
