## Week 3

Work completed this week:

- **Dataset Improvement**:
  - Script GH components to generate batch of images from 3D models, based on a spherical rotation:  
  
  <div align="center" style="padding:10px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week_3/Chair_view.jpg" width="700"></div>
  
  - Double size of dataset: Increase number of classes (10) and number of images per object (from 14 to 30).
- **Reduce overfitting**:
  - Increase dataset size
  - Add gaussian blur to images
  - Delete last layer of pretrained model
  - Add drop-out layers
- **Deployed early version of Web-App** for Testing, based on three.js template. >> http://stanislaschaillou.com/model_viewer/

**Next Steps**: 
  - Further train algorithm to reach 92/93% accuracy on validation set
  - Further tune model to counter overfitting. 
  - Save model to the back-end of web-app, and connect back and front end of web-app.
  - Look into 3d object matching (rather than guessing only the label, order object within found class from best to worst match)
