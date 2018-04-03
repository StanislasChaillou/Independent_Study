# Independent_Study
Independent Study @ Harvard GSD

<b><h2>Suggestive CAD</h2></b>

<i>Independent Study Proposal | Spring 2018 | Stanislas Chaillou | Advisor : Prof. Andrew Witt | Collaboration : Thomas Trinelle </i>

<p align="justify">The utilization of machine intuition has been leveraged in countless industries, from voice recognition, to suggestive search on the web, down to CCTV image processing. As the design process in architecture happens mostly through the medium of 3D software (Rhinoceros 3D, Maya, 3DSmax), our discipline could also benefit from the help of machine-generated suggestions. This is the goal of this independent study: study and propose a way to assist the designer, through suggestive modeling. As designers draw in the 3D space, a machine-learning-based algorithm would be able to assist the designer by proposing alternative, similar or complementary options to them. 
In a nutshell, we would look into precedent works in the field of suggestive modeling, to finally come up with a methodology and a tool that would be able to suggest models to designers as they draw. 
Problematic
Can machine learning enhance simple CAD tasks, and even assist the designer in the design process, by suggesting potential design options?</p>

<b>Description</b>

<p align="justify">This project can be broken down in 2 parts: understanding what we want the tool to be able to recognize (commonly called the testing set), and what we want the tool to be trained on (the training set). 
In our case simplifying the challenge to simple objects will insure the feasibility of this independent study. Therefore, we will train the algorithm to be able to recognize chairs, tables, doors and windows. Consequently, our training set will be a serie of 3d objects of these category, found in the ShapeNet  Library. This database offers pre-labeled objects and 360-degree views of them. The size of the training set and the training methodology will be determined in the first weeks of the independent study.
Ideally, using Keras, a machine learning package for Python, we will be able to create a convolutional neural network model, that will be able to learn from our objects’ images.
Using this technic, our goal ultimately is to be able to give a label to an object being modeled by the user, search in an extensive database of models according to the found label, and finally serve the matches we find to the user, through a simple interface. For the sake of this independent study, it might be more realistic to simply create a web-app that will be able to perform this task, and reserve for later the integration of this tool as a plugin in traditional modeling software.
Overall, our tool would comply with the following scheme:</p>
 
 ![alt text]( https://github.com/StanislasChaillou/Independent_Study/blob/master/Other/img_1.jpg)
 
<b>Advancement</b>

<ul>
  <li><a href="https://github.com/StanislasChaillou/Independent_Study/tree/master/Week_1"><b>Week 1</b> : Neural Network vs Convolutional Neural Network</a></li>
  <li><a href="https://github.com/StanislasChaillou/Independent_Study/tree/master/Week2"><b>Week 2</b> : Transfer Learning</a></li>
  <li><a href="https://github.com/StanislasChaillou/Independent_Study/tree/master/Week_3"><b>Week 3</b> : Classification Model</a></li>
  <li><a href="https://github.com/StanislasChaillou/Independent_Study/blob/master/Week%204/Readme.md"><b>Week 4</b> : Model Architecture</a></li>
</ul>
 
<b>Deliverables</b>

<ul>
<li>Research precedents in the field of suggestive CAD.</li>
   <li>Success criteria: precedents study is sufficiently exhaustive to inform future research. The precedents are understood in depth by the student.</li>
<li>Algorithm trained for a given set of 3d objects</li>
   <li>Success criteria: algorithm can perform simple recognition task on CAD objects, and tracing. One clear use case has been isolated, and the algorithm performs well enough for a given set of tasks.</li>
</ul>

<b>Scheduling</b>

<ul>
<li>02-05 until 02-26: Precedents study. </li>
<li>02-27 until 03-26: Database preparation, algorithm design and training</li>
<li>03-27 until 04-15: Algorithm test.</li>
<li>04-16 until 04-30: Further investigation, and application to concrete architectural use case.</li>
<li>04-30 until 05-06: Draft of final report</li>
</ul>

<b>Bibliography</b>

<ul>
<li>Multi-view Convolutional Neural Networks for 3D Shape Recognition, Hang Su, Subhransu Maji, Evangelos Kalogerakis, Erik Learned-Miller, University of Massachussets Amherst</li> 
<li>3D Modeling with Data-Driven Suggestions, Siddhartha Chaudhuri, Stanford University, August 2011.</li>
<li>Weakly-Supervised Component Suggestions for 3D Modeling, MINHYUK SUNG, Stanford University, HAO SU, Stanford University and University of California San Diego, VLADIMIR G. KIM, Adobe Research, SIDDHARTHA CHAUDHURI, IIT Bombay, LEONIDAS GUIBAS, Stanford University, Septembre 2017.</li>
<li>Data-Driven Suggestions for Creativity Support in 3D Modeling, Siddhartha Chaudhuri Vladlen Koltun, Stanford University, June 2016.</li>
<li>LightNet: A Lightweight 3D Convolutional Neural Network for Real-Time 3D Object Recognition, S. Zhi, Y. Liu, X. Li, and Y. Guo, National University of Defense Technology, China, August 2016.</li>
<li>Parsing IKEA Objects: Fine Pose Estimation, Joseph J. Lim Hamed Pirsiavash Antonio Torralba, MIT</li>
<li>Remixing and Resampling Three Dimensional Objects Use of Volumetric Representations And Machine Learning in Design, Nam Ju, Harvard Graduate School of Design, June 2017</li>
</ul>
