# Mix-It!

## Use-Case Specification: Delete own recipe

### Version 1.0

## 1. Use-Case Name
### 1.1 Brief Description
This case allows registerd users to delete their own created cocktail. By clicking on an "Rubbish bin - icon" on the cocktail list or details of an cocktail they created, they get the option to remove the cocktail.
They will be shown a confirmation page in order to prevent accidental removal.
## 2. Flow of Events
### 2.1 Basic Flow
UML Diagramm
![UML][]

### 2.2Mock-Up:
Deleting from details:
![MockDeleteDetail][]

Deleting from list:
![MockDeleteList][]

Confirming delete:
![MockDeleteConfirm][]

## 3.Special Requirements
not applicable

## 4.Preconditions
### 4.1 Content available
The detailed content of the cocktail will be removed from the database.

## 5.Postconditions
### 5.1 Detail layout
The icon for removal must be show on the cocktail list and on the detail page of an cocktail that we created by the current logged in user.

## 6.Extension Points
not applicable
  
<!-- picture links -->
[UML]: https://github.com/Mit-It/Documentation/blob/master/Use%20Cases/view-list.png "UML Diagram"
[MockDeleteDetail]: https://github.com/Mit-It/Documentation/blob/master/Wireframes/delete_detail.JPG "Mock-Up"
[MockDeleteList]: https://github.com/Mit-It/Documentation/blob/master/Wireframes/delete_own_list.JPG "Mock-Up"
[MockDeleteConfirm]: https://github.com/Mit-It/Documentation/blob/master/Wireframes/delete_confirm.JPG "Mock-Up"
