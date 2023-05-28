

# UX Ventures

UX Ventures is a Career Coaching homepage that offers assistance in helping UX Design students to find a job, get a promotion, or land a freelance contract. 
The goal is for the students to book a career coaching call.

- [Deployed UX Ventures Ltd. Homepage](https://dietkest.github.io/ux-ventures/index.html)

- [UX Ventures repository on GitHub](https://github.com/DietkeSt/ux-ventures)

Responsive screenshots:

  ![UX Ventures screenshots for different screen sizes](/assets/images/ux-ventures-screenshots.png)

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

  ![UX Ventures wireframe for first website draft](/assets/images/ux-ventures-wireframe.png)

<br>

### Design Style Guide

#### Buttons

  ![UX Ventures logo](/assets/images/buttons.png)

#### Colors

  ![Colors used on website: #04A4AC, #02727e, #040404, #f4f4f4](/assets/images/colors.png)

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

  ![UX Ventures logo](/assets/images/logo.png)

<br>

## Technologies Used

<br>

### Languages

- HTML5: was used to create the structure and content throughout the website.
- CSS3: was used to style the code throughout the website.
- Javascript: was used for opening calendar in a new window, for automatically updating the footer year

### Frameworks, Libraries & Programs

- Balsamiq: was used for Wireframe creation.
- Canva: was used for Logo creation and screenshots.
- Codeanywhere: was used for version control and terminal used to push to GitHub.
- GitHub: is used to store the project code and deployed website.
- Google Fonts: were used to import "Lato" and "Open Sans" font into style.css file which is used throughout the website.
- Fone Awesome: was used for all icons used throughout the website.

<br>

## Features

<br>

### Existing Features

#### Navigation Bar

- Fully responsive and sticky navigation bar that includes links to the Home page, and the About, Testimonials, and Book Call sections.
- The navigation bar is displayed in a hamburger menu on mobile.
- The navigation bar on the thankyou.html page is different as it only links back to the Home page and not the other sections.
- The navigation bar allows the user to easily navigate from section to section, and easily navigate back to the Home page from the Thank you page.

  ![Navigation Bar for UX Ventures website with different resolutions and hover effects](/assets/images/navigation.png)

#### Hero Image

- The hero image is included in the hero section, which includes a text overlay to make sure the user knows the purpose of this website.
- The hero section text is shorted on mobile resolution to not overwhelm the user.
- This section is a quick intro to the website and its purpose with an animation effect to grab the user's attention.

  ![Hero section for UX Ventures website with different resolutions](/assets/images/hero-features.png)

#### About Section

- The about section gives the user an overview of the background of Kim Steindel, and the services and benefits working with UX Ventures.
- Upon learning more about the background and benefits, this should entice the user in booking a career coaching call.

  ![About section for UX Ventures website with different resolutions](/assets/images/about.png)

#### Testimonials Section

- This gives the user an overview of career coaching experiences from past students in written form as well as video format.
- The embedded YouTube playlist will not automatically play, and can be opened directly on YouTube as well, if the user wishes to do so.
- This section will be allow the user to get an insight on further benefits of using career coaching services and should entice the user to book a call.

  ![Testimonials section for UX Ventures website with different resolutions](/assets/images/testimonials.png)

#### Book Call Section

- This section will allow the user to directly book a carrer coaching call, or send a contact message first.
- The career coaching call booking button is using the primary button design to entice the user to preferably book a call, versus sending a message. 
- This section also includes a portrait image of the career coach to connect with the user on a personal level.
- This section also includes a contact form with a secondary button to give the user the option to reach out first, if needed.

  ![Book Call section for UX Ventures website with different resolutions](/assets/images/book-call-features.png)

#### Footer

- The footer section includes a link to LinkedIn for UX Ventures, as well as a link to the developer's GitHub repository. The footer also contains the copyright statement.
- All links will open in a new tab for easier navigation, and feature a hover effect.
- This section helps the user to connect with UX Ventures on Social Media.

  ![Book Call section for UX Ventures website with different resolutions](/assets/images/footer.png)

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

<br>

## Testing

<br>

### Expected



<br>

### Validator Testing

Validator Testing
HTML
No errors were returned when passing through the official W3C validator
CSS
No errors were found when passing through the official (Jigsaw) validator
If errors list under Fixed Bugs

Manual testing for each section
and results and comment


<br>

### Fixed Bugs

<br>

### Unfixed Bugs

- Kept Logo image in html, instead of uploading it as background image for the div. The margin would not work properly on the div.
- Margin in Book-Call section for the ul is set to 5em, as the button would otherwise overlap with the text. Did not fix this further beyond the margin setting, as it consumed a lot of time to get to the bottom of why this issue was occuring.

<br>

### Deployment

#### Steps

1. Navigate to the GitHub repository for UX Ventures.
2. Click on the Settings tab.
3. Select the Master Branch from the source section drop-down menu.
4. Click Save.

- Deployed website can be found here: https://dietkest.github.io/ux-ventures/ 

#### Issues

- The image files links for the background images would not properly load, so had to adjust links for the background images to display correctly on deployment.

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

<br>

### Content

- The text on this website is taken from this website --LINK---- as was written by Kim Steindel (used with approval).
- The icons on this website were taken from Font Awesome --LINK----.
- The testimonials and videos were taken from this YouTube Channel --LINK---- (used with approval).

<br>

### Media

- The [Logo](/assets/images/logo.png) was created by myself (Dietke Steindel) with the help of paint and Canva.
- The [Book-call image of Kim Steindel](/assets/images/book-call.png) was used with Kim's approval.
- The [Hero image](https://www.pexels.com/de-de/foto/weisses-druckerpapier-196645/) was found on open source website Pexels.com.

<br>

### Acknowledgement

- Thanks to my husband, Kim Steindel, for providing written content for the website.
- Thanks to my mentor, Iuliia Konovalova, for providing great guidance and tips for this project.
