# Taste of Naija

Taste of Naija is a website built for the first imaginary Nigerian restaurant in Würzburg, Germany. The website targets people in and around Würzburg who love African food and those who are curious about how African food tastes.
The website provides useful information about the restaurant such as the address, opening times, contact information and food menu.

![Image of Taste of Naija website on different devices](/documentation/taste-of-naija.png)

## Contents

- [Features](#features)

- [Technologies used](#technologies-used)

- [Testing](#testing)

- [Deployment](#deployment)

- [Credits](#credits)

- [Acknowledgements](#acknowledgements)

## Features

### Existing Features

- **Navigation Bar**

    - This appears on all three pages in the project. It includes links to the 'Taste of Naija' logo, the Home, Menu and Feedback pages.
    - The section is identical on all pages and allows the user to navigate from one page to another without having to go back to the Home page.


![Navigation bar for Taste of Naija website](/documentation/nav-bar.png)

- '**The Hero Image**

    - The main page image displays the 'Naija Jollof' (Nigerian jollof rice) as it is popularly called.
    - This image was selected because it is one of the most popular dishes in Nigeria and one of the main dishes customers expect to find on the menu when they visit the restaurant.

![Hero Image for Taste of Naija website](/documentation/hero-image.png)

- **Contact and Opening Times section**

    - This section shows three different sub-sections which are all centered as much as possible to enable users view the information easily on wider screens:
        
        - Address: This shows the location of the restaurant and also provides a Google maps link to enable would be customers find the restaurant easily.

        - Phone and E-mail: This provides the phone number and email address to enable people call the restaurant for questions/reservations and also do the same via email

        - Opening Times: This shows the days of the week and times when the restaurant is open/closed for business.

![Screenshot of Contact and Opening Times section](/documentation/contact-and-opening-times.png)

- **The Footer**

    - The footer has the social media links for the restaurant to enable customers get regular updates on the restaurant activities.

    - These links are set to open in a new tab when clicked and they are highlighted in blue when hovered with a mouse to enable users know that they are links.

![Screenshot of footer page](/documentation/footer.png)

- **The Menu**

    - The menu section displays the different dishes on offer by the restaurant with their corresponding prices.

    - On smaller screens, the pictures are made slightly bigger while the prices are placed beneath the dish names using the 'flex-direction:column;' property

![Food menu and price list](/documentation/food-menu.png)

- **The Feedback**

    - The feedback section allows users provide useful suggestions and ideas to help the restaurant improve its services.

    - The First Name, Age and Feedback fields are required and prompt the users to fill them out before they can submit the form.

    - There is a 'Clear Form' button which enables the user clear the entire form if they wish to do so.

![Feedback form](/documentation/feedback.png)

### Features Left to Implement

- **Hamburger Menu**

    - A hamburger menu to appear for the different pages on smaller screen sizes.

## Technologies Used

- The following technologies were used in creating this project:

 - HTML5

 - CSS3

 - Google Fonts: This was used to import the Open Sans and Roboto fonts used throughout the project.

 - Git/Github: This was used for the actual coding of the project via Gitpod and also provided version control as well as remote storage for the project.

 - Screenpresso: Used to capture the screenshots for the Readme document

 - Beautifier: Used to remove extra unnecessary spaces in the css styling

 - Tables Generator: Used to generate the table used in the Testing section

 - AM I Responsive: This was used to show the project responsiveness [(see responsiveness image here)](#taste-of-naija) on the following device viewports:

    - Desktop
        1600x992px scaled down to scale(0.3181)
    
    - Laptop
        1280x802px scaled down to scale(0.277)

    - Tablet
        768x1024px scaled down to scale(0.219)

    - Mobile
        320x480px scaled down to scale(0.219)

 - Marvel App: Used to design the wireframes for the project at the initial design stages

 ## Testing

- The website is created for devices having a device-width of at least 320 pixels. Below are short Gifs showing how the website looks and scrolls on the iPhone4 device which has a device-width of 320 pixels.

    - ![Gif showing the look of the Home page when scrolling on the iPhone4](/documentation/testing/home-page-iphone4.gif)

    - ![Gif showing the look of the Menu page when scrolling on the iPhone4](/documentation/testing/food-menu-iphone4.gif)

    - ![Gif showing the look of the Feedback page when scrolling on the iPhone4](/documentation/testing/feedback-iphone4.gif)

- **Validators**

    - HTML

        - No errors were found using the official W3C validator

    - CSS

        - No errors were found using the W3C CSS (jigsaw) Validator

![Screenshot of HTML validator showing no errors in HTML](/documentation/testing/html-validator.png)

![Screenshot of CSS validator showing  no errors in CSS](/documentation/testing/css-validator.png)

The link to the full CSS validation results can be found here:

http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fsategie.github.io%2FTaste-of-Naija%2F&usermedium=all&vextwarning=&warning=1

- **Browser Compatibility**

    - The project was tested on the three browsers listed below. The pages ran smoothly on all three browsers and there were no significant differences in the different browsers.

        - Google Chrome Version 110.0.5481.178 (Official Build) (64-Bit)

        - Microsoft Edge Version 110.0.1587.57 (Official build) (64-bit)
        
        - Firefox Version 110.0.1 (64-bit)

    - The only thing that stood out while using Firefox was the 'Age' field in the Feedback page which displays the number selector icon constantly, while the other browsers only display the selector icon when the field is hovered on.

![Feedback page on Firefox](/documentation/testing/feedback-firefox.png)

| <b>Feedback page on Firefox</b> |

- **Lighthouse**

    - Lighthouse was used to test the project using the following criteria: Performance, Accessibility, Best Practices and SEO.

    - The colors and fonts chosen are easy to read by users.

    - Lighthouse was used on Google Chrome in Incognito mode to test the Home, Menu and Feedback pages for the above mentioned criteria.

 ![Screenshot of Home page testing results on Lighthouse](/documentation/testing/lighthouse-testing-home.png)

 ![Screenshot of Menu page testing results on Lighthouse](/documentation/testing/lighthouse-testing-menu.png)

 ![Screenshot of Feedback page testing results on Lighthouse](/documentation/testing/lighthouse-testing-feedback.png)

 - Testing Outcomes

|                **Test**               |                         **Test Action**                         |                                            **Expected Outcome**                                           | **Result** |
|:-------------------------------------:|:---------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------:|:----------:|
| Navigation Bar: Logo                  | Click on 'Taste of Naija' logo                                  | Browser goes to the Home page                                                                             | PASS       |
| Navigation Bar Links: Click           | Click on the Home, Menu or Feedback links                       | Browser goes to the respective Home, Menu and Feedback pages                                              | PASS       |
| Navigation Bar Links: Hover           | Hover on the Home, Menu or Feedback links                       | A dotted underline appears under the respective link                                                      | PASS       |
| Google maps link in 'Address' section | Click on the Google maps link                                   | Google maps opens in a new tab with the address of Taste of Naija displayed                               | PASS       |
| Footer links: Click                   | Click on the Facebook, Twitter or Instagram links in the footer | Browser opens the Facebook, Twitter or Instagram page in a new tab                                        | PASS       |
| Footer links: Hover                   | Hover on the Facebook, Twitter or Instagram links in the footer | The respective links change to a blue color                                                               | PASS       |
| Feedback Form: First Name field       | Attempt to submit form without entering text                    | User is prompted to fill in the first name                                                                | PASS       |
| Feedback Form: Age field              | Attempt to submit form without entering a number                | User is prompted to enter a number                                                                        | PASS       |
| Feedback Form: Email field            | Not a required field. Enter characters without adding an @ sign | User is informed that the field must have an @ sign                                                       | PASS       |
| Feedback Form: Feedback field         | Attempt to submit form without entering anything in the box     | User is prompted to fill the field                                                                        | PASS       |
| Feedback Form Buttons: Hover          | Hover on the 'Submit' or 'Clear Form' buttons                   | A dotted border appears on the button                                                                     | PASS       |
| Feedback Form Submit Button: Click    | Click on 'Submit Form' after filling required fields            | Form is successfully submitted. A new page opens with the confirmation of the submission and entered data | PASS       |
| Feedback Form Clear Button: Click     | Click on 'Clear Form' after entering data in the fields         | All entered data are cleared from the form                                                                | PASS       |


- **Unfixed Bugs**

    - There are no unfixed bugs.


## Deployment

- The site was deployed to Github using the following steps:

    1. In the Taste of Naija repository in Github, click on Settings.

    2. Click on *Pages* under *Code and Automation* on the left hand side.

    3. Under *Pages*, select the *main* branch from the dropdown menu in the *Branch* section and click on *Save*.

The project is live at https://sategie.github.io/Taste-of-Naija/

- **How to Fork the Repository**

    - You can make a copy of the project to make changes which do not affect the original repository by doing the following:

    1. Go to the project's Github repository https://github.com/sategie/Taste-of-Naija/blob/main/README.md

    2. Click on the 'Fork' button on the top right of the screen.

- **How to Clone the Repository**

    - To make a clone of the repository, the following need to be done:

        1. Go to the project's Github repository https://github.com/sategie/Taste-of-Naija/blob/main/README.md

        2. Click the green 'Code' button on the right.

        3. Click on HTTPS and copy the link.

        4. Open Git and change the working directory to where you want to have the cloned directory.

        5. Type *git clone* and paste the copied URL.

    - To make changes to the website, the following need to be done:

        1. Type *git add .*

        2. Type *git commit -m "short update comment"

        3. Type *git push*

    - Any updates commited to the main branch inmediately reflect in the hosted site.

## Credits

- **Content**

    - The idea for the Header HTML and CSS was taken from Code Institute's Love Running project.

    - The idea to use flexbox for the Menu section was taken from a Youtube Video: 'Create a Restaurant Menu with HTML & CSS Grid + Flexbox'

    - The fonts used for the project were obtained from Google Fonts.

- **Media**

    - The images used in the project were downloaded mostly from Unsplash.

## Acknowledgements

- I am extremely grateful to my family for supporting me in my coding journey thus far.

- Special thanks go to my mentor Brian Macharia who gave me useful tips and improvement areas to enable me complete the project.

- Last but not least, I would like to thank the Code Institute community on Slack for helping me out whenever I had HTML/CSS related questions.






























