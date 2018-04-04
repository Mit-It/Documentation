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
Mix-It uses the MVC for its architecture design.

MVC Diagram: 

![MVC][]

## 3.Architectural Goals and Constraints 
We couldn’t fully generate the Class Diagram in our IDE. The Database struckture will be implementet with an MySQL databse.

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
