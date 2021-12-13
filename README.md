## Location-Based Social Networks Datasets

**The datasets can be used for POI/next-POI recommendation, trajectory recommendation, friends recommendation (link prediction), activity recommendations, group recommendation and community discovery tasks.**

```
Dataset Statistics used in FGCRec (see our paper FGCRec: Fine-Grained Geographical Characteristics Modeling for Point-of-Interest Recommendation for details):

| Dataset           | Number of users | Number of POIs | Number of check-ins| User-POI matrix density|
| ----------------- | --------------- | -------------- | -------------------| ---------------------- |
| Foursquare_FGCRec | 7,642           | 28,484         | 512,523            | 0.13%                  |
| Gowalla_FGCRec    | 5,628           | 31,803         | 620,683            | 0.22%                  |
```

```
Dataset Statistics used in FGRec (see our paper FGRec: A Fine-Grained Point-of-Interest Recommendation Framework by Capturing Intrinsic Influences for details):

| Dataset          | Number of users | Number of POIs | Number of categories | Number of check-ins    | Number of social links  | User-POI matrix density|
| ---------------- | --------------- | -------------- | ---------------------| ---------------------- |-------------------------|----------------------- |
| Foursquare_FGRec | 2,551           | 13,474         | 10                   | 124,933                | 32,512                  |0.291%                  |
| Yelp_FGRec       | 30,887          | 30,887         | 624                  | 860,888                | 860,888                 |0.14%                   |
```

```
Dataset Statistics used in CARec (see our paper CARec: Content-Aware Point-of-Interest Recommendation via Adaptive Bayesian Personalized Ranking for details):
| Dataset          | Number of users | Number of POIs | Number of check-ins    | Number of reviews       | User-POI matrix density|
| ---------------- | --------------- | -------------- | ---------------------- |-------------------------|----------------------- |
| Foursquare_CARec | 9,728           | 12,449         | 177,142                | 234,793                 |0.15%                   |
| Yelp_CARec       | 5,577           | 6,900          | 518,186                | 542,707                 |0.46%                   |
```

```
Dataset Statistics used in MUC (see our paper Next Check-ins Prediction via History and Friendship on Location-Based Social Networks for details):

| Dataset        | Number of users | Number of POIs | Number of check-ins    | Number of social links  |
| -------------- | --------------- | -------------- | ---------------------- |-------------------------|
| Foursquare_MUC | 11,326          | 182,968        | 1,385,223              | 47,164                  |
| Gowalla_MUC    | 107,092         | 1,280,969      | 6,442,890              | 950,327                 |
```

tips： we divide the dataset into training set,  tuning set and test set in terms of the user’s check-in time. For
each user, the earliest 70 % check-ins are selected as training  data, the most recent 20 % check-ins as test data and the  remaining 10 % as the tuning data.

- Foursquare_FGCRec: Foursquare includes check-in data ranging from April 2012 to September 2013. 

- Gowalla_FGCRec: Gowalla contains check-in data ranging from February 2009 to October 2010.

- Foursquare_FGRec: Foursquare includes the check-in data of users who live in California, ranging from December 2009 to June 2013. 

- Yelp_FGRec: Yelp contains a large number of geotagged businesses (also called POIs) and reviews within several cities.

- Foursquare_CARec:  We filter users who visited less than 10 POIs in Foursquare dataset and POIs visited by less than 10 users.

- Yelp_CARec: https://www.yelp.com/dataset. We filter users who visited less than 32 POIs in Foursquare dataset and POIs visited by less than 31 users.

- Foursquare_MUC: Foursquare contains check-in data ranging from January 2011 to July 2011. 

- Gowalla_MUC: Gowalla includes check-in data between Feb. 2009 and Oct 2010.

## Citation

Please cite [our paper FGCRec](./ICC2020_FGCRec.pdf) if you use the datasets (Foursquare_FGCRec, Gowalla_FGCRec):
```
@inproceedings{suicc2020fgcrec,
  title={FGCRec: Fine-Grained Geographical Characteristics Modeling for Point-of-Interest Recommendation},
  author={Yijun Su, Xiang Li, Baoping Liu, Daren Zha, Ji Xiang, Wei Tang and Neng Gao},
  booktitle={IEEE International Conference on Communications}, 
  pages={1-6},
  doi={10.1109/ICC40277.2020.9148797},
  year={2020}
}
```

Please cite [our paper FGRec](./IJCNN2020_FGRec.pdf) if you use the datasets (Foursquare_FGRec, Yelp_FGRec):

```
@inproceedings{suijcnn2020fgrec,
  title={FGRec: A Fine-Grained Point-of-Interest Recommendation Framework by Capturing Intrinsic Influences},
  author={Yijun Su, Jia-Dong Zhang, Xiang Li,  Daren Zha, Ji Xiang, Wei Tang and Neng Gao},
  booktitle={IEEE International Joint Conference on Neural Networks, {IJCNN} 2020}, 
  pages={1-9},
  doi={10.1109/IJCNN48605.2020.9207571},
  year={2020}
}
```

Please cite [our paper CARec](./ICONIP2020_CARec.pdf) if you use the datasets (Foursquare_CARec, Yelp_CARec):

```
@article{LiuSZGX19,
  title={CARec: Content-Aware Point-of-Interest Recommendation via Adaptive Bayesian Personalized Ranking},
  author={Baoping Liu, Yijun Su,  Daren Zha, Neng Gao, and Ji Xiang},
  journal={Australian Journal of Intelligent Information Processing Systems}
  volume= {15},
  number= {3},
  pages= {61--68},
  year= {2019}
}
```

Please cite [our paper MUC](./MDM2018_MUC.pdf) if you use the datasets (Foursquare_MUC, Yelp_MUC):

```
@inproceedings{SuLTXH18,
  title={Next Check-in Location Prediction via Footprints and Friendship on Location-Based Social Networks},
  author={Yijun Su, Xiang Li,  Wei Tang, Ji Xiang and Neng Gao},
  booktitle={IEEE International Conference on Mobile Data Management, {MDM} 2018}, 
  pages={251-256},
  doi={10.1109/MDM.2018.00044},
  year={2018}
}
```
## Contact

If you have any questions, please contact us by suyijun.ucas@gmail.com, we will be happy to assist.

Last Update Date: December 13, 2021