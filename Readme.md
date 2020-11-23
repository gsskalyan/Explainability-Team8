# Project - Explainability
## Group - 8
### Members
- 	Shivakalyan Soundarathiagarajan (UCID - ss4477)
-	Kowsick Venkatachalapathi (UCID - KV322)
-	Adish Vakharia (UCID - AAV57)


The three parts of Project are submitted in directory structure as shown below,

### Part1
-	LIME -  Local Interpretable Model-Agnostic Explanations Implementation execution
-	Python Notebook with execution steps and output
-	Results and logs - Adding Google Drive link since models and logs could not be uploaded to Git hub owing to size restrictions
	
| Model | Epochs | Accuracy | IPYNB | Results | Tensorboard
| :---         |     :---:      |          ---: | :---         |     :---:      |     :---:      |
| Binary   | 100     | 96.25%    | [Binary_covid_cxr_100_epoch.ipynb](https://github.com/gsskalyan/Explainability-Team8/blob/master/Part1/binary_100_epochs/Binary_covid_cxr_100_epoch.ipynb)   | [results and logs](https://drive.google.com/drive/u/0/folders/1Yc6s18Z6DwhsOLtZEyB-nWhNLo_wWzJG) | [link](https://tensorboard.dev/experiment/ohoj0G5NRqWZYlwb8wb0zQ/)
| Multi class   | 45     | 79%    | [Multiclass_covid_cxr_45_epoch.ipynb](https://github.com/gsskalyan/Explainability-Team8/blob/master/Part1/multi_class_45_epoch/Multiclass_covid_cxr_45_epoch.ipynb)   | [results and logs](https://drive.google.com/drive/folders/1ug5ywpO_fmE7xbYrp66Ov36EN5MV7Wtm) | [link](https://tensorboard.dev/experiment/0f9f4f73Sgmbpm7be9Lg1w/)
| Binary(trial run)   | 10     | 97% (with high loss)    | [Binary_covid_cxr_10_epochs.ipynb](https://github.com/gsskalyan/Explainability-Team8/blob/master/Part1/binary_10_epochs/Binary_covid_cxr_10_epochs.ipynb)   | [results and logs](https://drive.google.com/drive/u/0/folders/1Yc6s18Z6DwhsOLtZEyB-nWhNLo_wWzJG) | [link](https://tensorboard.dev/experiment/i3fkQAPMQxuO2Qwl07x9Jw/)

### Part 2
-	SHAP Summary
-	PDF Report explaining SHAP Summary can be found [here](https://github.com/gsskalyan/Explainability-Team8/blob/master/Part2/Explainability_SHAP_Summary.pdf)
-	Summary Includes:
	    -	Detailed explanation about SHAP Model,its concepts with diagrams
	    -	Steps involved to plugin Covid19-Pneumonia model(pre-trained) to SHAP (Gradient Explainer)

### Part 3
-	Plugin Covid19-Pneumonia model(pre-trained) to SHAP
-	Python Notebook with execution steps and output can be found [here](https://github.com/gsskalyan/Explainability-Team8/blob/master/Part3/SHAP_Part3.ipynb)
-	Uses Gradient Explainer
-	(Constraints faced while executing)
