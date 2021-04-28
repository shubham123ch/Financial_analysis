# zomato_rating
project with visualisation

Table of Content:

Demo
Overview
Motivation
Technical Aspect
Installation
Run
Deployement on Heroku
Directory Tree
To Do
Bug / Feature Request
Technologies Used
Team
License
Credits
Demo
Link: https://indian-currency-prediction.herokuapp.com



Overview:



Motivation:



Technical Aspect:

This project is divided into two part:

Installation:

The Code is written in Python 3.7. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the 

repository:

Training a deep learning model 

using Keras. (Not covered in this repo. I'll update the link here once I make it public.)
Building and hosting a Flask web app on Heroku.
A user can choose image from a device or capture it using a pre-built camera.
Used Amazon S3 Bucket to store the uploaded image and predictions.
Used CSRF Token to protect against CSRF attacks.
Used Sentry to catch the exception on the back-end.
After uploading the image, the predictions are displayed on a Bar Chart.



pip install -r requirements.txt
Run
STEP 1

Linux and macOS User

Windows User


Directory Tree
├── app 
│   ├── __init__.py
│   ├── main.py
│   ├── model
│   ├── static
│   └── templates
├── config
│   ├── __init__.py
├── processing
│   ├── __init__.py
├── requirements.txt
├── runtime.txt
├── LICENSE
├── Procfile
├── README.md
└── wsgi.py

To Do:

Convert the app to run without any internet connection, i.e. PWA.
Add a better vizualization chart to display the predictions.
Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue here by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue here. Please include sample queries and their corresponding results.

Technologies Used:


   

 

Team/Author:

shubham

License:

Apache license


Copyright 2021 shubham chaturvedi

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

Credits:

Google Images Download - This project wouldn't have been possible without this tool. It saved my enormous amount of time while collecting the data. A huge shout-out to its creator Hardik Vasa.
