# DiabeteX - Take the Insulin
Diabetes is among critical diseases and lots of people are suffering from this disease. Age, obesity, lack of exercise, hereditary diabetes, living style, bad diet, high blood pressure, etc. can cause Diabetes. People having diabetes have high risk of diseases like heart disease, kidney disease, stroke, eye problem, nerve damage, etc.

#### Deep learning with neural networks is used to predict the probability of having diabetes in the future. 

### Based on the feature importance:
- Glucose is the most important factor in determining the onset of diabetes followed by BMI and Age.
- Other factors such as Diabetes Pedigree Function, Pregnancies, Blood Pressure, Skin Thickness and Insulin also contributes to the prediction.

### Tech Stacks Used:

- HTML
- CSS
- Flask
- Keras
- Tensorflow
- Deep Learning
- Docker

### Get Started

1) Pull the Image from DockerHub.
```sh
docker pull manan3349/diabetes_app:latest
```
2) Launch a Container to run our application.
```sh
 docker run -itd --name <any_name> -p 2222:1111 manan3349/diabetes_app
```
3) You then need to attach(go inside) the container.
```sh
docker attach <container_name>
```
4) Run the flask app:
```sh
 cd /ws1/
 flask run -host=0.0.0.0 -port=1111    or     python3 app.py
```
5) Go to BaseOS and retrive the IP
```sh
ifconfig enp0s3
```
6) Go to browser and search as:
```sh
http://<ip of baseos>:2222/home
```
7) Put your data to know the working of app.
