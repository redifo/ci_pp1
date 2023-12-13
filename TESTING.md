# Life Hacks -  Testing

![Website on different screen sizes](documentation/img/mockup.webp)

Deployed website: [Life Hacks](https://redifo.github.io/ci_pp1/)

- - -

## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
* [MANUAL TESTING](#manual-testing)

Continuously test throughout construction. Use Chrome developer tools to find and fix issues as you build. Be proactive in addressing challenges.

During development, rely on Google developer tools. Verify components are working. Use the console to check JavaScript and fix issues.

Check each page for responsiveness. Use Chrome and Firefox tools. Ensure a seamless user experience on various devices. Adapt to the multi-device landscape.
- - -

## AUTOMATED TESTING

### W3C Validator

The w3 html and jigsaw css validator has been used to make sure the code does not contain any errors. the results shown below are the results of the final tests. During the development of the code this validator has been used multiple times but the results were not recorded before the final testings.

 * [W3C](https://validator.w3.org/) 

 [index.html](documentation/testing/backslash-error.png)  

 [categories.html](documentation/testing/no-errors.png)   

 [contact.html](documentation/testing/no-errors.png)  
 
 [success.html](documentation/testing/successpage-errors.png)  

 [style.css](documentation/testing/jigsaw-css-no-error.png) 

- - -

### Lighthouse

The website has been tested by google chrome's lighthouse report and the results are shown below. 

### Desktop Results

home page
![index.html](documentation/testing/desktop-lighthouse-home.png)

categories page
![categroies.html](documentation/testing/desktop-lighthouse-categories.png)

contact us page
![contact.html](documentation/testing/desktop-lighthouse-contact.png)

success page
![success.html](documentation/testing/desktop-lighthouse-success.png)

### Mobile Results

Performance ratings are a bit low on some pages on mobile but achieving 100% on that metric is very hard without using very low quality photos.

home page
![index.html](documentation/testing/mobile-lighthouse-home.png)

categories page
![categroies.html](documentation/testing/mobile-lighthouse-categories.png)

contact us page
![contact.html](documentation/testing/mobile-lighthouse-contactpng.png)

success page
![success.html](documentation/testing/mobile-lighthouse-success.png)

- - -

## MANUAL TESTING

Full testing was performed on the following devices:

* pixel 7
* Ipad pro
* windows pc 1080p

Each device tested the site using the following browsers:

* Google Chrome
* Microsoft Edge

`Home page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | direct to home page | pass |
| All buttons and navigation menu items and social media icons- hover effect | Change colour when hovered on | Hover over each button on the page | Each button displayed the correct styling when hovered over | pass |
| form submission redirect | redirect to success page | form submitted | redirected to success page | pass |
| clcik to reveal text on life hack boxes | clicking shows the hidden text | clicking on all boxes | hidden text shown | pass |
| Social media icons | clicking on them opens the website in a new window | clicked on the items | all opened in a new tab | pass |

`Categories Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | direct to home page | pass |
| All buttons and navigation menu items and social media icons- hover effect | Change colour when hovered on | Hover over each button on the page | Each button displayed the correct styling when hovered over | pass |
| form submission redirect | redirect to success page | form submitted | redirected to success page | pass |
| clcik to reveal text on life hack boxes | clicking shows the hidden text | clicking on all boxes | hidden text shown | pass |
| Social media icons | clicking on them opens the website in a new window | clicked on the items | all opened in a new tab | pass |
|  the links show the right content on page | when clicked on a heading link it moves the page tot the right section | clicked on heading links | the page moved to the right location | pass |

`Contatcs Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | direct to home page | pass |
| All buttons and navigation menu items and social media icons- hover effect | Change colour when hovered on | Hover over each button on the page | Each button displayed the correct styling when hovered over | pass |
| Form submission redirect | Redirect to success page | form submitted | redirected to success page | pass |
| Social media icons | clicking on them opens the website in a new window | clicked on the items | all opened in a new tab | pass |


`Form Success Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites title | Link directs the user back to the home page | Clicked title | direct to home page | pass |
| Auto redirect  | auto redirect to home page in 5 seconds | opened the webpage | redirected to homepage | pass |
