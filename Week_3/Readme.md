## Week 3

Work completed this week:

- **Dataset Improvement**:
  - Script GH components to generate batch of images from 3D models, based on a spherical rotation:  
  
  <div align="center" style="margin:20px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week_3/Chair_view.jpg" width="700"></div>
  <div align="center" style="margin:20px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week_3/capture.gif" width="700"></div>
  
  - Double size of dataset: Increase number of classes (10) and number of images per object (from 14 to 30).
  - Upload to cloud, with FloydHub, to leverage higher computational power.
  
  - **Result:**
  For the same amount of classes, a higher image resolution and a new image capturing path for the camera, our model performs around 93% accuracy on the validation set (against 80% for the previous model).
    <div align="center" style="margin:20px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week_3/model1model2_.jpg" width="700"></div>
  
  
- **Reduce overfitting**:
  - Increase dataset size
  - Add gaussian blur to images
  - Delete last layer of pretrained model
  - Add drop-out layers
- **Deployed early version of Web-App** for Testing, based on three.js template. >> http://stanislaschaillou.com/model_viewer/
  <div align="center" style="margin:20px"><img src="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week_3/webapp.jpg" width="700"></div>

**Next Steps**: 
  - Save model to the back-end of web-app, and connect back and front end of web-app.
  - Look into 3d object matching (rather than guessing only the label, order object within found class from best to worst match)
