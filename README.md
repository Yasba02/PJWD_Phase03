# PJWD_Phase03
Voyageons ensemble project is a university project of the course : "Java and Web Development". Voyageons ensemble was created with node.js and includes a database connection.


## **Table of Contents**
- [Prerequisites](#Prerequisites)
- [Installation](#installation)
- [Database Configuration](#DatabaseConfiguration)
- [Usage](#usage)
     - [User registration](#Userregistration)
     - [User authentification](#Userauthentification)
     - [Comment](#Comment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [References](#References)

## **Prerequisites**
- Make sure you have installed Mariadb and configured it successfully ( You have a user account with a username and a password).
- Make sure you have installed Node.js
- Make sure you have installed Git
- Make sure you have installed HeidiSQL if managing the database via a GUI (This step is optional)

## **Installation**
To install and run this project on your local machine, follow these steps:

1. Open your terminal and clone the project repository.
2. Navigate into the project folder and install the required Node.js dependencies.
3. Open Mariadb or HeidiSQL, and create a database named voyageonsensemble.
4. Import and run the setup.sql script located in the scripts directory.
5. Configure the server and ensure that all necessary environment variables and configurations are properly set.


## **Database Configuration**

1.Navigate to the root and search for a .envtest file and copy it.
2.Create a new .env file where you will paste the copied file.
3.Replace the placeholders with your test database connection details as explained in the .envtest
4. Run the application using : node index.js or nodemon index.js if you nodemon installed.
5. Once the server is running, visit the following link in your browser: http://localhost:3000

## **Recommended IDE setup**
VScode

## **Project Structure**
```
.
├── docs_phase3 # Screencast and additional documents for the university
│ └── PJWD_Screencast.mov # Screencast that demonstrates functionality of the application
├── public # Static files served directly by the server
│ ├── images # where all the images used in the application are stored
│ 
├── scripts # Scripts to run to set up the databases
│ ├── setup.sql
├── Backend
│ ├── index.js
├── node_modules
├── route
│ ├── comment.js
│ ├── route.js
├── views
│ ├── homepage.ejs
├── index.html
├── Aboutus.html
├── Aboutus.Signin.html
├── Africa.html
├── Algierarticle.html
├── America.html
├── Asia.html 
├── Australiaarticle.html
├── Baliarticle.html
├── Californiaarticle.html
├── cotactus.html
├── contactUs.Signin.html
├── Dubaiarticle.html
├── Egyptarticle.html
├── Europe.html
├── Hikingarticle.html
├── Homepage.html
├── Login.html
├── Japanarticle.html
├── Login.html
├── Maldivesarticle.html
├── Milanoarticle.html
├── Moroccoarticle.html
├── newyorkarticle.html
├── Niagarafallsarticle.html
├── Oceania.html
├── Parisarticle.html
├── publish.html
├── Publish.Signin.html
├── Safariarticle.html
├── SignIn.html
├── Switzerlandarticle.html
├── package.json
├── package-lock.json
├── LICENSE.txt # License file
└── README.md # This file
```

## **Usage**
Voyageons ensemble is a travel blog, where travelers share articles about their experiences with the website administration, after approval the articles can be published to the public on behalf of the writers. The website supports commenting system to enable communication between readers and authors, or between readers themselves. 

## **User registration**
In order to get the access to read the articles users must first click on "Sign in" button and register in the website, by providing a name, email-address and a password. Using an API the email-address is checked if it really exists or not. 
Upon to successfull registartion the user will be redirected to the home page where they can start navigating and reading articles of different countries, grouped together by continent. The contact page provides contact informations and social media accounts of the blog, while the publish page provides contact information for authors who want to publish their articles in the blog.

## **User authentification**
If an account has aleady been created, the user can directly click on log in and enter the registered email and password. If the entered credentials are correct the user will be redirected to the homepage with access to the entire website content.

## **Comment**
At the buttom of each article, users have a space where they can write their thoughts, questions and opinions in the comment box, and posting it after filling the name box too. 
Readers can also read the comments that other users have left in the comments list.

## **Contributing**
This project is currently not available for contribution, it's a university project. 
However feel free to explore the code and learn from it.

## **License **
This project is under MIT License. See the License file for more details.
