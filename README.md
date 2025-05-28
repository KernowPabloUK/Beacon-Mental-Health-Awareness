# Individual Formative Assignment 1

## Beacon | Mental Health Awareness

![Responsive design preview](assets/readme-documentation/Screenshot%202025-05-28%20104107.png)

_Author: Paul Morgan_

### Description

The purpose of this website is to allow external users to access accessible, beginner-friendly information on mental health and stress management and recognise the signs in others requiring support. As a site owner, the site is designed to be welcoming and calming with an organised layout to assist external users' usage.

This has been built using HTML, CSS, and the Bootstrap framework, Google Fonts, and Font Awesome icons. Excluding items listed below (AI Usage Within the Project), all code/work is my own with no external sources.

### Features

1. Navigation
2. Mental Health section
3. Stress Management section
4. Resources Section
    1. Mental Health Resources
    2. Stress Management Resources
5. Contact section
6. Footer

### Deployment Procedure

The site will be deployed using GitHub Pages using the following steps.

-   Visit GitHub.
-   Navigate to the [Beacon | Mental Health Awareness /// Individual Formative Assignment 1](https://github.com/KernowPabloUK/individual-formative-assignment-1) repository.
-   Click settings along the top options bar.
-   Click pages on the left hand side menu bar.
-   Under Build & Deployment section, click the dropdown button under 'Branch' that is labelled 'None' and select "Main".
-   Click Save.
-   After a short time, refresh the page and at the top of the page a new box will appear stating 'Your site is live at...'
-   Click 'Visit site' button to open the newly deployed site in a new window

### How to View the Project

-   [View the deployed website](https://kernowpablouk.github.io/individual-formative-assignment-1/)

### AI Usage Within the Project

-   AI used to refine user stories into tasks and acceptance criteria.
-   AI used to generate all images and logo design.
-   AI used to generate affirmation message text throughout the site, Mental Health and Stress Management tips, resources, and signs on how to recognise text.
-   AI used to generate description and meta keywords for SEO within <head>.
-   AI used to generate boilerplate lists and cards for efficiency.
-   AI used for optimisation and accessibility suggestions.
-   AI used for CSS & HTML code review.

AI (Copilot) was used to enhance the development process, but developmental control was retained by the developer. AI was helpful in generating images and text based on appropriate prompting, and for creating boilerplates. However, boilerplates still required in-depth review by the developer to fix errors and remove additional, unnecessary classes and semantic tags. This resulted in time spent that could have been better utilised in the primary development itself.

Upon usage of AI for optimisation and code review, the results were hit and miss, with approximately 65% of suggestions being unnecessary, creating unwanted layout changes within the site or causing issues when validating HTML with W3C, which had to be rectified.

In summary, AI was a useful tool when directed at the correct job/role, but at present is not a substitute for utilising a senior developer when conducting code reviews, as you should not insert code suggestions from AI unless you understand and can explain what the inserted code is doing first.

### Documents

[Wireframe of initial design](./assets/readme-documentation/Balsamiq%20-%20Beacon%20Mental%20Health%20Awareness.pdf)

### Colours & Typography

#### Colours

I used [Coolors.co](https://coolors.co/) to curate a palette inspired by calming seas and tranquil skies. The selection emphasises soft, soothing tones to create a welcoming and peaceful atmosphere, while subtle dark accents maintain visual interest and thematic consistency. This approach ensures the colours support the site's content without overwhelming or distracting users, reinforcing the focus on mental health and well-being.

![Coolors.co Colour Palette](assets/readme-documentation/Mental%20Health%20Project.png)

#### Typography

I chose the following fonts from [Google Fonts](https://fonts.google.com/) to achieve a balance between clarity and approachability. The selected typefaces provide a professional appearance while maintaining a gentle, welcoming tone—supporting the site's goal of delivering important information in a manner that feels accessible and reassuring to users.

![Google Font Typography](assets/readme-documentation/Screenshot%202025-05-28%20101147.png)

### Testing & Validation

#### Initial HTML Verification of index.html

![Initial HTML Verification of index.html](assets/readme-documentation/Screenshot%202025-05-20%20150551.png)

The errors and warnings presented were resulting from AI optimisation and accessibility suggestions. The errors were resolved by applying ID to the < h > child of the respective divs. The warning was removed and further evidences the pitfalls that can occur when using AI and not verifying its suggestions.

#### HTML Verification of index.html post adjustments

![HTML Verification of index.html post adjustments](assets/readme-documentation/Screenshot%202025-05-20%20150712.png)

#### Initial HTML Verification of resources.html

![Initial HTML Verification of resources.html](assets/readme-documentation/Screenshot%202025-05-20%20150734.png)

The errors presented were human and part of the learning experience as the doctype seemed to have been mistakenly deleted part way through development and further emphasises the importance of testing and verification pre-deployment. The usage of a div as a direct child within an unordered list was corrected by converting to a list element with no adverse effects to the site's appearance or performance.

#### HTML Verification of resources.html post adjustments

![HTML Verification of resources.html post adjustments](assets/readme-documentation/Screenshot%202025-05-20%20150954.png)

#### CSS Verification of styles.css

![CSS Verification of styles.css](assets/readme-documentation/Screenshot%202025-05-20%20151030.png)

#### CSS warnings present upon Verification of styles.css

![CSS warnings present upon Verification of styles.css](assets/readme-documentation/Screenshot%202025-05-20%20151043.png)

The warnings here are not applicable as they relate to both the usage of variables so cannot be checked apart from by the site owner themselves for validity, and the usage of external libraries which came from Google so have to be trusted as correct as we cannot verify those ourselves being not the product owner.

#### Lighthouse tests

![Lighthouse tests](assets/readme-documentation/Screenshot%202025-05-20%20155145.png)

#### WAVE accessibility tests

![WAVE accessibility tests](assets/readme-documentation/Screenshot%202025-05-22%20093636.png)

These tests were conducted throughout the development process and at multiple intervals to ensure that as development progressed, there were no contrast, semantic or accessibility issues and any that presented were corrected at each stage before progressing with the development timeline.

### Webpage preview

#### Homepage Screenshot

![Homepage screenshot](./assets/readme-documentation/Screenshot%202025-05-21%20102830.png)

#### Mental Health section Screenshot - 1 - Cards with buttons to navigate to resources and scattered affirmation messages

![Mental Health section Screenshot - 1 - Cards with buttons to navigate to resources and scattered affirmation messages](./assets/readme-documentation/Screenshot%202025-05-21%20102852.png)

#### Mental Health section Screenshot - 2 - List of signs of Mental Health challenges with button to navigate to resources

![Mental Health section Screenshot - 2 - List of signs of Mental Health challenges](./assets/readme-documentation/Screenshot%202025-05-21%20102900.png)

#### Stress Management section Screenshot - 2 - Table of Stress Management tips with button to navigate to resources

![Stress Management section Screenshot - 2 - Table of Stress Management tips with button to navigate to resources](./assets/readme-documentation/Screenshot%202025-05-21%20102907.png)

#### Mental Health Resources with buttons to external resources

![Mental Health Resources with buttons to external resources](./assets/readme-documentation/Screenshot%202025-05-21%20102944.png)

#### Stress Management Resources with buttons to external resources

![Stress Management Resources with buttons to external resources](./assets/readme-documentation/Screenshot%202025-05-21%20103003.png)

#### Footer section screenshot with contact links

![Footer section screenshot with contact links](./assets/readme-documentation/Screenshot%202025-05-21%20102912.png)

### Credits

-   [Google Fonts](https://fonts.google.com/) for typography.
-   [Coolors.co](https://coolors.co/) for palette selection.
-   [Favicon.io](https://favicon.io/) for converting logo image to favicon.
-   [Font Awesome](https://fontawesome.com/) for icons used within the website.
-   [Pixelcut.ai](https://www.pixelcut.ai/) for removing the background from the logo.
-   [Stack Overflow](https://stackoverflow.com/) for random problem solving/syntax remembrance.
-   [Microsoft Copilot](https://copilot.microsoft.com/) for image and text generation.
-   [Bootstrap](https://getbootstrap.com/) for the framework to be built upon.
-   [Am I Responsive](https://ui.dev/amiresponsive) for the multi device image on this README.