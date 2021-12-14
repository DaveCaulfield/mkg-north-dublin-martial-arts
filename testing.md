# Testing

## Code Vaildation
The code for MKG North Dublin website has been tested using [W3C HTML Validator](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) . There were some minor fixes required after testing, a space in the telephome number between country code and mobile number. This was corrected and all html and CSS files passed validation checks.

HTML vaildator results:

- Home page 

![HTML home page vaildataion](/docs/readme-images/html-validator.png)

 - About page

 ![HTML About page vaildataion](/docs/readme-images/html-validator.png)

 - Classes page

 ![HTML Classes page vaildataions](/docs/readme-images/html-validator.png)

 - Gallery page

 ![HTML Gallery page vaildataion](/docs/readme-images/html-validator.png)

 - Thank you page

 ![HTML Thank you page vaildataion](/docs/readme-images/html-validator.png)



 CSS Vaildator results:

 ![CSS Vaildator results](/docs/readme-images/css-validator.png)


 ## Responsiveness Testing
- Responsivness was tested using [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/) and [Responsive design checker](https://responsivedesignchecker.com/). 
    - The site was found to be responsive for small, medium and large screens.

## Browser Compatability

- Different browsers were used to test the MKG North Dublin website. The site was found to work accross Google Chrome, Safari, Microsoft Edge and Mozilla Firefox web browsers. One issue identified by testing accross different browsers was Safari ios not renderering the right arrow icon in the class timetable - see Known bugs section for details.  


# Known Bugs
- During browser testing, Safari ios mobile did not render the icons in the timetable correctly.


<img src="docs/readme-images/timetable-bug.png" width="300" height="650" alt="screen shot of timetable bug"/>>


- A fix was found on Stackoverflow. A variation selector of \fe0e was added with the css entity to specify it as text not as (default) emoji. Implementing the variation selector resolved the issue.


<img src="docs/readme-images/timetable-fix.png" width="300" height="650" alt="screen shot of timetable fix"/>