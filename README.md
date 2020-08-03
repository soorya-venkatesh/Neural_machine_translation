# Neural_machine_translation

## Problem Statement:
Develop a Nerual machine translation system for English to Spanish.

## Dataset:
http://www.manythings.org/anki/ita-eng.zip
Contains 350k datapoints

## Approach:
A encoder-decoder model with Luong attention was used
https://arxiv.org/abs/1508.04025

## Results on Test Data:
BLEU score using dot score:0.6724
BLEU score using general score:0.6760
BLEU score using concat score:0.6904
