# bangkit-machine-learning

The source code of machine learning model's API of SnapCat in order to complete Bangkit Capstone Project

# Model Building's Notebook
- nanti

# API URL
- https://snapcat-image.example/prediction

# Dataset Reasource
- [Kaggle](https://www.kaggle.com/datasets/shawngano/gano-cat-breed-image-collection/data)

# API Endpoint
|   Endpoint   |   Method  | Body Sent (JSON) |                    Description                     |
|   :------:   | :-------: | :--------------: | :------------------------------------------------: |
|      /       |    GET    |       None       |          HTTP GET REQUEST Testing Endpoint         |
| /prediction  |    POST   | file: Image file |        HTTP POST REQUEST Prediction Endpoint       |


# The flow of Machine Learning Service
- nanti dibuat flowchartnya

# How to run this Flask app
- Clone this repo
- Open terminal and go to this project's root directory
- Type `python -m venv .venv` and hit enter
- In Linux, type `source .venv/bin/activate`
- In Windows, type `.venv\Scripts\activate`
- Type `pip install -r requirements.txt`
- Serve the Flask app by typing `flask run`
- It will run on `http://127.0.0.1:5000`

# How to predict image with Postman
- Open Postman
- Enter URL request bar with `http://127.0.0.1:5000/prediction`
- Select method POST
- Go to Body tab and select form-data
- Change key from form-data with file (it must be named `file`)
- Input the image that you want predict as a value of the key
- Send the request

![image](https://github.com/alfarissss/snapcat-ml-api/assets/134893804/8d790a17-5cdb-4d8f-bac5-4daced1b1789)

![image](https://github.com/alfarissss/snapcat-ml-api/assets/134893804/6f84e930-2fe6-4d19-a08e-b977ed5e5096)


## Architecture of SSD EfficientnetB0 for Cat Breeds Detection
![image](https://github.com/alfarissss/snapcat-ml-api/assets/134893804/3a9aefe9-ee82-4caf-a8eb-7bcd8c1bc3f1)


# References
- Karlita, T., Choirunisa, N. A., Asmara, R., & Setyorini, F. (2022). Cat Breeds Classification Using Compound Model Scaling Convolutional Neural Networks. Dalam Proceedings of the International Conference on Applied Science and Technology on Social Science 2021 (iCAST-SS 2021) (hlm. 909-914). Atlantis Press. DOI: 10.2991/assehr.k.220301.150 [Atlantis Press](https://www.atlantis-press.com/proceedings/icast-ss-21/125971139)
