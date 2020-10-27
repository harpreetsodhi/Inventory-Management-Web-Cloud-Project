# Inventory Management
<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/Inventory-Management-Web-Cloud-Project/blob/master/assets/arch.png?raw=true0" width="600" height="350">
    </a>
</div>
<br />

> A cloud based web application to enable people or organizations running their services at a small scale to better manage their resources and data.

## USER MANAGEMENT PORTAL

#### Cloud Resources Information
The user management portal is built using Sails.js which uses MVC architecture. So, the controller acts as the backend and views are the frontend for our application. This application is containerized and deployed on Amazon AWS as an EC2 instance. The database is hosted on Amazon RDS, which is a managed relational database.

#### Software Used
The user portal is built using sails.js framework where we used HTML, JavaScript and jQuery. For the frontend, we have used Bootstrap for interacive user experience

#### Security mechanisms for communication/storage
Two-phase locking protocol has been used to avoid any false update operation and inconsistency in the orders table maintained by the company. We send the user passwords by encrypting them and store them in database as ciphertext. We have made sure not to store passwords as plaintext anywhere in the code.

## PACKAGE MANAGEMENT PORTAL

#### Cloud Resources Information
The UI for the package management is dockerized and hosted on DockerHub. This dockerized app is hosted on AWS Elastic Beanstalk instance. Serverless Computing is used for company’s backend by using Amazon Web Services (AWS) platform. Several AWS services such as API Gateway, AWS Lambda, AWS-RDS have been used.

#### Software Used
We have used NodeJS and ExpressJS for designing the backend routing and controlling logic for Package Providers. Javascript templates are used for UI pages and handling HTML/CSS pages. For effective User Experience, Bootstrap-4 havs been used as a CSS framework for designing the frontend.

## INVENTORY MANAGEMET PORTAL

#### Cloud Resources Information
The backend for the company has been maintained over serverless computing frameworks/services provided by Amazon Web Services (AWS) platform. Several AWS services such as API Gateway, AWS Lambda, AWS-RDS has been used. To deploy the frontend for the company, we have used the OpenStack instance. A fully dockerized container has been made and deployed on OpenStack instance.

#### Software Used
NodeJS and ExpressJS has been used for designing the backend routing and controlling logic for Inventory. Embedded Javascript templates have been used for UI designing and handling HTML/CSS pages. For effective User Experience, Bootstrap-4 and MdBootstrap have been used as a CSS framework for designing the frontend.

# Demo

<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/Inventory-Management-Web-Cloud-Project/blob/master/assets/1.png?raw=true0" width="600" height="350">
    </a>
</div>
<br />

<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/Inventory-Management-Web-Cloud-Project/blob/master/assets/2.png?raw=true0" width="600" height="350">
    </a>
</div>
<br />

<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/Inventory-Management-Web-Cloud-Project/blob/master/assets/3.png?raw=true0" width="600" height="350">
    </a>
</div>
<br />

<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/Inventory-Management-Web-Cloud-Project/blob/master/assets/4.png?raw=true0" width="600" height="350">
    </a>
</div>
<br />

<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/Inventory-Management-Web-Cloud-Project/blob/master/assets/5.png?raw=true0" width="600" height="350">
    </a>
</div>
<br />

<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/Inventory-Management-Web-Cloud-Project/blob/master/assets/6.png?raw=true0" width="600" height="350">
    </a>
</div>
<br />


<div align="center">
    <a>
        <img src="https://github.com/harpreetsodhi/Inventory-Management-Web-Cloud-Project/blob/master/assets/7.png?raw=true0" width="600" height="350">
    </a>
</div>
<br />
