# Mobile Vet

The Mobile Vet is a Veterinary Service to treat poorly animals. There will be a main clinics (based in Thirsk), but owners can request a call-out if they are unable to get to the practice.

![Responsive Mockup](docs/screenshots/am-i-responsive.png)

## Features

### Features common to all pages

- **Navigation Bar**

  - The navigation bar is on all pages (for quick/easy navigation) and responds to smaller screens by reducing to a burger icon, which expands downwards to reveal all pages. Links to Mobile Vet, Services, Appointments and The Team pages. As a result, the user has no need to use their browser 'back' button.

![Nav Bar Burger Dropdown](docs/screenshots/navbar-burger-dropdown.png)

![Nav Bar](docs/screenshots/navbar.png)

- **The hero images**

  - Common to all but The Team page (which already contains three profile images) each page has an image with text overlay to summarise to the user what the page is about. Each page has a different image to keep the user interested.
  - Text sits on a semi-opaque background to keep text readable over the image. The box will be centre-justified relative to the image, vertically and horizontally.

![Hero Image](docs/screenshots/hero-image.png)

- **The Footer**

  - The footer section includes links to the associated Facebook, X and linkedin pages for The Mobile Vet. There they would gather more information relevant. The links open to a new tab to avoid the user from 'losing their bearings' on the site.
  - There is also a hyperlink to return the user to the top of the page, particularly useful for mobile users.
  - "This page is for educational purposes only." is self-explanatory.

![Footer](docs/screenshots/footer.png)

### Pages

- **Services**

- This page will give an overview of the kinds of treatment that the practice can deliver.

- **Appointments**

- This page allows the user to book an appointment with a vet convenient to them.

- **The Team**

- Owners want to know their pets are in safe hands. This page introduces member of The Team with profiles and 'friendly faces'.

## Testing

- I deployed before content creation for feedback from Mentor and friends.
- I also posted to #peer-code-review on Slack for peer review.
- I continuously tested my website on different screen sizes using DevTools on Chrome and different devices.
- Once the website was deployed I checked using W3C validator at every push/deployment - see Validator Testing section below.

### Validator Testing

- HTML
  - No errors or warnings were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Falanjameschapman.github.io%2Fmobile-vet%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](http://jigsaw.w3.org/css-validator/validator$link)
- LIGHTHOUSE
- Lighthouse validation results vary accross the site (see docs) and screen sizes but in all cases checked, Accessibility is above 90%. As an example:
 ![Lighthouse for The Team](docs/screenshots/lighthouse-the-team.png)

### Future Enhancements

- The form on The Appointments page doesn't do anything with the data captured, as it is not part of the course content to this point.
- On the index page, a Reviews section could be added to give further confidence to users on the level of service. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub)

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - <https://alanjameschapman.github.io/mobile-vet/index.htm

## Credits

### Content

- The text for the pages was created by ChatGPT
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The images used on all pages are from https://www.pexels.com/. The authors were Snapwire, Gustavo Fring and Tima Miroshnichenko.