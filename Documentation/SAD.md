# Software Architecture Document


## 1. Introduction 
### 1.1 Purpose
This document provides a detailed architectural overview of our system, 
using a number of different architectural views to depict different aspects of the system. 
It is intended to capture and understand the significant architectural decisions which have been made on the system.

### 1.2 Scope
The scope of this SAD is to show the architecture of the Mix-It project. Affected are the class structure and the data representation.

### 1.3 References
n/a

## 2. Architectural Representation
Mix-It uses the MVC from Laravel for its architecture design.

MVC Diagram: 

![MVC][]

## 3.Architectural Goals and Constraints 
This projekt will be a webbbased application. The PHP-framework Laravel will be used for implementing. Laravel uses PHP for the logic, HTML for the structure, CSS for design and JavaScript for some client-site logic and effects and also we will do. Also Bootstrap is included by default in each Laravel-Project. Bootstrap is a CSS and JavaScript Library which provides a lot of predesign design-patterns and other functionality. 

The Interface to the mixing-machine will be implemented on a rasperry-pi. The programming language on the rasperry pi will be python. For communication between website an pi we need an format both languages (php and python) can read. For transfer of the cocktails-data we will use the format json.

## 4. Use-Case View 
n/a

## 5. Logical View

![Overview][]


## 6. Process View
n/a

## 7. Deployment View
n/a

## 8. Implementation View
n/a

## 9. Data View
We're using a MYSQL database to store our data. 
Our ER Diagramm can be seen here.
![ER-Diagramm][]

## 10. Size and Performance
tbd

## 11. Quality
To ensure a high quality code we write and run tests with cucumber.

<!-- picture links -->
[MVC]: https://github.com/Mit-It/Documentation/blob/master/Development/MVC-Laravel.png "MVC Diagram"
[ER-Diagramm]: https://github.com/Mit-It/Documentation/blob/master/Database/database-struktur.png "ER-Diagramm"
