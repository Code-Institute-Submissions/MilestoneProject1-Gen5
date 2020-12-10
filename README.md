# Gen5

Welcome to Gen5, an informative website to compare the latest generation of gaming consoles, the PlayStation 5 and the Xbox Series X. Made for my Code Institute Milestone Project 1.

![Image of PS5 and Xbox Series X](assets/images/combo.jpg)

### Contents

1. [Introduction](#intro) 
2. [Technologies](#tech) 
3. [UX](#ux)
4. [Features](#feat)
5. [Testing](#test)
6. [Launch](#launch)
7. [Deployment](#deploy)
8. [Credits](#credit)

___

<a name="intro"></a>
### Introduction

This site will compare and contrast the fifth generation of gaming consoles (hence the name Gen5). With the recent release of the PlayStation 5 (Sony) and Xbox Series X (Microsoft), Gen5 will provide a direct comparison between the two as well as showcasing featues, accessories and games.
___

<a name="tech"></a>
### Technologies

Technologies used to create the site:

* HTML 
  * The project uses **HTML 5** to create the basic layout and site structure.
* CSS
  * The project uses **CSS 3** to style the html to be aesthetically pleasing and responsive.
* [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) 
  * The project uses **Bootstrap Version 4.5.2** to simplify the creation of site features, for example carousels and accordions. 
* [Font Awesome](https://fontawesome.com/)
  * The project uses **Font Awesome Version 5.15.1** to add icons that aid aesthetics or provide social media links.
* [Balsamiq](https://balsamiq.com/wireframes/?gclid=EAIaIQobChMIovzYmYzE7QIVhOvtCh0Nrwz5EAAYASAAEgKhdvD_BwE)
  * The project used **Balsamiq** to create wireframes during the planning phase.
___

<a name="ux"></a>
### UX

#### Potential Users

* Experienced with console gaming
* New to console gaming 
  * New gamer
  * Friends/family of new gamer

#### Features specific for users

Experienced with a console

* In depth comparison
* Future features/releases
* Newsletter
* Where to buy/prices
* Freebies/competitions
* Forum
* Special offers

New to console gaming

* Basic information /jargon buster
* Direct comparison
* Available games
* Gift ideas
* Accessories
* Previous consoles

#### User stories

Experienced with console gaming:

1. As an experienced gamer, I want to know which console has the best internal specifications e.g. best frame rate, internal storage and reverse compatibility.
2. As an experienced gamer, I want to sign up for a newsletter so that I am emailed updates about the latest releases and offers.
3. As an experienced gamer, I want to know which game franchises are console specific in the new generation.

New gamer

1. As a new gamer, I want a clear comparison between the two consoles e.g. their price or additional features.
2. As a new gamer, I want each feature to be explained so that I know why it is a pro/con.
3. a new gamer, I want to know which games are available on each console right now. 

Friends/family of new gamer

1. As a friend/family member, I want to know what accessories area available for each console and their prices.
2. As a friend/family member, I want to know about the latest games that are due for pre-order, which would make good presents.
3. As a friend/family member, I want to buy my (friend/family member) that latest console but I cannot remember the name of their current model. 

#### Wireframes

[Index Page Wireframe](assets/wireframes/MP1-index.png)

[Console Pages Wireframe](assets/wireframes/MP1-console.png)

[Sign Up Page Wireframe](assets/wireframes/MP1-newsletter.png)
___

<a name="feat"></a>
### Features

#### Header
##### Active
* Logo that links to index Page
* Interactive navbar to all site pages, with hover states.
* Responsive navbar that: 
  * removes icons on small screens 
  * alters layout to vertical on smaller screens 

##### To Do
* Dropdown menu for the console page buttons, linking to specific sections of the page.

#### Footer
##### Active
* Link to competition page (gift icon) with hover states.
* Responsive message that is hidden on smaller screens. 
* Links to social media that loads each website on a new tab, with hover states.

#### Index Page
##### Active
* Responsive hero image and introduction message.
* Info message that only appears on smaller screens, describing the responsive solution of the console comparison table.
* Comparison table that is responsive and has a horizontal scrollbar when screen is too small.

##### To Do
* Hover state over features column that describes each feature in simple terms. This will act as a gargon buster.

#### PS5/Xbox Page
##### Active
* Carousel showcasing accessories of the PlayStation 5 / Xbox series X.
* Responsive accordion with three inner cards each.
* Inner cards for console games, that have images, descriptions and price links. Also each card has a hover state shaddow.
* Trailer video that links to youtube, responsive on smaller sizes.

##### To Do
* Responsive hero image, past console gallery and intro message.
* Responsive carousel with title, description and price.

#### Sign Up Page
##### Active
* Responsive form for newletter sign up and competition, vertical alignment on smaller screens.

##### To Do
* Progress bar indocating current popularity of consoles.
___

<a name="test"></a>
### Testing

### Bugs Discovered

#### Solved Bugs

1. Navbar link alignment
  * The navbar links would automatically align on the left of the screen next to the logo. 
  * To solve this I applied justify-content: flex-end, allowing the links to hug the right side of the screen

2. Footer layout
  * The layout of the footer element would align vertically, even on larger screens.
  * To solve this I put each section (message and social links) into its own div. Then added width:40% and float:left to the message div and width:60% to the social lik div.

3. Footer social link layout
  * The layout of the footer social links aligned vertically,  wasting the provided space.
  * To solve this I added diplay:inline to the css, allowing them to align horizontally.

4. Hero image unresponsive
  * The hero image aligned centrally but was unresponsive, so was partially hidden on smaller screens.
  * To solve this I added max-width: 100%, height auto. this allowed it to resize on smaller screens without stretching and compremising the image quality on larger screens. 

5. Section dividers (<hr>) invisible
  * After entering section dividers, the space would be present but no line was visible.
  * To solve this I added a border-top: 2px solid yellow, which showed the dividing line while staying in the width perameters I had already set.

#### Remaining Bugs

1. Carousel unresponsive
  * The carousel does not centralise or resize for smaller screens.

2. Video link Layout
  * The youtube videos leave a large space underneith before the footer. This is particularly evident on larger screens.



### Manual Testing

Expected, testing, result, fix

### User Story Tests
___

<a name="launch"></a>
### Launch

___

<a name="deploy"></a>
### Deployment

___

<a name="credit"></a>
### Credits

#### Code

*

*

*

*

#### Media

#### Ackowledgements
___

