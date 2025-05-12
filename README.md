# Sentence_Splitting_Manzoni

This repository contains material related to the experiments carried out on sentence splitting of the novel "I Promessi Sposi" by Manzoni and on other Italian novels of the nineteenth century. At the moment the materials available include:
- folder "Manzoni-train-dev-test": dataset split in train/dev/test (80/10/10) used to retrain a [Stanza](https://stanfordnlp.github.io/stanza/) lemmatization model specific for the novel by Manzoni. Please note that only the segmentation has been checked and corrected;
- folder "test-novels": files used to evaluate the 7 sentence splitting tools on 4 novels of the 1800s: *I Promessi Sposi* (1840) by Manzoni, *I Malavoglia* (1881) by Giovanni Verga, *Le avventure di Pinocchio. Storia di un burattino* (1883) by Carlo Collodi, *Cuore* (1886) by Edmondo De Amicis.

A Colab notebook is available to run several of the systems (i.e. spacY, Stanza, Sentence Splitter, WtP) tested on the aforementioned novels: [https://colab.research.google.com/drive/1j0RhdutBVAxfxgX4X3XAPf1d52_xB9xz?usp=sharing](https://colab.research.google.com/drive/1j0RhdutBVAxfxgX4X3XAPf1d52_xB9xz?usp=sharing)
