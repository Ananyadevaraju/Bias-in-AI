# CE888---Assignment-2
## Bias in Policing in the US: Detecting and Mitigating Disparate Impact

### Overview:
Various fields use machine learning algorithms in decision-making to reduce human prejudice. It is important for these algorithms' forecasts to be unbiased in order for them to be more accurate in the real world.
Bias in machine learning models could mainly be introduced by the data they are trained on. Bias in data could be a result of human bias or inconsistency in data collection. Either ways, these biases are not reliable in real world, especially when one group of people belonging to a protected class are more affected due to these biases, than the other, which is termed as disparate impact. Hence, in order to avoid models from learning bias and making biased predictions, it is important to detect and mitigate bias in the data before training the models. Moreover, detecting bias can become harder after modelling, especially in a legal setting.  
In this study, a metric called Disparate Impact ratio is used for detecting bias in data against sex and race of the suspects in predicting police arrests. Furthermore, a pre-processing algorithm called Disparate Impact Remover is used to mitigate the detected bias in the data, before training the model to attain a fairer machine learning model.

###  Data:
The data for stop, question and frisk for the year 2019 in New York is obtained from https://www1.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page .

### Progrmming language:
Python 3 and above

### Dependencies:
Install the following packages,
* aif360
* fairlearn
* BlackBoxAuditing

### To execute the code, open the "Assignment-2" notebook in colab and run each piece of code
