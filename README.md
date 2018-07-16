# HealthCare

Digital healthcare facilities can allow dissemination of specialised knowledge among the medical commmunity through advanced network ,tech enabled peer-to-peer reviews, emergency medical consulations during epidemics and crises, instant bookings of ambulances and labs ,Many others can be achieved with this.

### Tech Stack
```
Front End----> Angularjs

Middleware---> Amazon API Gateway

Backend---> Lambda functions based on Nodejs and DynamoDB as NoSQL DataBase
```
### Third party API's

```
1. BMI and Symptom Checker API from mashap.(https://market.mashape.com/navii/bmi-calculator)
2. Twilio API to send sms after booking.
```

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development. 

### Prerequisites

```
XAMMP webserver----> https://www.apachefriends.org/index.html
```
### Setup

#### PART1---- BACKEND

A step by step series of examples that tell you how to get a development env running

```
No need to setup any environment for backend, Currently using Amazon AWS Lambda that is exposed via Amazon API gateway and DynamoDB as NoSQL database. 

```

#### PART2---- UI

```
Clone the repository


```
```
Unzip the file and place the healtcare folder under C:/xampp/htdocs folder of xammp server
```
```
Change DocumentRoot and DirectoryRoot of your webserver to "/path to /healthcare"

like- DocumentRoot "C:/xampp/htdocs/healthcare"
<Directory "C:/xampp/htdocs/healthcare">

```
```
Try http://localhost/apps/index.html
```

