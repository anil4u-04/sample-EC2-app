# sample-EC2-app(Python)

This is a simple web application using Python Flask. This is used in the demonstration deployment of sample application in EC2

Below are the steps required to get this working on a base linux system.

  -Install all required dependencies
  -Install and Configure Web Server
  -Start Web Server
  
## 1. Install all required dependencies

Python and its dependencies

    sudo apt-get update
    sudo apt-get install -y python3 python3-setuptools python3-dev build-essential python3-pip
 
 ## 2. Install and Configure Web Server

Install Python Flask dependency

    sudo apt install python3-flask

- Copy sampleApp.py or download it from source repository

## 3. Start Web Server

Start web server

    FLASK_APP=sampleApp.py flask run --host=0.0.0.0

## 4. Test

Open a browser and go to URL

    http://<IP>:5000                            => Welcome
    http://<IP>:5000/how%20are%20you            => I am good, how about you?
