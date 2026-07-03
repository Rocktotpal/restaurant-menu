# 02-Restaurant-menu

## 1. Purpose

Display a restaurant's food menu, allowing customers to browse dishes by category, compare prices, and explore available options.

## 2. Target Users

Customers physically visiting restaurant
Customers ordering online
Visitors browsing the menu before visiting

## 3. Features

View dish image
View dish name
View food description
Veg/Non-veg options
View Price

## 4. Sections

Restaurant Menu
header
main
|-- section.starter
|-- section.mainCourse
|-- section.desserts
footer

## 5. Components

header
----|--food image
----|--Restaurant logo
----|--Restaurant Name
----|--text 'Menu'
----|--food image
main
----|--section.starter
---------|--dish img
---------|--dish name
---------|--description
---------|--veg/non-veg price
----|--section.mainCourse
---------|--dish img
---------|--dish name
---------|--description
---------|--veg/non-veg price
----|--section.desserts
---------|--dish img
---------|--dish name
---------|--description
---------|--veg/non-veg price
footer
----|--contact

## 6. Layout Planning

image------------------------------logo
-----------Restaurant Name-------------
-----------------Menu------------------
----------------image------------------

Starter
card1------------card2------------card3

Main Course
card1------------card2------------card3

Desserts
card1------------card2------------card3

contact---------------------------email

## 7. HTML Structure

body
--|--header
-------|--div.logo
-----------|--img
-----------|--logo
-------|--h1: Restaurant Name
-------|--h2: 'Menu'
-------|--img
--|--main.menu-card
-------|--section.starter
-----------|--card1
---------------|--img
---------------|--h3
---------------|--p
---------------|--footer
--------------------|--div(veg/non-veg)
--------------------|--p(price)
-----------|--card2
-----------|--card3
-------|--section.mainCourse
-----------|--card1
---------------|--img
---------------|--h3
---------------|--p
---------------|--footer
--------------------|--div(veg/non-veg)
--------------------|--p(price)
-----------|--card2
-----------|--card3
-------|--section.desserts
-----------|--card1
---------------|--img
---------------|--h3
---------------|--p
---------------|--footer
--------------------|--div(veg/non-veg)
--------------------|--p(price)
-----------|--card2
-----------|--card3
--|--footer
-------|--div.contact
-----------|--p
-----------|--p

## 8. CSS planning

header-- display: flex; direction: column; align & justify: center;
div.logo-- display: flex; justify: space-between;

main.menu-card-- display: flex; direction: column;
sections-- display: flex; justify: space-between;
card-- display:flex; direction: column;

footer-- footer.card & div.contact-- display: flex; justify: space-between;

## 9. Responsive plan: Mobile

(1 card in one line)

body
--|--header
-------|--logo
-------|--h1: Restaurant Name
-------|--h2: 'Menu'
--|--main.menu-card
-------|--section.starter
------------|--card1
------------|--card2
------------|--card3
-------|--section.mainCourse
------------|--card1
------------|--card2
------------|--card3
-------|--section.desserts
------------|--card1
------------|--card2
------------|--card3
--|--footer
-------|--contact
-------|--email

(for tablet 2 cards in one line)

## 10. Future Improvements

Search dishes
Filter Veg/Non-Veg
Category tabs
Dark mode
Online ordering
Ratings
Customer reviews
