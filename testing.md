### Bugs Discovered

#### Solved Bugs

1. Navbar link alignment
  * The navbar links would automatically align on the left of the screen next to the logo. 
  * To solve this I applied justify-content: flex-end, allowing the links to hug the right side of the screen
  * Code from [W3Schools.com](https://www.w3schools.com/cssref/css3_pr_justify-content.asp)

2. Footer layout
  * The layout of the footer element would align vertically, even on larger screens.
  * To solve this I put each section (message and social links) into its own div. Then added width:40% and float:left to the message div and width:60% to the social lik div.

3. Footer social link layout
  * The layout of the footer social links aligned vertically,  wasting the provided space.
  * To solve this I added diplay:inline to the css, allowing them to align horizontally.
  * Code from [stackoverflow.com](https://stackoverflow.com/questions/5661520/centering-2-divs-inside-another-vertically)

4. Hero image unresponsive
  * The hero image aligned centrally but was unresponsive, so was partially hidden on smaller screens.
  * To solve this I added max-width: 100%, height auto. this allowed it to resize on smaller screens without stretching and compremising the image quality on larger screens. 
  * Code from [W3Schools.com](https://www.w3schools.com/css/css3_images.asp)

5. Section dividers (hr) invisible
  * After entering section dividers, the space would be present but no line was visible.
  * To solve this I added a border-top: 2px solid yellow, which showed the dividing line while staying in the width perameters I had already set.
  * Code from [W3Schools.com](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_style_hr)

6.  Carousel unresponsive
  * The carousel does not centralise or resize for smaller screens.
  * To solve this I added width: 70%, margin-left: 0 auto, margin-right: 0 auto, allowing the carousel to be responsive and centralised.

7. Table columns are uneven
  * The table on the index page are uneven and dependent on the content added to them.
  * To solve this I replace the entire table with two replacements,each with a bootstrap template. One for larger screens and one for smaller screens.
  * Code from [bootstrap.com](https://getbootstrap.com/docs/4.0/layout/grid/), container-large
  * Code from [stackoverflow.com](https://stackoverflow.com/questions/16351404/bootstrap-combining-rows-rowspan), container-small

8. PS/Xbox hero image alignment
  * The hero images of the console pages are not aligned aesthetically.
  * To solve this I seperated the hero image and past images onto seperate levels and made each responsive to the full width of the page. 

#### Remaining Bugs

1. Video link Layout
  * The youtube videos leave a large space underneith before the footer. This is particularly evident on larger screens. 

2. Accordian cards not level
  * The cards in each accordian seem to be aligned by the bottom of the card, rather than the top.

3. Progress bar unresponsive
  * The progress bar does not repond to input from the questionnaire, requires javascript.

### Manual Testing

action, expected behaviour, result

1. Internal link (Logo)
  * Click the Gen5 logo 
  * Returns the user to the homepage
  * Result: pass

2. Internal link (Navbar links)
  * Click each navbar link 
  * Takes the user to each assosiated page
  * Result: pass

3. Internal link (footer link)
  * Click the present icon 
  * Takes the user to the sign-up page
  * Result: pass

4. Internal link (Sign up button)
  * Click the sign up button (Note:all required information must be entered)
  * Takes the user to a "sign-up complete" page
  * Result: pass

5. Internal link (Home button)
  * Click the home button on the "sign-up complete" page
  * Returns the user to the homepage
  * Result: pass

6. External link (footer social links)
  * Click the social links 
  * Takes the user to the assosiated social media homepage on a seperate tab
  * Result: pass (Note: if you are logged into the social media site, the link will take you to your page, not the homepage)

7. External link (Carousel description links)
  * Click the link in each description 
  * Takes the user to the product page, on a seperrate tab
  * Result: pass

8. Navbar link active state
  * Click each navbar link 
  * Each link will be underlined when the user is on the associated page
  * Result: pass

9. Navbar link hover state
  * Hover over each navbar link with the mouse
  * Each link will highlighted
  * Result: pass

10. Tooltip hover states (console comparison table)
  * Hover over each tooltip, questionmark icon in features column 
  * Each tooltip will reveal a specific message for each feature
  * Result: pass

11. Carousel navigation
  * Click each arrow icon at the sides of the carousel
  * The arrows will take you to the next/previous slide 
  * Result: pass 

12. Accordion segment buttons
  * Click each segment header 
  * A specific portion of the accordion is revealed. Note: clicking again will hide the section
  * Result: pass

13. Game card hover state
  * Hover over a game card 
  * The shaddow of the card will intensify
  * Result: pass

14. Console trailer
  * Click the central play button 
  * Click once to play the video, click again to pause the video
  * Result: pass

15. Form requirements
  * Leave any section of the form empty and try to submit
  * The form will not submit and highlight the missing information
  * Result: pass

16. Media Queries
  * Resize the site window 
  * The layout/ content will alter to present effectively
  * Result: pass, tested between 320px to 1359px.  

### Validator Tests

#### index.html
  * W3C HTML Validator - Document checking completed. No errors or warnings to show.
  * Chrome Lighthouse - 99, 95, 93, 90.
  * ![Lighthouse assessment](assets/lighthouse/lighthouse1.png)

#### xbox.html
  * W3C HTML Validator - Document checking completed. No errors or warnings to show.
  * Chrome Lighthouse - 96, 93, 93, 90. 
  * ![Lighthouse assessment](assets/lighthouse/lighthouse2.png)

#### ps5.html
  * W3C HTML Validator - Document checking completed. No errors or warnings to show.
  * Chrome Lighthouse - 97, 93, 93, 90. 
  * ![Lighthouse assessment](assets/lighthouse/lighthouse3.png)

#### sign-up.html
  * W3C HTML Validator - Document checking completed. No errors or warnings to show.
  * Chrome Lighthouse - 99, 97, 93, 100. 
  * ![Lighthouse assessment](assets/lighthouse/lighthouse4.png)

#### complete.html
  * W3C HTML Validator - Document checking completed. No errors or warnings to show.
  * Chrome Lighthouse - 100, 100, 93, 100. 
  * ![Lighthouse assessment](assets/lighthouse/lighthouse5.png)

#### style.css
  * W3C CSS Validator - Congratulations! No error found.

### User Story Tests

#### Experienced with console gaming:
1. As an experienced gamer, I want to know which console has the best internal specifications e.g. best frame rate, internal storage and reverse compatibility.
  * To address this I created a features table that directly compares the specifications of each console.
  * ![User Story 1](assets/userstory/us1.png)

2. As an experienced gamer, I want to sign up for a newsletter so that I am emailed updates about the latest releases and offers.
  * To address this I created a sign up page with a form to take user details, including name and email.
  * ![User Story 2](assets/userstory/us2.png)

3. As an experienced gamer, I want to know which game franchises are console specific in the new generation.
  * To address this I created a specific section in the games accordion to showcase console specific franchises, on both the xbox and ps page.
  * ![User Story 3](assets/userstory/us3.png)

#### New gamer
1. As a new gamer, I want a clear comparison between the two consoles e.g. their price or additional features.
  * To address this I added a price comparison to the console comparison table, as well as some other basic features.
  * ![User Story 4](assets/userstory/us4.png)

2. As a new gamer, I want each feature to be explained so that I know why it is a pro/con.
  * To address this I added a tooltip to each feature on the comparison table, explaining the feature in simple terms.
  * ![User Story 5](assets/userstory/us5.png)

3. As a new gamer, I want to know which games are available on each console right now. 
  * To address this I added a latest releases section to the games accordian, to show the most up to date, available games. I did this for both the xbox and ps pages.
  * ![User Story 6](assets/userstory/us6.png)

#### Friends/family of new gamer
1. As a friend/family member, I want to know what accessories area available for each console and their prices.
  * To address this I added an accessories carousel to the xbox and ps pages. Each included a price and link to selling website.
  * ![User Story 7](assets/userstory/us7.png)

2. As a friend/family member, I want to know about the latest games that are due for pre-order, which would make good presents.
  * To address this I added a pre-order section to the games accordion, to showcase games coming out in the near future.
  * ![User Story 8](assets/userstory/us8.png)
  
3. As a friend/family member, I want to buy my (friend/family member) that latest console but I cannot remember the name of their current model. 
  * To address this I added images of the previous consoles in the series, as they may know an old console by appearence and not by name.
  * ![User Story 9](assets/userstory/us9.png)