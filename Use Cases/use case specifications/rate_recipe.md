# Mix-It!

## Use-Case Specification: Rate recipe

### Version 1.0

## 1. Use-Case Name
### 1.1 Brief Description
This case allows logged in users to rate a cocktail.
The user can give one to five stars, where five stars are the best.
## 2. Flow of Events
### 2.1 Basic Flow
UML Diagramm
![UML][]

### 2.2Mock-Up:
Rate cocktail:
![MockRateCocktail][]

Change rating: 
![MockChangeRating][]

## 3.Special Requirements
not applicable

## 4.Preconditions
### 4.1 Content available
The rating connected to user and cocktail will be stored in the Database.

## 5.Postconditions
### 5.1 Detail layout
The rating form will be shown on the detail page of each cocktail for logged in users. If the user has already given a rating for the cocktail the change rating form will appear and the original rating will be shown instead of the add rating form.

## 6.Extension Points
not applicable
  
<!-- picture links -->
[UML]: https://github.com/Mit-It/Documentation/blob/master/Use%20Cases/rate_recipe.png "UML Diagram"
[MockRateCocktail]: https://github.com/Mit-It/Documentation/blob/master/Wireframes/Mock_rate_recipe.JPG "Mock-Up"
[MockChangeRating]: https://github.com/Mit-It/Documentation/blob/master/Wireframes/Mock_change_rating.JPG "Mock-Up"
