# Client APP
[Client APP](https://github.com/hafidzamr/heart-disease)

# Heart Disease Prediction - Logistic-Regression
Dataset From [Kaggle](http://kaggle.com)

# Requirement 
```
 - Operating System x64
 - Python 3.6.8
```
# How to Install

Run pip install -r requirements.txt (Python 2) (but you still can use it if you have installed python3)

Run pip3 install -r requirements.txt (Python 3)

# How to use?

Method request POST :

example body
```
{
	"age":"57",
	"sex":"0",
	"cp":"1",
	"trestbps":"130",
	"chol":"236",
	"fbs":"0",
	"restecg":"0",
	"thalach":"174",
	"exang":"0",
	"oldpeak":"0",
	"slope":"1",
	"ca":"1",
	"thal":"2"
}
```

# Example using Postman
![test_postman](https://user-images.githubusercontent.com/49369600/65882729-c97a3980-e3bf-11e9-97aa-48c3be27cf05.png)
```
*Note
* Dont Forget to change form-data to raw and change type of raw from text to json on body
* Result =
	- "Tidak Terkena Penyakit Jantung" is mean "No Have Heart Disease"
	- "Terkena Penyakit Jantung" is mean "Have Heart Disease"
```




