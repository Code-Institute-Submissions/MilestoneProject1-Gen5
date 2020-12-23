# Gen5

Welcome to Gen5, an informative website to compare the latest generation of gaming consoles, the PlayStation 5 and the Xbox Series X. Made for my Code Institute Milestone Project 1.

Follow the link to [Gen5](https://dominicspears.github.io/MilestoneProject1-Gen5/)
![Image of PS5 and Xbox Series X](assets/images/combo.jpg)

### Contents

1. [Introduction](#intro) 
2. [Technologies](#tech) 
3. [UX](#ux)
4. [Features](#feat)
5. [Testing](#test)
6. [Deployment](#deploy)
7. [Credits](#credit)

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
* [Google Fonts](https://fonts.google.com/)
  * the project uses **google fonts** as a source for its extra fonts.
* [Balsamiq](https://balsamiq.com/wireframes/?gclid=EAIaIQobChMIovzYmYzE7QIVhOvtCh0Nrwz5EAAYASAAEgKhdvD_BwE)
  * The project used **Balsamiq** to create wireframes during the planning phase.
* [Color Dropper](https://chrome.google.com/webstore/detail/color-dropper/cbagleaaaocejmdeichhdkmjebpljckh)
  * The prject uses the **color dropper** (a Chrome add on) to help select colors.
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
3. As a new gamer, I want to know which games are available on each console right now. 

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
* Pop up on features column that describes each feature in simple terms. This will act as a gargon buster. (requires javascript)

#### PS5/Xbox Page
##### Active
* Responsive carousel showcasing accessories of the PlayStation 5 / Xbox series X with title, description, price and links.
* Responsive accordion with three inner cards each.
* Inner cards for console games, that have images, descriptions and price links. Also each card has a hover state shaddow.
* Trailer video that links to youtube, responsive on smaller sizes.

##### To Do
* Responsive hero image, past console gallery and intro message.

#### Sign Up Page
##### Active
* Responsive form for newletter sign up and competition, vertical alignment on smaller screens.
* Progress bar indocating current popularity of consoles.
___

<a name="test"></a>
### Testing

For all testing, please follow the link to a dedicated page. [Testing Page](testing.md) 


___

<a name="deploy"></a>
### Deployment

___

<a name="credit"></a>
### Credits

#### Code
* Universal selector code taken from code institute [Love Running - mini project]() 

* Extra universal selector (box-sizing) taken from [W3Schools.com](https://www.w3schools.com/css/css3_box-sizing.asp)

* Code used to align navbar using justify-content:flex-end on [W3Schools.com](https://www.w3schools.com/cssref/css3_pr_justify-content.asp)

* Navbar layout taken from [W3Schools.com](https://www.w3schools.com/howto/howto_css_fixed_menu.asp), heavily modified and styled to suit needs. 

* Hero image (responsiveness only) code taken from [W3Schools.com](https://www.w3schools.com/css/css3_images.asp)

* Footer template taken from [Love Running - mini project](), modified and styled to suit needs

* Font awesome latest version [upload guide](https://www.youtube.com/watch?v=wiw68Y-hPlA) 

* Footer alignment code taken from [Stack overflow](https://stackoverflow.com/questions/5661520/centering-2-divs-inside-another-vertically)

* Code to center a table taken from [W3Schools.com](https://www.w3schools.com/howto/howto_css_table_center.asp), adapted for streamlining.

* Header responsiveness code taken from [Love Running- Mini Project]()

* Code to hide divs at smaller screen sizes taken from [jquery](https://stackoverflow.com/questions/19705066/remove-a-div-if-screen-size-is-smaller-than-640px)

* Code to make hr element appear on screem taken from [W3Schools.com](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_style_hr)

* Convert colors from rgba to hex on [W3Schools.com](https://www.w3schools.com/colors/colors_hexadecimal.asp?color=00bfff)

* Code for border collapse of table styling taken from [W3Schools.com](https://www.w3schools.com/css/css_table.asp), remainder of styling my own.

* Coloring nth column in table taken from [corelangs.com](http://www.corelangs.com/css/table/tablecolor.html)

* Code for cropping a rectagular image into a square taken from [reactgo.com](https://reactgo.com/css-crop-images/), styling to suit needs.

* Video centering and responsiveness taken from [youtube.com](https://www.youtube.com/watch?v=9YffrCViTVk), modified for needs, personalised styling.

* Template code for carousel taken from [bootstrap.com](https://getbootstrap.com/docs/4.0/components/carousel/), heavily modified and styled for needs

* CSS for carousel image size taken from [stackoverflow.com](https://stackoverflow.com/questions/23018344/how-can-i-fix-bootstrap-carousel-dimensions/23018550). Further modification needed. 

* Template code for cars ans styling from [W3Schools.com](https://www.w3schools.com/howto/howto_css_cards.asp), modifies for needs, personalised styling. 

* CSS for form buttoms taken from [W3Schools.com](https://www.w3schools.com/css/css_form.asp), highly modified for needs, personally styled. 

* Text area code taken from [W3Schools.com](https://www.w3schools.com/tags/att_textarea_required.asp), modified for needs.

* Template code for form taken from Love Running - mini project, modified, personalised styling.

* Template code for accordion taken from [bootstrap.com](https://getbootstrap.com/docs/4.5/components/collapse/#accordion-example), heavily modified for needs, personally styled.

* Gallery template code taken from [love running - mini project](https://courses.codeinstitute.net/courses/course-v1:CodeInstitute+CF101+2017_T1/courseware/1f0ccaac7a3e43d895c1beae5363f46c/91bcf3d697f44e988fad959414892426/?activate_block_id=block-v1%3ACodeInstitute%2BCF101%2B2017_T1%2Btype%40sequential%2Bblock%4091bcf3d697f44e988fad959414892426)

* Width of carousel code taken from [stackoverflow.com](https://stackoverflow.com/questions/30538967/how-to-center-image-in-carousel/30539078)

* Progress bar template code taken from [bootstrap.com](https://www.w3schools.com/bootstrap/bootstrap_progressbars.asp), heavily modified to suit needs, personalised css.

* New bootstrap grid template (for index table) taken from [bootstrap.com](https://getbootstrap.com/docs/4.0/layout/grid/), heavily modified for use, personal css

* Bootstrap grid rowspan equivalent solution taken from [stackoverflow.com](https://stackoverflow.com/questions/16351404/bootstrap-combining-rows-rowspan), modified and personal css added

#### Media
##### Images
All images were located via bing images, searched under "free to share and use" licences.

##### Playstation Images

* Hero image of the [PS5/Xbox Series X Combination](https://images.saymedia-content.com/.image/c_limit%2Ccs_srgb%2Cfl_progressive%2Cq_auto:good%2Cw_700/MTc0MTUxOTI3NTA2OTM3MTE3/everything-we-know-about-the-next-console-generation-so-far.jpg)

* Hero image of the [PS5 only](https://www.diariodeunjugon.com/wp-content/uploads/2020/06/asi-es-playstation-5-sony-1.jpg)

* Gallery image of the [PS4](https://res-5.cloudinary.com/gadgetby/image/upload/c_pad,dpr_1.0,f_auto,h_1200,q_80,w_1200/media/catalog/product/g/a/gadgetbyps4slim-1_1.jpg)

* Gallery image of the [PS3](https://www.lukiegames.com/assets/images/PS3/ps3_sys_20gb_bw_p_z52mxa.jpg)

* Gallery image of the [PS2](https://www.techhog.com/wp-content/uploads/2020/05/How-to-Play-PS2-Games-on-PS4.jpg)

* Gallery image of the [PS1](https://retro.poromagia.com/media/images/products/2017/02/Playstation-1-Console-(PS1)-With-Original-Controller-1-130970.JPG)

* Carousel accessory image of a [PS controller](https://i0.wp.com/www.gamingpark.it/wp-content/uploads/2020/04/DualSense3db_h.jpg?fit=1600%2C1067&ssl=1)

* Carousel accessory image of a [PS remote](https://internationaljournalofresearch.files.wordpress.com/2020/07/sony-ps5-rickmote.jpg)

* Carousel accessory image of a [PS camera](https://17kgroup.it/wp-content/uploads/2020/06/PS-Camera.jpg)

##### Xbox Images

* Hero image of the [Xbox Series X](http://www.xboxygen.com/IMG/jpg/xbox-series-x-console.jpg)

* Gallery image of the [Xbox One X](https://trp02.s3.amazonaws.com/wp-content/uploads/2017/11/Xbox-One-X_Console-Controller_Hrz_ANR-White-Background.jpg)

* Gallery image of the [Xbox One](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Microsoft-Xbox-One-Console-Set-wKinect.jpg/1200px-Microsoft-Xbox-One-Console-Set-wKinect.jpg)

* Gallery image of the [Xbox 360](https://th.bing.com/th/id/OIP.HqGoQC-TohRe4EMYkDafmAHaEK?pid=Api&rs=1)

* Gallery image of the [Xbox](https://solaris525.files.wordpress.com/2012/05/xbox.jpg)

* Carousel image of an [Xbox controller](https://1.bp.blogspot.com/-yVlr_T2PTSk/XntSfZmXaqI/AAAAAAAAD8s/ZoXU07aVsng2GyIpKsfcbZFW7tcOmf_uQCNcBGAsYHQ/s1600/XboxSeriesXController_HERO.jpg)

* Carousel image of [Headphones](https://1.bp.blogspot.com/-k18GMWSaCJY/WREHvwXh-LI/AAAAAAAAAWw/25Lm8elEg5cj5oMQAyYlEGNFXaY1xa7sQCLcB/w1200-h630-p-k-no-nu/headset-scorpio-1494270699699_v2_900x506.png)

* Carousel image of an [Xbox Kinect](https://www.lagzero.net/wp-content/uploads/2010/06/kinect-xbox.jpg)

##### Game Images

* Accordian image of [Puyo puyo Tetris](https://www.mamamo.it/wp-content/uploads/2017/05/puyo_puyo_tetris_2.jpg)

* Accordian image of [Hogwarts Legacy](http://www.xboxygen.com/local/cache-vignettes/L790xH451/harry-potter-hogwarts-legacy-eee3d.jpg?1600288546)

* Accordian image of [Suicide Squad](http://www.internerdz.com.br/wp-content/uploads/2020/08/Suicide-Squad-Kill-the-Justice-League_Reveal-Trailer_Image1_Squad-1674225f416ed9a26659.71128312-1024x436.png)

* Accordian image of [Hitman 3](https://generacionxbox.com/wp-content/uploads/2020/06/hitman-3-xboxone.png)

* Accordian image of [Spider Man Miles Morales](https://theworldwentaway.files.wordpress.com/2020/07/miles-morales-2.png?w=1024)

* Accordian image of [Horizon Forbidden West](https://1.bp.blogspot.com/-8ryF6fFJm-E/XuKk8W45PoI/AAAAAAAAWBA/qYEqxJDIBUsWVW5_oRJ-20P7eKZtlk6mACLcBGAsYHQ/w1200-h630-p-k-no-nu/Horizon-Forbidden-West.png)

* Accordian image of [Oddworld: Soulstorm](http://www.xboxygen.com/IMG/png/oddworld_soulstorm_rs.png)

* Accordian image of [Cyberpunk 2077](https://images.wired.it/wp-content/uploads/2020/12/08120018/cyberpunk-2077_cover.jpeg)

* Accordian image of [The Pathless](https://1.bp.blogspot.com/-KS4tJ47pDws/Xy1-xnBSd-I/AAAAAAAAIxo/V4f8fNUOb9M7ty5tbhZrCONzp3BiPpQGACNcBGAsYHQ/s640/Pathless.png)

* Accordian image of [Halo Guardians](https://theworldwentaway.files.wordpress.com/2015/11/halo5.jpg)

* Accordian image of [Sea of Thieves](https://gamepedia.cursecdn.com/seaofthieves_gamepedia/thumb/b/b3/Ss1.jpg/1200px-Ss1.jpg)

* Accordian image of [Sunset Overdrive](http://cdn4.dualshockers.com/wp-content/uploads/2014/10/sunset_overdrive_review_arsenal.jpg?eaa32f)

* Accordian image of [Warhammer - Chaosbane](https://generacionxbox.com/wp-content/uploads/2019/04/warhammer-chaosbane-preview-header1-940x529.jpg)
##### Videos

* PlayStation 5 [trailer](https://www.youtube.com/watch?v=ZmSNJEYtyds)

* Xbox Series X [trailer](https://www.youtube.com/watch?v=DIMAujZpry0)

##### Text

* Table contents collected from [psu.com](https://www.psu.com/forums/threads/ps5-vs-xbox-series-x-updated-specs-comparison.340035/)

#### Ackowledgements

* Inspired by Code Institute HTML/CSS - [Love Running Mini Project](https://courses.codeinstitute.net/courses/course-v1:CodeInstitute+CF101+2017_T1/course/)
General reference / tutorial assisstance. Login required.

* Inspired by [W3Schools.com](https://www.w3schools.com/html/html_intro.asp)
General reference / tutorial assistance.
___

