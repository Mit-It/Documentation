# Mix-It!

# Software Requirements Specification

## Version 1.0

### Revision History
| **Date** | **Version** | **Description** | **Author** |
| --- | --- | --- | --- |
| 19.10.2017 | 1.0 | Initial fill | Mit-It! Team |

### Table of Contents

| 1.        Introduction        |
| --- |
|         Purpose        |
|         Scope        |
|         Definitions, Acronyms, and Abbreviations        |
|         References        |
|         Overview        |
| 2.        Overall Description        |
| 3.        Specific Requirements        |
|         Functionality        |
|         Usability        |
|         Reliability        |
|         Performance        |
|         Supportability        |
|         Design Constraints        |
|         On-line User Documentation and Help System Requirements        |
|         Purchased Components        |
|         Interfaces        |
| 3.9.1        User Interfaces        |
| 3.9.2        Hardware Interfaces        |
| 3.9.3        Software Interfaces        |
| 3.9.4        Communications Interfaces        |
|         Licensing Requirements        |
|         Legal, Copyright, and Other Notices        |
|         Applicable Standards        |
| 4.        Supporting Information        |
| Software Requirements Specification |

## 1.**Introduction**


### 1.1 **Purpose**

This document serves as a detailled description and explenation of the Mix-It! project. It contains the required features, planned functionallity, and a detailled description on the system reaction. The used hard- and Software as well as interfaces will be shown.

### 1.2 **Scope**

This document applies for the latest version of the project. Mix-It! will give you the oppertunity to check out many different Cocktail recipes and auto-mix them with a machine.

### 1.3 **Definitions, Acronyms, and Abbreviations**

Not applicable

### 1.4 **References**

Not applicable

### 1.5 **Overview**
Mix-It! will be all about creating cocktails recipes and automatic cocktail making.
There will be filters implemented to sort your favorite kind and a search option to get the cocktail you desire.
Cocktails recipes will be shown in detail with all the ingredients you need.
Our device can then be linked to your account and with one button press your cocktail will be mixed!

## 2. **Overall Description**

The overall description is given by the use-case diagramm.
It describes all the features of the application.

![Use-Case](https://github.com/Mit-It/Documentation/blob/master/Pictures/Use_case.jpg)


## 3. **Specific Requirements**


### 3.1 **Functionality**

#### 3.1.1 **Cocktail-list**  
  A visitor can view the different cocktails in a list form on the website.

#### 3.1.2 **Cocktail-Detail**  
  A visitor can view the details containing a description and the recipe of any cocktail in the list.

#### 3.1.3 **Cocktail-Delete**  
  Cocktails can only be deleted by the user that created it or by an admin. It will be removed from the database and the list.

#### 3.1.4 **Cocktail-Adding**  
  Cocktails can only be added by users that are logged in. They must provide a description and a recipe.

 #### 3.1.5 **Cocktail-Rating**  
  Cocktails can be rated from 0 to 5 stars. The average value of all votes will be displayed.

####  3.1.6 **Login**  
  The user can log in to the service by providing his username and password.

####  3.1.7 **Logout**  
  The user can log out.

####  3.1.8 **Registrate**  
  A visitor can create an account by providing an E-mail, username and password.

####  3.1.9 **Delete Account**  
  An account can be removed by the user itself or and admin.

####  3.1.10 **Machine**  
  The cocktail mixing machine can be added to an user account.

####  3.1.11 **Mixing**  
  The website provides the option for every cocktail to use the machine to mix the cocktail.

### 3.2 **Usability**  

#### 3.2.1  **User-Interface**  
The application will be easy to use with an structured and clean user interface. The design should be responsive

### 3.3 **Reliability**  

##### 3.3.1 **Availability**  
The website should be available 95% of the time. During the development this availibility is not needed.

### 3.4 **Performance**  

#### 3.4.1 **Response time**  
The response time of the website should be as fast as possible. At maximum 4 seconds on any page.

#### 3.4.1 **Capacity**  
The website should handle up to 500 registerd users and up to 75 users at one time.

### 3.5 **Supportability**  

#### 3.5.1 **Server**  
As the website will be developed locally we will use a Tomcat container.
The server therefore must run an apache tomcat webserver and must be able to support a mysql database.

### 3.6 **Design Constraints**  

#### 3.6.1 **Git**  
Git is used for version control

#### 3.6.1 **Database**  
For our database MySql will be used

#### 3.6.1 **Mixing machine**  
The mixing machine will use a raspberry pi.
The code will be written with python

### 3.7 **On-line User Documentation and Help System Requirements**  
Not applicable

### 3.8 **Purchased Components**  
Not applicable

### 3.9 **Interfaces**  

#### 3.9.1 **User Interfaces**  
The user interface is the website.

#### 3.9.2 **Hardware Interfaces**  
A raspberry pi will be used as a hardware interface between the website and the mixer.

#### 3.9.3 **Software Interfaces**  
Not applicable

#### 3.9.4 **Communications Interfaces**  
Not applicable

### 3.10 **Licensing Requirements**  
Not applicable

### 3.11 **Legal, Copyright, and Other Notices**  
Not applicable

### 3.12 **Applicable Standards**  
Not applicable

## 4. **Supporting Information**  
Not applicable
