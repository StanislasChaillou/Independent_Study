
## Week 4

Work completed this week:

- **Defined overall model architecture**
  - 2 Steps:
    - **Classification**: Uses model trained on all classes | recognize class of 3D object
    - **Matching**: Uses model trained on objects of each specific class | one model per class | ranks all model in class from best to worst match.
    
      <div align="center" style="margin:20px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week 4/model_scheme_1.JPG" width="700"></div>
    
- **Classification** : [Training Notebook](https://github.com/StanislasChaillou/Independent_Study/blob/master/Week%204/Classification_Model.ipynb), [Testing Notebook](https://github.com/StanislasChaillou/Independent_Study/blob/master/Week%204/Classification_Model_testing.ipynb)

  <div align="center" style="margin:20px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week 4/ml_chair.gif" width="700"></div>

- **Matching** : [Notebook](https://github.com/StanislasChaillou/Independent_Study/blob/master/Week%204/Matching_Model.ipynb)

  <div align="center" style="margin:20px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week 4/best_match_1.JPG" width="700"></div>
      - Top 10 **best** matches in database (200 objects)

  <div align="center" style="margin:20px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week 4/best_matches_1.JPG" width="700"></div>
    
    - Top 10 **worst** matches in database (200 objects)
    
  <div align="center" style="margin:20px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week 4/worst_matches_1.JPG" width="700"></div>
