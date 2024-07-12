# Sentence_Splitting_Manzoni

This repository contains material related to the experiments carried out on sentence splitting of the novel "I Promessi Sposi" by Manzoni and on other Italian novels of the nineteenth century. At the moment the materials available include:
- dataset split in train/dev/test (80/10/10) used to retrain a [Stanza](https://stanfordnlp.github.io/stanza/) model specific for the novel by Manzoni; the test set was used to evaluate the performance of various automatic tools;
- the files used to evaluate the same tools on 3 other novels of the 1800s: *I Malavoglia* (1881) by Giovanni Verga, *Le avventure di Pinocchio. Storia di un burattino* (1883) by Carlo Collodi, *Cuore* (1886) by Edmondo De Amicis.

A Colab notebook was created to run many of the systems (i.e. spacY, Stanza, Sentence Splitter, WtP) tested on the aforementioned novels: [https://colab.research.google.com/drive/1j0RhdutBVAxfxgX4X3XAPf1d52_xB9xz?usp=sharing](https://colab.research.google.com/drive/1j0RhdutBVAxfxgX4X3XAPf1d52_xB9xz?usp=sharing)
