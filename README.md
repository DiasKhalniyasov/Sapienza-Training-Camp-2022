# Sapienza-Training-Camp-2022
Sapienza Training Camp 2022 competition, hosted by Leonardo Labs

main : https://www.kaggle.com/competitions/sapienza-training-camp-2022

Our solution: resnext50_32x4d -> linear (7) using pytorch
Mean F1 Score: 0.97560

In this competition there are 7 different classes of marine ships:


0: battleships
1: coast-guard
2: containerships
3: cruise-ships
4: drilling-rigs
5: motor-yachts
6: submarines


Every classes have a different number of images per class.
The images have been scraped from internet, and a certain numer of "no ship" images can be present in the train dataset (e.g. advertising images)
