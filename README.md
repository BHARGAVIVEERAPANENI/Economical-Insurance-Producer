# Project Name
> Economical-Insurance-Producer


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)


## General Information
- This project will get CSV Files through Restapi and parse these files and produce these files into apache kafka. 

## Technologies Used
- Java - version 1.8
- Spring Boot - version 2.5.3
- Apache Kafka 



## Setup
project requirements/dependencies.
Open application.properties and replace Kafka Server IP and Port with your details.

spring.kafka.bootstrap-servers:localhost:9092


## Project Status
Project is:  complete
Sample Request:

POST /files/upload HTTP/1.1
Host: localhost:8080
Cache-Control: no-cache
Postman-Token: 6f6a7454-43f5-f3d4-5ae1-cc20b0fbac25
Content-Type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW

------WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="file1"; filename="convertcsv.csv"
Content-Type: application/vnd.ms-excel


------WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="file2"; filename="userInfo.csv"
Content-Type: application/vnd.ms-excel


------WebKitFormBoundary7MA4YWxkTrZu0gW--


## Room for Improvement
produce stream data/batch produce


