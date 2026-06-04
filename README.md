# COVID-19_Detection

Link to dataset - [Click here](https://www.kaggle.com/datasets/hgunraj/covidxct)

### Workflow of Phase -1 : 
<p align="center"><img src="images/phase-1.jpg" height = "250" width="800"></p>

### Workflow of Phase -2 : 
<p align="center"><img src="images/phase-2.jpg" height = "200" width="800"></p>





# Quick Links
Two different models were trained in two differnt phases for 70 and 14 epochs respectively.

### Notebooks for training: 

* [Notebook](https://github.com/sanskar-hasija/COVID-19_Detection/blob/main/Phase-1.ipynb) - Phase-1 Training 

* [Notebook](https://github.com/sanskar-hasija/COVID-19_Detection/blob/main/Phase-1.ipynb) - Phase-2 Training 

The trained model for evaluation and inference can be downloaded from [here](https://github.com/sanskar-hasija/COVID-19_Detection/tree/main/models).


Predictions from both phase-1 and phase-2 on the test set were combined and confusion matrix for each phase as well as for combined phases was constructed.
* [Notebook](https://github.com/sanskar-hasija/COVID-19_Detection/blob/main/Testing_Evaluation.ipynb) - Evaluation 


# Training Curves 
### Loss Curves : 
<p align="center"><img src="images/phase%20-1%20loss.jpg" > <img src="images/phase%20-2%20loss.jpg" ></p>

### Accuracy Curves : 
<p align="center"><img src="images/phase-1%20acc.jpg" > <img src="images/phase%20-2%20acc.jpg" ></p>

# Results:

### Positive Predictive Value 
<div class="tg-wrap"><table class="tg">
  <tr>
    <th class="tg-7btt" colspan="3">Positive Predictive Value (%)</th>
  </tr>
  <tr>
    <td class="tg-7btt">Normal</td>
    <td class="tg-7btt">Pneumonia</td>
    <td class="tg-7btt">COVID-19</td>
  </tr>
  <tr>
    <td class="tg-c3ow">98.99</td>
    <td class="tg-c3ow">99.56</td>
    <td class="tg-c3ow">95.62</td>
  </tr>
</table></div>

### Sensitivity
<div class="tg-wrap"><table class="tg">
  <tr>
    <th class="tg-7btt" colspan="3">Sensitivity (%)</th>
  </tr>
  <tr>
    <td class="tg-7btt">Normal</td>
    <td class="tg-7btt">Pneumonia</td>
    <td class="tg-7btt">COVID-19</td>
  </tr>
  <tr>
    <td class="tg-c3ow">99.40</td>
    <td class="tg-c3ow">97.50</td>
    <td class="tg-c3ow">97.42</td>
  </tr>
</table></div>

### Specificity
<div class="tg-wrap"><table class="tg">
  <tr>
    <th class="tg-7btt" colspan="3">Specificity (%)</th>
  </tr>
  <tr>
    <td class="tg-7btt">Normal</td>
    <td class="tg-7btt">Pneumonia</td>
    <td class="tg-7btt">COVID-19</td>
  </tr>
  <tr>
    <td class="tg-c3ow">99.10</td>
    <td class="tg-c3ow">99.81</td>
    <td class="tg-c3ow">98.68</td>
  </tr>
</table></div>

### F1-Score 
<div class="tg-wrap"><table class="tg">
  <tr>
    <th class="tg-7btt" colspan="3">F1-Score (%)</th>
  </tr>
  <tr>
    <td class="tg-7btt">Normal</td>
    <td class="tg-7btt">Pneumonia</td>
    <td class="tg-7btt">COVID-19</td>
  </tr>
  <tr>
    <td class="tg-c3ow">99.19</td>
    <td class="tg-c3ow">98.52</td>
    <td class="tg-c3ow">96.57</td>
  </tr>
</table></div>

### Confusion Matrix
<p align="left"><img src="images/combined%20cm.jpg" ></p>
