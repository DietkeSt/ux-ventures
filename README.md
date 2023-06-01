

# UX Ventures

UX Ventures is a Career Coaching homepage that offers assistance in helping UX Design students to find a job, get a promotion, or land a freelance contract. 
The goal is for the students to book a career coaching call.

- [Deployed UX Ventures Ltd. Homepage](https://dietkest.github.io/ux-ventures/index.html)

- [UX Ventures repository on GitHub](https://github.com/DietkeSt/ux-ventures)

Responsive screenshots:

  ![UX Ventures screenshots for different screen sizes](/documentation/ux-ventures-screenshots.png)

<br>

## User Experience

<br>

### User Stories

1. **First time visitor goal:** As a user, I want to be able to book 1on1 coaching to help me with my job interviews.
    - **Success criteria:** We know this to be true, if a user books a 1on1 coaching call.
    - **Development:** I think adding a Coaching section with a button to book 1on1 coaching would help the user.
2. **Returning visitor goal:** As a user, I want to have access to a Resource section with files to help me with my application.
    - **Success criteria:** We know this to be true, if a user downloads a file from the Resource section.
    - **Development:** I think adding a link to the  Resources page in the navigation should help the user.
3. **Frequent user goal:** As a user, I want to see Career Tips so that I can see relevant advice for landing a job in UX.
    - **Success criteria:** We know this to be true, if a user engages with the Career Tips section.
    - **Development:** I think adding a link to the Career Tips page that includes video or blog updates would help the user.

<br>

### Wireframes

  ![UX Ventures wireframe for first website draft](/documentation/ux-ventures-wireframe.png)

<br>

### Design Style Guide

#### Buttons

  ![Image for button styling](/documentation/buttons.png)

#### Colors

  ![Colors used on website: #04A4AC, #02727e, #040404, #f4f4f4](/documentation/colors.png)

#### Font

- [Google Fonts import URL](https://fonts.googleapis.com/css2?family=Lato:wght@300&family=Open+Sans:wght@300&display=swap)

- **Primary font:** 'Lato', sans-serif;

- **Secondary font:** 'Open Sans', sans-serif;

- **h1:**  #04A4AC, 32px, Open Sans

- **h2:** #04A4AC, 28px, Open Sans

- **h3:** #04A4AC, 21px, Open Sans

- **p:** #040404, 18px, Lato

- **li:** #040404, 18px, Lato

#### Logo

  ![UX Ventures logo](/documentation/logo.png)

<br>

## Technologies Used

<br>

### Languages

- [HTML5](https://en.wikipedia.org/wiki/HTML5): was used to create the structure and content throughout the website.
- [CSS3](https://en.wikipedia.org/wiki/CSS): was used to style the code throughout the website.
- [Javascript](https://en.wikipedia.org/wiki/JavaScript): was used for opening calendar in a new window, for automatically updating the footer year

### Frameworks, Libraries & Programs

- [Balsamiq](https://balsamiq.com/wireframes/): was used for Wireframe creation.
- [Canva](https://www.canva.com/): was used for Logo creation and screenshots
- [Snagit](https://www.techsmith.com/screen-capture.html): was used to convert screen recordings into GIFs.
- [Codeanywhere](https://codeanywhere.com/): was used for version control and terminal used to push to GitHub.
- [GitHub](https://github.com/): is used to store the project code and deployed website.
- [Google Fonts](https://fonts.google.com/): were used to import "Lato" and "Open Sans" font into style.css file which is used throughout the website.
- [Font Awesome](https://fontawesome.com/): was used for all icons used throughout the website.
- [Google Drive](https://drive.google.com/): is used to store documentation GIFs and videos.

<br>

## Features

<br>

### Existing Features

#### Navigation Bar

- Fully responsive and sticky navigation bar that includes links to the Home page, and the About, Testimonials, and Book Call sections.
- The navigation bar is displayed in a hamburger menu on smaller screens to enhance readability and accessibility of the navigation menu.
- The navigation bar on the thankyou.html page is different as it only displays the logo that links back to the Home page and not the other sections, because it should enhance calmness for the user to not be overwhelmed.
- The navigation bar allows the user to easily navigate from section to section, and easily navigate back to the Home page from the Thank you page.
- The navigation bar has a logo that redirects to top of the page when clicked for easy navigation.
- The navigation menu includes a link to the Home section, a link to the About section, a link to the Testimonials section and a button link to the Book Call section that can be reached by clicking on each link.
- There is a color changing hover affect applied to the Home, About, Testimonials and Book Call section for easier navigation.

  ![Navigation Bar for UX Ventures website with different resolutions and hover effects](/documentation/navigation.png)

#### Hero Image

- The hero image is included in the hero section, which includes a text overlay to make sure the user knows the purpose of this website.
- The hero section text is shorted on mobile resolution to not overwhelm the user.
- This section is a quick intro to the website and its purpose with an animation effect to grab the user's attention.

  ![Hero section for UX Ventures website with different resolutions](/documentation/hero-features.png)

#### About Section

- The about section gives the user an overview of the background of Kim Steindel, and the services and benefits working with UX Ventures.
- Upon learning more about the background and benefits, this should entice the user in booking a career coaching call.

  ![About section for UX Ventures website with different resolutions](/documentation/about.png)

#### Testimonials Section

- This gives the user an overview of career coaching experiences from past students in written form as well as video format.
- The embedded YouTube playlist will not automatically play, and can be opened directly on YouTube as well, if the user wishes to do so.
- The embedded YouTube videos can directly be played on the website, if the user wishes to do so, which is a great experience for the user as no extra tab or window needs to be opened.
- This section will  allow the user to get an insight on further benefits of using career coaching services and should entice the user to book a call.

  ![Testimonials section for UX Ventures website with different resolutions](/documentation/testimonials.png)

#### Book Call Section

- This section will allow the user to directly book a carrer coaching call, or send a contact message first.
- The career coaching call booking button is using the primary button design to entice the user to preferably book a call, versus sending a message. 
- This section also includes a portrait image of the career coach to connect with the user on a personal level.
- This section also includes a contact form with a secondary button to give the user the option to reach out first, if needed.
- That contact form includes first name, last name, email and message fields that are required to be filled by the user to be able to submit the form, if not filled, it will not be sent.
- The contact form fields also require the correct format to be used. If the email field is not filled with an email format, the form cannot be submitted and the user will see an error message to correct the field entry.

  ![Book Call section for UX Ventures website with different resolutions](/documentation/book-call-features.png)

#### Footer

- The footer section includes a link to LinkedIn for UX Ventures, as well as a link to the developer's GitHub repository. The footer also contains the copyright statement to give the user a quick overview of the creator of the website, the owner of the website as well as quick access to Social Media to connect with UX Ventures.
- When the user clicks on the links, they will open in a new tab for easier navigation, and feature a hover effect for better readability.

  ![Book Call section for UX Ventures website with different resolutions](/documentation/footer.png)

#### Thank You Page

- The Thank You Page opens after a user submits a message via the contact form, so the user knows that the message was successfully sent.
- The page includes a separate navigation with only the logo visible and a return to Home page button. This is done on purpose, to not overwhelm the user with too much content on the Thank You page.

  ![Book Call section for UX Ventures website with different resolutions](/documentation/thank-you.png)

<br>

### Feature Ideas To Implement

#### Resource section

- The resource section is needed, so that users want to revisit the website, even when not booking a coaching call.
- This section should offer downloadable content, like material on how to write better CVs, etc.

#### Career Tips section

- The career tips section is needed for users to re-visit the website.
- This section should include career tips in blog format and video format. They will be useful for the user when preparing for their next career step.

#### Paid Services

- The paid services could be implemented for the call-book and resource sections.
- This would involve implementing a solution for direct online payments when users want to download content or book a coaching call.

#### Further Improvements

- Make sure to do further accessibility testing with tools like the [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/).
- Include a fully functioning form without the help of tools like [Sheetmonkey](https://sheetmonkey.io/).
- Improve commit messages by keeping them shorter, as I went above the character limit from time to time.
- Also use the correct filepath when adding commits, instead of just using "add ."

<br>

## Testing

<br>

### Functionality & Responsiveness

1. Browser test for functionality:
   
   - [Chrome](https://www.google.com/intl/en_ie/chrome/):
    
        ![Chrome functionality test](https://drive.google.com/uc?id=1RK5PuRC0ik2YZFpTtsdYW7MUmArzr4Gs)
        
   - [Firefox](https://www.mozilla.org/en-US/firefox/new/):
  
        ![Firefox functionality test](https://drive.google.com/uc?id=1Rz2nKI9WJiPN6o1gEome-FKpBJdQl519)
        
   - [Safari](https://www.apple.com/safari/):
  
        ![Safari functionality test](https://drive.google.com/uc?id=1m330nqL1oNa-EJ6RP_0GF9Ku0vnds-IN)

2. Responsiveness test:

   - With [Responsive Viewer](https://chrome.google.com/webstore/detail/responsive-viewer/) Chrome extension:
  
        ![Responsive Viewer testing gif](https://drive.google.com/uc?id=1-QXmhwiXhVvg_kowmoCbNZCADV_PGKYT)
        
        Or, watch the Responsive Viewer testing video [here](https://drive.google.com/file/d/1mIZ2ADsKHXGSmtG08jh-rykGGGG1tS9x/view?usp=share_link)
    
   - [DevTools](https://developer.chrome.com/docs/devtools/):
   
        ![DevTools responsiveness testing gif](https://drive.google.com/uc?id=17kMDw10v71FkG4RSscJmUE0Oo-xh35Lw)
        
        Or, watch the DevTools testing video [here](https://drive.google.com/file/d/1V6tL2tVCKPUREmTmNhuY_raBfSHR8TZS/view?usp=sharing)
   
3. All links were tested as well, and are opening as expected.
 
    #### Navigation

   - **Logo**: By clicking on the logo the user is redirected to index.html.

        - Test passed.
   - **Home**: By clicking on Home the user is redirected to index.html.

        - Test passed.
   - **About**: By clicking on About the user is redirected to about section.

        - Test passed.
   - **Testimonials**: By clicking on Testimonials the user is redirected to testimonials section.

        - Test passed.
   - **Book Call**: By clicking on Book Call the user is redirected to book-call section.

        - Test passed.
    
    #### Testimonial Section
    
   - **YouTube Video**: By clicking on the play button, the video start. By clicking on "Watch on Youtube" the user is redirected to [Youtube Playlist](https://www.youtube.com/watch?v=RE25PyaUTiU&list=PL9G_LUWtBLYO18IPrNxlQck5Sf8BLBzp1) in an external tab.

        - Test passed.

    #### Book Call Section
 
   - **Book Call Button**: By clicking on the Book Call button a new window with a Google Calendar booking option is opening for the user.

        - Test passed.
   - **Form Submit Button**: By clicking on Send Message after the form is correctly filled out the user is redirected to thankyou.html

        - Test passed.

    #### Footer
    
   - **Developer GitHub**: By clicking on Dietke Steindel the user is redirected to https://github.com/DietkeSt/ which opens in a new tab.

        - Test passed.
   - **Social Media**: By clicking on the LinkedIn icon the user is redirected to https://www.linkedin.com/company/ux-ventures-ltd/ which opens in a new tab.

        - Test passed.

    #### Thank You Page
    
   - **Developer GitHub**: By clicking on the logo the user is redirected to index.html

        - Test passed.
   - **Social Media**: By clicking on the logo the user is redirected to index.html

        - Test passed.

<br>

### Validator Testing

#### HTML

- No errors were returned when passing through the official [W3C validator](https://validator.w3.org/).
 
    ![html validator testing image](/documentation/html-validator.png)
    
#### CSS

- No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/).

    ![css validator testing image](/documentation/css-validator.png)

- 7 warnings were found when passing through the official (Jigsaw) validator.

    ![css validator testing warning image](/documentation/css-validator-warnings.png)

    - 3 warnings regarding button background-color and border-color being the same value.
      - **Comment**: This was intended as only the background-color should change upon hover, not the border-color.

    - 4 warnings regarding the use of calc variables: "Due to their dynamic nature, CSS variables are currently not statically checked".

<br>

### Lighthouse

- Checked with [lighthouse in devtools](https://developer.chrome.com/docs/lighthouse/overview/):

    #### index.html:

  -   Desktop check was all above 90%:
     ![Book Call section for UX Ventures website with different resolutions](/documentation/lighthouse-desktop.png)
     
  - Mobile test shows only 83% in Best Practices:
    ![Book Call section for UX Ventures website with different resolutions](/documentation/lighthouse-mobile.png)

    - Found issues to be related to embeded video playlist and logo.
    - However, I could not verify any interference with  accessibility, or performance:
     ![Book Call section for UX Ventures website with different resolutions](/documentation/lighthouse-mobile-bestpractices.png)

   #### thankyou.html:

  -   Desktop check was all above 90%:
     ![Book Call section for UX Ventures website with different resolutions](/documentation/lighthouse-desktop-thankyou.png)
     
  - Mobile check was all above 90%:
    ![Book Call section for UX Ventures website with different resolutions](/documentation/lighthouse-mobile-thankyou.png)


<br>

### Fixed Bugs

- The image files links for the background images would not properly load, so had to adjust links for the background images to display correctly on deployment.
- On mobile resolution, the hero text was not centered. This was caused by margin set for the container which I removed.
- On mobile, the embedded iframe did not have the correct margin set for the column display. Corrected the top margin for cohesive experience for the user.
- Footer would not display any styling, this was caused by a missing CSS closing tag for the book-call section. Adding the missing tag solved the issue.
- To enhance readability fixed the background color of the footer to a darker shade.

<br>

### Unfixed Bugs

- Kept Logo image in html, instead of uploading it as background image for the div. The margin would not work properly on the div.
- Margin in Book-Call section for the ul is set to 5em, as the button would otherwise overlap with the text. Did not fix this further beyond the margin setting, as it consumed a lot of time to get to the bottom of why this issue was occuring.

<br>

### Deployment

#### From Codeanywhere

To push the code to Github from Codeanywhere, the following command can be used:

- 


#### On GitHub

1. Navigate to the GitHub repository for UX Ventures.
2. Click on the "Settings" tab and navigate to "Pages."
3. Select "Deploy from branch" for "Source."
4. Choose the "main" branch and save the changes.
5. It takes a few minutes until the deployed website is created and visible.

- Deployed website can be found here: https://dietkest.github.io/ux-ventures/ 

#### Local deployment

To make a local copy of this project in VSCode, these steps can be followed:

1. Navigate here <https://github.com/DietkeSt/ux-ventures.git>, and click on "Code > Local > HTTPS"
    
2. Click on "Download ZIP"
![Clone repository](/documentation/clone-repository.png)

3. Navigate to the folder you want to open by using cd
![cd file](/documentation/vscode-cd.png)

4. Then, type code and the pathfile
![code filepath](/documentation/vscode-code.png)

<br>

## Credits

<br>

#### W3Schools

- Flex Direction code found here: <https://www.w3schools.com/cssref/css3_pr_flex-direction.php>

#### StackOverflow

- Box-sizing borderbox: <https://stackoverflow.com/questions/24605308/how-to-add-space-between-buttons-and-its-borders>
- Flex box: <https://stackoverflow.com/questions/48464444/how-to-display-3-items-per-row-in-flexbox>
- Current year in footer: <https://stackoverflow.com/questions/4562587/shortest-way-to-print-current-year-in-a-website>
- Open in new window, not tab: <https://stackoverflow.com/questions/12939928/make-a-link-open-a-new-window-not-tab>

#### FreeFrontend

- Hero Animation code found here: <https://freefrontend.com/css-hero-effects/>
- Blockquote styling found here: <https://freefrontend.com/css-quote-styles/>

#### Developer.Mozilla

- Z-index usage guide found here: <https://developer.mozilla.org/en-US/docs/Web/CSS/z-index>
- Width calculator guide found here: <https://developer.mozilla.org/en-US/docs/Web/CSS/calc>

#### Others

- Tested using [bootstrap button](https://getbootstrap.com/docs/5.1/components/buttons/), but removed again.  
- [SheetMonkey](https://sheetmonkey.io/) for form submission action and redirect.
- Found info on using titles in html on [W3Doc](https://www.w3docs.com/snippets/html/how-to-add-a-mouseover-text-with-html.html).
- Followed along [Kevin Powell's video](https://www.youtube.com/watch?v=8QKOaTYvYUA) to create responsive navigation bar for mobile.

<br>

### Content

- The code on this website was created by the developer, Dietke Steindel, unless otherwise credited.
- The text on this website is taken from [this website](https://kimsteindel.weebly.com/), and was written by Kim Steindel (used with approval).
- The icons on this website were taken from [Font Awesome](https://fontawesome.com/).
- The fonts used website were taken from [Google Fonts](https://fonts.google.com/).
- The testimonials and videos were taken from this [YouTube channel](https://www.youtube.com/@kimsteindel227) (used with approval).

<br>

### Media

- The [Logo](/assets/images/logo.png) was created by myself (Dietke Steindel) with the help of paint and Canva due to knowledge of the business and requirements of the logo.
- The [Book-call image of Kim Steindel](/assets/images/book-call.png) was used with Kim's approval.
- The [Hero image](https://www.pexels.com/de-de/foto/weisses-druckerpapier-196645/) was found on open source website Pexels.com.

<br>

### Acknowledgement

- Thanks to my husband, (the carrer coach) **Kim Steindel**, for providing written content for the website.
- Thanks to my mentor, **Iuliia Konovalova**, for providing great guidance and tips for this project.
- Thanks to Code Institute Slack community for feedback and help.
