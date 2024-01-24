* Kept source code inside code/main.py
* This source expect an input.csv file.This is also placed in code/input.csv.Required fields are added in this csv file.
* As requested,written a docker-compose file for creating two services.One for main application run and the other one for testing.
* In order to run and test the container application in an ubuntu environment ,follow the following steps.
    * sudo apt  install docker-compose
    * git clone to local directory
    * docker-compose up -d
    * check the output through 'docker logs code-testing'
