## Location-Based Social Networks Datasets

```
Statistics:

| Dataset           | Number of users | Number of POIs | Number of check-ins| User-POI matrix density|
| ----------------- | --------------- | -------------- | -------------------| ---------------------- |
| Foursquare_FGCRec | 7,642           | 28,484         | 512,523            | 0.13%                  |
| Gowalla_FGCRec    | 5,628           | 31,803         | 620,683            | 0.22%                  |
```
tips： we divide the dataset into training set,  tuning set and test set in terms of the user’s check-in time. For
each user, the earliest 70 % check-ins are selected as training  data, the most recent 20 % check-ins as test data and the  remaining 10 % as the tuning data.

- Foursquare_FGCRec: Foursquare includes check-in data ranging from April 2012 to September 2013. 

- Gowalla_FGCRec: Gowalla contains check-in data ranging from February 2009 to October 2010.

## Citation
Please cite our paper if you use the datasets:
```
@inproceedings{su2020fgrec,
  title={FGCRec: Fine-Grained Geographical Characteristics Modeling for Point-of-Interest Recommendation},
  author={Yijun Su, Xiang Li, Baoping Liu, Daren Zha, Ji Xiang, Wei Tang and Neng Gao},
  booktitle={IEEE International Conference on Communications}, 
  pages={1-6},
  doi={10.1109/ICC40277.2020.9148797},
  year={2020}
}
```
## Contact

If you have any questions, please contact us by suyijun.ucas@gmail.com, we will be happy to assist.

Last Update Date: August 12, 2021