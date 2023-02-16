# Neural_machine_translation

## Problem Statement:
Develop a Nerual machine translation system for English to Spanish.

## Dataset:
http://www.manythings.org/anki/ita-eng.zip

Contains 350k datapoints

## Approach:
A encoder-decoder model with Luong attention was used
https://arxiv.org/abs/1508.04025

## KPI on Test Data:
* BLEU score using dot score:0.6724
* BLEU score using general score:0.6760
* BLEU score using concat score:0.6904

## Sample results
![c2](https://user-images.githubusercontent.com/63422900/219459128-0e5354e0-e472-4968-b79c-a2318326951e.png)
![c1](https://user-images.githubusercontent.com/63422900/219458861-fa29ace6-c8b0-4104-9dd0-1df15bfb474b.png)

