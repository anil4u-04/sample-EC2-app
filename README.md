# sample-EC2-app(Python)

This is a simple web application using Python Flask. This is used in the demonstration deployment of sample application in EC2

Below are the steps required to get this working on a base linux system.

  -Install all required dependencies
  -Install and Configure Web Server
  -Start Web Server
  
## 1. Install all required dependencies

Python and its dependencies

    apt-get install -y python python-setuptools python-dev build-essential python-pip python-mysqldb
 
 ## 2. Install and Configure Web Server

Install Python Flask dependency

    pip install flask
    pip install flask-mysql

- Copy app.py or download it from source repository

## 3. Test

Open a browser and go to URL

    http://<IP>:5000                            => Welcome
    http://<IP>:5000/how%20are%20you            => I am good, how about you?
