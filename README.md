# Caligrafy - A Light PHP Framework
![Caligrafy](http://broadposter.com/public/uploads/08fc6d5af320f97c1f341b82.png)

## Requirements
+ PHP > 7.0
+ MySql > 5.6

## Installation
+ Pull the code from github
+ create a .env file by copying the example `cp .env.example .env`
+ Change the values in .env file to match your local or production server settings
+ run `composer install` to get all the dependencies needed
+ make the folder `/public/uploads/` readable if you intend to allow uploads in your application. You will need to run the command `sudo chmod -R 777 /public/uploads`
+ You are good to go!

> For more advanced installation, check the documentation [here](https://github.com/DoryAzar/mvc/wiki/1.-Getting-Started)

## Dependencies

This framework uses several third-party librairies that are included in the distribution
+ Phug (PHP Pug) is used for creating powerful HTML views and templates
+ GUMP Validation is used to provide an easy and painless data validation and filtering
+ dotEnv is used to provide the capability of setting up environment variables for both local and production servers
+ claviska/SimpleImage is used to provide the ability to do server-side manipulations on images
+ stripe/stripe-php is used for payment features


## Documentation

We have created a rigorous documentation to help you understand the basics of the framework and to get you started as quickly as possible

1. [Getting Started](https://github.com/DoryAzar/mvc/wiki/1.-Getting-Started)
    > + [Installation](https://github.com/DoryAzar/mvc/wiki/1.-Getting-Started)
    > + [Understanding MVC architecture](https://github.com/DoryAzar/mvc/wiki/1.-Getting-Started#architecture)
    > + [Framework fundamentals](https://github.com/DoryAzar/mvc/wiki/1.-Getting-Started#fundamentals)
    > + [File Structure](https://github.com/DoryAzar/mvc/wiki/1.-Getting-Started#filestructure)

2. [Routing](https://github.com/DoryAzar/mvc/wiki/2.-Routing)
    > + [Defining Routes](https://github.com/DoryAzar/mvc/wiki/2.-Routing#definingroutes)
    > + ["Hello World" Route](https://github.com/DoryAzar/mvc/wiki/2.-Routing#basicroute)
    > + [Routing with parameters](https://github.com/DoryAzar/mvc/wiki/2.-Routing#parameterroute)
    > + [Controller Routing](https://github.com/DoryAzar/mvc/wiki/2.-Routing#controllerroute)
    > + [HTML Form Methods](https://github.com/DoryAzar/mvc/wiki/2.-Routing#htmlformmethods)
    
3. [Request](https://github.com/DoryAzar/mvc/wiki/3.-Request)
    > + [Accessing the Request](https://github.com/DoryAzar/mvc/wiki/3.-Request#accessrequest)
    > + [Request Properties](https://github.com/DoryAzar/mvc/wiki/3.-Request#requestproperties)
    > + [Request Methods](https://github.com/DoryAzar/mvc/wiki/3.-Request#requestmethods)

4. [Models](https://github.com/DoryAzar/mvc/wiki/4.-Models)
    > + [Relational Databases](https://github.com/DoryAzar/mvc/wiki/4.-Models)
    > + [Model Fundamentals](https://github.com/DoryAzar/mvc/wiki/4.-Models#modelfundamentals)
    > + [Interfacing with the Model](https://github.com/DoryAzar/mvc/wiki/4.-Models#modelfundamentals)
    > + [Model Methods](https://github.com/DoryAzar/mvc/wiki/4.-Models#modelmethods)
5. [Relationships](https://github.com/DoryAzar/mvc/wiki/5.-Relationships)
    > + [One-to-One Relationship](https://github.com/DoryAzar/mvc/wiki/5.-Relationships)
    > + [One-to-Many Relationship](https://github.com/DoryAzar/mvc/wiki/5.-Relationships#onetomany)
    > + [Many-to-Many Relationship](https://github.com/DoryAzar/mvc/wiki/5.-Relationships#manytomany)
    > + [Overriding Naming Convention](https://github.com/DoryAzar/mvc/wiki/5.-Relationships#override)
6. [Validation](https://github.com/DoryAzar/mvc/wiki/6.-Validation)
    > + [Data Validation](https://github.com/DoryAzar/mvc/wiki/6.-Validation#validation)
    > + [Data Filtering](https://github.com/DoryAzar/mvc/wiki/6.-Validation#filter)
    > + [Validation & Filtering](https://github.com/DoryAzar/mvc/wiki/6.-Validation#validationandfiltering)
    > + [File Validation](https://github.com/DoryAzar/mvc/wiki/6.-Validation#filevalidation)
7. [Views](https://github.com/DoryAzar/mvc/wiki/7.-Views)
    > + [Introduction to Phug](https://github.com/DoryAzar/mvc/wiki/7.-Views#introduction)
    > + [Pug Templates](https://github.com/DoryAzar/mvc/wiki/7.-Views#templates)
    > + [Structure and Format](https://github.com/DoryAzar/mvc/wiki/7.-Views#structure)
    > + [Getting Started with Views](https://github.com/DoryAzar/mvc/wiki/7.-Views#viewsstartup)
    > + [Simple View](https://github.com/DoryAzar/mvc/wiki/7.-Views#simpleview)
    > + [View with parameters](https://github.com/DoryAzar/mvc/wiki/7.-Views#parameterview)
8. [Controllers](https://github.com/DoryAzar/mvc/wiki/8.-Controllers)
    > + [Getting Started with Controllers](https://github.com/DoryAzar/mvc/wiki/8.-Controllers)
    > + [Creating a Controller](https://github.com/DoryAzar/mvc/wiki/8.-Controllers#createcontroller)
    > + [Routing to the Controller](https://github.com/DoryAzar/mvc/wiki/8.-Controllers#controllerrouting)
    > + [Controller Context](https://github.com/DoryAzar/mvc/wiki/8.-Controllers#controllercontext)
    > + [Controller Methods](https://github.com/DoryAzar/mvc/wiki/8.-Controllers#controllermethods)
9. [Helpers, Forms & REST API](https://github.com/DoryAzar/mvc/wiki/9.-Helpers-,-Forms-&-REST-API)
    > + [Helpers](https://github.com/DoryAzar/mvc/wiki/9.-Helpers-,-Forms-&-REST-API#helpers)
    > + [HTML Forms](https://github.com/DoryAzar/mvc/wiki/9.-Helpers-,-Forms-&-REST-API#forms)
    > + [REST API](https://github.com/DoryAzar/mvc/wiki/9.-Helpers-,-Forms-&-REST-API#restapi)
10. [Authentication](https://github.com/DoryAzar/mvc/wiki/9.1-Authentication)
11. [Stripe Payment](https://github.com/DoryAzar/mvc/wiki/9.2-Stripe-Payment)
12. [Metadata & Rich Cards](https://github.com/DoryAzar/mvc/wiki/9.3-Metadata-&-Social-Rich-Cards)
    
