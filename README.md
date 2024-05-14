# Soil Health and Crop Recommendation
<h2>Objective</h2>
<p>To build a ML/DL model which takes the soil features like macro nutrients and micro nutrients into account to recommend crops and give a fertility score</p>

<h2>Dataset</h2>
<p>The dataset consists of soil data in 3 districts. The dataset has 18 columns and 2736 instances. The 18 columns include pH, EC, OC, N, P, K, S, Ca, Mg, Zn, Fe, Cu, Mn, Mo, Tex, District Label</p>

<h2>Models</h2>
<p>1. Decision Tree</p>
<p>2. SVM </p>
<p>3. Random Forest</p>
<p>4. Artificial Neural Networks</p>
<h2>Accuracy</h2>
<p>1. Decision Tree: Gave an accuracy of 99.63%</p>
<p>2.1 SVM with RBF kernel: Gave an accuracy of 86.13%/p>
<p>2.2 SVM with Polynomial Kernel: Gave an accuracy of 94.89%</p> 
<p>3. Random Forest: Gave an ccuracy of 99.78%</p>
<p>4. ANN M1 with 5 dense layers and relu activation function on alternate layers and sigmoid on last layer, and adam optimiser: Gave an accuracy of 85%</p>
<p>5. ANN M2 with 5 dense layers and relu activation function on all layers and softmax on the last layer, and rmsprop optimiser: gave an accuracy of 95%</p>
<p> Although ML models show more accuracy than DL models, it is proven that for a large amount ofdata DL models are more precise. Hence, ANN M2 is chosen as the suitable model. </p>

<img src="soil 1.jpeg.jpeg">

# Working
<p> The website Crop Booster is integrated with the ANN model. The user must input the soil features, and the crops recommended will be displayed along with fetility score.</p>
<img src="soil 2.jpeg">
