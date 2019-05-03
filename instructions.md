# Mando Front-end Technical Assessment
Welcome to Mando’s technical assessment for frontend development. The following test asks you to produce some code to present a fairly common pattern utilising a combination of HTML, CSS and JavaScript. 
The test is designed to be undertaken by all levels of frontend developer but includes varying degrees of complexity to allow candidates to demonstrate their technical proficiency. 
You are not expected to complete all parts of the test in the allocated time but to make a judgement as to what will best demonstrate your skills to maximum effect. 

You have 2 hours to provide your solution.

Required files are available here: [https://github.com/andypimlett/frontend-test]

You are free to use any resources you have access to in order to complete the assessment. We will provide a workstation but you are welcome to use your own laptop if you have a development environment you prefer. 

You may find it easier to utilise codesandbox.io as an IDE due to ease of integration of dependencies. 

 
## The Design
The design team have provided this initial design to produce an MVP (Minimum Viable Product) to demonstrate to the client. Details of required functionality are included in the following pages. The product owner has requested that you prioritise features at your own discretion to deliver a solid demo in the time frame provided.

[Design File](design.png)
 
## JSON
* Consume the provided JSON to output a selection of cards showing details of online courses for a student. 
* You can parse the static JSON or consume via XHR using your preferred method (extra credit for implementing with XHR) 

## HTML / CSS 
* Display the cards in a 4 (Desktop), 3 (Tablet) and 1 (Mobile) column layout using Flexbox or CSS Grid making suitable judgements to present the design at different device sizes.
* Above the cards should be a summary area displaying users name, username, bio and avatar placeholder.
* The summary area should also dynamically indicate the following: 
* A progress bar showing total progress 
* Number of completed modules 
* Number of in progress modules 
* Number of modules remaining 

* HTML should have applicable accessibility consideration (for example inclusion of suitable aria attributes) 
* You may use your preferred methodology for structured styling but use of a common approach is expected (e.g BEM) 
* The card should be clickable, but the action disabled by default. 
* Cards should display an SVG icon to symbolise the category of the course in the card header. SVGs are available at ... 
* The card should include a brief summary and a button to expand to show a list of details (see behaviour below). Once again additional credit will be given to appropriate accessibility considerations for this behaviour. 

## JavaScript
* Use the status data property to visually indicate the state of the module with an appropriate icon. 
* Use the category of the course to choose the correct SVG header icon. 
* Implement a set of clickable filters to show All, HTML, CSS and JavaScript related cards based on the category data. 
* On clicking the expansion button on the card the card should transition to an expanded state displaying the list of details included in the data. 
* Clicking the toggle again should collapse the card to its original state. 

## Forms Processing
* Beneath the summary area should be a form displaying the users name and bio. 
* The user should be able to update the information and click submit, processing should be handled without a page request. 
* On submission the student name and bio should update in the header accordingly. 
* Validation should be included to ensure the user must enter a name and bio in order to submit the form 
* The student’s username is generated dynamically by concatenating, lowering case, reversing and adding a random number. 

## Considerations 
* We will provide a suitable workstation for the work to be undertaken and will be available if you experience any problems that block your progress. Just ask. 
* You should focus attention where you believe you have the best chance of demonstrating your level of expertise; remembering that high quality uncompleted delivery is desirable over completed but poor quality. 
* You are free to choose the tooling and approach you prefer but obviously credit will be given for demonstration of current methods and approaches that maximise the use of the available time. 
* You are free to utilise any libraries and frameworks for JavaScript but it is expected CSS will be your own work. Additional credit will be given for solutions which are less reliant on third party code - use your judgement to maximise the use of your time and quality. 
* Following the test you should be able to provide a working, static, implementation which does not require a build step. However please also provide source and build environment to allow us to fully explore your solution. 
* Your solution should work in the current version of Chrome. 
* Please zip your work on completion and use WeTransfer (or similar) to forward your work to andy.pimlett@mando.agency - we will check we have everything prior to you leaving.


