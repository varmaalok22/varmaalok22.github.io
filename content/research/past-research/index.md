+++
date = '2025-12-27T13:40:31-08:00'
draft = false
title = 'Past Research'
hide_title = true
+++

## Past Research

### Bistability in cerebellar Purkinje neurons
For my PhD, I studied the physiology of Purkinje neurons in the cerebellum of larval zebrafish (_Danio rerio_). Purkinje neurons (PNs) are the central processing units of the cerebellum. They are spontaneously active and exhibit bistability, switching between two stable firing modes — tonic and bursting. If each of the ~200 PNs in a larval zebrafish can be in one of two states, there is an astronomically large number of possible state combinations the population could exist in. The broad goal of my graduate thesis was to understand what the bistable firing mode of a cell meant for circuit function, and how a circuit could function in the face of such combinatorics.

By recording from pairs of PNs, I showed that pairs of bursting PNs exhibited more similar activity patterns compared to other state combinations. This means that the degree of population synchrony in the cerebellum can be tuned by simply altering the fraction of bursting neurons in the population. Hence, I wanted to measure the proportion and distribution of cells in each state within the PN population, and understand how it could change over the course of circuit maturation.

Calcium imaging is the gold standard method in querying population activity. However, calcium signals in bistable cells like PNs do not disambiguate cellular state. I hypothesized that machine learning models could be trained to deduce bistable state from calcium signals, given sufficient data. Hence, I generated a state- labelled imaging dataset by first mapping the relationship between electrophysiology and calcium signals in PNs, and then applying it to all our lab's electrophysiological recordings. In collaboration with scientists at the Indian Institute of Science, I trained and benchmarked several machine learning models to classify neuronal state from calcium imaging data, and found that a CNN-LSTM (convolutional neural network with long short-term memory) performed best. Notably, although trained on data from zebrafish PNs, this network, called CaMLsort, generalized well to other bistable neurons like the dopaminergic neurons of the ventral tegmental area in mammals (see _[Varma et al., 2024](https://doi.org/10.1113/JP284373)_). Given that tools to study bistability have been lacking thus far, this work now sets the stage for further mechanistic and functional investigations into bistability across different neural circuits.

For more details of my PhD work, you can read my thesis **[here](AV_Thesis_Final.pdf)**.
