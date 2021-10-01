## Location-Based Social Networks Datasets

<mark>The datasets can be used for POI/next-POI recommendation, trajectory recommendation, friends recommendation (link prediction),
activity recommendations, group recommendation and community discovery tasks.mark>
```
Statistics for FGCRec:

| Dataset           | Number of users | Number of POIs | Number of check-ins| User-POI matrix density|
| ----------------- | --------------- | -------------- | -------------------| ---------------------- |
| Foursquare_FGCRec | 7,642           | 28,484         | 512,523            | 0.13%                  |
| Gowalla_FGCRec    | 5,628           | 31,803         | 620,683            | 0.22%                  |
```

```
Statistics for FGRec:

| Dataset          | Number of users | Number of POIs | Number of categories | Number of check-ins    | Number of social links  | User-POI matrix density|
| ---------------- | --------------- | -------------- | ---------------------| ---------------------- |-------------------------|----------------------- |
| Foursquare_FGRec | 2,551           | 13,474         | 10                   | 124,933                | 32,512                  |0.291%                  |
| Yelp_FGRec       | 30,887          | 30,887         | 624                  | 860,888                | 860,888                 |0.14%                   |
```

tips： we divide the dataset into training set,  tuning set and test set in terms of the user’s check-in time. For
each user, the earliest 70 % check-ins are selected as training  data, the most recent 20 % check-ins as test data and the  remaining 10 % as the tuning data.

- Foursquare_FGCRec: Foursquare includes check-in data ranging from April 2012 to September 2013. 

- Gowalla_FGCRec: Gowalla contains check-in data ranging from February 2009 to October 2010.

- Foursquare_FGRec: Foursquare includes the check-in data of users who live in California, ranging from December 2009 to June 2013. 

- Yelp_FGRec: Yelp contains a large number of geotagged businesses (also called POIs) and reviews within several cities.

## Citation

Please cite our paper if you use the datasets (Foursquare_FGCRec, Gowalla_FGCRec):
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

Please cite our paper if you use the datasets (Foursquare_FGRec, Yelp_FGRec):

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

## Contact

If you have any questions, please contact us by suyijun.ucas@gmail.com, we will be happy to assist.

Last Update Date: October 1, 2021